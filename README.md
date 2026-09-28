// ==================== index.html ====================
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Instituto Viver Bem - Organização sem fins lucrativos dedicada à inclusão social e ao apoio comunitário.">
<link rel="stylesheet" href="css/style.css">
<title>Instituto Viver Bem - Início</title>
</head>
<body>
<a href="#conteudo-principal" class="skip-link">Pular para o conteúdo principal</a>
<header>
  <div class="header-top">
    <h1>Instituto Viver Bem</h1>
      <button class="nav-toggle" aria-expanded="false" aria-controls="menu-principal" aria-label="Abrir menu de navegação">
    <span class="hamburger-icon"></span>
  </button>
    <button type="button" class="theme-toggle" id="btn-tema" aria-pressed="false">🌙 Modo escuro</button>
  </div>
  <nav aria-label="Navegação principal">
    <ul id="menu-principal" class="menu-principal">
      <li><a href="index.html" aria-current="page">Início</a></li>
      <li class="tem-submenu">
        <a href="projetos.html" aria-haspopup="true" aria-expanded="false">Projetos</a>
        <ul class="submenu">
          <li><a href="projetos.html#doacoes">Campanhas de Doação</a></li>
          <li><a href="projetos.html#voluntariado">Voluntariado</a></li>
        </ul>
      </li>
      <li><a href="cadastro.html">Participe</a></li>
    </ul>
  </nav>
</header>
<main class="container" id="conteudo-principal" tabindex="-1">
  <section class="col-12" aria-labelledby="apresentacao">
    <h2 id="apresentacao">Quem Somos</h2>
    <picture><source type="image/webp" srcset="imagens/ong-400.webp 400w, imagens/ong-800.webp 800w" sizes="(max-width: 800px) 100vw, 800px"><img src="imagens/ong-800.jpg" srcset="imagens/ong-400.jpg 400w, imagens/ong-800.jpg 800w" sizes="(max-width: 800px) 100vw, 800px" width="800" height="400" alt="Voluntários realizando uma ação social comunitária"></picture>
    <p>O Instituto Viver Bem é uma organização sem fins lucrativos dedicada à promoção da inclusão social e à melhoria da qualidade de vida de pessoas e famílias em situação de vulnerabilidade.</p>
    <p>Por meio de projetos sociais, ações comunitárias e do trabalho voluntário, buscamos transformar realidades e fortalecer a solidariedade em nossa comunidade.</p>
  </section>
  <section class="col-12 col-md-6" aria-labelledby="missao">
    <h2 id="missao">Nossa Missão</h2>
    <p>Promover oportunidades, inclusão e apoio social por meio de iniciativas que valorizem a dignidade humana e incentivem a participação da comunidade.</p>
  </section>
  <section class="col-12 col-md-6" aria-labelledby="contato">
    <h2 id="contato">Entre em Contato</h2>
    <address>
      <p><strong>Endereço:</strong> Rua da Solidariedade, 100 - Centro</p>
      <p><strong>Cidade:</strong> Ouro Preto - MG</p>
      <p><strong>Telefone:</strong> (31) 3551-0000</p>
      <p><strong>E-mail:</strong> contato@institutoviverbem.org.br</p>
    </address>
  </section>
</main>
<footer>
  <p>&copy; 2026 Instituto Viver Bem. Todos os direitos reservados.</p>
</footer>
<script src="js/script.js"></script>
</body>
</html>

// ==================== projetos.html ====================
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Conheça os projetos sociais, campanhas de doação e oportunidades de voluntariado do Instituto Viver Bem.">
<link rel="stylesheet" href="css/style.css">
<title>Instituto Viver Bem - Projetos</title>
</head>
<body>
<a href="#conteudo-principal" class="skip-link">Pular para o conteúdo principal</a>
<header>
  <div class="header-top">
    <h1>Projetos e Ações Sociais</h1>
      <button class="nav-toggle" aria-expanded="false" aria-controls="menu-principal" aria-label="Abrir menu de navegação">
    <span class="hamburger-icon"></span>
  </button>
    <button type="button" class="theme-toggle" id="btn-tema" aria-pressed="false">🌙 Modo escuro</button>
  </div>
  <nav aria-label="Navegação principal">
    <ul id="menu-principal" class="menu-principal">
      <li><a href="index.html">Início</a></li>
      <li class="tem-submenu">
        <a href="projetos.html" aria-haspopup="true" aria-expanded="false" aria-current="page">Projetos</a>
        <ul class="submenu">
          <li><a href="projetos.html#doacoes">Campanhas de Doação</a></li>
          <li><a href="projetos.html#voluntariado">Voluntariado</a></li>
        </ul>
      </li>
      <li><a href="cadastro.html">Participe</a></li>
    </ul>
  </nav>
