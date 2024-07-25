<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>雨天咖啡廳動態背景</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            background: #a0a0a0;
            position: relative;
        }
        canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        #backgroundImage {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <img id="backgroundImage" src="background.jpg" alt="背景圖片">
    <canvas id="rainCanvas"></canvas>
    <script src="script.js"></script>
</body>
</html>
