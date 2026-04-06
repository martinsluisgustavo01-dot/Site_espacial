<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌌 Cosmos Curioso - Fatos Incríveis do Espaço</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400&display=swap');

        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0a0a2e, #1a0033);
            color: #e0e0ff;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
        }
        header {
            background: rgba(0, 0, 50, 0.9);
            padding: 2rem 0;
            text-align: center;
            border-bottom: 3px solid #00ffff;
        }
        h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            margin: 0;
            text-shadow: 0 0 20px #00ffff;
        }
        .subtitle {
            font-size: 1.3rem;
            opacity: 0.9;
        }
        nav {
            background: #1a0033;
            padding: 1rem;
            text-align: center;
        }
        nav a {
            color: #00ffff;
            margin: 0 1.5rem;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
        }
        nav a:hover {
            color: #ff00ff;
            text-shadow: 0 0 10px #ff00ff;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 2rem;
        }
        .card {
            background: rgba(255,255,255,0.05);
            border-radius: 15px;
            padding: 1.8rem;
            margin: 1.5rem 0;
            box-shadow: 0 10px 30px rgba(0, 255, 255, 0.1);
            border: 1px solid #00ffff33;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .card h2 {
            color: #00ffff;
            font-family: 'Orbitron', sans-serif;
            margin-top: 0;
        }
        .fact-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #ff00ff;
            opacity: 0.8;
        }
        footer {
            text-align: center;
            padding: 3rem 1rem;
            background: #0a0a2e;
            font-size: 0.9rem;
            opacity: 0.7;
        }
        .hero {
            height: 400px;
            background: url('https://images.nasa.gov/images/PIA23648_1.jpg') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: linear-gradient(transparent, #0a0a2e);
        }
        .hero-content {
            z-index: 2;
        }
    </style>
</head>
<body>
    <header>
        <h1>🌌 COSMOS CURIOSO</h1>
        <p class="subtitle">Descubra os segredos mais incríveis do Universo</p>
    </header>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#curiosidades">Curiosidades</a>
        <a href="#sistema-solar">Sistema Solar</a>
        <a href="#universo">Universo</a>
    </nav>

    <div class="hero">
        <div class="hero-content">
            <h2 style="font-size: 2.8rem; text-shadow: 0 0 30px #ffffff;">O espaço nunca foi tão fascinante</h2>
        </div>
    </div>

    <div class="container" id="inicio">
        <h2 style="text-align:center; font-family:'Orbitron'; color:#00ffff;">Bem-vindo ao Cosmos Curioso!</h2>
        <p style="text-align:center; max-width:700px; margin:0 auto 3rem;">
            Um site dedicado a curiosidades incríveis sobre o espaço, planetas, estrelas e o Universo. 
            Prepare-se para se surpreender com fatos que vão expandir sua mente!
        </p>
    </div>

    <div class="container" id="curiosidades">
        <h2 style="color:#ff00ff; text-align:center;">🔭 Curiosidades Incríveis</h2>

        <div class="card">
            <span class="fact-number">01</span>
            <h2>O Sol que vemos é do passado</h2>
            <p>A luz do Sol leva cerca de 8 minutos e 19 segundos para chegar até nós. Isso significa que, quando olhamos para o Sol, estamos vendo como ele era há mais de 8 minutos.</p>
        </div>

        <div class="card">
            <span class="fact-number">02</span>
            <h2>Não existe som no espaço</h2>
            <p>O espaço é um vácuo quase perfeito. Sem ar ou moléculas para transmitir as ondas sonoras, o espaço é completamente silencioso. Explosões espaciais nos filmes são pura ficção sonora!</p>
        </div>

        <div class="card">
            <span class="fact-number">03</span>
            <h2>Mais estrelas do que grãos de areia</h2>
            <p>Existem mais estrelas no Universo observável do que grãos de areia em todas as praias da Terra. Só na Via Láctea há entre 200 e 400 bilhões de estrelas.</p>
        </div>

        <div class="card">
            <span class="fact-number">04</span>
            <h2>Estamos viajando a mais de 100.000 km/h</h2>
            <p>A Terra orbita o Sol a aproximadamente 107.000 km/h. Além disso, o Sistema Solar inteiro se move pela galáxia a cerca de 828.000 km/h!</p>
        </div>

        <div class="card">
            <span class="fact-number">05</span>
            <h2>Planetas gasosos gigantes</h2>
            <p>Júpiter, Saturno, Urano e Netuno são gigantes gasosos — não possuem superfície sólida para "pisar". Se você tentasse, afundaria nas camadas de gás e pressão extrema.</p>
        </div>

        <div class="card">
            <span class="fact-number">06</span>
            <h2>Um planeta feito de diamantes?</h2>
            <p>O exoplaneta 55 Cancri e, a 40 anos-luz de distância, pode ser composto por até um terço de diamantes devido à sua alta concentração de carbono.</p>
        </div>

        <div class="card">
            <span class="fact-number">07</span>
            <h2>Lixo espacial ao redor da Terra</h2>
            <p>Existem mais de 500.000 pedaços de lixo espacial orbitando nosso planeta — desde ferramentas perdidas até partes de foguetes.</p>
        </div>

        <div class="card">
            <span class="fact-number">08</span>
            <h2>O Universo está se expandindo</h2>
            <p>O Universo tem cerca de 13,8 bilhões de anos e continua se expandindo. A maior parte dele (cerca de 95%) é composta por matéria escura e energia escura, que ainda não entendemos completamente.</p>
        </div>
    </div>

    <div class="container" id="sistema-solar">
        <h2 style="color:#00ffff; text-align:center;">🪐 Nosso Sistema Solar</h2>
        <div class="card">
            <p><strong>Mercúrio</strong> tem uma "cauda" como um cometa, causada pelos ventos solares.</p>
            <p><strong>Saturno</strong> tem uma enorme tempestade hexagonal no polo norte.</p>
            <p><strong>Netuno</strong> tem os ventos mais fortes do Sistema Solar, chegando a 2.400 km/h.</p>
            <p>Se todos os planetas fossem alinhados entre a Terra e a Lua, caberiam perfeitamente no espaço entre eles.</p>
        </div>
    </div>

    <div class="container" id="universo">
        <h2 style="color:#ff00ff; text-align:center;">🌠 O Universo como um todo</h2>
        <div class="card">
            <p>O Universo observável tem cerca de 93 bilhões de anos-luz de diâmetro, mas só tem 13,8 bilhões de anos. Isso é possível graças à expansão do espaço.</p>
            <p>Buracos negros não são "buracos" — são regiões onde a gravidade é tão forte que nem a luz escapa.</p>
            <p>A estrela mais antiga conhecida (Matusalém) parece ter uma idade próxima ou até maior que a do próprio Universo — um enigma para os astrônomos.</p>
        </div>
    </div>

    <footer>
        <p>🌌 Site criado com curiosidade e paixão pelo Universo • Fontes: NASA, National Geographic, astrônomos e fatos comprovados</p>
        <p>Feito para inspirar a próxima geração de exploradores espaciais. Atualize sempre — o cosmos está em constante mudança!</p>
    </footer>
</body>
</html>
