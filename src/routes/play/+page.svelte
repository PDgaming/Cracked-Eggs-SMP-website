<script>
    import "../../font.css";
    import logo from "./logo.png";
</script>

<svelte:head>
    <title>Cracked Eggs - Play</title>
</svelte:head>

<div class="play">
    <h5>Join Our Minecraft Server At</h5>
    <div class="join">
        <div class="join-text">
            <h5>
                Play With Your Friends on the Cracked Eggs Server, and all you
                need to do is log in!
            </h5>
            <div class="steps">
                <h5>
                    1. In Minecraft, go to <span> Multiplayer </span>
                    , then select
                    <span> add Server </span>
                </h5>
                <h5>
                    2. Enter the server address into the server address box and
                    click <span> Done </span>
                </h5>
            </div>
            <br />
            <h4>Server Address</h4>
            <h5>Cracked_eggs.alternos.me</h5>
        </div>
    </div>
    <div class="server-image">
        <img src={logo} alt="Server-logo" />
    </div>
</div>

<style>
    .join-text {
        font-family: "Minecraft-Regular";
        width: 40vw;
        padding-top: 25px;
        padding-left: 25px;
        margin-bottom: 30px;
    }
    .join {
        background-image: linear-gradient(
                rgba(0, 0, 0, 0.8),
                rgba(0, 0, 0, 0.8)
            ),
            url("./mc-dirt-block-texture.jpg");
        border: 5px solid black;
        width: 91vw;
        height: 350px;
    }
    .steps {
        margin-left: 50px;
    }
    .server-image {
        height: 280px;
        width: 45vw;
        position: relative;
        top: -20rem;
        left: 44vw;
        background-color: orange;
    }
    .server-image img {
        height: 270px;
        width: 45vw;
    }
    .steps span {
        color: rgb(253, 213, 84);
    }
    .play {
        margin-left: -190px;
        margin-top: 30px;
        width: auto;
        height: 310px;
        color: white;
        margin-bottom: 100px;
    }
    @media screen and (max-width: 1280px) {
        .play {
            margin: auto -70px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1260px) {
        .play {
            margin: auto -60px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1260px) {
        .play {
            margin: auto -50px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1220px) {
        .play {
            margin: auto -40px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1200px) {
        .play {
            margin: auto -35px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1190px) {
        .play {
            margin: auto -30px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1180px) {
        .play {
            margin: auto -25px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1173px) {
        .server-image {
            top: -20rem;
        }
    }
    @media screen and (max-width: 1170px) {
        .play {
            margin: auto -20px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1160px) {
        .play {
            margin: auto -15px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1150px) {
        .play {
            margin: auto -10px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1130px) {
        .play {
            margin: auto 0px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1110px) {
        .play {
            margin: auto 5px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1100px) {
        .play {
            margin: auto 10px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1090px) {
        .play {
            margin: auto 15px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1080px) {
        .play {
            margin: auto 20px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1070px) {
        .play {
            margin: auto 25px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1050px) {
        .play {
            margin: auto 35px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1040px) {
        .play {
            margin: auto 40px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 1020px) {
        .play {
            margin: auto 45px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 900px) {
        .play {
            margin: auto 40px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 800px) {
        .play {
            margin: auto 35px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 700px) {
        .play {
            margin: auto 33px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 630px) {
        .play {
            margin: auto 30px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 580px) {
        .play {
            margin: auto 25px;
            margin-top: 30px;
        }
    }
    @media screen and (max-width: 490px) {
        .play {
            margin: auto 22px;
            margin-top: 30px;
        }
    }
</style>
