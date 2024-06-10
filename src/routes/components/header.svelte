<script>
    import { goto } from "$app/navigation";

    function home() {
        goto("/");
    }
    function play() {
        goto("/play");
    }
</script>

<button on:click={home}>Home</button>
<button on:click={play}>Play Now</button>
