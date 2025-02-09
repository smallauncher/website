<script lang="ts">
    import { faArrowDown } from "@fortawesome/free-solid-svg-icons";
    import Fa from "svelte-fa";
    import Header from "../components/header.svelte";

    const owner = "smallauncher";
    const repo = "smallauncher";
    const urlDownload = `https://github.com/${owner}/${repo}/releases/latest`;
</script>

<div
    class="flex flex-col w-screen h-screen bg-[url(/background.png)] bg-cover bg-center"
>
    <Header />
    <div
        class="flex flex-col w-full h-full gap-10 items-center justify-center text-white"
    >
        <h1 class="text-6xl font-bold shadow-black text-shadow-sm">
            smallauncher
        </h1>
        <a
            href={urlDownload}
            class="flex items-center p-2 gap-2 bg-cyan-900 hover:bg-cyan-800 rounded-lg text-lg shadow-black shadow-md"
        >
            <Fa icon={faArrowDown} />
            <p>Download</p></a
        >
    </div>
</div>
