<script>
    import { goto } from "$app/navigation";
    import logo from "./logo.png";

    function home() {
        goto("/");
    }
    function play() {
        goto("/play");
    }
</script>

<div class="header">
    <img src={logo} alt="Cracked_Eggs_Img" />
    <button on:click={play} id="playButton">Play Now</button><br />
    <div class="button">
        <button on:click={home} id="homeButton">Home</button>
    </div>
</div>

<style>
    .header {
        height: 35vh;
        padding-left: 20px;
    }
    .header img {
        margin-top: 20px;
        width: 350px;
    }
    .header button {
        height: 50px;
        width: 100px;
    }
    #playButton {
        margin-left: 700px;
    }
</style>
