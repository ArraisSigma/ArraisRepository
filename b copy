<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerador de Elogios</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fffcf9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            flex-direction: column;
        }

        .container {
            text-align: center;
            background-color: #fff9c4;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 500px;
        }

        h1 {
            font-size: 2.5em;
            color: #f57c00;
            margin-bottom: 20px;
        }

        .compliment {
            font-size: 1.5em;
            font-weight: bold;
            color: #43a047;
            margin-bottom: 30px;
            font-style: italic;
            padding: 20px;
            background-color: #ffeb3b;
            border-radius: 10px;
        }

        button {
            padding: 15px 30px;
            font-size: 1.2em;
            color: white;
            background-color: #f57c00;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #ff9800;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Gerador de Elogios</h1>
    <div id="compliment" class="compliment">Clique no botão abaixo para receber um elogio!</div>
    <button onclick="generateCompliment()">Gerar Elogio</button>
</div>

<script>
    const compliments = [
        "Você tem um sorriso contagiante!",
        "Sua energia é incrível!",
        "Você ilumina qualquer ambiente com sua presença!",
        "Você é uma pessoa maravilhosa e merece tudo de bom!",
        "Sua bondade é um exemplo para todos ao seu redor!",
        "Você tem um grande coração!",
        "Sua criatividade é inspiradora!",
        "Você é muito inteligente e tem um ótimo senso de humor!",
        "Sua dedicação e empenho são impressionantes!",
        "Você é uma pessoa única e especial!"
    ];

    function generateCompliment() {
        const randomIndex = Math.floor(Math.random() * compliments.length);
        document.getElementById('compliment').innerText = compliments[randomIndex];
    }
</script>

</body>
</html>
