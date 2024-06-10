<script>
    import { goto } from "$app/navigation";
    import logo from "./logo.jpeg";

    function home() {
        goto("/");
    }
    function play() {
        goto("/play");
    }
</script>

<div class="header">
    <img src={logo} alt="Cracked_Eggs_Img" />
    <button on:click={home}>Home</button>
    <button on:click={play}>Play Now</button>
</div>

<style>
    .header {
        background-color: brown;
        height: 35vh;
    }
    .header img {
        width: 100px;
    }
</style>
