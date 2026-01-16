# Papelarias-Plaza index.html.
Site institucional e catálogo da Papelarias Plaza - Produtos Personalizados.
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Papelaria Plaza | Produtos Personalizados</title>
    <style>
        /* Estilização Geral */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #ff6f61;
            color: white;
            padding: 2rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav {
            background: #fff;
            padding: 1rem;
            text-align: center;
            border-bottom: 2px solid #eee;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #ff6f61;
            font-weight: bold;
        }

        /* Seção de Produtos */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
        }

        .grid-produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s;
            text-align: center;
            padding-bottom: 1.5rem;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            background-color: #eee;
        }

        .card h3 {
            color: #444;
            margin: 1rem 0 0.5rem;
        }

        .card p {
            color: #777;
            font-size: 0.9rem;
            padding: 0 1rem;
        }

        .preco {
            display: block;
            font-size: 1.2rem;
            color: #ff6f61;
            font-weight: bold;
            margin: 1rem 0;
        }

        .btn-comprar {
            background-color: #ff6f61;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            text-transform: uppercase;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn-comprar:hover {
            background-color: #e65b50;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Papelaria Plaza</h1>
        <p>Transformando papel em memórias únicas</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Agendas</a>
        <a href="#">Cadernos</a>
        <a href="#">Kits Presente</a>
        <a href="#">Contato</a>
    </nav>

    <div class="container">
        <h2 style="text-align: center; margin-bottom: 2rem;">Nossos Personalizados</h2>
        
        <div class="grid-produtos">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1531346878377-a5be20888e57?auto=format&fit=crop&q=80&w=400" alt="Agenda Personalizada">
                <h3>Agenda 2026</h3>
                <p>Com seu nome na capa e divisórias exclusivas.</p>
                <span class="preco">R$ 89,90</span>
                <button class="btn-comprar">Personalizar</button>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1544816155-12df9643f363?auto=format&fit=crop&q=80&w=400" alt="Caderno Kraft">
                <h3>Caderno de Ideias</h3>
                <p>Capa dura em Kraft com gravação a laser.</p>
                <span class="preco">R$ 45,00</span>
                <button class="btn-comprar">Personalizar</button>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1583485088034-697b5bc54ccd?auto=format&fit=crop&q=80&w=400" alt="Bloco de Notas">
                <h3>Bloco de Notas</h3>
                <p>Kit com 3 blocos destacáveis com sua marca.</p>
                <span class="preco">R$ 29,90</span>
                <button class="btn-comprar">Personalizar</button>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1516962215378-7fa2e137ae93?auto=format&fit=crop&q=80&w=400" alt="Estojo Personalizado">
                <h3>Estojo de Luxo</h3>
                <p>Couro sintético com iniciais bordadas.</p>
                <span class="preco">R$ 55,00</span>
                <button class="btn-comprar">Personalizar</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Papelaria Plaza - Todos os direitos reservados
