<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Club Premium - Streaming Ilimitado</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;800&family=Orbitron:wght@700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #ff3e7f;
            --primary-dark: #d82a68;
            --secondary: #6a11cb;
            --dark: #121826;
            --light: #f8f9fa;
            --accent: #00d2ff;
            --success: #2ecc71;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, var(--dark) 0%, #1a243a 100%);
            color: var(--light);
            line-height: 1.6;
        }

        header {
            background: rgba(10, 15, 30, 0.9);
            backdrop-filter: blur(10px);
            position: fixed;
            width: 100%;
            z-index: 1000;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        .logo {
            display: flex;
            align-items: center;
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(90deg, var(--primary) 0%, var(--accent) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .logo i {
            margin-right: 10px;
            font-size: 2rem;
            color: var(--accent);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 30px;
        }

        nav ul li a {
            color: var(--light);
            text-decoration: none;
            font-weight: 600;
            font-size: 1rem;
            transition: color 0.3s;
            position: relative;
            padding: 5px 0;
        }

        nav ul li a:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: var(--primary);
            transition: width 0.3s;
        }

        nav ul li a:hover {
            color: var(--primary);
        }

        nav ul li a:hover:after {
            width: 100%;
        }

        .hero {
            padding: 160px 0 100px;
            background: radial-gradient(circle at top right, rgba(106, 17, 203, 0.2) 0%, rgba(18, 24, 38, 0) 50%);
            position: relative;
            text-align: center;
        }

        .hero h1 {
            font-size: 3.2rem;
            font-weight: 800;
            background: linear-gradient(90deg, var(--light), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.2rem;
            color: rgba(255,255,255,0.85);
            margin: 20px auto;
            max-width: 600px;
        }

        .btn {
            display: inline-block;
            padding: 15px 35px;
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            color: white;
            text-decoration: none;
            font-weight: 600;
            border-radius: 50px;
            margin-top: 20px;
            transition: background 0.3s;
        }

        .btn:hover {
            background: linear-gradient(90deg, var(--secondary), var(--primary));
        }

        .qr-section {
            text-align: center;
            padding: 60px 0;
        }

        .qr-section img {
            max-width: 250px;
            margin-top: 20px;
            border: 5px solid var(--light);
            border-radius: 20px;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #0e111c;
            color: #aaa;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 10px;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0;
            }

            .hero h1 {
                font-size: 2.2rem;
            }

            .btn {
                padding: 12px 25px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container header-content">
            <div class="logo"><i class="fas fa-crown"></i> Club Premium</div>
            <nav>
                <ul>
                    <li><a href="#inicio">Início</a></li>
                    <li><a href="#planos">Planos</a></li>
                    <li><a href="#pagamento">Pagamento</a></li>
                    <li><a href="https://wa.me/5582981515330" target="_blank">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero" id="inicio">
        <div class="container">
            <h1>Streaming Premium por preços que cabem no seu bolso</h1>
            <p>Acesse Netflix, Amazon Prime, Disney+, Max, Spotify e muito mais. Tudo 100% legalizado e testado com suporte rápido pelo WhatsApp.</p>
            <a class="btn" href="https://wa.me/5582981515330" target="_blank">Quero Acessar Agora</a>
        </div>
    </section>

    <section class="qr-section" id="pagamento">
        <h2>Pagamento via Pix</h2>
        <p>Escaneie o QR Code abaixo para pagamento imediato:</p>
        <img src="https://i.imgur.com/yourQRcode.png" alt="QR Code Pix">
        <p>Após o pagamento, envie o comprovante para <strong>(82) 98151-5330</strong></p>
    </section>

    <footer>
        &copy; 2025 Club Premium por Antônio Marcos. Todos os direitos reservados.
    </footer>

</body>
</html>