</header>
<main class="container" id="conteudo-principal" tabindex="-1">
  <section class="col-12" aria-labelledby="introducao">
    <h2 id="introducao">Conheça Nossos Projetos</h2>
    <p>O Instituto Viver Bem desenvolve ações sociais voltadas ao apoio de pessoas e famílias em situação de vulnerabilidade. Conheça algumas das nossas principais iniciativas.</p>
    <div class="alerta alerta-info" role="status">
      <span class="alerta-icone" aria-hidden="true">ℹ</span>
      <p>Novas vagas de voluntariado abertas para o próximo trimestre. Cadastre-se e participe!</p>
    </div>
  </section>

  <section class="col-12" aria-labelledby="projetos-sociais">
    <h2 id="projetos-sociais">Projetos Sociais</h2>
    <div class="cards-grid">
      <article class="card-projeto col-12 col-md-4">
        <span class="badge badge-urgente">Urgente</span>
        <h3>Alimento para Todos</h3>
        <p>Campanha destinada à arrecadação e distribuição de alimentos para famílias em situação de vulnerabilidade.</p>
        <span class="badge badge-doacao">Aceita doação</span>
      </article>
      <article class="card-projeto col-12 col-md-4">
        <span class="badge badge-voluntariado">Voluntariado</span>
        <h3>Educação que Transforma</h3>
        <p>Projeto que busca oferecer apoio educacional e atividades de aprendizagem para crianças e adolescentes da comunidade.</p>
        <span class="badge badge-voluntariado">Aceita voluntários</span>
      </article>
      <article class="card-projeto col-12 col-md-4">
        <span class="badge badge-doacao">Doação</span>
        <h3>Ação Comunitária</h3>
        <p>Realização de atividades comunitárias, campanhas de conscientização e ações de apoio social.</p>
        <span class="badge badge-doacao">Aceita doação</span>
      </article>
    </div>
  </section>

  <section class="col-12 col-md-6" aria-labelledby="doacoes">
    <h2 id="doacoes">Campanhas de Doação</h2>
    <p>As doações ajudam a manter nossos projetos e ampliar o atendimento às pessoas beneficiadas pelas ações da instituição.</p>
    <ul>
      <li>Doação de alimentos não perecíveis.</li>
      <li>Doação de materiais escolares.</li>
      <li>Contribuição financeira.</li>
      <li>Doação de materiais de higiene.</li>
    </ul>
    <p>Para demonstrar interesse em contribuir, acesse a página <a href="cadastro.html">Participe</a>.</p>
  </section>

  <section class="col-12 col-md-6" aria-labelledby="voluntariado">
    <h2 id="voluntariado">Voluntariado</h2>
    <p>O trabalho voluntário é uma forma de contribuir diretamente com nossas ações e ajudar no desenvolvimento dos projetos sociais.</p>
    <ul>
      <li>Participação em campanhas de arrecadação.</li>
      <li>Auxílio em eventos comunitários.</li>
      <li>Apoio às atividades educacionais.</li>
      <li>Colaboração em ações sociais.</li>
    </ul>
    <p>Se você deseja fazer parte das nossas ações, <a href="cadastro.html">realize seu cadastro</a>.</p>
  </section>

  <section class="col-12 chamada-participar" aria-labelledby="participar">
    <h2 id="participar">Como Participar</h2>
    <p>Você pode contribuir com o Instituto Viver Bem realizando uma doação ou participando como voluntário. Preencha nosso formulário para demonstrar seu interesse.</p>
    <p>
      <a class="btn-cta" href="cadastro.html">Quero participar</a>
      <button type="button" class="btn-cta" id="btn-abrir-modal" style="background-color: var(--color-primary);">Como funciona a doação?</button>
    </p>
  </section>
</main>

<div class="modal-overlay" id="modal-doacao" role="dialog" aria-modal="true" aria-labelledby="modal-titulo">
  <div class="modal-caixa">
    <div class="modal-cabecalho">
      <h3 id="modal-titulo">Como funciona sua doação</h3>
      <button type="button" class="modal-fechar" id="btn-fechar-modal" aria-label="Fechar">&times;</button>
    </div>
    <p>Sua contribuição é revertida diretamente para os projetos sociais em andamento. Após o cadastro, nossa equipe entra em contato para combinar a forma de doação (PIX, transferência ou entrega presencial).</p>
    <p><strong>Transparência total:</strong> relatórios trimestrais são enviados a todos os doadores cadastrados.</p>
  </div>
</div>

<div class="toast toast-sucesso" id="toast-feedback" role="status" aria-live="polite">
  <span aria-hidden="true">✓</span>
  <span id="toast-mensagem">Ação realizada com sucesso!</span>
</div>

<footer>
  <p>&copy; 2026 Instituto Viver Bem. Todos os direitos reservados.</p>
  <address>Rua da Solidariedade, 100 - Centro - Ouro Preto - MG</address>
</footer>
<script src="js/script.js"></script>
</body>
</html>

// ==================== cadastro.html ====================
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Cadastre-se no Instituto Viver Bem para participar como voluntário ou contribuir com nossas ações sociais.">
<link rel="stylesheet" href="css/style.css">
<title>Instituto Viver Bem - Participe</title>
</head>
<body>
<a href="#conteudo-principal" class="skip-link">Pular para o conteúdo principal</a>
<header>
  <div class="header-top">
    <h1>Participe do Instituto Viver Bem</h1>
      <button class="nav-toggle" aria-expanded="false" aria-controls="menu-principal" aria-label="Abrir menu de navegação">
    <span class="hamburger-icon"></span>
  </button>
    <button type="button" class="theme-toggle" id="btn-tema" aria-pressed="false">🌙 Modo escuro</button>
  </div>
  <nav aria-label="Navegação principal">
    <ul id="menu-principal" class="menu-principal">
      <li><a href="index.html">Início</a></li>
      <li class="tem-submenu">
        <a href="projetos.html" aria-haspopup="true" aria-expanded="false">Projetos</a>
        <ul class="submenu">
          <li><a href="projetos.html#doacoes">Campanhas de Doação</a></li>
          <li><a href="projetos.html#voluntariado">Voluntariado</a></li>
        </ul>
      </li>
      <li><a href="cadastro.html" aria-current="page">Participe</a></li>
    </ul>
  </nav>
