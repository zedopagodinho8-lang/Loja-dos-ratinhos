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

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #111; /* fundo preto */
  color: #f0f0f0;   /* texto claro */
}

header {
  background: #000; /* cabeçalho preto */
  color: #00aaff;   /* azul para destaque */
  padding: 15px;
  text-align: center;
}

nav button {
  background: #00aaff;
  color: #fff;
  border: none;
  padding: 10px 15px;
  border-radius: 5px;
  cursor: pointer;
}

nav button:hover {
  background: #0088cc; /* azul mais escuro no hover */
}

.produtos {
  display: flex;
  justify-content: space-around;
  margin: 20px;
}

.produto {
  background: #222; /* caixas em cinza escuro */
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 0 8px rgba(0,0,0,0.5);
}

.produto h2 {
  color: #00aaff; /* nome do produto em azul */
}

#carrinho {
  margin: 20px;
  background: #222;
  padding: 15px;
  border-radius: 8px;
}

#carrinho h2 {
  color: #00aaff;
}
