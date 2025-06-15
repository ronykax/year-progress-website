<script lang="ts">
	import { marked } from "marked";
	import tosMarkdown from "$lib/content/tos.md?raw";

	const html = marked.parse(tosMarkdown);
</script>

<svelte:head>
	<title>Terms of Service</title>
</svelte:head>

<div class="prose max-w-3xl mx-auto px-6 py-20 prose-invert font-sans">
	{@html html}
</div>
