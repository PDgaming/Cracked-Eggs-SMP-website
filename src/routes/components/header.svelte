<script>
    import { goto } from "$app/navigation";
    import logo from "./logo.png";

    function home() {
        goto("/");
    }
    function play() {
        goto("/play");
    }
    function requirements() {
        goto("/server-requirements");
    }
    function rules() {
        goto("/rules");
    }
</script>

<div class="header">
    <img src={logo} alt="Cracked_Eggs_Img" />
    <div class="button">
        <button on:click={home} id="homeButton">Home</button>
        <button on:click={requirements} id="requirementsButton"
            >Server Requirements</button
        >
        <button on:click={rules} id="rulesButton">Rules</button>
        <button on:click={play} id="playButton">Play Now</button>
    </div>
</div>

<style>
    .header {
        height: 200px;
        padding-left: 20px;
        background-image: linear-gradient(
                rgba(0, 0, 0, 0.3),
                rgba(0, 0, 0, 0.3)
            ),
            url("./banner.png");
        border: 5px solid black;
        background-repeat: no-repeat;
        background-size: 100% 100%;
    }
    .header img {
        margin-top: 20px;
        width: 200px;
        rotate: -15deg;
    }
    .header button {
        height: 50px;
        width: 100px;
    }
    #homeButton {
        margin-top: 15px;
    }
    #requirementsButton {
        width: auto;
    }
</style>
