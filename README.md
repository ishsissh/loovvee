<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هدية لك </title>
    <style>
        body {
            background-color: #000;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 50px;
        }
        .heart {
            font-size: 100px;
            animation: heartbeat 1s infinite alternate;
        }
        @keyframes heartbeat {
            from { transform: scale(1); }
            to { transform: scale(1.2); }
        }
        .message {
            font-size: 24px;
            margin-top: 20px;
        }
        .rose {
            width: 150px;
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="heart"></div>
    <h1>هذي وردتي يا أجمل شي في حياتي</h1>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Red_rose.svg" alt="Rose" class="rose">
    <p class="message">كل عام وأنتي معاي </p>

    <audio autoplay loop>
        <source src="your-song.mp3" type="audio/mpeg">
        متصفحك لا يدعم تشغيل الصوت.
    </audio>
</body>
</html>
