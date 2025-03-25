<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مشاهدة أو تحميل</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri&display=swap');

        body {
            background: url('https://i.imgur.com/VBQtMRK.jpg') no-repeat center center fixed;
            background-size: cover;
            text-align: center;
            font-family: 'Amiri', serif;
            direction: rtl;
            color: white;
            padding-top: 100px;
            position: relative;
        }
        .container {
            background: rgba(0, 0, 0, 0.7);
            padding: 30px;
            border-radius: 15px;
            display: inline-block;
            box-shadow: 0px 0px 15px rgba(255, 215, 0, 0.6);
        }
        h1 {
            font-size: 28px;
            margin-bottom: 20px;
        }
        .btn {
            display: block;
            width: 220px;
            margin: 10px auto;
            padding: 15px;
            font-size: 20px;
            font-weight: bold;
            border: none;
            cursor: pointer;
            text-decoration: none;
            color: white;
            border-radius: 8px;
            transition: 0.3s;
        }
        .watch {
            background: #f39c12;
            box-shadow: 0 0 10px rgba(243, 156, 18, 0.7);
        }
        .watch:hover {
            background: #e67e22;
        }
        .download {
            background: #27ae60;
            box-shadow: 0 0 10px rgba(39, 174, 96, 0.7);
        }
        .download:hover {
            background: #2ecc71;
        }
        .ramadan-decor {
            position: absolute;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
            width: 120px;
        }
        .lantern {
            position: absolute;
            width: 60px;
            animation: flicker 1.5s infinite alternate;
        }
        .lantern-left {
            top: 30px;
            left: 10%;
        }
        .lantern-right {
            top: 30px;
            right: 10%;
        }
        @keyframes flicker {
            0% { opacity: 1; }
            100% { opacity: 0.7; }
        }
    </style>
</head>
<body>

    <img class="ramadan-decor" src="https://i.imgur.com/ZKf6RvF.png" alt="هلال رمضان">
    <img class="lantern lantern-left" src="https://i.imgur.com/a2P84A2.png" alt="فانوس رمضان">
    <img class="lantern lantern-right" src="https://i.imgur.com/a2P84A2.png" alt="فانوس رمضان">
    
    <div class="container">
        <h1>✨ اختر طريقة المشاهدة ✨</h1>
        <a href="https://youtu.be/0tPc5T4jzyo?si=zNDzT40UNY3q1wO1" class="btn watch" target="_blank">📺 المشاهدة المباشرة</a>
        <a href="https://mega.nz/file/njpHXApL#TtfTukIltZVyI6agG3kwk0J7ffAmISa9zFdkedThPQg" class="btn download" target="_blank">⬇️ تحميل</a>
    </div>

</body>
</html>
