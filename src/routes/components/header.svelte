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
    <center>
        <div class="button">
            <button on:click={home} id="homeButton">Home</button>
            <button on:click={requirements} id="requirementsButton"
                >Server Requirements</button
            >
            <button on:click={rules} id="rulesButton">Rules</button>
            <button on:click={play} id="playButton">Play Now</button>
        </div>
    </center>
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
    .button {
        margin-top: 15px;
        display: inline;
        justify-content: space-between;
    }
    .button button {
        height: 50px;
        width: 100px;
    }
    #requirementsButton {
        width: auto;
    }
    @media screen and (max-width: 521px) {
        .header button {
            width: 90px;
        }
    }
    @media screen and (max-width: 490px) {
        .button button {
            width: auto;
        }
        .button {
            width: 400px;
        }
    }
    @media screen and (max-width: 440px) {
        .button {
            width: 360px;
        }
        .header {
            height: 250px;
        }
    }
</style>
