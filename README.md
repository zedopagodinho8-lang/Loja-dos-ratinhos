# Loja-dos-ratinhos  
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Minha Loja Online</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Loja Online Escolar</h1>
    <nav>
      <button onclick="verCarrinho()">🛒 Carrinho</button>
    </nav>
  </header>

  <main>
    <section class="produtos">
      <div class="produto">
        <h2>Camiseta</h2>
        <p>R$ 50,00</p>
        <button onclick="adicionarCarrinho('Camiseta', 50)">Adicionar</button>
      </div>
      <div class="produto">
        <h2>Boné</h2>
        <p>R$ 30,00</p>
        <button onclick="adicionarCarrinho('Boné', 30)">Adicionar</button>
      </div>
      <div class="produto">
        <h2>Mochila</h2>
        <p>R$ 120,00</p>
        <button onclick="adicionarCarrinho('Mochila', 120)">Adicionar</button>
      </div>
    </section>

    <section id="carrinho">
      <h2>Seu Carrinho</h2>
      <ul id="lista-carrinho"></ul>
      <p id="total">Total: R$ 0,00</p>
    </section>
  </main>
</body>
<script src="script.js"></script>
</html> 
