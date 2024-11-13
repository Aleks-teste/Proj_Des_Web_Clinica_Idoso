<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechSaúde</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Cor de fundo mais escura que o banner */
        body {
            background-color: #7b8e8f; /* Cor mais escura para o fundo */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Estilos do cabeçalho */
        header {
            background-color: #94a9a7; /* Cor de fundo do banner (mais clara que o fundo) */
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        /* Logo e nome no cabeçalho */
        .banner img {
            width: 3cm;  /* Logo com tamanho fixo de 3x3cm */
            height: 3cm;
        }

        .banner h1 {
            margin-left: 15px;
            font-size: 2rem;
            color: #ffffff;
        }

        /* Navegação */
        nav {
            background-color: #3a4d4f; /* Cor de fundo para os botões */
            padding: 10px;
            display: flex;
            justify-content: center;
        }

        nav button {
            background-color: #7b8e8f;
            color: white;
            border: none;
            padding: 10px 20px;
            margin: 0 5px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 1rem;
        }

        nav button:hover {
            background-color: #5d7374;
        }

        /* Seções do conteúdo */
        main {
            padding: 20px;
            color: #333;
        }

        .content {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .content img {
            width: 45%;
            border-radius: 8px;
        }

        .content .column-right {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .banner-text h2 {
            font-size: 2.5rem;
            color: #333;
            text-align: center;
        }

        /* Estilos da seção de pagamento */
        .payment {
            background-color: #f4f4f4;
            padding: 20px;
            text-align: center;
        }

        .payment h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
        }

        .logos img {
            width: 80px;
            margin: 0 10px;
        }

        /* Rodapé */
        footer {
            background-color: #3a4d4f;
            padding: 10px;
            text-align: center;
        }

        footer button {
            background-color: #7b8e8f;
            color: white;
            border: none;
            padding: 10px 20px;
            margin: 0 5px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 1rem;
        }

        footer button:hover {
            background-color: #5d7374;
        }
    </style>
</head>
<body>
    <header>
        <div class="banner">
            <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/TEC%20SAUDE.jpg" alt="Logo TechSaúde">
            <h1>TechSaúde</h1>
        </div>
    </header>
    <nav>
        <button>HOME</button>
        <button>DICA DOS PROFISSIONAIS</button>
        <button>SERVIÇOS</button>
        <button>CONTATO</button>
    </nav>
    <main>
        <section class="content">
            <div class="column-left">
                <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/enfermeiro.jpg" alt="Enfermeira em atendimento">
            </div>
            <div class="column-right">
                <div class="banner-text">
                    <h2>VIDA LONGA, COM QUALIDADE</h2>
                </div>
            </div>
        </section>
        <section class="payment">
            <h2>FORMA DE PAGAMENTO</h2>
            <div class="logos">
                <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/medium_visa.png" alt="Visa">
                <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/Como-fazer-cartao-de-credito-Mastercard.jpg" alt="MasterCard">
                <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/cart%C3%A3o-diners.jpg"  alt="Dinerclub">
                <img src="https://assets.onecompiler.app/42s77e8pp/42syh9akn/pix%20correto.jpg" alt="Pix">
            </div>
        </section>
    </main>
    <footer>
        <button>WHATSAPP</button>
        <button>TELEFONE</button>
    </footer>
</body>
</html>

