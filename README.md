<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Churros dos Deuses</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            flex-direction: column;
        }

        header {
            padding: 20px;
        }

        h1 {
            font-size: 4rem; /* Aumenta o tamanho da letra do título */
            margin: 0;
        }

        p {
            font-size: 2rem; /* Aumenta o tamanho da letra do parágrafo */
            margin: 10px 0;
        }

        footer {
            font-size: 1.5rem;
            margin-top: 20px;
            color: #555;
        }

        main {
            width: 100%;
        }

        article {
            max-width: 600px; /* Limita a largura do artigo */
            margin: 0 auto;
        }

        .churros-demo {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }

        .churro-img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Churros dos Deuses</h1>
    <p>Compre os melhores churros da região</p>
</header>

<main>
    <article>
        <h2>Detalhes sobre nossos churros</h2>
        <p>Os churros mais frescos e deliciosos, preparados com ingredientes de alta qualidade, feitos para satisfazer.</p>
    </article>

    <div class="churros-demo">
        <img src="https://static.itdg.com.br/images/640-440/b0a2d7797c9b1174ec771c88d64d2322/324392-original.jpg" alt="Churro 1" class="churro-img">
        <img src="https://nutrimassasesalgados.com/wp-content/uploads/2020/05/MG_6938-copiar.jpg" alt="Churro 2" class="churro-img">
        <img src="https://receitadaboa.com.br/wp-content/uploads/2024/12/iStock-1808237503.jpg" alt="Churro 3" class="churro-img">
    </div>
</main>

<footer>
    Tudo por apenas R$20,00
</footer>

</body>
</html>
