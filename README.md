<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>บอกรักแฟน</title>
    <style>
        body {
            font-family: 'Tahoma', sans-serif;
            background-color: #ffe6e6;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        header {
            font-size: 2.5em;
            font-weight: bold;
            color: #ff4d4d;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2em;
            color: #333;
            text-align: center;
            max-width: 600px;
            margin: 10px 0;
        }
        .heart {
            font-size: 4em;
            color: #ff4d4d;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
        .image-container {
            margin: 20px 0;
            display: flex;
            justify-content: center;
        }
        .image-container img {
            width: 300px;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            margin-top: 30px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>
<body>
    <header>เค้ารักเธอมากๆเลยนะไอ้อ้วน</header>
    <div class="heart">❤️</div>
    <div class="image-container">
        <img src="https://cdn.discordapp.com/attachments/508954909115416576/1317125813300363366/F9EF068B-972D-4FF7-BABF-16B53825D96C.jpg?ex=675d8c80&is=675c3b00&hm=5884dc6c819763071d7cb151e50a632215df15f7a4bc72b5b8bfa92314d699b9&" alt="รูปภาพความรัก">
    </div>
    <p>เธอสำคัญที่สุดในชีวิตของเค้าเลยนะ<br>
       อยู่กับเค้าไปนานๆนะคะ "ที่รักของเค้า" เด็กบ้า</p>
    <footer>&copy; 2024 บอกรักแฟน | รักนะไอ้หมาบ้า</footer>
</body>
</html>
