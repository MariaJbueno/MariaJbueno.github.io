<style>
    /* Estilo global */
    body {
        font-family: 'Georgia', serif;
        background-color: #f1f1f1;
        margin: 0;
        padding: 0;
        color: #333;
        display: flex;
        justify-content: center;
        align-items: flex-start;
        flex-direction: column;
        text-align: center;
        min-height: 100vh;
    }

    /* Título principal */
    h1 {
        font-size: 50px;
        color: #8b4513;
        font-weight: 900;
        margin-bottom: 20px;
        text-transform: uppercase;
        letter-spacing: 4px;
        line-height: 1.2;
    }

    /* Texto do parágrafo */
    p {
        font-size: 18px;
        color: #4b4b4b;
        line-height: 1.8;
        max-width: 900px;
        width: 100%;
        margin: 0 auto 30px auto;
        padding: 0 20px;
        font-style: italic;
    }

    /* Divisória decorativa */
    .divider {
        width: 80%;
        height: 3px;
        background-color: #8b4513;
        margin: 30px auto;
        border-radius: 5px;
    }

    /* Botões de navegação */
    .btn {
        display: inline-block;
        padding: 15px 35px;
        margin: 20px;
        background-color: #8b4513;
        color: white;
        text-decoration: none;
        font-size: 22px;
        border-radius: 25px;
        transition: background-color 0.3s ease, transform 0.2s ease;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
        font-weight: bold;
    }

    .btn:hover {
        background-color: #a0522d;
        transform: translateY(-3px);
    }

    .btn:active {
        background-color: #5c3a1f;
        transform: translateY(1px);
    }

    /* Fundo delicado */
    .container {
        background-color: #fffaf0;
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        max-width: 1000px;
        width: 90%;
        margin: 40px auto;
        text-align: center;
        background-image: url('https://www.transparenttextures.com/patterns/just-white.png');
    }

    /* Estilo da imagem no cardápio de bebidas */
    .menu-image {
        width: 100%;
        max-width: 500px;
        border-radius: 10px;
        margin: 20px auto;
    }

    /* Estilo para o texto e imagem lado a lado */
    .features {
        text-align: left;
        font-size: 18px;
        color: #4b4b4b;
        margin: 20px auto;
        max-width: 800px;
        line-height: 1.6;
    }

    .features ul {
        padding-left: 20px;
    }

    .features li {
        margin: 10px 0;
    }

    /* Organizar a imagem ao lado do texto */
    .feature-item {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
    }

    .feature-item img {
        margin-left: 20px;
    }

    /* Animação de fade-in */
    .fade-in {
        animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }
</style>

<div class="container fade-in">
    <h1>Cardápio de Bebidas</h1>
    <p>Explore nossa seleção de bebidas, preparadas com ingredientes frescos e de qualidade. Além disso, a água é cortesia e acompanha qualquer pedido de café + salgado. Experimente nossos cafés aromáticos, cappuccinos irresistíveis e sucos naturais refrescantes para complementar a sua refeição.</p>

    <div class="divider"></div>

    <!-- Café Preto Simples -->
    <h2>Café Preto Simples</h2>
    <div class="feature-item">
        <img src="https://www.estadao.com.br/recomenda/wp-content/uploads/2024/04/Qual-o-melhor-cafe-gourmet-do-mercado-segundo-especialistas.jpeg.webp" alt="Café Preto Simples" class="menu-image">
        <div class="features">
            <p>Uma verdadeira explosão de sabor para os apreciadores do café puro! Nosso Café Preto Simples traz o sabor forte e encorpado, perfeito para dar aquele impulso no seu dia. Ideal para quem aprecia a intensidade e o aroma inconfundível de um bom café.</p>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Cappuccinos -->
    <h2>Cappuccinos</h2>
    <div class="feature-item">
        <img src="https://m.media-amazon.com/images/I/51+Xlc7uwwL._AC_UF894,1000_QL80_.jpg" alt="Cappuccino Tradicional" class="menu-image">
        <div class="features">
            <p>Delicie-se com nossos cappuccinos cremossíssimos, preparados com o melhor espresso e leite vaporizado, criando uma experiência única. Escolha entre as combinações de sabores irresistíveis que temos para você:</p>
            <ul>
                <li>Cappuccino de Baunilha e Caramelo</li>
                <li>Cappuccino de Canela e Chocolate</li>
                <li>Cappuccino de Avelã e Café</li>
                <li>Cappuccino Tradicional, para quem não abre mão do clássico!</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Cappuccino Especial da Maju -->
    <h2>Cappuccino Especial da Maju</h2>
    <div class="feature-item">
        <img src="https://www.rbsdirect.com.br/imagesrc/23490969.jpg?version=1575255600" alt="Cappuccino Especial da Maju" class="menu-image">
        <div class="features">
            <p>O Cappuccino Especial da Maju é uma verdadeira iguaria! Prepare-se para uma combinação única de chocolate amargo, creme de avelã e uma camada extra de prazer com a colher de creme de avelã, perfeita para quem deseja uma experiência mais indulgente e sofisticada.</p>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Refrigerantes -->
    <h2>Refrigerantes</h2>
    <div class="feature-item">
        <img src="https://s1.static.brasilescola.uol.com.br/be/conteudo/images/todos-os-refrigerantes-apresentam-acidos-na-sua-composicao-55aea38007f81.jpg" alt="Refrigerantes" class="menu-image">
        <div class="features">
            <p>Refresque-se com os melhores refrigerantes, prontos para harmonizar com seu pedido. Escolha sua marca favorita e aproveite os sabores frescos e intensos:</p>
            <ul>
                <li>Coca-Cola</li>
                <li>Guaraná Antarctica</li>
                <li>Fanta Laranja</li>
                <li>Pepsi</li>
                <li>Schweppes Citrus</li>
                <li>Sprite</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Sucos Naturais -->
    <h2>Sucos Naturais</h2>
    <div class="feature-item">
        <img src="https://drbrunocosme.com.br/wp-content/uploads/2020/08/sucos-naturais-rodeado-de-frutas-min-1-e1600551951486.jpg" alt="Sucos Naturais" class="menu-image">
        <div class="features">
            <p>Refresque-se com a nossa seleção de sucos naturais, feitos com frutas frescas e cheios de sabor. Perfeitos para quem busca uma opção leve e nutritiva:</p>
            <ul>
                <li>Suco de Laranja com Maracujá</li>
                <li>Suco de Abacaxi com Hortelã</li>
                <li>Suco de Morango com Limão</li>
                <li>Suco de Melancia com Gengibre</li>
                <li>Suco de Manga com Laranja</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Botões -->
    <a href="/" class="btn">Voltar para a Página Inicial</a>
    <a href="pg2" class="btn">Ver Cardápio de Salgados & Bolos</a>
</div>
