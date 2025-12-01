<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Riovertech Engenharia | Projetos de Energia Solar em Rio Verde</title>
  <meta name="description" content="Projetos, execução e manutenção de usinas de energia solar em Rio Verde e região. Solicite seu orçamento com a Riovertech Engenharia.">
  <link rel="canonical" href="https://riovertechengenharia.com.br/">
  <meta property="og:title" content="Riovertech Engenharia — Energia Solar">
  <meta property="og:description" content="Projetos, execução e manutenção de usinas solares em Rio Verde/GO. Peça um orçamento.">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://riovertechengenharia.com.br/">
  <meta property="og:image" content="https://riovertechengenharia.com.br/og.jpg">
  <meta name="theme-color" content="#0b5cff">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --blue:#0b5cff;      /* azul da marca */
      --orange:#ff7a00;    /* laranja da marca */
      --bg:#0b1020;
      --card:#111831;
      --text:#e7ecf7;
      --muted:#a5b0c2;
      --border:#233053;
      --whatsapp:#25d366;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;color:var(--text);background:linear-gradient(180deg,#0b1020,#0e1430 45%,#0b1020)}
    a{color:inherit;text-decoration:none}
    .container{max-width:1100px;margin:0 auto;padding:0 20px}
    header{position:sticky;top:0;backdrop-filter:blur(10px);background:rgba(11,16,32,.6);border-bottom:1px solid var(--border);z-index:10}
    .nav{display:flex;align-items:center;justify-content:space-between;height:68px}
    .brand{display:flex;align-items:center;gap:12px;font-weight:700}
    .brand img{height:34px}
    .menu{display:flex;gap:18px}
    .btn{display:inline-block;padding:12px 18px;border-radius:10px;font-weight:600;transition:.06s transform,.2s box-shadow}
    .btn.primary{background:var(--blue);color:#fff;box-shadow:0 10px 25px rgba(11,92,255,.25)}
    .btn.primary:hover{transform:translateY(-1px)}
    .btn.ghost{border:1px solid var(--border);color:var(--text)}
    .btn.whats{background:var(--whatsapp);color:#10331b}
    .hero{padding:78px 0 36px}
    .hero-grid{display:grid;grid-template-columns:1.15fr 1fr;gap:36px;align-items:center}
    h1{font-size:clamp(32px,4.5vw,54px);line-height:1.06;margin:0 0 12px}
    h2{font-size:28px;margin:0 0 14px}
    .subtitle{color:var(--muted);font-size:18px;margin-bottom:22px}
    .badges{display:flex;gap:10px;margin:16px 0 28px;flex-wrap:wrap}
    .badge{padding:8px 12px;border:1px solid var(--border);border-radius:999px;color:#c9d3e3;font-size:13px}
    .card{background:radial-gradient(120% 120% at 0% 0%,#151c3a,#0f1530);border:1px solid var(--border);border-radius:16px;padding:22px}
    .illus{aspect-ratio:16/10;border-radius:14px;background:
        linear-gradient(135deg,rgba(11,92,255,.25),rgba(255,122,0,.25)),
        url('https://images.unsplash.com/photo-1509395176047-4a66953fd231?q=80&w=1200&auto=format&fit=crop') center/cover no-repeat;
        border:1px solid var(--border)}
    section{padding:44px 0}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .service h3{margin:8px 0;color:#ffb366}
    .kpis{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:10px}
    .kpi{text-align:center;padding:14px;border:1px dashed var(--border);border-radius:12px}
    .processo{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
    .processo .step{padding:16px;border:1px solid var(--border);border-radius:12px;background:#0f1732}
    .about{display:grid;grid-template-columns:1.1fr 1fr;gap:18px}
    .contact{display:grid;grid-template-columns:1.2fr .8fr;gap:18px}
    .footer{border-top:1px solid var(--border);color:var(--muted);font-size:14px;padding:18px 0}
    /* Floating WhatsApp */
    .float-whats{position:fixed;right:18px;bottom:18px;z-index:20}
    @media (max-width: 900px){
      .menu{display:none}
      .hero-grid,.grid-3,.about,.contact,.kpis,.processo{grid-template-columns:1fr}
    }
  </style>

  <!-- Schema.org -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"LocalBusiness",
    "name":"Riovertech Engenharia",
    "url":"https://riovertechengenharia.com.br/",
    "logo":"https://riovertechengenharia.com.br/logo-riovertech.png",
    "image":"https://riovertechengenharia.com.br/og.jpg",
    "telephone":"+55 64 98106-6647",
    "email":"riovertechengenharia@gmail.com",
    "address":{"@type":"PostalAddress","addressLocality":"Rio Verde","addressRegion":"GO","addressCountry":"BR"},
    "areaServed":"Rio Verde e região",
    "sameAs":[]
  }
  </script>
</head>
<body>
  <header>
    <div class="container nav">
      <a class="brand" href="#">
        <img src="logo-riovertech.png" alt="Riovertech Engenharia">
        <span>RIOVERTECH <span style="color:var(--orange)">ENGENHARIA</span></span>
      </a>
      <nav class="menu" aria-label="principal">
        <a href="#servicos">Serviços</a>
        <a href="#processo">Como trabalhamos</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
        <a class="btn ghost" href="https://wa.me/5564981066647?text=Ol%C3%A1%2C%20vim%20do%20site%20da%20Riovertech%20Engenharia%20e%20gostaria%20de%20um%20or%C3%A7amento." target="_blank" rel="noopener">WhatsApp</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-grid">
        <div>
          <h1>Energia Solar com projeto, obra e manutenção — fim a fim</h1>
          <p class="subtitle">Riovertech Engenharia: soluções fotovoltaicas para residências, comércios e usinas em Rio Verde e região. Planejamento técnico, homologação e entrega com segurança.</p>
          <div class="badges">
            <span class="badge">Projetos e ART</span>
            <span class="badge">Homologação junto à concessionária</span>
            <span class="badge">Garantia e suporte local</span>
          </div>
          <div class="kpis">
            <div class="kpi"><strong>+100</strong><div>Sistemas entregues</div></div>
            <div class="kpi"><strong>4.9/5</strong><div>Satisfação média</div></div>
            <div class="kpi"><strong>72h</strong><div>Proposta técnica</div></div>
            <div class="kpi"><strong>10 anos</strong><div>de atuação</div></div>
          </div>
          <div style="margin-top:20px" class="cta">
            <a class="btn primary" href="#contato">Solicitar orçamento</a>
            <a class="btn whats" href="https://wa.me/5564981066647?text=Ol%C3%A1%2C%20vim%20do%20site%20da%20Riovertech%20Engenharia%20e%20gostaria%20de%20um%20or%C3%A7amento." target="_blank" rel="noopener">Falar no WhatsApp</a>
          </div>
        </div>
        <div class="card">
          <div class="illus" role="img" aria-label="Painéis solares instalados"></div>
        </div>
      </div>
    </section>

    <section id="servicos">
      <h2>Serviços</h2>
      <p class="subtitle">Da concepção ao pós‑obra, com foco em performance e segurança.</p>
      <div class="grid-3">
        <div class="card service">
          <h3>Projetos de energia solar</h3>
          <p>Dimensionamento, estudo de viabilidade, especificação de equipamentos e documentação técnica (ART/homologação).</p>
          <ul>
            <li>Residencial, comercial e usinas</li>
            <li>Simulação de geração</li>
            <li>Memorial e diagramas</li>
          </ul>
        </div>
        <div class="card service">
          <h3>Execução de obras</h3>
          <p>Instalação completa com equipe qualificada, comissionamento e teste de performance.</p>
          <ul>
            <li>Estruturas e cabeamento</li>
            <li>Inversores e proteções</li>
            <li>Entrega “pronta para gerar”</li>
          </ul>
        </div>
        <div class="card service">
          <h3>Manutenção em usinas</h3>
          <p>Planos preventivos e corretivos para manter alta produtividade do sistema.</p>
          <ul>
            <li>Monitoramento e limpeza</li>
            <li>Termografia e inspeções</li>
            <li>Troca de componentes</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="processo">
      <h2>Como trabalhamos</h2>
      <div class="processo">
        <div class="step"><strong>1) Diagnóstico</strong><br>Levantamento de consumo e local da instalação.</div>
        <div class="step"><strong>2) Projeto</strong><br>Dimensionamento, memorial, ART e cronograma.</div>
        <div class="step"><strong>3) Obra</strong><br>Instalação, testes e homologação.</div>
        <div class="step"><strong>4) Pós‑obra</strong><br>Monitoramento, manutenção e suporte.</div>
      </div>
    </section>

    <section id="sobre">
      <h2>Sobre a Riovertech</h2>
      <div class="about">
        <div class="card">
          <p>Engenharia especializada em soluções fotovoltaicas, unindo rigor técnico e atendimento próximo. Atuamos em Rio Verde/GO e região com foco em eficiência, segurança e retorno do investimento.</p>
          <p><strong>Diferenciais:</strong> equipe certificada, projeto próprio, garantia e suporte local, equipamentos de marcas renomadas.</p>
        </div>
        <div class="card">
          <h3>Certificações e parceiros</h3>
          <ul>
            <li>ART e conformidade com normas ABNT/NBR</li>
            <li>Homologação junto à concessionária</li>
            <li>Marcas parceiras: inversores, módulos e estruturas</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="contato">
      <h2>Solicite um orçamento</h2>
      <div class="contact">
        <div class="card">
          <!-- Opção A: Netlify Forms (se publicar na Netlify) -->
          <form name="orcamento" method="POST" data-netlify="true">
            <input type="hidden" name="form-name" value="orcamento">
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
              <div>
                <label for="nome">Nome</label>
                <input id="nome" name="nome" required style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
              </div>
              <div>
                <label for="telefone">Telefone/WhatsApp</label>
                <input id="telefone" name="telefone" required inputmode="tel" placeholder="(64) 9 8106‑6647" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
              </div>
              <div>
                <label for="email">E‑mail</label>
                <input id="email" name="email" type="email" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
              </div>
              <div>
                <label for="tipo">Tipo de projeto</label>
                <select id="tipo" name="tipo" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
                  <option>Residencial</option>
                  <option>Comercial</option>
                  <option>Rural</option>
                  <option>Usina</option>
                </select>
              </div>
              <div>
                <label for="conta">Valor médio da conta (R$)</label>
                <input id="conta" name="conta" inputmode="numeric" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
              </div>
              <div>
                <label for="cidade">Cidade/Endereço</label>
                <input id="cidade" name="cidade" placeholder="Rua, nº, Bairro – Rio Verde/GO" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)">
              </div>
              <div style="grid-column:1/-1">
                <label for="msg">Observações</label>
                <textarea id="msg" name="mensagem" rows="4" style="width:100%;padding:12px;border-radius:10px;border:1px solid var(--border);background:#0f1732;color:var(--text)"></textarea>
              </div>
            </div>
            <div style="margin-top:12px;display:flex;gap:10px;flex-wrap:wrap">
              <button class="btn primary" type="submit">Enviar pedido</button>
              <a class="btn whats" href="https://wa.me/5564981066647?text=Ol%C3%A1%2C%20vim%20do%20site%20da%20Riovertech%20Engenharia%20e%20gostaria%20de%20um%20or%C3%A7amento." target="_blank" rel="noopener">Chamar no WhatsApp</a>
            </div>
          </form>

          <!-- Opção B (se usar Vercel): substitua o <form> acima por:
          <form action="https://formsubmit.co/riovertechengenharia@gmail.com" method="POST">
            <input type="hidden" name="_subject" value="Orçamento - Site Riovertech">
            <input type="hidden" name="_captcha" value="false">
            <input type="hidden" name="_template" value="table">
            <input type="hidden" name="_next" value="https://riovertechengenharia.com.br/">
            ... (mesmos campos)
          </form>
          -->
        </div>
        <div class="card">
          <h3>Contato</h3>
          <p><strong>WhatsApp:</strong> <a href="https://wa.me/5564981066647" target="_blank" rel="noopener">+55 (64) 98106‑6647</a></p>
          <p><strong>E‑mail:</strong> <a href="mailto:riovertechengenharia@gmail.com">riovertechengenharia@gmail.com</a></p>
          <p><strong>Endereço:</strong> Rio Verde/GO — informe rua, nº e bairro para exibirmos aqui.</p>
          <p><a class="btn ghost" href="https://maps.google.com/?q=Rio+Verde%2C+GO" target="_blank" rel="noopener">Ver no mapa</a></p>
          <h3>Horário de atendimento</h3>
          <p>Seg a Sex: 08h às 18h • Sáb: 08h às 12h</p>
          <p class="subtitle">Retorno em até 24h úteis.</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      © <span id="year"></span> Riovertech Engenharia. Todos os direitos reservados. • <a href="/privacidade.html">Privacidade (LGPD)</a>
    </div>
  </footer>

  <a class="float-whats btn whats" href="https://wa.me/5564981066647?text=Ol%C3%A1%2C%20vim%20do%20site%20da%20Riovertech%20Engenharia%20e%20gostaria%20de%20um%20or%C3%A7amento." target="_blank" rel="noopener" aria-label="Abrir WhatsApp">WhatsApp</a>

  <script>document.getElementById('year').textContent=new Date().getFullYear();</script>
</body>
</html>
