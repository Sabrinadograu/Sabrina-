<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            width: 90%;
            margin: auto;
            overflow: hidden;
        }
        .book {
            background: #fff;
            margin: 1em 0;
            padding: 1em;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333;
        }
        p {
            line-height: 1.5;
        }

        @media (min-width: 600px) {
            .container {
                width: 80%;
            }
            .book {
                padding: 2em;
            }
        }

        @media (min-width: 768px) {
            .book {
                display: flex;
                justify-content: space-between;
                align-items: center;
            }
            .book h2, .book p {
                margin: 0;
            }
        }

        @media (min-width: 1024px) {
            header {
                text-align: left;
                padding: 1.5em 2em;
            }
            .container {
                width: 70%;
            }
            .book {
                padding: 2em 3em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Biblioteca Online</h1>
    </header>
    <div class="container">
        <div class="book">
            <div>
                <h2>O Nome do Vento</h2>
                <p>Autor: Patrick Rothfuss</p>
                <p>Descrição: A fascinante história de Kvothe, um jovem prodígio nas artes mágicas, que se torna uma lenda.</p>
            </div>
        </div>
        <div class="book">
            <div>
                <h2>1984</h2>
                <p>Autor: George Orwell</p>
                <p>Descrição: Um clássico distópico que explora os perigos de um regime totalitário e o controle extremo sobre a sociedade.</p>
            </div>
        </div>
        <!-- Adicione mais livros aqui -->
    </div>
</body>
</html>