</header>
<main class="container" id="conteudo-principal" tabindex="-1">
  <section class="col-12" aria-labelledby="titulo-cadastro">
    <h2 id="titulo-cadastro">Cadastro de Participação</h2>
    <p>Preencha o formulário abaixo para demonstrar seu interesse em participar das ações do Instituto Viver Bem.</p>

    <form action="#" method="post">
      <fieldset>
        <legend>Dados Pessoais</legend>
        <div class="form-group">
          <label for="nome">Nome completo:</label>
          <input type="text" id="nome" name="nome" aria-describedby="erro-nome" required autocomplete="name">
        </div>
        <div class="form-group">
          <label for="cpf">CPF:</label>
          <input type="text" id="cpf" name="cpf" aria-describedby="erro-cpf" placeholder="000.000.000-00" pattern="[0-9]{3}\.[0-9]{3}\.[0-9]{3}-[0-9]{2}" title="Digite o CPF no formato 000.000.000-00" maxlength="14" required autocomplete="off">
        </div>
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email" name="email" aria-describedby="erro-email" placeholder="seuemail@exemplo.com" required autocomplete="email">
        </div>
        <div class="form-group">
          <label for="nascimento">Data de nascimento:</label>
          <input type="date" id="nascimento" name="nascimento" required autocomplete="bday">
        </div>
      </fieldset>

      <fieldset>
        <legend>Contato e Endereço</legend>
        <div class="form-group">
          <label for="telefone">Telefone:</label>
          <input type="tel" id="telefone" name="telefone" aria-describedby="erro-telefone" placeholder="(00) 00000-0000" pattern="\([0-9]{2}\) [0-9]{5}-[0-9]{4}" title="Digite o telefone no formato (00) 00000-0000" maxlength="15" required autocomplete="tel">
        </div>
        <div class="form-group">
          <label for="cep">CEP:</label>
          <input type="text" id="cep" name="cep" aria-describedby="erro-cep" placeholder="00000-000" pattern="[0-9]{5}-[0-9]{3}" title="Digite o CEP no formato 00000-000" maxlength="9" required autocomplete="postal-code">
        </div>
        <div class="form-group">
          <label for="endereco">Endereço:</label>
          <input type="text" id="endereco" name="endereco" required autocomplete="address-line1">
        </div>
        <div class="form-group">
          <label for="numero">Número:</label>
          <input type="text" id="numero" name="numero" required autocomplete="off">
        </div>
        <div class="form-group">
          <label for="bairro">Bairro:</label>
          <input type="text" id="bairro" name="bairro" required autocomplete="address-level3">
        </div>
        <div class="form-group">
          <label for="cidade">Cidade:</label>
          <input type="text" id="cidade" name="cidade" required autocomplete="address-level2">
        </div>
        <div class="form-group">
          <label for="estado">Estado:</label>
          <select id="estado" name="estado" required autocomplete="address-level1">
            <option value="">Selecione</option>
            <option value="AC">Acre</option>
            <option value="AL">Alagoas</option>
            <option value="AP">Amapá</option>
            <option value="AM">Amazonas</option>
            <option value="BA">Bahia</option>
            <option value="CE">Ceará</option>
            <option value="DF">Distrito Federal</option>
            <option value="ES">Espírito Santo</option>
            <option value="GO">Goiás</option>
            <option value="MA">Maranhão</option>
            <option value="MT">Mato Grosso</option>
            <option value="MS">Mato Grosso do Sul</option>
            <option value="MG">Minas Gerais</option>
            <option value="PA">Pará</option>
            <option value="PB">Paraíba</option>
            <option value="PR">Paraná</option>
            <option value="PE">Pernambuco</option>
            <option value="PI">Piauí</option>
            <option value="RJ">Rio de Janeiro</option>
            <option value="RN">Rio Grande do Norte</option>
            <option value="RS">Rio Grande do Sul</option>
            <option value="RO">Rondônia</option>
            <option value="RR">Roraima</option>
            <option value="SC">Santa Catarina</option>
            <option value="SP">São Paulo</option>
            <option value="SE">Sergipe</option>
            <option value="TO">Tocantins</option>
          </select>
        </div>
      </fieldset>

      <fieldset>
        <legend>Forma de Participação</legend>
        <p>Como você deseja participar?</p>
        <div class="radio-group">
          <input type="radio" id="doacao" name="participacao" value="doacao" required>
          <label for="doacao">Quero contribuir com uma doação</label>
        </div>
        <div class="radio-group">
          <input type="radio" id="voluntario" name="participacao" value="voluntario">
          <label for="voluntario">Quero ser voluntário</label>
        </div>
        <div class="radio-group">
          <input type="radio" id="ambos" name="participacao" value="ambos">
          <label for="ambos">Quero doar e ser voluntário</label>
        </div>
      </fieldset>

      <fieldset>
        <legend>Observações</legend>
        <div class="form-group">
          <label for="mensagem">Conte-nos como gostaria de contribuir:</label>
          <textarea id="mensagem" name="mensagem" rows="6" cols="50" placeholder="Digite sua mensagem..."></textarea>
        </div>
      </fieldset>

      <div class="botoes-form">
        <button type="submit">Enviar cadastro</button>
        <button type="reset">Limpar formulário</button>
      </div>
    </form>
  </section>
</main>
<footer>
  <p>&copy; 2026 Instituto Viver Bem. Todos os direitos reservados.</p>
  <address>Rua da Solidariedade, 100 - Centro - Ouro Preto - MG</address>
</footer>
<script src="js/script.js"></script>
</body>
</html>

// ==================== css/style.css ====================
/* ==========================================================================
   DESIGN SYSTEM - Variáveis customizadas
   ========================================================================== */
