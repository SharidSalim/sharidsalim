<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Jaldi:wght@400;700&display=swap');
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            padding: 20px;
        }
        header {
            width: 100%;
            padding: 33px;
            background-color: #020036;
            border-radius: 6px;
            display: flex;
            justify-content: space-between;
            
        }
        header #des h1 {
            font-family: "Jaldi", serif;
            color: white; letter-spacing: 18px;
            font-weight: bold;
        }
        header #gif img {
            width: 180px;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <div id="des">
            <h1>Sharid Salim</h1>
            <p style="font-family: 'Jaldi', serif; font-size: 15px; line-height: 18px; color: white;">A passionate student and tech enthusiast exploring the vast <br> online universe. <br>
                I love building websites and creating digital experiences.</p>
        </div>
        <div id="gif">
            <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif?cid=790b76110xpfbm0dx3f44dkid30x8t481ifkqmorvd0ko6ov&ep=v1_gifs_search&rid=giphy.gif&ct=g" alt="gif">
        </div>
    </header>
</body>
</html>