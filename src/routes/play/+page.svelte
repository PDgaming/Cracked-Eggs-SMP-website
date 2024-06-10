<script>
    import "../../font.css";
    import "./styles.css";
</script>

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
        <img alt="Server-Image" />
    </div>
</div>

<style>
    .join-text {
        font-family: "Minecraft-Regular";
        width: 37vw;
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
    }
    .steps {
        margin-left: 50px;
    }
    .server-image {
        background-color: red;
        height: 40vh;
        width: 40vw;
        position: relative;
        top: -295px;
        left: 570px;
    }
    .steps span {
        color: rgb(253, 213, 84);
    }
    .play {
        margin-top: 30px;
        margin-left: -50px;
        margin-right: -50px;
        width: auto;
        height: 60vh;
        color: white;
        margin-bottom: 100px;
    }
</style>
