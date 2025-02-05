<script>
    // Aqui você pode adicionar scripts, se necessário
</script>

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

    /* Adicionando imagem da cafeteria no início */
    .cafeteria-image {
        width: 100%;
        max-width: 800px;
        border-radius: 10px;
        margin: 20px auto;
    }

    /* Estilo da imagem no tópico de reuniões */
    .meeting-image {
        width: 50%;
        height: auto;
        border-radius: 10px;
        margin-left: 20px;
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

    /* Estilo específico para o "Nosso Espaço" */
    .our-space {
        text-align: center;
        font-size: 22px;
        color: #4b4b4b;
        margin: 30px auto;
        max-width: 800px;
        line-height: 1.8;
        font-style: italic;
    }
</style>

<div class="container fade-in">
    <h1>Cafeteria da Maju</h1>
    <p>Bem-vindo à Cafeteria da Maju! Um ambiente aconchegante, perfeito para quem aprecia um bom café e deliciosos quitutes. Nossa cafeteria nasceu do sonho de oferecer momentos especiais, com um cardápio variado e ingredientes selecionados para garantir qualidade e sabor incomparáveis.</p>

    <!-- Primeira imagem (referente à cafeteria) -->
    <img src="https://blog.bicafebrasil.com.br/wp-content/uploads/2023/09/Cafeteria-gourmet.jpg" alt="Imagem da Cafeteria" class="cafeteria-image">

    <div class="divider"></div>

    <!-- Tópico sobre o "Nosso Espaço" -->
    <div class="our-space">
        <h3>Nosso Espaço</h3>
        <p>Há muitos anos, em um canto tranquilo da cidade, um pequeno café foi aberto com o objetivo de reunir pessoas ao redor de uma boa xícara de café e uma experiência única. Com o tempo, este espaço ganhou vida própria, acolhendo pessoas de todos os tipos: artistas, executivos, estudantes e famílias. Cada mesa tem sua própria história, e ao longo dos anos, algumas até se tornaram palco de ideias inovadoras e amizades duradouras. Nosso espaço é mais do que um café; é um lugar de encontros que transformam o cotidiano. Venha viver essa história você também!</p>
    </div>

    <div class="divider"></div>

    <!-- Tópico sobre o ambiente para reuniões -->
    <div class="feature-item">
        <div class="feature-text">
            <h3>Ambiente para Reuniões</h3>
            <p>Quando você chega à nossa cafeteria, sente imediatamente a sensação de acolhimento. Mas, ao procurar um espaço para reuniões, você encontra o que há de melhor. Nossas mesas são projetadas para grupos de qualquer tamanho, e o ambiente é silencioso e perfeito para discussões produtivas. Aqui, já organizamos reuniões de negócios que terminaram em grandes parcerias, tudo graças ao ambiente inspirador e ao delicioso aroma de café que nos acompanha. Toda a energia desse espaço é voltada para o sucesso de cada encontro. Venha fazer parte dessa experiência!</p>
        </div>
        <img src="https://conteudo.solutudo.com.br/wp-content/uploads/2020/02/Capturar.png" alt="Ambiente para Reuniões" class="meeting-image">
    </div>

    <div class="divider"></div>

    <!-- Tópico sobre as comidas -->
    <div class="feature-item">
        <div class="feature-text">
            <h3>Nossas Comidas</h3>
            <p>Na Cafeteria da Maju, não só servimos café, mas também deliciosos pratos preparados com carinho. De pães fresquinhos a sobremesas irresistíveis, temos opções para todos os gostos. Venha provar as nossas quiches, sanduíches gourmet, bolos caseiros e muito mais. Cada prato foi criado com ingredientes frescos e selecionados para garantir uma experiência gastronômica incrível!</p>
        </div>
        <img src="https://www.nutrimixassessoria.com.br/wp-content/uploads/2020/02/card%C3%A1pio-para-cafeteria-gourmet-1140x760.jpg" alt="Comidas da Cafeteria" class="meeting-image">
    </div>

    <div class="divider"></div>

    <!-- Tópico sobre as bebidas e cafés -->
    <div class="feature-item">
        <div class="feature-text">
            <h3>Nossas Bebidas e Cafés</h3>
            <p>Descubra o melhor café da cidade! Temos uma seleção especial de cafés gourmet, chás e bebidas quentes e geladas que prometem agradar aos mais exigentes. A Cafeteria da Maju é o lugar perfeito para quem valoriza o sabor e o aroma inconfundível de um bom café.</p>
        </div>
        <img src="https://blog.bicafebrasil.com.br/wp-content/uploads/2023/09/cafeteria-gourmet-5.jpg" alt="Cafés e Bebidas" class="meeting-image">
    </div>

    <div class="divider"></div>

    <!-- Tópico sobre os profissionais qualificados -->
    <div class="feature-item">
        <div class="feature-text">
            <h3>Profissionais Qualificados</h3>
            <p>Na Cafeteria da Maju, contamos com uma equipe apaixonada pelo que faz, composta por profissionais qualificados e dedicados. Cada membro da nossa equipe tem o compromisso de proporcionar a melhor experiência possível aos nossos clientes, sempre com amor e carinho pela nossa história e tradição.</p>
        </div>
        <img src="https://cdn.abrahao.com.br/base/83c/602/c00/maquina-cafeteria-profissional.jpg" alt="Profissionais da Cafeteria" class="meeting-image">
    </div>

    <div class="divider"></div>

    <a href="pg2" class="btn">Ver Cardápio de Salgados & Bolos</a>
    <a href="pg3" class="btn">Ver Cardápio de Bebidas</a>
</div>
