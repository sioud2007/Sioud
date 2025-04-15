# الياس الصيود مولود في 2007 يا خ** يا عزيز 
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ألعاب كلاسيكية</title>
    <style>
        /* تنسيق عام للجسم */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
            direction: rtl;
        }

        /* تنسيق الهيدر */
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        header p {
            font-size: 18px;
            margin-top: 10px;
        }

        /* تصميم قائمة الألعاب */
        .games-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
            padding: 20px;
        }

        .game {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }

        .game img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .game a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        .game a:hover {
            color: #007BFF;
        }

        /* التأثيرات عند التمرير */
        .game:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
        }

        /* تحسين التنسيق للموبايل */
        @media (max-width: 768px) {
            .games-list {
                flex-direction: column;
                align-items: center;
            }

            .game {
                width: 90%;
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>موقع الألعاب الكلاسيكية</h1>
        <p>استمتع بألعابك المفضلة القديمة في هذا الموقع!</p>
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