:root {
  /* Cores primárias (identidade institucional) */
  --color-primary: #2E7D32;
  --color-primary-dark: #1B5E20;
  --color-primary-light: #81C784;

  /* Cores secundárias (ações e destaque) */
  --color-secondary: #C2470A;   /* ajustado de #EF6C00: contraste 3.08:1 -> 5.00:1 com texto branco (WCAG AA) */
  --color-secondary-dark: #A83B08;
  --color-secondary-decor: #EF6C00; /* tom vivo original, reservado para decoração sem texto sobreposto */

  /* Tons neutros */
  --color-neutral-900: #212121;
  --color-neutral-600: #616161;
  --color-neutral-300: #E0E0E0;
  --color-neutral-100: #F5F5F5;
  --color-white: #FFFFFF;      /* fixo: usado para texto/ícones sobre fundos coloridos (header, toast) */
  --color-surface: #FFFFFF;    /* variável: fundo da página, inputs e cartões flutuantes (muda no dark mode) */

  /* Feedback */
  --color-error: #C62828;
  --color-success: #2E7D32;

  /* Tipografia - escala modular */
  --font-family-base: 'Segoe UI', Arial, sans-serif;
  --font-size-sm: 0.875rem;
  --font-size-base: 1rem;
  --font-size-lg: 1.25rem;
  --font-size-xl: 1.75rem;
  --font-size-2xl: 2.5rem;

  /* Espaçamentos modulares (base 8px) */
  --space-1: 0.25rem;
  --space-2: 0.5rem;
  --space-3: 1rem;
  --space-4: 1.5rem;
  --space-5: 2rem;
  --space-6: 3rem;

  /* Outros */
  --radius-base: 8px;
  --shadow-card: 0 2px 8px rgba(0, 0, 0, 0.1);
  --transition-base: 0.2s ease-in-out;
}

/* ==========================================================================
   MODO ESCURO - via preferência do sistema OU toggle manual (data-theme)
   ========================================================================== */
@media (prefers-color-scheme: dark) {
  :root:not([data-theme="light"]) {
    --color-neutral-900: #F5F5F5;   /* texto principal vira claro */
    --color-neutral-600: #BDBDBD;
    --color-neutral-300: #424242;
    --color-neutral-100: #1E1E1E;   /* fundos de cartão escurecem */
    --color-surface: #121212;       /* fundo da página/inputs/modal escurece */
    --color-primary-light: #A5D6A7; /* clareado para manter contraste sobre fundo escuro */
  }
}

:root[data-theme="dark"] {
  --color-neutral-900: #F5F5F5;
  --color-neutral-600: #BDBDBD;
  --color-neutral-300: #424242;
  --color-neutral-100: #1E1E1E;
  --color-surface: #121212;
  --color-primary-light: #A5D6A7;
}

/* Botão de alternância de tema */
.theme-toggle {
  background: none;
  border: 2px solid var(--color-white);
  color: var(--color-white);
  border-radius: var(--radius-base);
  padding: var(--space-1) var(--space-3);
  cursor: pointer;
  font-size: var(--font-size-sm);
}

/* ==========================================================================
   RESET E BASE
   ========================================================================== */
* {
  box-sizing: border-box;
}

/* Skip link: oculto por padrão, visível ao receber foco via teclado */
.skip-link {
  position: absolute;
  top: -60px;
  left: 0;
  background-color: var(--color-primary-dark);
  color: var(--color-white);
  padding: var(--space-2) var(--space-4);
  z-index: 2000;
  transition: top var(--transition-base);
}

.skip-link:focus {
  top: 0;
}

/* Foco visível consistente em toda a aplicação (WCAG 2.4.7) */
a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible,
[tabindex]:focus-visible {
  outline: 3px solid var(--color-primary-light);
  outline-offset: 2px;
}

body {
  margin: 0;
  font-family: var(--font-family-base);
  font-size: var(--font-size-base);
  color: var(--color-neutral-900);
  background-color: var(--color-surface);
  line-height: 1.6;
}

h1, h2, h3 {
  color: var(--color-primary-dark);
  line-height: 1.2;
}

h1 { font-size: var(--font-size-2xl); margin: 0; }
h2 { font-size: var(--font-size-xl); margin-top: 0; }
h3 { font-size: var(--font-size-lg); margin-top: 0; }

p { margin: 0 0 var(--space-3); }

a {
  color: var(--color-primary);
  text-decoration: none;
}

a:hover, a:focus {
  color: var(--color-primary-dark);
  text-decoration: underline;
}

img {
  max-width: 100%;
  height: auto;
  border-radius: var(--radius-base);
}

/* ==========================================================================
   GRID - Sistema de 12 colunas
   ========================================================================== */
.container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: var(--space-4);
  max-width: 1200px;
  margin: 0 auto;
  padding: var(--space-5) var(--space-3);
}

.col-12 { grid-column: span 12; }
.col-8  { grid-column: span 8; }
.col-6  { grid-column: span 6; }
.col-4  { grid-column: span 4; }
.col-3  { grid-column: span 3; }

/* Breakpoints (mobile-first) */
@media (min-width: 480px) {
  .container { padding: var(--space-5) var(--space-4); }
}

@media (min-width: 768px) {
  .col-md-6 { grid-column: span 6; }
  .col-md-4 { grid-column: span 4; }
}

@media (min-width: 992px) {
  .col-lg-4 { grid-column: span 4; }
  .col-lg-3 { grid-column: span 3; }
}

@media (min-width: 1200px) {
  .container { padding: var(--space-6) 0; }
}

@media (min-width: 1440px) {
  .container { max-width: 1320px; }
}

/* ==========================================================================
   HEADER E NAVEGAÇÃO (Flexbox)
   ========================================================================== */
header {
  display: flex;
  flex-direction: column;
  gap: var(--space-3);
  background-color: var(--color-primary);
  color: var(--color-white);
  padding: var(--space-4) var(--space-4);
}

.header-top {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  gap: var(--space-3);
}

header h1 {
  color: var(--color-white);
  font-size: var(--font-size-xl);
  margin: 0;
}

/* Botão hambúrguer (visível apenas em telas pequenas) */
.nav-toggle {
  display: block;
  flex-shrink: 0;
  background: none;
  border: 2px solid var(--color-white);
  border-radius: var(--radius-base);
  padding: var(--space-2) var(--space-3);
  cursor: pointer;
}

