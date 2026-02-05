<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARCANJO ANIMADO | CURSO</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            cursor: crosshair;
        }

        body {
            background-color: #0a0a0a;
            color: #00ff41;
            font-family: 'Courier New', Courier, monospace;
            line-height: 1.6;
            overflow-x: hidden;
            padding: 20px;
        }

        .glitch-wrapper {
            text-align: center;
            margin-bottom: 50px;
            padding-top: 40px;
        }

        .glitch {
            font-size: 3.5rem;
            font-weight: bold;
            text-transform: uppercase;
            position: relative;
            text-shadow: 0.05em 0 0 #00fffc, -0.03em -0.04em 0 #fc00ff,
                         0.025em 0.04em 0 #fffc00;
            animation: glitch 725ms infinite;
        }

        @keyframes glitch {
            0% { text-shadow: 0.05em 0 0 #00fffc, -0.03em -0.04em 0 #fc00ff, 0.025em 0.04em 0 #fffc00; }
            15% { text-shadow: -0.05em -0.025em 0 #00fffc, 0.025em 0.025em 0 #fc00ff, -0.05em -0.05em 0 #fffc00; }
            50% { text-shadow: 0.025em 0.05em 0 #00fffc, 0.05em 0 0 #fc00ff, 0 -0.05em 0 #fffc00; }
            100% { text-shadow: -0.025em 0 0 #00fffc, -0.025em -0.025em 0 #fc00ff, -0.025em -0.05em 0 #fffc00; }
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(0, 20, 0, 0.8);
            padding: 30px;
            border: 1px solid #00ff41;
        }

        h2 {
            color: #fff;
            border-bottom: 2px solid #00ff41;
            margin: 30px 0 15px 0;
        }

        .highlight { color: #ff003c; font-weight: bold; }
        
        .grid-codigos {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 10px;
        }

        li {
            margin-bottom: 8px;
            list-style: none;
            border-left: 3px solid #00ff41;
            padding-left: 10px;
        }

        body::before {
            content: " ";
            display: block;
            position: fixed;
            top: 0; left: 0; bottom: 0; right: 0;
            background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%);
            z-index: 2;
            background-size: 100% 4px;
            pointer-events: none;
        }
    </style>
</head>
<body>

    <div class="glitch-wrapper">
        <div class="glitch">ARCANJO ANIMADO</div>
        <p>CURSO DE MODULAÇÃO</p>
    </div>

    <div class="container">
        <h2>BEM-VINDO</h2>
        <p>Este curso é de extrema importância. <span class="highlight">Obrigatório para subir de patente.</span></p>
        <p>Dúvidas? Não tenha medo de perguntar!</p>

        <h2>CÓDIGO Q</h2>
        <div class="grid-codigos">
            <ul>
                <li><strong>QAP</strong> – Na escuta</li>
                <li><strong>QRR</strong> – Reforço</li>
                <li><strong>QTH</strong> – Localização</li>
                <li><strong>QRA</strong> – Nome/Patente</li>
                <li><strong>QSL</strong> – Entendido</li>
            </ul>
            <ul>
                <li><strong>QRX</strong> – Prioridade/Silêncio</li>
                <li><strong>QTA</strong> – Abortar</li>
                <li><strong>TKS</strong> – Obrigado</li>
                <li><strong>QRV</strong> – À disposição</li>
                <li><strong>QSJ</strong> – Dinheiro Sujo</li>
            </ul>
        </div>

        <h2>REGRAS DE RÁDIO</h2>
        <ul>
            <li>➢ Proibido xingamentos ou palavras como "ah", "ééé".</li>
            <li>➢ Modulação breve e rápida.</li>
            <li>➢ Conversas paralelas apenas no /pd.</li>
            <li>➢ Mantenha a calma sob pressão.</li>
        </ul>

        <h2>CÓDIGOS DE PATRULHA</h2>
        <ul>
            <li><strong>Cód 0:</strong> Início</li>
            <li><strong>Cód 1:</strong> Baixa intensidade</li>
            <li><strong>Cód 5:</strong> <span class="highlight">FOGO LIBERADO</span></li>
            <li><strong>Cód 7:</strong> QRR MÁXIMO</li>
        </ul>
    </div>

</body>
</html>
