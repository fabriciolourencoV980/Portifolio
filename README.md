
<!DOCTYPE html>
<html lang="Pt-Br">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Férias dos sonhos</title>
    <link rel="stylesheet" href="style/style.css" />
    <link rel="shortcut icon" href="img/parque.png" type="image/x-icon" />

    <!-- Ícones -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
      integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
  </head>
  <body>
    <div class="container">
      <div class="navbar-container">
        <nav>
          <a href="#">
            <img src="img/Icone.jpg" alt="Icone" class="logo" />
            <ul class="navbar-items">
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Preços</a>
              </li>
              <li>
                <a href="#">Contatos</a>
              </li>
              <li>
                <a href="#" class="default-btn">Entrar</a>
              </li>
            </ul>
          </a>
        </nav>
      </div>
      <main>
        <div class="main-banner">
          <h1>Hospede aqui</h1>
          <p>O melhor site de viagens e hospedagem!</p>
        </div>
        <section class="services-container">
          <ul>
            <li>
              <i class="fas fa-plane"></i>
              <h3>Passagens</h3>
              <p>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque
                beatae quas quisquam officia sequi odit ullam, qui nemo
                laudantium eligendi, corporis vero. Molestias nesciunt, officia
                quasi debitis veniam eum eaque. Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </li>
            <li>
              <i class="fas fa-passport"></i>
              <h3>Passaporte</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Cum
                tempore, nesciunt officia itaque cupiditate autem maxime ducimus
                voluptatem nobis facilis vel molestiae temporibus deserunt
                placeat a necessitatibus sint porro dolorem!
              </p>
            </li>
            <li>
              <i class="fas fa-map"></i>
              <h3>Locais Turisticos</h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga
                iusto laudantium officiis, optio magnam deleniti maxime dicta
                esse. Enim quam repellat dolorum amet iste molestias delectus
                quod in fugit nisi! Lorem, ipsum dolor. Lorem ipsum dolor sit
                amet consectetur adipisicing elit. Eos corrupti minus iusto
                recusan
              </p>
            </li>
          </ul>
        </section>
        <section class="pricing-container">
          <h2>Planos e preços</h2>
          <p>Selecione o Plano que melhor condiz com sua necessidade</p>
          <div class="plans-container">
            <div class="plan">
              <ul>
                <li class="price">R$1500</li>
                <li class="plan-name">Básico</li>
                <li>Café da manhã</li>
                <li>Almoço</li>
                <li>Janta</li>
                <li>Passeio tématico</li>
                <li class="plan-btn">Saber Mais</li>
              </ul>
            </div>
            <div class="plan">
              <ul>
                <li class="price">R$2500</li>
                <li class="plan-name">Intermediário</li>
                <li>Café da manhã</li>
                <li>Almoço</li>
                <li>Janta</li>
                <li>Serviço de quarto</li>
                <li class="plan-btn">Saber Mais</li>
              </ul>
            </div>
            <div class="plan">
              <ul>
                <li class="price recommended">R$3000</li>
                <li class="plan-name">Premium</li>
                <li>Café da manhã</li>
                <li>Almoço</li>
                <li>Janta</li>
                <li>Serviço de quarto</li>
                <li>Acesso a trilhas</li>
                <li class="plan-btn">Saber Mais</li>
              </ul>
            </div>
          </div>
        </section>
        <section class="searchdomain-container">
            <h2>Qual tipo de aventuro você deseja!</h2>
            <p>Verifique qual melhor se encaixa em seu bolso</p>
            <form>
                <input 
                type="text"
                name="domain"
                id="domain"
                placeholder="Digite o Plano desejado"/>
                <input type="submit" value="procurar plano">
            </form>
        </section>
        <section class="contact-container">
          <h2>Entre em contato Já</h2>
          <p>
            Entre em contato com nossa equipe para obter mais informações
            referente aos planos de hospedagem
          </p>
           <form>
            <input type="text" name="name" id="name" placeholder="Seu nome">
            <input type="email" name="email" id="email" placeholder="Seu e-mail">
            <textarea name="message" id="message" placeholder="Descreva o que você precisa"></textarea>
            <input type="submit" value="enviar">
        </form>
        </section>
      </main>
    </div>
  </body>
</html>