.hamburger-icon,
.hamburger-icon::before,
.hamburger-icon::after {
  display: block;
  width: 22px;
  height: 3px;
  background-color: var(--color-white);
  border-radius: 2px;
  transition: transform var(--transition-base), opacity var(--transition-base);
}

.hamburger-icon::before { content: ""; margin-bottom: 5px; }
.hamburger-icon::after { content: ""; margin-top: 5px; }

/* Estado aberto do hambúrguer -> transforma em "X" */
.nav-toggle[aria-expanded="true"] .hamburger-icon {
  background-color: transparent;
}
.nav-toggle[aria-expanded="true"] .hamburger-icon::before {
  transform: translateY(4px) rotate(45deg);
}
.nav-toggle[aria-expanded="true"] .hamburger-icon::after {
  transform: translateY(-4px) rotate(-45deg);
}

/* Menu principal: escondido por padrão no mobile, exibido via classe .menu-aberto */
nav {
  width: 100%;
}

.menu-principal {
  display: flex;
  flex-direction: column;
  gap: var(--space-1);
  list-style: none;
  margin: 0;
  padding: 0;
  width: 100%;
  max-height: 0;
  overflow: hidden;
  transition: max-height var(--transition-base);
}

.menu-principal.menu-aberto {
  max-height: 400px;
}

.menu-principal > li > a {
  color: var(--color-white);
  font-weight: bold;
  display: block;
  padding: var(--space-2);
  border-radius: var(--radius-base);
  transition: background-color var(--transition-base);
}

.menu-principal > li > a:hover,
.menu-principal > li > a:focus {
  background-color: var(--color-primary-dark);
  text-decoration: none;
}

/* Submenu (dropdown) - fechado por padrão, controlado por classe no mobile */
.submenu {
  list-style: none;
  margin: 0;
  padding-left: var(--space-4);
  display: none;
}

.tem-submenu.submenu-aberto .submenu {
  display: block;
}

.submenu a {
  color: var(--color-white);
  display: block;
  padding: var(--space-1) var(--space-2);
  font-size: var(--font-size-sm);
}

@media (min-width: 768px) {
  header {
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    position: relative;
  }

  .nav-toggle {
    display: none;
  }

  .menu-principal {
    flex-direction: row;
    gap: var(--space-4);
    width: auto;
    max-height: none;
    overflow: visible;
  }

  .tem-submenu {
    position: relative;
  }

  /* Dropdown no desktop: hover ou foco no teclado */
  .submenu {
    display: block;
    position: absolute;
    top: 100%;
    left: 0;
    min-width: 220px;
    background-color: var(--color-primary-dark);
    border-radius: var(--radius-base);
    padding: var(--space-2) 0;
    box-shadow: var(--shadow-card);
    opacity: 0;
    visibility: hidden;
    transform: translateY(-8px);
    transition: opacity var(--transition-base), transform var(--transition-base), visibility var(--transition-base);
  }

  .tem-submenu:hover .submenu {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
  }

  .tem-submenu:focus-within .submenu {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
  }

  .tem-submenu.submenu-aberto .submenu {
    opacity: 1;
    visibility: visible;
    transform: translateY(0);
  }
}

/* ==========================================================================
   CARDS DE PROJETOS (Flexbox)
   ========================================================================== */
.cards-grid {
  display: flex;
  flex-wrap: wrap;
  gap: var(--space-4);
}

.card-projeto {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  background-color: var(--color-neutral-100);
  border: 1px solid var(--color-neutral-300);
  border-left: 4px solid var(--color-primary);
  border-radius: var(--radius-base);
  padding: var(--space-4);
  box-shadow: var(--shadow-card);
  transition: transform var(--transition-base), box-shadow var(--transition-base), border-color var(--transition-base);
}

.card-projeto:hover,
.card-projeto:focus-within {
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.15);
  border-left-color: var(--color-secondary);
}

/* ==========================================================================
   CHAMADA PARA AÇÃO / BOTÕES
   ========================================================================== */
.chamada-participar {
  background-color: var(--color-neutral-100);
  border-radius: var(--radius-base);
  padding: var(--space-5);
  text-align: center;
}

.btn-cta,
button[type="submit"] {
  display: inline-block;
  background-color: var(--color-secondary);
  color: var(--color-white);
  font-weight: bold;
  border: none;
  padding: var(--space-2) var(--space-4);
  border-radius: var(--radius-base);
  cursor: pointer;
  box-shadow: var(--shadow-card);
  transition: background-color var(--transition-base),
              transform var(--transition-base),
              box-shadow var(--transition-base);
}

.btn-cta:hover,
button[type="submit"]:hover {
  background-color: var(--color-secondary-dark);
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.18);
}

.btn-cta:focus-visible,
button[type="submit"]:focus-visible {
  outline: 3px solid var(--color-primary-light);
  outline-offset: 2px;
}

.btn-cta:active,
button[type="submit"]:active {
  transform: translateY(1px) scale(0.98);
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.15);
}

button[type="submit"]:disabled {
  background-color: var(--color-neutral-300);
  color: var(--color-neutral-600);
  cursor: not-allowed;
  box-shadow: none;
  transform: none;
}

button[type="reset"] {
  display: inline-block;
  background-color: transparent;
  color: var(--color-neutral-600);
  border: 1px solid var(--color-neutral-300);
  padding: var(--space-2) var(--space-4);
  border-radius: var(--radius-base);
  cursor: pointer;
  transition: background-color var(--transition-base), color var(--transition-base);
}

button[type="reset"]:hover {
  background-color: var(--color-neutral-100);
  color: var(--color-neutral-900);
}

button[type="reset"]:focus-visible {
  outline: 3px solid var(--color-primary-light);
  outline-offset: 2px;
}

button[type="reset"]:active {
  transform: translateY(1px) scale(0.98);
}

/* ==========================================================================
   FORMULÁRIO (Flexbox)
   ========================================================================== */
