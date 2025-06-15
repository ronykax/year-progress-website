<script lang="ts">
    import Plus from "phosphor-icons-svelte/IconPlusBold.svelte";
    import ArrowSquareOut from "phosphor-icons-svelte/IconArrowSquareOutBold.svelte";
</script>

<div
    class="mx-auto max-w-7xl px-8 font-sans flex flex-col justify-center h-screen"
>
    <div
        class="flex w-full gap-12 flex-col md:flex-row h-full justify-center items-center"
    >
        <div class="w-full flex flex-col gap-8 lg:gap-12">
            <span class="text-4xl md:text-6xl font-semibold font-display">
                Track the year
                <br />
                At a glance
            </span>

            <span class="text-lg md:text-2xl opacity-75 font-sans">
                A Discord app that divides the current year into 100 pieces and
                shows how much of it has passed.
            </span>

            <div class="flex flex-col md:flex-row gap-4 text-lg">
                <a
                    href="https://discord.com/oauth2/authorize?client_id=1058434901080277134"
                >
                    <button
                        class="bg-[#5865f2] px-8 py-4 rounded-2xl font-semibold cursor-pointer hover:-translate-y-1.5 duration-200 flex gap-3 items-center"
                    >
                        <Plus />
                        Add App
                    </button>
                </a>

                <a href="https://discord.gg/jvWWH8nZxp">
                    <button
                        class="bg-[#fff]/10 px-8 py-4 rounded-2xl font-semibold cursor-pointer hover:-translate-y-1.5 duration-200 flex gap-3 items-center"
                    >
                        <ArrowSquareOut />
                        Support Server
                    </button>
                </a>
            </div>
        </div>

        <div
            class="w-full h-fit rounded-3xl border-2 border-white/25 overflow-hidden shadow-2xl"
        >
            <img class="" src="/hero.png" alt="" />
        </div>
    </div>

    <div class="opacity-50 flex gap-3 justify-between md:justify-center py-10">
        <span>© 2025 All Rights Reserved</span>

        <div class="flex flex-col gap-3 text-end md:flex-row">
            <span class="hidden md:block">•</span>
            <a href="/privacy" class="underline underline-offset-2">
                Privacy Policy
            </a>
            <span class="hidden md:block">•</span>
            <a href="/terms" class="underline underline-offset-2">
                Terms of Service
            </a>
            <span class="hidden md:block">•</span>
            <a
                href="https://github.com/ronykax/year-progress"
                class="underline underline-offset-2"
            >
                View Code
            </a>
        </div>
    </div>
</div>
