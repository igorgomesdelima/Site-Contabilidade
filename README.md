<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercicio Extra</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Cardápio</a></li>
                <li><a href="#about">Sobre Nós</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <div class="start">
            <h1>Bem-vindo a Alessio`s</h1>
            <p>Saborosas pizzas feitas especialmente para voce!</p>
            <a href="#menu" class="cta-button">Ver Cardapio</a>
        </div>
    </section>

    <section id="menu">
        <h2>Cardapio</h2>

            <ul class="menu-list">
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Margherita</h3>
                    <p>Molho de tomate, mussartela, majericao fresco.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Pepperone</h3>
                    <p>Molho de tomate, pepperoni, quijo e mussarela.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Quatro queijos</h3>
                    <p>Molho de tomate, mussarela, parmesao, gorgonzola, provolone.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Calabresa</h3>
                    <p>Molho de tomate, calabresa, cebola, quijo mussarela.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Vegetariana</h3>
                    <p>Molho de tomate, pimentoes, cogumelos, azeitonas, queijo mussarela</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Frango Catupiry</h3>
                    <p>Molho de tomate, frango desfiado, catupiry, milho, queijo mussarela.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Portuguesa</h3>
                    <p>Molho de tomate, presunto, ovos, cebola, azeitona, queijo mussarela.</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Supreme</h3>
                    <p>Molho de tomate, pepperoni, pimentoes, cebola roxa, azeitona, queijo mussarela</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Tropical</h3>
                    <p>Molho de tomate, presunto, abacaxi, queijo mussarela</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Margherita Especial</h3>
                    <p>Molho de tomate, mussarela de bufala, tomate seco, majericao, azeite de oliva</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Carne de Sol</h3>
                    <p>Molho de tomate, carne de sol desfiada, cebola roxa, queijo mussarela</p>
                        
                </li>
                <li>
                    <img src="imagens/pexels-engin-akyurt-2260208.jpg" alt="">
                    <h3>Pizza Caprese</h3>
                    <p>Molho de tomate, tomate, mussarela de bufala, majericao, azeite</p>
                        
                </li>
            </ul>
    </section>

    <section id="about">
        <h2>Sobre Nos</h2>
        <p>Nossa pizzaria e dedicada a criar as melhores pizzas do mundo, com ingredientes frescos e receitas exclusivas.</p>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <p>Entre em contato conosco para fazer pedidos ou tirar suas duvidas.</p>
        <address>
            <p>
              <strong>Endereço:</strong>
              Avenida Onze de Outubro, nº 123<br>
              Centro, Cidade Qualquer/RJ CEP: 12345-678
            </p>
      
            <div>
              <p><strong>Telefone:</strong> (11) 5555-5555</p>
              <p>
                <strong>E-mail:</strong>
                <a href="mailto:contato@alessios.pizza">contato@alessios.pizza</a>
              </p>
            </div>
      
            <div>
              <p><strong>Horário de Funcionamento:</strong></p>
              <p>Segunda a Sábado: 11h00 às 23h00 - Domingo: 16h00 às 23h00</p>
              <p></p>
            </div>
          </address>
            <a href="#contact" class="cta-button">Peca agora mesmo!</a>
    </section>
    </main>

    <footer>
        <p>&copy; 2024 Alessios Pizzaria</p>
    </footer>

</body>
</html>

CSS:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --color-primary: #ffa500;
    --color-dark: #232323;
    --color-light: #eaeaea;
    --color-white: white;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

a {
    color: var(--color-primary);
}

header {
    background-color: var(--color-dark);
    color: var(--color-white);
    padding: 1.5rem 0;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav li {
    display: inline;
    margin: 0 1.5rem;
}

nav a {
    text-decoration: none;
    font-weight: 700;
}

.start {
    background-image: url("imagens/pexels-narda-yescas-1566837.jpg");
    background-size: cover;
    color: var(--color-white);
    min-height: 75vh;
    padding: 10rem 0;
    text-align: center;
}

.start h1 {
    font-size: 4rem;
    font-weight: 100;
}

.start p {
    font-size: 1.5rem;
    margin-top: 1.5rem;
}

.cta-button {
    background-color: var(--color-primary);
    border-radius: 8px;
    color: var(--color-dark);
    display: inline-block;
    font-size: 1.25rem;
    font-weight: 700;
    padding: .75rem 1.5rem;
    text-decoration: none;
    margin-top: 1.5rem;
}

section:not(#home) {
    padding: 4rem;
    text-align: center;
}

main {
    padding: 4rem;
    text-align: center;
}

h2 {
    font-size: 3rem;
    margin-bottom: 1.5rem;
}

p {
    font-size: 1.25rem;
}

.menu-list {
    list-style: none;
}

.menu-list > li {
    background-color: var(--color-light);
    border-radius: .5rem;
    box-shadow: 0 .25 12px -4px rgba(0, 0, 0, 0.1);
    display: inline-block;
    margin: 1.5rem;
    height: 28rem;
    width: 28rem;
    text-align: left;
}

.menu-list img {
    border-top-left-radius: .5rem;
    border-top-right-radius: .5rem;
    object-fit: cover;
    width: 100%;
}

.menu-list h3, .menu-list p {
    padding: 1rem 1.25rem;
}

#about {
    background-image: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 0) 0%,
    rgba(0, 0, 0, 0.8) 100%
    ),
    url("imagens/pexels-eneida-nieves-905847.jpg");
    background-size: cover;
    background-position: center;
    color: var(--color-white);
}

address {
    margin: 2rem 0;
    font-style: italic;
}

address > * {
    display: inline-block;
    margin: 1.5rem;
    text-align: left;
}

footer {
    background-color: var(--color-dark);
    color: var(--color-white);
    padding: 2rem;
    text-align: center;
}