fieldset {
  display: flex;
  flex-wrap: wrap;
  gap: var(--space-3);
  border: 1px solid var(--color-neutral-300);
  border-radius: var(--radius-base);
  padding: var(--space-4);
  margin-bottom: var(--space-4);
}

legend {
  font-weight: bold;
  color: var(--color-primary-dark);
  padding: 0 var(--space-2);
}

.form-group {
  display: flex;
  flex-direction: column;
  gap: var(--space-1);
  flex: 1 1 220px;
}

label {
  font-size: var(--font-size-sm);
  font-weight: bold;
  color: var(--color-neutral-900);
}

input, select, textarea {
  font-family: inherit;
  font-size: var(--font-size-base);
  padding: var(--space-2);
  border: 1px solid var(--color-neutral-300);
  border-radius: var(--radius-base);
  background-color: var(--color-surface);
  transition: border-color var(--transition-base), box-shadow var(--transition-base);
}

input:focus, select:focus, textarea:focus {
  outline: none;
  border-color: var(--color-primary);
  box-shadow: 0 0 0 3px rgba(46, 125, 50, 0.2);
}

/* Feedback de preenchimento: só aparece depois que o usuário interage (:not(:placeholder-shown)) */
input:not(:placeholder-shown):invalid,
textarea:not(:placeholder-shown):invalid {
  border-color: var(--color-error);
  background-image: linear-gradient(to right, rgba(198,40,40,0.04), transparent);
}

input:not(:placeholder-shown):invalid:focus {
  box-shadow: 0 0 0 3px rgba(198, 40, 40, 0.15);
}

input:not(:placeholder-shown):valid,
textarea:not(:placeholder-shown):valid {
  border-color: var(--color-success);
}

input:not(:placeholder-shown):valid:focus {
  box-shadow: 0 0 0 3px rgba(46, 125, 50, 0.15);
}

/* select e campos sem placeholder usam :user-invalid quando suportado, fallback :invalid simples */
select:invalid,
input[type="date"]:invalid {
  border-color: var(--color-neutral-300);
}

select:focus:invalid,
input[type="date"]:focus:invalid {
  border-color: var(--color-error);
}

.radio-group {
  display: flex;
  align-items: center;
  gap: var(--space-2);
  flex-basis: 100%;
}

.botoes-form {
  display: flex;
  gap: var(--space-3);
  justify-content: flex-end;
  flex-basis: 100%;
}

/* ==========================================================================
   FOOTER (Flexbox)
   ========================================================================== */
footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: var(--space-2);
  background-color: var(--color-neutral-900);
  color: var(--color-neutral-100);
  text-align: center;
  padding: var(--space-4);
  font-size: var(--font-size-sm);
}

footer address {
  font-style: normal;
}

@media (min-width: 768px) {
  footer {
    flex-direction: row;
    justify-content: space-between;
    text-align: left;
  }
}

/* ==========================================================================
   COMPONENTES DE FEEDBACK - Badges, Alertas, Toast e Modal
   ========================================================================== */

/* Badges */
.badge {
  display: inline-flex;
  align-self: flex-start;
  align-items: center;
  gap: var(--space-1);
  font-size: var(--font-size-sm);
  font-weight: bold;
  padding: var(--space-1) var(--space-2);
  border-radius: 999px;
  line-height: 1.4;
}

.badge-doacao {
  background-color: rgba(46, 125, 50, 0.12);
  color: var(--color-primary-dark);
}

.badge-voluntariado {
  background-color: rgba(239, 108, 0, 0.12);
  color: var(--color-secondary-dark);
}

.badge-urgente {
  background-color: rgba(198, 40, 40, 0.12);
  color: var(--color-error);
}

/* Alertas contextuais */
.alerta {
  display: flex;
  align-items: flex-start;
  gap: var(--space-3);
  padding: var(--space-3) var(--space-4);
  border-radius: var(--radius-base);
  border-left: 4px solid transparent;
  margin-bottom: var(--space-4);
}

.alerta-sucesso {
  background-color: rgba(46, 125, 50, 0.08);
  border-left-color: var(--color-success);
  color: var(--color-primary-dark);
}

.alerta-erro {
  background-color: rgba(198, 40, 40, 0.08);
  border-left-color: var(--color-error);
  color: var(--color-error);
}

.alerta-info {
  background-color: rgba(2, 119, 189, 0.08);
  border-left-color: #0277BD;
  color: #01579B;
}

.alerta-icone {
  font-weight: bold;
  font-size: var(--font-size-lg);
}

/* Toast (notificação não obstrutiva) */
.toast {
  position: fixed;
  bottom: var(--space-4);
  right: var(--space-4);
  display: flex;
  align-items: center;
  gap: var(--space-2);
  background-color: var(--color-neutral-900);
  color: var(--color-white);
  padding: var(--space-3) var(--space-4);
  border-radius: var(--radius-base);
  box-shadow: 0 6px 20px rgba(0, 0, 0, 0.25);
  opacity: 0;
  visibility: hidden;
  transform: translateY(16px);
  transition: opacity var(--transition-base), transform var(--transition-base), visibility var(--transition-base);
  z-index: 1000;
}

.toast.toast-visivel {
  opacity: 1;
  visibility: visible;
  transform: translateY(0);
}

.toast-sucesso { border-left: 4px solid var(--color-success); }
.toast-erro { border-left: 4px solid var(--color-error); }

/* Modal */
.modal-overlay {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: var(--space-4);
  opacity: 0;
  visibility: hidden;
  transition: opacity var(--transition-base), visibility var(--transition-base);
  z-index: 1000;
}

.modal-overlay.modal-visivel {
  opacity: 1;
  visibility: visible;
}

.modal-caixa {
  background-color: var(--color-surface);
  border-radius: var(--radius-base);
  padding: var(--space-5);
  max-width: 480px;
  width: 100%;
  box-shadow: 0 12px 32px rgba(0, 0, 0, 0.25);
  transform: scale(0.95);
  transition: transform var(--transition-base);
}

