<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARCANJO PERALTA | CURSO</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0f0f0f;
            color: #ccc;
            font-family: 'Inter', sans-serif;
            line-height: 1.5;
            padding: 20px;
        }

        .main-card {
            max-width: 1100px;
            margin: 0 auto;
            background-color: #161616;
            border: 1px solid #2a2a2a;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        .logo {
            font-weight: 700;
            font-size: 1.2rem;
            letter-spacing: 1px;
            color: #fff;
        }

        nav a {
            color: #666;
            text-decoration: none;
            margin-left: 20px;
            font-size: 0.8rem;
            text-transform: uppercase;
        }

        /* Seção de Introdução */
        .intro-grid {
            display: flex;
            gap: 40px;
            margin-bottom: 50px;
        }

        .profile-img {
            min-width: 320px;
            height: 350px;
            background: #222 url('https://via.placeholder.com/320x350/222/555?text=IMAGEM+ARCANJO') center/cover;
            border-radius: 2px;
        }

        .intro-text h1 {
            font-size: 2.8rem;
            color: #fff;
            margin-bottom: 15px;
        }

        .intro-text h3 {
            color: #fff;
            margin-top: 20px;
            margin-bottom: 10px;
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .intro-text p {
            font-size: 0.95rem;
            color: #999;
            margin-bottom: 15px;
        }

        /* Estilo das Seções */
        .section-title {
            font-size: 0.9rem;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin: 40px 0 20px 0;
            display: flex;
            align-items: center;
            border-top: 1px solid #333;
            padding-top: 20px;
        }

        .section-title span {
            color: #555;
            margin-right: 15px;
            font-weight: bold;
        }

        /* Grid de Códigos Q */
        .codigo-q-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            font-size: 0.85rem;
        }

        .codigo-item {
            list-style: none;
            padding: 4px 0;
            border-bottom: 1px solid #222;
        }

        .codigo-item b {
            color: #eee;
        }

        /* Regras e Patrulha */
        .rules-list, .patrol-list {
            list-style: none;
            font-size: 0.88rem;
        }

        .rules-list li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
            color: #aaa;
        }

        .rules-list li::before {
            content: "➢";
            position: absolute;
            left: 0;
            color: #666;
        }

        .patrol-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 30px;
        }

        .patrol-item {
            margin-bottom: 15px;
        }

        .patrol-item b {
            display: block;
            color: #fff;
            margin-bottom: 5px;
        }

        .patrol-item span {
            color: #888;
            font-size: 0.85rem;
        }

        .highlight-red {
            color: #ff4d4d;
            font-weight: bold;
        }

        footer {
            margin-top: 60px;
            padding-top: 20px;
            border-top: 1px solid #333;
            display: flex;
            justify-content: space-between;
            font-size: 0.7rem;
            color: #555;
            letter-spacing: 1px;
        }

    </style>
