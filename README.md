<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Gospel</title>
  <style>
    body {
      margin: 0;
      font-family: 'Berkshire Swash', regular;
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #000;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 36px;
      color: #fff;
      margin: 0;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
    }

    .hero h2 {
      font-size: 28px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      max-width: 600px;
      margin: 0 auto 40px;
      color: #aaa;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 30px;
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .product {
      background-color: #1c1c1c;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
    }

    .product h3 {
      margin: 10px 0;
      font-size: 18px;
    }

    .form-section {
      padding: 40px 20px;
      background-color: #000;
      text-align: center;
    }

    .form-section h2 {
      margin-bottom: 20px;
    }

    form {
      max-width: 500px;
      margin: auto;
    }

    input, textarea {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: none;
      border-radius: 6px;
      background-color: #222;
      color: #fff;
    }

    button {
      background-color: #e50914;
      border: none;
      padding: 12px 20px;
      border-radius: 6px;
      color: #fff;
      font-weight: bold;
      cursor: pointer;
    }

    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: red;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #111;
      color: #aaa;
    }
  </style>
</head>
<body>

  <header>
    <h1>ASA ARTIGOS GOSPEL</h1>
  </header>

  <section class="hero">
    <h2>Artigos que edificam sua fé</h2>
    <p>Bíblias, camisas cristãs, bonés, devocionais e muito mais para o povo de Deus.</p>
  </section>

  <section class="products">
    <div class="product">
      <h3>Bíblias</h3>
    </div>
    <div class="product">
      <h3>Camisas</h3>
    </div>
    <div class="product">
      <h3>Bonés</h3>
    </div>
    <div class="product">
      <h3>Devocionais</h3>
    </div>
    <div class="product">
      <h3>Mais produtos</h3>
    </div>
  </section>

  <section class="form-section">
    <h2>Entre em contato</h2>
    <form action="https://formspree.io/f/seudestino" method="POST">
      <input type="text" name="nome" placeholder="Seu nome" required>
      <input type="email" name="email" placeholder="Seu e-mail" required>
      <textarea name="mensagem" placeholder="Sua mensagem" rows="5" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <a href="https://wa.me/5563999515321" class="whatsapp" target="_blank">W</a>

  <footer>
    &copy; 2025 Loja Gospel. Todos os direitos reservados.
  </footer>

</body>
</html>
