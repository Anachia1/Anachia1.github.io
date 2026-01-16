<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>My GMod Server</title>
    <style>
        body {
            margin: 0; padding: 0;
            overflow: hidden;
            font-family: 'Arial', sans-serif;
            color: white;
            background: #000;
        }

        /* Слайдшоу */
        .background {
            position: fixed; top: 0; left: 0;
            width: 100%; height: 100%;
            z-index: -1;
            background-size: cover;
            background-position: center;
            transition: background-image 1.5s ease-in-out;
        }

        /* Затемнение для читаемости */
        .overlay {
            position: fixed; top: 0; left: 0;
            width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }

        /* Интерфейс */
        .ui {
            position: absolute; bottom: 50px; left: 50px; right: 50px;
        }

        .status-text { font-size: 24px; margin-bottom: 10px; }

        .progress-container {
            width: 100%; height: 10px;
            background: rgba(255,255,255,0.2);
            border-radius: 5px;
        }

        .progress-bar {
            width: 0%; height: 100%;
            background: #3498db;
            border-radius: 5px;
            transition: width 0.3s;
        }

        .hint-box {
            position: absolute; top: 50px; right: 50px;
            width: 300px; padding: 20px;
            background: rgba(0,0,0,0.7);
            border-left: 5px solid #3498db;
        }
    </style>
</head>
<body>

    <div class="background" id="bg"></div>
    <div class="overlay"></div>

    <audio id="music" autoplay loop>
        <source src="music.mp3" type="audio/mpeg">
    </audio>

    <div class="hint-box">
        <h3>Подсказка:</h3>
        <p id="hint">Загрузка советов...</p>
    </div>

    <div class="ui">
        <div class="status-text" id="status">Подключение к серверу...</div>
        <div class="progress-container">
            <div class="progress-bar" id="bar"></div>
        </div>
    </div>

    <script>
        // 1. Слайдшоу
        const images = ["img1.jpg", "img2.jpg", "img3.jpg"];
        let currentImg = 0;
        function changeBG() {
            document.getElementById('bg').style.backgroundImage = `url('${images[currentImg]}')`;
            currentImg = (currentImg + 1) % images.length;
        }
        setInterval(changeBG, 5000);
        changeBG();

        // 2. Подсказки
        const hints = [
            "Не нарушайте правила сервера.",
            "Нажмите F4, чтобы открыть меню.",
            "Администрация всегда готова помочь."
        ];
        setInterval(() => {
            document.getElementById('hint').innerText = hints[Math.floor(Math.random() * hints.length)];
        }, 7000);

        // 3. Функции GMod
        function GameDetails(servername, serverurl, mapname, maxplayers, steamid, gamemode) {
            // Можно вывести название карты или режим
        }

        function SetStatusChanged(status) {
            document.getElementById('status').innerText = status;
        }

        function SetFilesTotal(total) {
            window.totalFiles = total;
        }

        function SetFilesNeeded(needed) {
            let progress = ((window.totalFiles - needed) / window.totalFiles) * 100;
            document.getElementById('bar').style.width = progress + "%";
        }
    </script>
</body>
</html>
