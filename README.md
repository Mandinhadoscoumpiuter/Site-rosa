
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Rosa de Botões</title>
    <style>
        body {
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
            padding: 50px;
        }
        .button {
            background-color: #ff69b4;
            border: none;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            cursor: pointer;
            margin: 10px;
            border-radius: 10px;
        }
        .button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <h1>Bem-vindo ao Site Rosa de Botões!</h1>
    <p>Clique nos botões abaixo e veja o que acontece!</p>
    <button class="button" onclick="alert('Você clicou no botão 1!')">Botão 1</button>
    <button class="button" onclick="alert('Você clicou no botão 2!')">Botão 2</button>
    <button class="button" onclick="alert('Você clicou no botão 3!')">Botão 3</button>
</body>
</html>
