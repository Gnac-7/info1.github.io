<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona z galaktyką w tle</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('galaktyka.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            text-align: center;
        }
        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0.5em;
        }
        p {
            font-size: 1.5em;
            max-width: 600px;
            margin: 0 auto;
        }
        .content {
            margin: 2em 0;
        }
        .footer {
            position: absolute;
            bottom: 10px;
            width: 100%;
            text-align: center;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 2em;
            }
            p {
                font-size: 1.2em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Baza</h1>
        <div class="content">
            <p>pierdoły o waznych rzeczach</p>
        </div>
    </div>
    <div class="footer">
        <p>&copy; 2024 skibidi gacek. Wszystkie prawa zastrzeżone.</p>
    </div>
</body>
</html>
