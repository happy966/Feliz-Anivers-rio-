<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apontando para o Link</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .container {
            text-align: center;
        }

        .link {
            font-size: 24px;
            font-weight: bold;
            text-decoration: none;
            color: #007BFF;
        }

        .hand {
            width: 100px;
            animation: pointerAnimation 2s infinite;
        }

        @keyframes pointerAnimation {
            0% {
                transform: rotate(0deg);
            }
            50% {
                transform: rotate(20deg);
            }
            100% {
                transform: rotate(0deg);
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Hand_pointing_left.svg/600px-Hand_pointing_left.svg.png" alt="Mão Apontando" class="hand">
        <p>Acesse o link:</p>
        <a href="https://happy966.github.io/Feliz-Anivers-rio-/" class="link" target="_blank">Clique aqui para visitar</a>
    </div>

</body>
</html>