</head>
<body>

    <div class="main-card">
        <header>
            <div class="logo">▲ ARCANJO PERALTA</div>
            <nav>
                <a href="#">Sobre</a>
                <a href="#">Patentes</a>
                <a href="#">Regras</a>
                <a href="#">Contato</a>
            </nav>
        </header>

        <section class="intro-grid">
            <div class="profile-img"></div>
            <div class="intro-text">
                <h1>ARCANJO PERALTA</h1>
                <h3>Curso de Modulação</h3>
                <p>Seja bem-vindo ao Curso de Modulação, este curso é de extrema importância para aprender / relembrar o modo correto de modular na rádio.</p>
                <p>Como não é um curso opcional, <b>quem quiser subir sua patente terá que ter os cursos para cada patente.</b></p>
                <p>Estamos disponíveis para dúvidas, não tenha medo de perguntar!</p>
            </div>
        </section>

        <h2 class="section-title"><span>01</span> Código Q</h2>
        <p style="font-size: 0.85rem; margin-bottom: 20px; color: #777;">Principais códigos Q utilizados em nossa guarnição:</p>
        
        <div class="codigo-q-grid">
            <ul>
                <li class="codigo-item"><b>QAP</b> – Na escuta</li>
                <li class="codigo-item"><b>QRR</b> – Pedido de reforço</li>
                <li class="codigo-item"><b>QTH</b> – Localização</li>
                <li class="codigo-item"><b>QRA</b> – Nome e patente</li>
                <li class="codigo-item"><b>QRL</b> – Estou ocupado</li>
                <li class="codigo-item"><b>QRQ</b> – Transmita mais rápido</li>
            </ul>
            <ul>
                <li class="codigo-item"><b>QRS</b> – Transmita mais devagar</li>
                <li class="codigo-item"><b>QRU</b> – Ocorrência</li>
                <li class="codigo-item"><b>QTX</b> – Saindo de serviço</li>
                <li class="codigo-item"><b>QSV / VTR</b> – Viatura</li>
                <li class="codigo-item"><b>QSL</b> – Entendido</li>
                <li class="codigo-item"><b>QSO</b> – Comunicar algo importante</li>
            </ul>
            <ul>
                <li class="codigo-item"><b>QRX</b> – Prioridade (Silenciar)</li>
                <li class="codigo-item"><b>QTA</b> – Abortar</li>
                <li class="codigo-item"><b>TKS</b> – Obrigado</li>
                <li class="codigo-item"><b>QSM</b> – Repita a mensagem</li>
                <li class="codigo-item"><b>QRV</b> – A disposição</li>
                <li class="codigo-item"><b>QSJ</b> – Dinheiro Sujo</li>
            </ul>
        </div>

        <h2 class="section-title"><span>02</span> Regras sobre a Modulação</h2>
        <ul class="rules-list">
            <li>Não usar palavras inadequadas (xingamentos, "ah", "ééé", "matei um...").</li>
            <li>Sempre prezar por uma modulação breve e rápida.</li>
            <li>Não manter conversas paralelas; caso queira, utilize o <b>/pd</b>.</li>
            <li>Manter a calma mesmo sob pressão para que todos entendam.</li>
            <li>Caso peça QRR, diga qual seu QRA.</li>
            <li>Se alguém pedir QRX, silencie imediatamente e aguarde o operador.</li>
            <li>Não atropele a modulação de outros oficiais.</li>
            <li>Modulação em VTRs feita pelo P2 (GTM o piloto pode modular).</li>
            <li>Em perseguição, a primária modula. Se der QTA, a secundária assume.</li>
        </ul>

        <h2 class="section-title"><span>03</span> Código de Patrulha</h2>
        <div class="patrol-grid">
            <div>
                <div class="patrol-item"><b>Código 0:</b> <span>➥ Iniciando patrulhamento.</span></div>
                <div class="patrol-item"><b>Código 1:</b> <span>➥ Intensidade baixa (trânsito).</span></div>
                <div class="patrol-item"><b>Código 2:</b> <span>➥ Intensidade média (Drogas/Registradora/Mascarados).</span></div>
                <div class="patrol-item"><b>Código 3:</b> <span>➥ Uso não letal / Intensidade alta (armados).</span></div>
            </div>
            <div>
                <div class="patrol-item"><b>Código 4:</b> <span>➥ Situação contida / sob controle.</span></div>
                <div class="patrol-item"><b>Código 5:</b> <span class="highlight-red">➥ FOGO LIBERADO (Atire para matar).</span></div>
                <div class="patrol-item"><b>Código 6 ou 360º:</b> <span>➥ Fazer o perímetro no local / Investigar.</span></div>
                <div class="patrol-item"><b>Código 7:</b> <span class="highlight-red">➥ QRR MÁXIMO, CHAMAR FORÇA TÁTICA.</span></div>
            </div>
        </div>

        <footer>
            <div>© 2024 ARCANJO PERALTA</div>
            <div>CONTEÚDO RESTRITO - TRANSMISSÃO CRIPTOGRAFADA</div>
        </footer>
    </div>

</body>
</html>
