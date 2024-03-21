<!DOCTYPE html>
<html>
<head>
    <title>Ilululand</title>
    <style>
        body {
            height: 800px;
            background-color: deepskyblue;
            background-image: linear-gradient(lightblue, deepskyblue);
        }

        .logo {
            margin-top: 100px;
            width: 200px;
            height: auto;
        }

        h1 {
            font-size: 60px;
            color: #191935;
            font-family: 'Cascadia Mono'
        }

        .icon_container {
            display: inline-block;
            height: 70px;
            width: 70px;
        }

            .icon_container:nth-child(1) {
                margin-right: 50px;
            }

            .icon_container:nth-child(2) {
                margin-right: 50px;
            }

            .icon_container:nth-child(3) {
            }

            .icon_container:nth-child(4) {
                margin-left: 50px;
            }

            .icon_container:nth-child(5) {
                margin-left: 50px;
            }

        .icon {
            width: 50px;
            height: auto;
            display: inline-block;
            padding: 10px;
            transition: width 0.2s, height 0.2s;
        }

            .icon:hover {
                width: 65px;
                height: auto;
            }

                .icon_container:hover .txt {
                    opacity: 1;
                }

        .txt {
            display: inline-block;
            opacity: 0;
            font-size: 20px;
            transition: 0.2s;
            margin-left: 10px;
            color: #191935;
            font-family: 'Cascadia Mono';
            font-weight: bold;
        }
    </style>
</head>
<body>

    <center><img class="logo" src="fish.png" /></center>
    <center><h1>ILULULAND</h1></center>
    <center>
        <div>
            <div class="icon_container">
                <a href="https://www.youtube.com/@Ilululand/featured"><img class="icon" src="youtube logo.png" /></a>
                <div class="txt">Youtube</div>
            </div>
            <div class="icon_container">
                <a href="https://discord.gg/7gvny26G"><img class="icon" src="discord icon.png" /></a>
                <div class="txt">Dicord</div>
            </div>
            <div class="icon_container">
                <a href="https://twitter.com/ilululandmc"><img class="icon" src="X logo.png" style="border-radius: 20%" /></a>
                <div class="txt">X</div>
            </div>
            <div class="icon_container">
                <a href="https://github.com/ilululand"><img class="icon" src="github logo.png" style="border-radius: 50%" /></a>
                <div class="txt">Github</div>
            </div>
            <div class="icon_container">
                <a href="https://www.pinterest.ph/ilululandmc/"><img class="icon" src="Pinterest logo.png" /></a>
                <div class="txt">Pinteret</div>
            </div>
        </div>
    </center>
</body>
</html>
