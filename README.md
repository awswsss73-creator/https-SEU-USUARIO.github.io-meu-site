<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Site</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
    }
    header {
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0,0,0,0.3);
    }
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      min-height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 20px;
      max-width: 600px;
    }
    .btn {
      margin-top: 30px;
      padding: 15px 30px;
      background: #00c6ff;
      background: linear-gradient(45deg, #00c6ff, #0072ff);
      border: none;
      border-radius: 30px;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
    }
    .btn:hover {
      opacity: 0.9;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0,0,0,0.4);
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Meu Site</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Sobre</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Bem-vindo ao meu site</h2>
    <p>Este é um site simples, moderno e responsivo. Ele pode ser usado como base para um negócio, portfólio ou projeto pessoal.</p>
    <button class="btn">Começar</button>
  </section>

  <footer>
    © 2026 - Meu Site. Todos os direitos reservados.
  </footer>
</body>
</html>
