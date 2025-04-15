# Sioud
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ألعاب كلاسيكية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
        }
        .games-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }
        .game {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
        }
        .game img {
            width: 100%;
            border-radius: 10px;
        }
        .game a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .game a:hover {
            color: #007BFF;
        }
    </style>
</head>
<body>
    <header>
        <h1>موقع الألعاب الكلاسيكية</h1>
    </header>
    <div class="games-list">
        <div class="game">
            <img src="https://via.placeholder.com/150" alt="لعبة 1">
            <a href="https://example.com/game1" target="_blank">لعبة 1</a>
        </div>
        <div class="game">
            <img src="https://via.placeholder.com/150" alt="لعبة 2">
            <a href="https://example.com/game2" target="_blank">لعبة 2</a>
        </div>
        <div class="game">
            <img src="https://via.placeholder.com/150" alt="لعبة 3">
            <a href="https://example.com/game3" target="_blank">لعبة 3</a>
        </div>
    </div>
</body>
</html>
