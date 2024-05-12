<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uma Mensagem Especial</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-image:url(https://files.oaiusercontent.com/file-zFZAxxrzkcRL1dBjCTuCU7BP?se=2024-05-12T15%3A41%3A12Z&sp=r&sv=2023-11-03&sr=b&rscc=max-age%3D31536000%2C%20immutable&rscd=attachment%3B%20filename%3Dae2dd579-8121-43d3-af57-fdbcc3fffb64.webp&sig=66CjORDqKWWk5pZQCQYhkSJIIyPZGnUcW921CtcjEfE%3D);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .mensagem {
            text-align: center;
            background-color: #ffffff;
            padding: 30px; /* Aumentado de 20px para 30px para mais espaço interno */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .mensagem p {
            font-size: 16px;
            color: #333;
            margin-top: 20px; /* Adiciona margem no topo de cada parágrafo */
            margin-bottom: 20px; /* Adiciona margem na base de cada parágrafo */
        }

        button {
            background-color: #7996ff;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #ff3f3f;
        }
    </style>
</head>
<body>
    <div class="mensagem">
        <p>Hey, clica nessa parada aqui...</p>
        <button onclick="mostrarMensagem()">Clique aqui!</button>
        <p id="textoEscondido" style="display: none;">
            🍹 Na Taurus, um bar cheio de história,<br>
    Robyson, Sheila e Kauany foram em busca de glória.<br>
    Primeiro veio a caipirinha de maracujá,<br>
    Um começo refrescante, ah, que bom que está!<br><br>
    
    Seguiu-se a de frutas vermelhas, com esperança no ar,<br>
    Mas ao provar, um rosto torto, difícil de disfarçar.<br>
    "Sheila, isso é uma tragédia, que sabor é esse?"<br>
    "Ruim demais," concordaram, "desse, desiste!"<br><br>
    
    Por fim, a de abacaxi, suave e certeira,<br>
    Bom, mas não o suficiente para ganhar a primeira.<br>
    Maracujá ainda reina, o campeão sem rival,<br>
    Na noite na Taurus, foi o tropical especial.<br><br>
    
    Entre risos e goles, a noite voou,<br>
    Com histórias que só uma boa amizade criou.<br>
    No bar Taurus, o trio fez seu lar,<br>
    Em noites assim, sempre bom brindar!🌟🍹
</p>
        </p>
        <button onclick="mostrarSegundaMensagem()">Clique aqui mais uma vez!</button>
        <p id="segundaMensagem" style="display: none;">Obrigado por ser uma amiga! Amiga!</p>
    </div>
    <script>
        function mostrarMensagem() {
            document.getElementById('textoEscondido').style.display = 'block';
        }
        function mostrarSegundaMensagem() {
            document.getElementById('segundaMensagem').style.display = 'block';
        }
    </script>
</body>
</html>
