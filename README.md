<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Assistência de Sucesso</title>
  <meta name="description" content="Aprenda assistência técnica de celulares do zero, conquiste clientes recorrentes e lucre até R$250 por reparo. Curso completo por apenas R$47!">
  <style>
    :root {
      --primary: #0052cc;
      --accent: #ffcc00;
      --light: #f5f5f5;
      --dark: #222;
      --text: #333;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', Tahoma, sans-serif; color: var(--text); line-height: 1.6; }
    a { text-decoration: none; }
    img { max-width: 100%; height: auto; display: block; }
    .container { width: 90%; max-width: 1200px; margin: auto; }
    header { background: var(--primary); color: #fff; padding: 20px 0; }
    header .container { display: flex; align-items: center; justify-content: space-between; }
    header h1 { font-size: 1.8rem; }
    nav a { color: #fff; margin-left: 20px; font-weight: 500; }
    .hero {
      background: url('https://via.placeholder.com/1200x600') center/cover no-repeat;
      color: #fff;
      text-align: center;
      padding: 100px 20px;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top: 0; left: 0; width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.5);
    }
    .hero-content { position: relative; z-index: 1; max-width: 800px; margin: auto; }
    .hero-content h2 { font-size: 2.5rem; margin-bottom: 20px; }
    .hero-content p { font-size: 1.2rem; margin-bottom: 30px; }
    .btn { display: inline-block; background: var(--accent); color: var(--dark); padding: 15px 30px; font-weight: bold; border-radius: 5px; }
    section.features { padding: 60px 0; }
    .features h3 { font-size: 2rem; text-align: center; margin-bottom: 40px; }
    .grid { display: grid; gap: 30px; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }
    .feature { background: #fff; border: 1px solid #ddd; border-radius: 8px; padding: 20px; text-align: center; }
    .feature-icon { font-size: 3rem; margin-bottom: 15px; color: var(--primary); }
    .feature h4 { margin-bottom: 10px; font-size: 1.2rem; }
    section.about { background: var(--light); padding: 60px 0; }
    .about-content { display: flex; flex-wrap: wrap; align-items: center; gap: 40px; }
    .about-text { flex: 1 1 300px; }
    .about-img { flex: 1 1 300px; }
    section.pricing { padding: 60px 0; text-align: center; }
    .pricing h3 { font-size: 2rem; margin-bottom: 20px; }
    .price-card { display: inline-block; background: #fff; border: 2px solid var(--accent); padding: 30px; border-radius: 8px; }
    .price-card h4 { margin-bottom: 15px; font-size: 1.5rem; }
    .price-card p { font-size: 2.5rem; font-weight: bold; margin-bottom: 20px; }
    section.faq { padding: 60px 0; }
    .faq h3 { text-align: center; font-size: 2rem; margin-bottom: 40px; }
    .faq-item { margin-bottom: 20px; }
    .faq-item summary { font-weight: 600; cursor: pointer; }
    footer { background: var(--dark); color: #fff; text-align: center; padding: 30px 0; }
    footer p { font-size: 0.9rem; }
    footer a { color: var(--accent); }
    @media (max-width: 768px) {
      .hero-content h2 { font-size: 2rem; }
      .features h3, .pricing h3, .faq h3 { font-size: 1.8rem; }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <div class="container">
      <h1>Assistência de Sucesso</h1>
      <nav>
        <a href="#features">O que Você Aprende</a>
        <a href="#about">Sobre o Curso</a>
        <a href="#pricing">Investimento</a>
        <a href="#faq">Dúvidas</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="hero-content container">
      <h2>Do Zero aos Clientes Recorrentes em 7 Dias</h2>
      <p>Descubra como faturar até R$250 por reparo e atrair clientes diariamente, mesmo sem experiência.</p>
      <a href="https://pay.kiwify.com.br/M7ymSoq" class="btn">Quero Começar por R$47</a>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="features container">
    <h3>O que Você Aprenderá</h3>
    <div class="grid">
      <div class="feature">
        <div class="feature-icon">📢</div>
        <h4>Captação de Clientes</h4>
        <p>Aprenda a atrair e fidelizar clientes usando Instagram e Facebook Ads.</p>
      </div>
      <div class="feature">
        <div class="feature-icon">🔧</div>
        <h4>Técnica de Reparos</h4>
        <p>Domine trocas de telas e reparos de placas com segurança e rapidez.</p>
      </div>
      <div class="feature">
        <div class="feature-icon">💰</div>
        <h4>Lucre Acima de R$250</h4>
        <p>Saiba como precificar serviços para maximizar seu lucro.</p>
      </div>
      <div class="feature">
        <div class="feature-icon">📊</div>
        <h4>Gestão Financeira</h4>
        <p>Controle seu fluxo de caixa e organize seu negócio para crescer.</p>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="about container">
    <div class="about-content">
      <div class="about-text">
        <h3>Sobre o Curso</h3>
        <p>Este curso foi desenvolvido por Pedro Magaldi, especialista em assistência técnica de celulares e marketing digital. Com aulas 100% práticas, você terá acesso a:</p>
        <ul>
          <li>Vídeo aulas passo a passo;</li>
          <li>Templates de orçamentos prontos;</li>
          <li>Grupo de networking exclusivo;</li>
          <li>Suporte direto para tirar dúvidas.</li>
        </ul>
        <a href="https://pay.kiwify.com.br/M7ymSoq" class="btn">Garanta sua Vaga</a>
      </div>
      <div class="about-img">
        <img src="https://via.placeholder.com/400x300" alt="Instrutor Pedro Magaldi">
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="pricing container">
    <h3>Investimento</h3>
    <div class="price-card">
      <h4>Curso Completo</h4>
      <p>R$47,00</p>
      <a href="https://pay.kiwify.com.br/M7ymSoq" class="btn">Inscreva-se Já</a>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="faq container">
    <h3>Dúvidas Frequentes</h3>
    <details class="faq-item">
      <summary>Preciso ter experiência prévia?</summary>
      <p>Não! O curso começa do zero e guia você passo a passo.</p>
    </details>
    <details class="faq-item">
      <summary>Posso parcelar o pagamento?</summary>
      <p>Sim, o pagamento no Kiwify pode ser parcelado em até 12x.</p>
    </details>
    <details class="faq-item">
      <summary>Quanto tempo tenho acesso ao conteúdo?</summary>
      <p>Acesso vitalício ao material e atualizações gratuitas.</p>
    </details>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Assistência de Sucesso. Todos os direitos reservados.</p>
      <p>Desenvolvido por Pedro Magaldi</p>
    </div>
  </footer>
</body>
</html>
