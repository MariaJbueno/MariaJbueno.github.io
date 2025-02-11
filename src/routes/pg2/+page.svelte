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

    /* Estilo da imagem no cardápio de salgados e bolos */
    .menu-image {
        width: 100%;
        max-width: 500px; /* Tamanho ajustado para imagem menor */
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
    <h1>Cardápio de Salgados & Bolos</h1>
    <p>Combinando tradição e sabores irresistíveis, nossa cafeteria oferece uma variedade deliciosa de salgados e bolos caseiros preparados com muito carinho. Cada receita foi feita para agradar todos os paladares e garantir momentos de prazer a cada mordida.</p>

    <div class="divider"></div>

    <!-- Salgados Fritos e Assados -->
    <h2>Salgados Fritos e Assados</h2>
    <div class="feature-item">
        <img src="https://img77.uenicdn.com/image/upload/v1571243986/service_images/shutterstock_796742416.jpg" alt="Salgados Fritos e Assados" class="menu-image">
        <div class="features">
            <p>Deliciosos e irresistíveis, nossos salgados fritos e assados são feitos com ingredientes fresquinhos e recheios especiais. Perfeitos para qualquer ocasião, entre as opções você encontra:</p>
            <ul>
                <li>Enroladinho de Salsicha, crocante e cheio de sabor.</li>
                <li>Empadas recheadas com uma combinação de frango ou palmito.</li>
                <li>Esfirras fechadas, macias e recheadas com carne temperada.</li>
                <li>Coxinhas crocantes por fora e recheio cremoso por dentro.</li>
                <li>Quibe assado, ideal para quem gosta de um toque de especiarias.</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Tortas Salgadas -->
    <h2>Tortas Salgadas</h2>
    <div class="feature-item">
        <img src="https://s2-receitas.glbimg.com/ot5-WEA2yVDkKSI6HaB9ykTeGLU=/1200x/smart/filters:cover():strip_icc()/i.s3.glbimg.com/v1/AUTH_1f540e0b94d8437dbbc39d567a1dee68/internal_photos/bs/2022/S/r/pZJK3BQR2eJR3Zi2nKPg/torta-salgada-de-frango-receita.jpg" alt="Tortas Salgadas" class="menu-image">
        <div class="features">
            <p>As nossas tortas salgadas são feitas com o melhor dos recheios, oferecendo uma verdadeira explosão de sabor. São preparadas com massa leve e crocante, com diversos recheios deliciosos. Experimente:</p>
            <ul>
                <li>Torta de Frango Cremosa, com peito de frango e um toque de catupiry.</li>
                <li>Torta de Carne Moída, com tempero especial e bastante sabor.</li>
                <li>Torta de Palmito, feita com recheio de palmito fresco e temperos finos.</li>
                <li>Torta de Calabresa com Queijo, para quem ama sabores mais intensos.</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Bolos Doces Recheados -->
    <h2>Bolos Doces Recheados</h2>
    <div class="feature-item">
        <img src="https://www.confeitariadaluana.com.br/wp-content/uploads/2020/06/Bolos-recheados.jpg" alt="Bolos Doces Recheados" class="menu-image">
        <div class="features">
            <p>Deliciosos bolos recheados, com opções irresistíveis como o bolo de chocolate com brigadeiro e morango. Uma verdadeira explosão de sabor para todos os gostos:</p>
            <ul>
                <li>Bolo Red Velvet com Leite Ninho, uma combinação suave e cremosa.</li>
                <li>Bolo de Creme de Avelã, rico e indulgente.</li>
                <li>Bolo de Brigadeiro, para os amantes do chocolate.</li>
                <li>Bolo de Frutas Cítricas, refrescante e leve.</li>
                <li>Bolo de Frutas Vermelhas, uma opção delicada e doce.</li>
                <li>Bolo de Doce de Leite e Nozes, uma mistura irresistível.</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Tortas Doces e Mousses -->
    <h2>Tortas Doces e Mousses</h2>
    <div class="feature-item">
        <img src="https://tudosobrebrigadeirogourmet.com/wp-content/uploads/2023/04/5-receitas-Tortas-para-Vender-em-Pedacos.webp" alt="Tortas Doces" class="menu-image">
        <div class="features">
            <p>Experimente nossas deliciosas tortas doces, perfeitas para o seu momento de prazer. Dentre as opções, destacamos:</p>
            <ul>
                <li>Torta de Morango com Castanhas, uma mistura crocante e doce.</li>
                <li>Torta de Limão, com recheio cremoso e crosta crocante.</li>
                <li>Torta de Maracujá, refrescante e deliciosa.</li>
                <li>Torta de Maçã, com um toque de canela e especiarias.</li>
                <li>Torta de Chocolate com cobertura de Kit Kat, Bis e Ferrero Rocher.</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Bolos Caseiros -->
    <h2>Bolos Caseiros</h2>
    <div class="feature-item">
        <img src="https://www.mundodosdoces.com/wp-content/uploads/2018/11/lojabolocaseiro4.jpg" alt="Bolos Caseiros" class="menu-image">
        <div class="features">
            <p>Deliciosos bolos caseiros, preparados com carinho e ingredientes fresquinhos. Perfeitos para qualquer momento do dia, nossos bolos são feitos de maneira tradicional, com um toque especial em cada receita. Opções disponíveis:</p>
            <ul>
                <li>Bolo de Fubá, leve e fofinho, um clássico das receitas caseiras.</li>
                <li>Bolo de Coco, delicioso e cheio de sabor, com aquele toque do coco ralado.</li>
                <li>Bolo de Cenoura, molhadinho e fofinho, com um leve sabor de especiarias.</li>
                <li>Bolo de Milho, perfeito para quem adora um bolo caseiro de sabor marcante.</li>
            </ul>
        </div>
    </div>

    <div class="divider"></div>

    <!-- Botões -->
    <a href="/" class="btn">Voltar para a Página Inicial</a>
    <a href="pg3" class="btn">Ver Cardápio de Bebidas</a>
</div>
