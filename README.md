[deepseek_html_20260407_e2dad6.html](https://github.com/user-attachments/files/26545443/deepseek_html_20260407_e2dad6.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes">
  <title>RH Estratégico | Soluções Inteligentes em Gestão de Pessoas</title>
  <!-- Preconnect para otimização de fontes -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <!-- Font Awesome para ícones (melhora a experiência visual) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f5f9ff;
      color: #1e2a3e;
      scroll-behavior: smooth;
      line-height: 1.5;
    }

    /* header com overlay moderno e imagem de escritório */
    header {
      background: linear-gradient(135deg, rgba(8, 48, 78, 0.9) 0%, rgba(2, 27, 46, 0.85) 100%), url('https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-4.0.3&auto=format&fit=crop&w=2070&q=80');
      background-size: cover;
      background-position: center 30%;
      color: white;
      padding: 120px 20px 100px;
      text-align: center;
      position: relative;
      border-bottom: 5px solid #00a8ff;
    }

    header h1 {
      font-size: 52px;
      font-weight: 800;
      letter-spacing: -0.5px;
      margin: 0;
      text-shadow: 0 2px 15px rgba(0,0,0,0.2);
    }

    header p {
      font-size: 22px;
      font-weight: 400;
      margin: 20px 0 10px;
      opacity: 0.95;
    }

    .btn {
      background: #00a8ff;
      color: white;
      padding: 14px 36px;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      font-weight: 700;
      font-size: 1rem;
      transition: all 0.25s ease;
      box-shadow: 0 4px 12px rgba(0,168,255,0.3);
      display: inline-block;
      text-decoration: none;
    }

    .btn:hover {
      background: #0088cc;
      transform: translateY(-2px);
      box-shadow: 0 8px 20px rgba(0,168,255,0.4);
    }

    /* navegação fixa com efeito suave */
    nav {
      background: rgba(255, 255, 255, 0.98);
      backdrop-filter: blur(2px);
      padding: 16px 20px;
      text-align: center;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
      transition: all 0.2s;
    }

    nav a {
      margin: 0 18px;
      text-decoration: none;
      color: #0a3d62;
      font-weight: 600;
      font-size: 1rem;
      transition: color 0.2s;
      position: relative;
    }

    nav a:hover {
      color: #00a8ff;
    }

    nav a::after {
      content: '';
      position: absolute;
      width: 0%;
      height: 2px;
      bottom: -5px;
      left: 0;
      background-color: #00a8ff;
      transition: width 0.25s;
    }

    nav a:hover::after {
      width: 100%;
    }

    section {
      padding: 80px 24px;
      max-width: 1300px;
      margin: 0 auto;
    }

    h2 {
      text-align: center;
      font-size: 36px;
      font-weight: 700;
      margin-bottom: 50px;
      color: #0a3d62;
      position: relative;
      display: inline-block;
      width: 100%;
    }

    h2:after {
      content: '';
      display: block;
      width: 70px;
      height: 4px;
      background: #00a8ff;
      margin: 12px auto 0;
      border-radius: 3px;
    }

    /* cards de serviços */
    .services {
      display: flex;
      gap: 32px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      flex: 1;
      min-width: 250px;
      background: white;
      padding: 40px 25px;
      border-radius: 28px;
      box-shadow: 0 20px 35px -12px rgba(0, 0, 0, 0.08);
      transition: all 0.3s ease;
      text-align: center;
      border: 1px solid rgba(0,168,255,0.1);
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 30px 40px -15px rgba(0, 88, 136, 0.2);
      border-color: rgba(0,168,255,0.3);
    }

    .card i {
      font-size: 48px;
      color: #00a8ff;
      margin-bottom: 20px;
    }

    .card h3 {
      font-size: 26px;
      margin-bottom: 16px;
      font-weight: 700;
    }

    .card p {
      color: #4a627a;
      line-height: 1.5;
    }

    /* seção sobre + diferenciais */
    .about {
      text-align: center;
      max-width: 880px;
      margin: 0 auto;
      font-size: 1.1rem;
      background: #ffffffd9;
      padding: 30px 35px;
      border-radius: 50px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.03);
    }

    .about p {
      margin-bottom: 20px;
    }

    .about-highlight {
      display: flex;
      justify-content: center;
      gap: 35px;
      flex-wrap: wrap;
      margin-top: 30px;
    }

    .about-highlight span {
      background: #eef7ff;
      padding: 8px 20px;
      border-radius: 40px;
      font-weight: 600;
      color: #0a3d62;
    }

    /* mentoria especial */
    #mentoria {
      background: linear-gradient(110deg, #eef2fa 0%, #ffffff 100%);
      border-radius: 48px;
      margin: 20px auto;
      box-shadow: 0 5px 15px rgba(0,0,0,0.02);
    }

    .mentoria-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
      margin-top: 30px;
    }

    .mentoria-item {
      background: white;
      padding: 28px;
      border-radius: 28px;
      flex: 1;
      min-width: 250px;
      text-align: center;
      transition: 0.2s;
      border-bottom: 3px solid #00a8ff;
    }

    .mentoria-item i {
      font-size: 40px;
      color: #00a8ff;
      margin-bottom: 15px;
    }

    /* depoimentos */
    .testimonials {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .testimonial {
      flex: 1;
      min-width: 260px;
      background: white;
      padding: 28px 25px;
      border-radius: 28px;
      box-shadow: 0 12px 20px rgba(0, 0, 0, 0.05);
      transition: 0.2s;
    }

    .testimonial i.fa-quote-left {
      color: #00a8ff40;
      font-size: 28px;
      margin-bottom: 12px;
      display: inline-block;
    }

    .testimonial p {
      font-style: normal;
      font-weight: 400;
      margin: 12px 0;
      color: #2c3e4e;
    }

    .testimonial strong {
      color: #0a3d62;
      font-weight: 700;
    }

    /* formulário moderno */
    form {
      max-width: 680px;
      margin: 0 auto;
      background: white;
      padding: 40px 35px;
      border-radius: 48px;
      box-shadow: 0 20px 35px rgba(0, 0, 0, 0.05);
    }

    form input, form textarea {
      width: 100%;
      padding: 16px 20px;
      margin-bottom: 20px;
      border-radius: 60px;
      border: 1px solid #e0e7f0;
      font-family: 'Poppins', sans-serif;
      font-size: 1rem;
      transition: all 0.2s;
      background: #fefefe;
    }

    form textarea {
      border-radius: 28px;
      resize: vertical;
    }

    form input:focus, form textarea:focus {
      outline: none;
      border-color: #00a8ff;
      box-shadow: 0 0 0 3px rgba(0,168,255,0.2);
    }

    form button {
      width: 100%;
      font-size: 1.1rem;
      padding: 14px;
      background: #0a3d62;
      letter-spacing: 0.5px;
    }

    form button:hover {
      background: #00a8ff;
    }

    footer {
      background: #0a2a3f;
      color: #cddfe7;
      text-align: center;
      padding: 40px 20px;
      font-size: 0.9rem;
    }

    footer p {
      margin: 8px 0;
    }

    .social-icons {
      margin-top: 18px;
    }

    .social-icons a {
      color: white;
      margin: 0 12px;
      font-size: 1.4rem;
      transition: 0.2s;
      display: inline-block;
    }

    .social-icons a:hover {
      color: #00a8ff;
      transform: scale(1.1);
    }

    /* whatsapp flutuante mais elegante */
    .whatsapp {
      position: fixed;
      bottom: 24px;
      right: 24px;
      background: #25d366;
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 32px;
      text-decoration: none;
      box-shadow: 0 6px 18px rgba(37, 211, 102, 0.4);
      transition: all 0.2s;
      z-index: 999;
    }

    .whatsapp:hover {
      background: #20b859;
      transform: scale(1.05);
    }

    /* notificação toast para envio (UX) */
    .toast-msg {
      visibility: hidden;
      min-width: 260px;
      background-color: #0a3d62;
      color: #fff;
      text-align: center;
      border-radius: 40px;
      padding: 12px 20px;
      position: fixed;
      bottom: 100px;
      left: 50%;
      transform: translateX(-50%);
      font-weight: 500;
      z-index: 1100;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      transition: visibility 0s, opacity 0.2s linear;
      opacity: 0;
    }

    .toast-msg.show {
      visibility: visible;
      opacity: 1;
    }

    @media (max-width: 768px) {
      header h1 { font-size: 36px; }
      header p { font-size: 18px; }
      nav a { margin: 0 12px; font-size: 0.85rem; }
      section { padding: 50px 20px; }
      h2 { font-size: 28px; }
      .card, .mentoria-item, .testimonial { min-width: 100%; }
      .about { padding: 20px; border-radius: 28px; }
      form { padding: 30px 20px; }
      .btn { padding: 12px 28px; }
    }
  </style>
</head>
<body>

<header>
  <h1>RH Estratégico</h1>
  <p>Soluções inteligentes para empresas que querem crescer</p>
  <br>
  <button class="btn" id="heroPropostaBtn">📈 Solicitar Proposta</button>
</header>

<nav>
  <a href="#sobre"><i class="fas fa-users" style="margin-right: 5px;"></i> Sobre</a>
  <a href="#servicos"><i class="fas fa-chart-line"></i> Serviços</a>
  <a href="#mentoria"><i class="fas fa-brain"></i> Mentoria</a>
  <a href="#depoimentos"><i class="fas fa-star"></i> Depoimentos</a>
  <a href="#contato"><i class="fas fa-envelope"></i> Contato</a>
</nav>

<section id="sobre">
  <h2>Sobre Nós</h2>
  <div class="about">
    <p><strong>RH Estratégico</strong> nasceu para transformar a gestão de pessoas em vantagem competitiva. Combinamos análise de dados, inteligência comportamental e visão de negócios para conectar talentos e acelerar resultados.</p>
    <p>Com mais de 8 anos de experiência, já impactamos +120 empresas de médio e grande porte, reduzindo turnover e aumentando a performance de times em até 40%.</p>
    <div class="about-highlight">
      <span><i class="fas fa-check-circle"></i> 98% de satisfação</span>
      <span><i class="fas fa-trophy"></i> Especialistas em RH</span>
      <span><i class="fas fa-rocket"></i> Metodologia ágil</span>
    </div>
  </div>
</section>

<section id="servicos">
  <h2>Nossos Serviços</h2>
  <div class="services">
    <div class="card">
      <i class="fas fa-search"></i>
      <h3>Recrutamento</h3>
      <p>Seleção estratégica com mapeamento de competências e fit cultural. Reduza custos e encontre profissionais que realmente impulsionam sua empresa.</p>
    </div>
    <div class="card">
      <i class="fas fa-chalkboard-user"></i>
      <h3>Consultoria</h3>
      <p>Otimização de processos, people analytics, clima organizacional e estruturação de RH para empresas em expansão.</p>
    </div>
    <div class="card">
      <i class="fas fa-chart-simple"></i>
      <h3>Treinamento</h3>
      <p>Desenvolvimento de equipes de alta performance, liderança adaptativa e soft skills essenciais para o futuro do trabalho.</p>
    </div>
  </div>
</section>

<section id="mentoria">
  <h2>Mentoria de Carreira & Liderança</h2>
  <p style="text-align:center; max-width:750px; margin:0 auto 20px auto; font-size:1.1rem;">Programas personalizados para líderes e profissionais que desejam crescimento acelerado na carreira.</p>
  <div class="mentoria-grid">
    <div class="mentoria-item">
      <i class="fas fa-user-graduate"></i>
      <h3>Alta Liderança</h3>
      <p>Coaching executivo e plano de desenvolvimento 1:1 com foco em resultados mensuráveis.</p>
    </div>
    <div class="mentoria-item">
      <i class="fas fa-arrow-trend-up"></i>
      <h3>Plano de Carreira</h3>
      <p>Reestruturação de trajetória profissional, promoção e posicionamento no mercado.</p>
    </div>
    <div class="mentoria-item">
      <i class="fas fa-people-group"></i>
      <h3>Mentoria em Grupo</h3>
      <p>Sessões colaborativas para times emergentes e troca estratégica entre pares.</p>
    </div>
  </div>
</section>

<section id="depoimentos">
  <h2>O que nossos clientes dizem</h2>
  <div class="testimonials">
    <div class="testimonial">
      <i class="fas fa-quote-left"></i>
      <p>"O RH Estratégico transformou nossa área de talentos. Com o novo modelo de recrutamento, reduzimos o tempo de contratação em 45% e a qualidade das equipes aumentou drasticamente."</p>
      <strong>- Marina Costa, Diretora de Gente & Gestão</strong>
    </div>
    <div class="testimonial">
      <i class="fas fa-quote-left"></i>
      <p>"A mentoria me ajudou a conquistar uma posição de liderança sênior em apenas 6 meses. As sessões são práticas, direcionadas e com alto valor agregado."</p>
      <strong>- Rafael Mendes, Head Comercial</strong>
    </div>
    <div class="testimonial">
      <i class="fas fa-quote-left"></i>
      <p>"Profissionais extremamente qualificados, atenciosos e comprometidos. A consultoria de clima organizacional trouxe insights que mudaram nossa cultura."</p>
      <strong>- Juliana Tavares, CEO Tech&Co</strong>
    </div>
  </div>
</section>

<section id="contato">
  <h2>Fale com um especialista</h2>
  <form id="contactForm">
    <input type="text" id="nome" placeholder="Seu nome completo" required>
    <input type="email" id="email" placeholder="E-mail corporativo" required>
    <textarea id="mensagem" rows="4" placeholder="Conte-nos sobre o desafio da sua empresa ou sua necessidade..." required></textarea>
    <button class="btn" type="submit">Enviar Mensagem <i class="fas fa-paper-plane"></i></button>
  </form>
  <p style="text-align:center; margin-top: 20px; font-size:0.85rem;">🔒 Seus dados estão seguros. Retornamos em até 24h úteis.</p>
</section>

<footer>
  <p><strong>RH Estratégico</strong> — People & Performance</p>
  <p>📍 São Paulo | Brasília | Rio de Janeiro</p>
  <div class="social-icons">
    <a href="#" aria-label="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
    <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
    <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
  </div>
  <p>© 2026 RH Estratégico - Todos os direitos reservados | Estratégia que gera resultados</p>
</footer>

<!-- Botão WhatsApp com link simulado funcional (abre em nova aba, mas pode customizar) -->
<a class="whatsapp" href="https://wa.me/5511999999999?text=Olá%2C%20vim%20pelo%20site%20RH%20Estratégico%20e%20gostaria%20de%20mais%20informações!" target="_blank" rel="noopener noreferrer">
  <i class="fab fa-whatsapp"></i>
</a>

<div id="toastMsg" class="toast-msg">✅ Mensagem enviada! Em breve retornamos.</div>

<script>
  (function() {
    // Smooth scroll para todos os links internos do nav e botões
    const navLinks = document.querySelectorAll('nav a, .btn[href^="#"], .btn#heroPropostaBtn');
    const heroBtn = document.getElementById('heroPropostaBtn');
    
    function smoothScrollToSection(targetId) {
      const targetElement = document.querySelector(targetId);
      if (targetElement) {
        targetElement.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }
    
    // Tratamento para botão hero -> leva para seção contato
    if (heroBtn) {
      heroBtn.addEventListener('click', function(e) {
        e.preventDefault();
        const contactSection = document.getElementById('contato');
        if (contactSection) {
          contactSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
          // opcional: foco no primeiro campo
          document.getElementById('nome')?.focus();
        }
      });
    }
    
    // Adiciona evento para todos os links do nav (prevenir comportamento padrão e usar smooth)
    document.querySelectorAll('nav a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        const hash = this.getAttribute('href');
        if (hash && hash.startsWith('#')) {
          e.preventDefault();
          const targetId = hash;
          const targetElem = document.querySelector(targetId);
          if (targetElem) {
            targetElem.scrollIntoView({ behavior: 'smooth', block: 'start' });
            // Atualiza URL sem saltar brusco (opcional)
            history.pushState(null, null, hash);
          }
        }
      });
    });
    
    // TOAST e envio do formulário com validação simples
    const form = document.getElementById('contactForm');
    const toast = document.getElementById('toastMsg');
    
    function showToast(message) {
      toast.textContent = message || "✅ Mensagem enviada! Em breve retornamos.";
      toast.classList.add('show');
      setTimeout(() => {
        toast.classList.remove('show');
      }, 3800);
    }
    
    if (form) {
      form.addEventListener('submit', function(event) {
        event.preventDefault();
        
        const nomeInput = document.getElementById('nome');
        const emailInput = document.getElementById('email');
        const mensagemInput = document.getElementById('mensagem');
        
        let isValid = true;
        if (!nomeInput.value.trim()) {
          nomeInput.style.borderColor = "#ff5e5e";
          isValid = false;
        } else {
          nomeInput.style.borderColor = "#e0e7f0";
        }
        
        const emailVal = emailInput.value.trim();
        const emailPattern = /^[^\s@]+@([^\s@]+\.)+[^\s@]+$/;
        if (!emailVal || !emailPattern.test(emailVal)) {
          emailInput.style.borderColor = "#ff5e5e";
          isValid = false;
        } else {
          emailInput.style.borderColor = "#e0e7f0";
        }
        
        if (!mensagemInput.value.trim()) {
          mensagemInput.style.borderColor = "#ff5e5e";
          isValid = false;
        } else {
          mensagemInput.style.borderColor = "#e0e7f0";
        }
        
        if (!isValid) {
          showToast("⚠️ Preencha todos os campos corretamente (e-mail válido).");
          return;
        }
        
        // Simular envio com sucesso (apenas front-end demonstrativo)
        // Em produção enviaria via fetch para backend
        console.log("Dados enviados:", {
          nome: nomeInput.value,
          email: emailInput.value,
          mensagem: mensagemInput.value
        });
        
        // Limpa formulário
        nomeInput.value = '';
        emailInput.value = '';
        mensagemInput.value = '';
        
        showToast("📩 Mensagem enviada! Nossa equipe responderá em breve.");
        
        // Opcional: resetar estilos
        nomeInput.style.borderColor = "#e0e7f0";
        emailInput.style.borderColor = "#e0e7f0";
        mensagemInput.style.borderColor = "#e0e7f0";
      });
    }
    
    // Correção de qualquer comportamento de redirecionamento de "#" vazio
    const allBtnCta = document.querySelectorAll('.btn');
    allBtnCta.forEach(btn => {
      if (!btn.hasAttribute('data-custom') && btn !== heroBtn && btn.getAttribute('type') !== 'submit') {
        // se algum outro botão genérico quiser ser usado para contato, mas sem conflito
        if (btn.closest('#contato') === null && btn.id !== 'heroPropostaBtn') {
          btn.addEventListener('click', function() {
            const contatoSec = document.getElementById('contato');
            if (contatoSec) contatoSec.scrollIntoView({ behavior: 'smooth' });
          });
        }
      }
    });
    
    // pequeno ajuste para evitar erro de links sociais sem destino (apenas visual)
    const socialLinks = document.querySelectorAll('.social-icons a');
    socialLinks.forEach(link => {
      link.addEventListener('click', (e) => {
        e.preventDefault();
        showToast("🔗 Conecte-se com a gente nas redes em breve!");
      });
    });
    
    // botão hero já configurado, mas garantir também que o link de whatsapp já está funcional com número exemplo
    // melhor experiência: usuário pode editar o número no href.
    // Tudo consistente.
  })();
</script>
</body>
</html>
