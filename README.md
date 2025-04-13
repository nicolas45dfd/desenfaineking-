<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DesenFaineKing 👑</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1E3A8A; /* Albastru */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            color: white;
        }

        .content {
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 40px;
            font-weight: bold;
        }

        .buttons {
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        .button {
            padding: 20px 40px;
            font-size: 1.5rem;
            background-color: #FF9900;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #ffb84d;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>Bine ai venit pe DesenFaineKing 👑</h1>
        <div class="buttons">
            <button class="button" onclick="window.location.href='https://www.netflix.com'">Netflix</button>
            <button class="button" onclick="window.location.href='https://www.disneyplus.com'">Disney</button>
            <button class="button" onclick="window.location.href='https://www.cartoonnetwork.com'">Cartoon Network</button>
        </div>
    </div>
</body>
</html>

