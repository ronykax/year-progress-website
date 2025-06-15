<script lang="ts">
    import { marked } from "marked";
    import tosMarkdown from "$lib/content/privacy.md?raw";

    const html = marked.parse(tosMarkdown);
</script>

<svelte:head>
    <title>Privacy Policy</title>
</svelte:head>

<div class="prose max-w-3xl mx-auto px-6 py-20 prose-invert font-sans">
    {@html html}
</div>