.modal-overlay.modal-visivel .modal-caixa {
  transform: scale(1);
}

.modal-cabecalho {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: var(--space-3);
}

.modal-fechar {
  background: none;
  border: none;
  font-size: var(--font-size-lg);
  cursor: pointer;
  color: var(--color-neutral-600);
  line-height: 1;
  padding: var(--space-1);
}

.modal-fechar:hover,
.modal-fechar:focus-visible {
  color: var(--color-error);
}

// ==================== js/script.js ====================
// Alternância de tema claro/escuro, persistida em localStorage
(function () {
  const CHAVE_TEMA = 'ivb_tema';
  const btnTema = document.getElementById('btn-tema');
  const temaSalvo = localStorage.getItem(CHAVE_TEMA);

  function aplicarTema(tema) {
    document.documentElement.setAttribute('data-theme', tema);
    if (btnTema) {
      btnTema.setAttribute('aria-pressed', String(tema === 'dark'));
      btnTema.textContent = tema === 'dark' ? '☀️ Modo claro' : '🌙 Modo escuro';
    }
  }

  // Aplica preferência salva assim que possível (evita "flash" de tema errado)
  if (temaSalvo) aplicarTema(temaSalvo);

  if (btnTema) {
    btnTema.addEventListener('click', function () {
      const atual = document.documentElement.getAttribute('data-theme');
      const novoTema = atual === 'dark' ? 'light' : 'dark';
      aplicarTema(novoTema);
      localStorage.setItem(CHAVE_TEMA, novoTema);
    });
  }
})();

// Modal e Toast (componentes de feedback)
document.addEventListener('DOMContentLoaded', function () {
  const btnAbrirModal = document.getElementById('btn-abrir-modal');
  const btnFecharModal = document.getElementById('btn-fechar-modal');
  const modal = document.getElementById('modal-doacao');
  const toast = document.getElementById('toast-feedback');

  let elementoComFocoAnterior = null;

  function elementosFocaveisNoModal() {
    return modal.querySelectorAll('a[href], button, input, select, textarea, [tabindex]:not([tabindex="-1"])');
  }

  function abrirModal() {
    elementoComFocoAnterior = document.activeElement; // guarda quem tinha foco antes de abrir
    modal.classList.add('modal-visivel');
    const focaveis = elementosFocaveisNoModal();
    if (focaveis.length) focaveis[0].focus(); // move o foco para dentro do modal
  }

  function fecharModal() {
    modal.classList.remove('modal-visivel');
    if (elementoComFocoAnterior) elementoComFocoAnterior.focus(); // devolve o foco à origem
  }

  function aprisionarFoco(evento) {
    if (!modal.classList.contains('modal-visivel') || evento.key !== 'Tab') return;
    const focaveis = Array.from(elementosFocaveisNoModal());
    if (!focaveis.length) return;
    const primeiro = focaveis[0];
    const ultimo = focaveis[focaveis.length - 1];

    if (evento.shiftKey && document.activeElement === primeiro) {
      evento.preventDefault();
      ultimo.focus();
    } else if (!evento.shiftKey && document.activeElement === ultimo) {
      evento.preventDefault();
      primeiro.focus();
    }
  }

  if (btnAbrirModal && modal) {
    btnAbrirModal.addEventListener('click', abrirModal);
    btnFecharModal.addEventListener('click', fecharModal);
    modal.addEventListener('click', function (e) {
      if (e.target === modal) fecharModal();
    });
    document.addEventListener('keydown', function (e) {
      if (e.key === 'Escape') fecharModal();
      aprisionarFoco(e);
    });
  }

  // Toast de exemplo: aparece automaticamente para demonstração visual
  if (toast) {
    setTimeout(function () {
      toast.classList.add('toast-visivel');
      setTimeout(function () {
        toast.classList.remove('toast-visivel');
      }, 4000);
    }, 1000);
  }
});

// Menu hambúrguer (mobile) e dropdown (desktop/mobile via toque)
document.addEventListener('DOMContentLoaded', function () {
  const navToggle = document.querySelector('.nav-toggle');
  const menuPrincipal = document.getElementById('menu-principal');

  if (navToggle && menuPrincipal) {
    navToggle.addEventListener('click', function () {
      const aberto = navToggle.getAttribute('aria-expanded') === 'true';
      navToggle.setAttribute('aria-expanded', String(!aberto));
      menuPrincipal.classList.toggle('menu-aberto');
    });
  }

  // Dropdown "Projetos": no toque (mobile), o clique no link-pai abre/fecha o submenu
  const itemComSubmenu = document.querySelector('.tem-submenu');
  if (itemComSubmenu) {
    const linkPai = itemComSubmenu.querySelector('> a');
    linkPai.addEventListener('click', function (evento) {
      if (window.innerWidth < 768) {
        evento.preventDefault();
        const aberto = itemComSubmenu.classList.toggle('submenu-aberto');
        linkPai.setAttribute('aria-expanded', String(aberto));
      }
    });
  }
});

