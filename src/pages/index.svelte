<script>
    import { onMount } from "svelte";

    onMount(async () => {
        const hello = await (await fetch("http://localhost:3001/")).text();
        console.log(hello);
    });
</script>

<div class="bg-coollabs text-white">Home</div>
