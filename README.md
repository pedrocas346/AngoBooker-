# AngoBooker-<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Portfólio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#sobre">Sobre Mim</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Bem-vindo ao Meu Portfólio</h1>
    <p>Desenvolvedor apaixonado por criar soluções digitais.</p>
  </section>

  <section id="sobre">
    <h2>Sobre Mim</h2>
    <p>Sou um desenvolvedor web com experiência em projetos criativos e funcionais.</p>
  </section>

  <section id="projetos">
    <h2>Projetos</h2>
    <div class="projetos-container">
      <div class="projeto">
        <h3>Projeto 1</h3>
        <p>Descrição do projeto 1.</p>
      </div>
      <div class="projeto">
        <h3>Projeto 2</h3>
        <p>Descrição do projeto 2.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Email: exemplo@email.com</p>
  </section>

  <footer>
    <p>© 2025 Meu Nome. Todos os direitos reservados.</p>
  </footer>
</body>
</html>* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem 0;
  text-align: center;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
}

.hero {
  background: #f4f4f4;
  padding: 2rem;
  text-align: center;
}

section {
  padding: 2rem;
  text-align: center;
}

.projetos-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
  flex-wrap: wrap;
}

.projeto {
  background: #e3e3e3;
  padding: 1rem;
  width: 300px;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}
