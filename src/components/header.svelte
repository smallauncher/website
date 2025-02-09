<script>
    import { faDiscord, faGithub } from "@fortawesome/free-brands-svg-icons";

    import Fa from "svelte-fa";
</script>

<div
    class="flex w-full p-2 items-center justify-between bg-zinc-800 text-white"
>
    <a
        class="flex items-center justify-center gap-2 font-bold"
        href="/"
        aria-label="home"
    >
        <img class="h-8 w-8" alt="logo" src="/favicon.png" />
        <p>Smallauncher</p>
    </a>
    <div class="flex items-center gap-2">
        <a
            class="flex items-center justify-center"
            href="https://discord.gg/yGJCn8P2yY"
        >
            <Fa class="h-8 w-8 text-5xl" icon={faDiscord} color="#ffffff" />
        </a>
        <a
            class="flex items-center justify-center"
            href="https://github.com/smallauncher/smallauncher"
        >
            <Fa class="h-8 w-8 text-5xl" icon={faGithub} color="#ffffff" />
        </a>
    </div>
</div>
