<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="image/favicon.ico" rel="shortcut icon">
    <title>扬的照片墙</title>
    <style>
        body {
            margin: 0px;
        }
        #div1 {
            width: 100%;
            height: 50px;
            background: rgba(50, 161, 235, 0.966);
        }
        #div2 {
            background-image: url(image/bg.jpg);
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            min-width: 1000px;
            z-index: -10;
            zoom: 1;
            background-color: #fff;
            background-repeat: no-repeat;
            background-size: cover;
            -webkit-background-size: cover;
            -o-background-size: cover;
            background-position: center 0;
        }
        #photo_box {
            width: 280px;
            height: 400px;
            position: fixed;
            left: 0;
            right: 0;
            top: 0;
            bottom: 0;
            margin: 200px auto;
            transform-style: preserve-3d;
            transform: rotateX(-5deg) rotateY(0deg);
            animation: run 30s linear infinite;
        }
        #photo_box img {
            width: 250px;
            height: 350px;
            border: 5px solid #ccc;
            border-radius: 5px;
            position: absolute;
            left: 0;
            top: 0;
        }
        #photo_box img:nth-child(1) {
            transform: rotateY(0deg) translateZ(500px);
        }

        #photo_box img:nth-child(2) {
            transform: rotateY(36deg) translateZ(500px);
        }
        #photo_box img:nth-child(3) {
            transform: rotateY(72deg) translateZ(500px);
        }
        #photo_box img:nth-child(4) {
            transform: rotateY(108deg) translateZ(500px);
        }
        #photo_box img:nth-child(5) {
            transform: rotateY(144deg) translateZ(500px);
        }
        #photo_box img:nth-child(6) {
            transform: rotateY(180deg) translateZ(500px);
        }
        #photo_box img:nth-child(7) {
            transform: rotateY(216deg) translateZ(500px);

        }
        #photo_box img:nth-child(8) {
            transform: rotateY(252deg) translateZ(500px);
        }
        #photo_box img:nth-child(9) {
            transform: rotateY(288deg) translateZ(500px);
        }
        #photo_box img:nth-child(10) {
            transform: rotateY(324deg) translateZ(500px);
        }
        #photo_box img:nth-child(11) {
            transform: rotateY(360deg) translateZ(500px);
        }
        @keyframes run {
            0% {
                transform: rotateX(0deg) rotateY(0deg);
            }
            25% {
               transform: rotateX(10deg) rotateY(90deg);
            }
            50% {
                transform: rotateX(0deg) rotateY(180deg);
            }
            75% {
                transform: rotateX(-10deg) rotateY(270deg);
            }
            100% {
                transform: rotateX(0deg) rotateY(360deg);
            }
        }
        #text1 {
            float: left;
            color: #fff;
            width: 150px;
            padding: 12px 0;
            height: 50px;
        }
        #text2 {
            float: right;
            width: 100px;
            color: #fff;
            padding: 12px 0;
            height: 50px;
        }
        #text3 {
            float: right;
            width: 100px;
            color: #fff;
            padding: 12px 0;
            height: 50px;
        }
    </style>
</head>
<body>
    <div id="div2">
        <div id="photo_box">
            <img src="image/1.jpg">
            <img src="image/2.jpg">
            <img src="image/3.jpg">
            <img src="image/4.jpg">
            <img src="image/5.jpg">
            <img src="image/6.jpg">
            <img src="image/7.jpg">
            <img src="image/8.jpg">
            <img src="image/9.jpg">
            <img src="image/10.jpg">
            <img src="image/11.jpg">
        </div>
    </div>
</body>
</html>