// Máscaras de preenchimento para CPF, Telefone e CEP
document.addEventListener('DOMContentLoaded', function () {

  function aplicarMascaraCPF(campo) {
    campo.addEventListener('input', function () {
      let valor = campo.value.replace(/\D/g, '').slice(0, 11);
      valor = valor.replace(/(\d{3})(\d)/, '$1.$2');
      valor = valor.replace(/(\d{3})(\d)/, '$1.$2');
      valor = valor.replace(/(\d{3})(\d{1,2})$/, '$1-$2');
      campo.value = valor;
    });
  }

  function aplicarMascaraTelefone(campo) {
    campo.addEventListener('input', function () {
      let valor = campo.value.replace(/\D/g, '').slice(0, 11);
      valor = valor.replace(/(\d{2})(\d)/, '($1) $2');
      valor = valor.replace(/(\d{5})(\d{1,4})$/, '$1-$2');
      campo.value = valor;
    });
  }

  function aplicarMascaraCEP(campo) {
    campo.addEventListener('input', function () {
      let valor = campo.value.replace(/\D/g, '').slice(0, 8);
      valor = valor.replace(/(\d{5})(\d{1,3})$/, '$1-$2');
      campo.value = valor;
    });
  }

  const cpf = document.getElementById('cpf');
  const telefone = document.getElementById('telefone');
  const cep = document.getElementById('cep');

  if (cpf) aplicarMascaraCPF(cpf);
  if (telefone) aplicarMascaraTelefone(telefone);
  if (cep) aplicarMascaraCEP(cep);
});

// ==================== README.md ====================
# Instituto Viver Bem

Plataforma web para uma organização não-governamental (ONG) do terceiro setor, desenvolvida como projeto acadêmico da disciplina de Desenvolvimento Front-end (Universidade Cruzeiro do Sul Virtual). A aplicação simula um site institucional real, permitindo apresentar a ONG, divulgar projetos sociais e captar cadastros de doadores e voluntários.

## Sobre o projeto

O Instituto Viver Bem é uma ONG fictícia dedicada à inclusão social e ao apoio comunitário. O projeto nasceu como um conjunto de páginas HTML estáticas e evoluiu, ao longo de quatro Experiências Práticas, para uma Single Page Application (SPA) completa, estilizada, acessível e pronta para produção — refletindo o ciclo de vida real de uma aplicação front-end profissional.

## Tecnologias utilizadas

- **HTML5** semântico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** — Custom Properties (design system), CSS Grid (12 colunas), Flexbox, Media Queries
- **JavaScript (ES6 Modules)** — roteamento SPA, manipulação de DOM, validação de formulários
- **localStorage** — persistência de cadastros entre sessões
- **IMask.js** — máscaras de input (CPF, telefone, CEP) via CDN

## Funcionalidades

- Navegação SPA via hash routing, sem recarregamento de página
- Templates dinâmicos gerados via JavaScript (Template Literals)
- Formulário de cadastro com validação em tempo real (RegEx) e feedback visual
- Persistência de cadastros no `localStorage`
- Componentes de feedback: modal, toast, alertas e badges
- Menu de navegação responsivo com dropdown (desktop) e hambúrguer (mobile)
- Interface acessível, em conformidade com WCAG 2.1 (Nível AA)

## Pré-requisitos

- Navegador moderno com suporte a ES6 Modules (Chrome, Firefox, Edge ou Safari atualizados)
- Servidor HTTP local para servir os arquivos (necessário por causa de `type="module"`, que não funciona via `file://` devido a restrições de CORS)

## Instalação e execução local

```bash
# 1. Clonar o repositório
git clone https://github.com/danilo/instituto-viver-bem.git

# 2. Acessar a pasta do projeto
cd instituto-viver-bem

# 3. Servir os arquivos via HTTP
# Opção A: extensão "Live Server" do VS Code (clique com o botão
# direito em html/index.html > "Open with Live Server")
# Opção B: usando Node.js
npx serve .

# 4. Abrir no navegador
http://localhost:5500/html/index.html
```

## Estrutura de pastas

```
/instituto-viver-bem
├── /html
│   └── index.html          # Shell único da SPA
├── /css
│   └── style.css            # Design system, Grid, Flexbox e componentes
├── /js
│   ├── main.js               # Ponto de entrada da aplicação
│   └── /modules
│       ├── router.js          # Navegação SPA (hash routing)
│       ├── templates.js       # Geração de views dinâmicas
│       ├── form-validacao.js  # Validação e máscaras de formulário
│       └── storage.js         # Persistência via localStorage
├── /imagens
│   └── ...                   # Assets de mídia otimizados
└── README.md
```

## Estratégia de versionamento

O repositório segue o modelo **GitFlow**:

- `main` — código estável, correspondente às releases publicadas
- `develop` — branch de integração contínua do desenvolvimento
- `feature/*` — uma branch por funcionalidade, criada a partir de `develop`
- `hotfix/*` — correções urgentes, criadas a partir de `main`

As mensagens de commit seguem o padrão **Conventional Commits** (`feat:`, `fix:`, `refactor:`, `docs:`), e as releases usam **versionamento semântico** (`MAJOR.MINOR.PATCH`):

| Tag | Descrição |
|---|---|
| `v0.1.0` | Estrutura HTML5 semântica (EP1) |
| `v0.2.0` | Design system, Grid, Flexbox e componentes visuais (EP2) |
| `v0.3.0` | SPA funcional com JavaScript modular (EP3) |
| `v1.0.0` | Versão de produção: otimizada, acessível e documentada (EP4) |

Nenhum commit é feito diretamente em `main`; todo código passa por uma branch `feature/*` e é integrado via Pull Request revisado antes do merge em `develop`.

## Acessibilidade

O projeto segue as diretrizes **WCAG 2.1 (Nível AA)**, incluindo:

- Contraste mínimo de 4.5:1 entre texto e fundo
- Navegação completa por teclado (`Tab`, `Enter`, `Esc`)
- Uso de `aria-label`, `aria-expanded` e `aria-haspopup` em elementos interativos
- Estrutura semântica e hierarquia de cabeçalhos coerente
- Textos alternativos descritivos em todas as imagens

## Deploy

Aplicação publicada em: `[link do ambiente de produção]`

## Licença e autoria

Projeto acadêmico desenvolvido por **Danilo Portela Gomes** para a disciplina de Desenvolvimento Front-end (Análise e Desenvolvimento de Sistemas — Cruzeiro do Sul Virtual). Uso educacional.
