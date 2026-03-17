<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ProfEPT – IF Goiano Campus Ceres</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;900&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet" />

  <style>
    /* ================================================
       VARIÁVEIS E RESET
    ================================================ */
    :root {
      --verde-escuro:  #1a4731;
      --verde-medio:   #2d7a50;
      --verde-claro:   #4caf7d;
      --verde-suave:   #e8f5ee;
      --neutro-escuro: #1e1e1e;
      --neutro-medio:  #4a4a4a;
      --neutro-claro:  #f5f5f3;
      --branco:        #ffffff;
      --sombra:        rgba(26,71,49,.12);
      --radius:        12px;
      --transition:    .35s cubic-bezier(.4,0,.2,1);
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; font-size: 16px; }

    body {
      font-family: 'DM Sans', sans-serif;
      color: var(--neutro-escuro);
      background: var(--branco);
      overflow-x: hidden;
    }

    img { max-width: 100%; display: block; }
    a   { text-decoration: none; color: inherit; }

    /* ================================================
       NAVEGAÇÃO FIXA
    ================================================ */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 1000;
      background: rgba(255,255,255,.92);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(45,122,80,.15);
      transition: box-shadow var(--transition);
    }
    nav.scrolled { box-shadow: 0 4px 24px var(--sombra); }

    .nav-inner {
      max-width: 1200px;
      margin: 0 auto;
      padding: .85rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
    }

    /* logos na nav */
    .nav-logos {
      display: flex;
      align-items: center;
      gap: 1rem;
    }
    .nav-logos img {
      height: 44px;
      width: auto;
      object-fit: contain;
    }
    .nav-sep {
      width: 1px;
      height: 36px;
      background: var(--verde-claro);
      opacity: .5;
    }

    /* links */
    .nav-links {
      display: flex;
      list-style: none;
      gap: .25rem;
    }
    .nav-links a {
      font-size: .875rem;
      font-weight: 500;
      letter-spacing: .02em;
      padding: .45rem .85rem;
      border-radius: 6px;
      color: var(--verde-escuro);
      transition: background var(--transition), color var(--transition);
    }
    .nav-links a:hover {
      background: var(--verde-suave);
      color: var(--verde-medio);
    }

    /* hambúrguer */
    .hamburger {
      display: none;
      flex-direction: column;
      gap: 5px;
      cursor: pointer;
      padding: 4px;
    }
    .hamburger span {
      display: block;
      width: 24px; height: 2px;
      background: var(--verde-escuro);
      border-radius: 2px;
      transition: transform var(--transition), opacity var(--transition);
    }
    .hamburger.open span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
    .hamburger.open span:nth-child(2) { opacity: 0; }
    .hamburger.open span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }

    /* mobile menu */
    .mobile-menu {
      display: none;
      flex-direction: column;
      gap: 0;
      padding: 0 2rem 1rem;
      background: var(--branco);
    }
    .mobile-menu.open { display: flex; }
    .mobile-menu a {
      font-size: .95rem;
      font-weight: 500;
      padding: .75rem .5rem;
      color: var(--verde-escuro);
      border-bottom: 1px solid var(--verde-suave);
    }

    /* ================================================
       HERO
    ================================================ */
    #hero {
      min-height: 100svh;
      display: flex;
      align-items: center;
      position: relative;
      overflow: hidden;
      background: linear-gradient(135deg, var(--verde-escuro) 0%, #0e3320 50%, #071a12 100%);
    }

    /* fundo decorativo */
    .hero-bg-circles {
      position: absolute; inset: 0; pointer-events: none;
    }
    .hero-bg-circles::before,
    .hero-bg-circles::after {
      content: '';
      position: absolute;
      border-radius: 50%;
      background: rgba(76,175,125,.08);
    }
    .hero-bg-circles::before {
      width: 600px; height: 600px;
      top: -160px; right: -160px;
    }
    .hero-bg-circles::after {
      width: 400px; height: 400px;
      bottom: -120px; left: -80px;
      background: rgba(45,122,80,.1);
    }

    /* grade decorativa */
    .hero-grid {
      position: absolute; inset: 0; pointer-events: none;
      background-image:
        linear-gradient(rgba(76,175,125,.06) 1px, transparent 1px),
        linear-gradient(90deg, rgba(76,175,125,.06) 1px, transparent 1px);
      background-size: 64px 64px;
    }

    .hero-inner {
      position: relative;
      max-width: 1200px;
      margin: 0 auto;
      padding: 8rem 2rem 5rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 4rem;
      align-items: center;
    }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: rgba(76,175,125,.18);
      border: 1px solid rgba(76,175,125,.4);
      border-radius: 100px;
      padding: .35rem 1rem;
      font-size: .78rem;
      font-weight: 500;
      letter-spacing: .08em;
      text-transform: uppercase;
      color: var(--verde-claro);
      margin-bottom: 1.5rem;
    }
    .hero-badge::before {
      content: '';
      width: 6px; height: 6px;
      border-radius: 50%;
      background: var(--verde-claro);
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%,100% { opacity: 1; transform: scale(1); }
      50%      { opacity: .4; transform: scale(1.5); }
    }

    .hero-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2rem, 4vw, 3.5rem);
      font-weight: 700;
      line-height: 1.15;
      color: var(--branco);
      margin-bottom: 1.5rem;
    }
    .hero-title em {
      font-style: normal;
      color: var(--verde-claro);
    }

    .hero-subtitle {
      font-size: 1.05rem;
      font-weight: 300;
      line-height: 1.7;
      color: rgba(255,255,255,.72);
      margin-bottom: 2.5rem;
      max-width: 500px;
    }

    .hero-cta {
      display: inline-flex;
      align-items: center;
      gap: .6rem;
      background: var(--verde-claro);
      color: var(--verde-escuro);
      font-weight: 600;
      font-size: .95rem;
      padding: .9rem 2rem;
      border-radius: 8px;
      transition: background var(--transition), transform var(--transition), box-shadow var(--transition);
      box-shadow: 0 4px 20px rgba(76,175,125,.35);
    }
    .hero-cta:hover {
      background: var(--branco);
      transform: translateY(-2px);
      box-shadow: 0 8px 28px rgba(76,175,125,.45);
    }
    .hero-cta svg { flex-shrink: 0; }

    /* card decorativo lado direito */
    .hero-visual {
      display: flex;
      flex-direction: column;
      gap: 1.25rem;
      animation: floatUp .9s ease both .2s;
    }
    @keyframes floatUp {
      from { opacity: 0; transform: translateY(32px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .hero-stat-card {
      background: rgba(255,255,255,.06);
      border: 1px solid rgba(255,255,255,.12);
      backdrop-filter: blur(8px);
      border-radius: var(--radius);
      padding: 1.5rem;
    }
    .hero-stat-card .stat-number {
      font-family: 'Playfair Display', serif;
      font-size: 2.4rem;
      font-weight: 700;
      color: var(--verde-claro);
      line-height: 1;
    }
    .hero-stat-card .stat-label {
      font-size: .85rem;
      color: rgba(255,255,255,.65);
      margin-top: .35rem;
      line-height: 1.4;
    }
    .hero-stats-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.25rem;
    }

    .hero-logos-card {
      background: rgba(255,255,255,.06);
      border: 1px solid rgba(255,255,255,.12);
      backdrop-filter: blur(8px);
      border-radius: var(--radius);
      padding: 1.5rem;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 2rem;
    }
    .hero-logos-card img {
      height: 52px;
      width: auto;
      object-fit: contain;
      filter: brightness(0) invert(1);
      opacity: .9;
    }
    .hero-logos-card .v-sep {
      width: 1px;
      height: 40px;
      background: rgba(255,255,255,.25);
    }

    /* ================================================
       SEÇÕES COMUNS
    ================================================ */
    section { padding: 5rem 2rem; }

    .section-inner {
      max-width: 1100px;
      margin: 0 auto;
    }

    .section-label {
      display: inline-block;
      font-size: .75rem;
      font-weight: 600;
      letter-spacing: .14em;
      text-transform: uppercase;
      color: var(--verde-medio);
      margin-bottom: .9rem;
    }
    .section-label::before {
      content: '— ';
      opacity: .5;
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.7rem, 3vw, 2.6rem);
      font-weight: 700;
      line-height: 1.2;
      color: var(--verde-escuro);
      margin-bottom: 1.5rem;
    }

    .section-text {
      font-size: 1.05rem;
      font-weight: 300;
      line-height: 1.8;
      color: var(--neutro-medio);
    }

    /* divisor decorativo */
    .divider {
      width: 60px; height: 3px;
      background: linear-gradient(90deg, var(--verde-claro), transparent);
      border-radius: 3px;
      margin-bottom: 2rem;
    }

    /* ================================================
       SOBRE – FUNDO BRANCO
    ================================================ */
    #sobre {
      background: var(--branco);
    }
    #sobre .section-inner {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }

    .sobre-visual {
      position: relative;
    }
    .sobre-visual-block {
      background: var(--verde-suave);
      border-radius: 16px;
      padding: 3rem;
      border-left: 4px solid var(--verde-claro);
    }
    .sobre-visual-block blockquote {
      font-family: 'Playfair Display', serif;
      font-size: 1.25rem;
      font-style: italic;
      color: var(--verde-escuro);
      line-height: 1.6;
    }
    .sobre-visual-block cite {
      display: block;
      margin-top: 1.25rem;
      font-size: .85rem;
      font-style: normal;
      color: var(--verde-medio);
      font-weight: 500;
    }
    .sobre-deco {
      position: absolute;
      width: 120px; height: 120px;
      border-radius: 50%;
      background: linear-gradient(135deg, var(--verde-claro), var(--verde-medio));
      opacity: .12;
      bottom: -32px; right: -32px;
      z-index: -1;
    }

    /* ================================================
       INTRODUÇÃO – FUNDO VERDE SUAVE
    ================================================ */
    #introducao {
      background: var(--verde-suave);
      position: relative;
      overflow: hidden;
    }
    #introducao::before {
      content: '"';
      position: absolute;
      top: -2rem; left: 2rem;
      font-family: 'Playfair Display', serif;
      font-size: 20rem;
      color: var(--verde-claro);
      opacity: .07;
      line-height: 1;
      pointer-events: none;
    }

    #introducao .section-inner {
      display: grid;
      grid-template-columns: 1.2fr 1fr;
      gap: 5rem;
      align-items: start;
    }

    .intro-highlight {
      background: var(--branco);
      border-radius: var(--radius);
      padding: 2rem;
      box-shadow: 0 4px 24px var(--sombra);
    }
    .intro-highlight h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.15rem;
      color: var(--verde-escuro);
      margin-bottom: 1rem;
    }
    .intro-highlight p {
      font-size: .95rem;
      font-weight: 300;
      line-height: 1.75;
      color: var(--neutro-medio);
    }

    /* ================================================
       OBJETIVOS
    ================================================ */
    #objetivos {
      background: var(--neutro-claro);
    }
    .objetivos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.5rem;
      margin-top: 3rem;
    }
    .objetivo-card {
      background: var(--branco);
      border-radius: var(--radius);
      padding: 2rem;
      border-top: 3px solid var(--verde-claro);
      box-shadow: 0 2px 16px var(--sombra);
      transition: transform var(--transition), box-shadow var(--transition);
    }
    .objetivo-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 32px var(--sombra);
    }
    .objetivo-icon {
      width: 48px; height: 48px;
      border-radius: 10px;
      background: var(--verde-suave);
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1.25rem;
    }
    .objetivo-icon svg { width: 24px; height: 24px; color: var(--verde-medio); }
    .objetivo-card h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      color: var(--verde-escuro);
      margin-bottom: .75rem;
      line-height: 1.3;
    }
    .objetivo-card p {
      font-size: .9rem;
      font-weight: 300;
      line-height: 1.7;
      color: var(--neutro-medio);
    }

    /* ================================================
       CAMPUS CERES
    ================================================ */
    #campus {
      background: linear-gradient(135deg, var(--verde-escuro) 0%, #0e3320 100%);
      color: var(--branco);
      position: relative;
      overflow: hidden;
    }
    #campus::after {
      content: '';
      position: absolute;
      width: 500px; height: 500px;
      border-radius: 50%;
      background: rgba(76,175,125,.07);
      bottom: -150px; right: -100px;
      pointer-events: none;
    }
    #campus .section-label { color: var(--verde-claro); }
    #campus .section-title { color: var(--branco); }
    #campus .divider { background: linear-gradient(90deg, var(--verde-claro), transparent); }

    #campus .section-inner {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }

    .campus-text { position: relative; z-index: 1; }
    .campus-text .section-text { color: rgba(255,255,255,.78); }

    .campus-info-cards {
      position: relative; z-index: 1;
      display: flex;
      flex-direction: column;
      gap: 1.25rem;
    }
    .campus-info-card {
      background: rgba(255,255,255,.07);
      border: 1px solid rgba(255,255,255,.12);
      border-radius: var(--radius);
      padding: 1.25rem 1.5rem;
      display: flex;
      align-items: flex-start;
      gap: 1rem;
    }
    .campus-info-card svg {
      flex-shrink: 0;
      width: 22px; height: 22px;
      color: var(--verde-claro);
      margin-top: .1rem;
    }
    .campus-info-card div {
      font-size: .9rem;
      line-height: 1.6;
      color: rgba(255,255,255,.8);
    }
    .campus-info-card strong {
      display: block;
      color: var(--branco);
      font-weight: 500;
      margin-bottom: .2rem;
    }

    /* ================================================
       RESULTADOS E IMPACTOS
    ================================================ */
    #resultados {
      background: var(--branco);
    }

    /* linha de métricas grandes */
    .resultados-metricas {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1.25rem;
      margin-bottom: 3.5rem;
    }
    .metrica-card {
      background: var(--verde-suave);
      border-radius: var(--radius);
      padding: 1.75rem 1.5rem;
      text-align: center;
      border-top: 3px solid var(--verde-claro);
      transition: transform var(--transition), box-shadow var(--transition);
    }
    .metrica-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 28px var(--sombra);
    }
    .metrica-card .metrica-num {
      font-family: 'Playfair Display', serif;
      font-size: 2.1rem;
      font-weight: 700;
      color: var(--verde-escuro);
      line-height: 1;
    }
    .metrica-card .metrica-label {
      font-size: .82rem;
      color: var(--neutro-medio);
      margin-top: .5rem;
      line-height: 1.45;
      font-weight: 400;
    }

    /* blocos temáticos em duas colunas */
    .resultados-blocos {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-bottom: 3.5rem;
    }

    .resultado-bloco {
      background: var(--neutro-claro);
      border-radius: var(--radius);
      padding: 2rem;
      border-left: 4px solid var(--verde-claro);
    }
    .resultado-bloco h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.05rem;
      color: var(--verde-escuro);
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: .55rem;
    }
    .resultado-bloco h3 .bloco-emoji {
      font-size: 1.15rem;
      line-height: 1;
    }
    .resultado-bloco ul {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: .55rem;
    }
    .resultado-bloco ul li {
      font-size: .9rem;
      font-weight: 300;
      color: var(--neutro-medio);
      display: flex;
      align-items: flex-start;
      gap: .6rem;
      line-height: 1.55;
    }
    .resultado-bloco ul li::before {
      content: '';
      flex-shrink: 0;
      width: 6px; height: 6px;
      border-radius: 50%;
      background: var(--verde-claro);
      margin-top: .42rem;
    }
    .resultado-bloco p.bloco-texto {
      font-size: .9rem;
      font-weight: 300;
      color: var(--neutro-medio);
      line-height: 1.7;
    }

    /* barra de progresso para dados percentuais */
    .barra-wrap {
      margin-top: .5rem;
      display: flex;
      flex-direction: column;
      gap: .65rem;
    }
    .barra-item { display: flex; flex-direction: column; gap: .25rem; }
    .barra-label {
      display: flex;
      justify-content: space-between;
      font-size: .8rem;
      color: var(--neutro-medio);
    }
    .barra-label strong { color: var(--verde-escuro); font-weight: 500; }
    .barra-track {
      height: 7px;
      background: rgba(76,175,125,.18);
      border-radius: 10px;
      overflow: hidden;
    }
    .barra-fill {
      height: 100%;
      background: linear-gradient(90deg, var(--verde-claro), var(--verde-medio));
      border-radius: 10px;
      transform-origin: left;
      animation: barraGrow 1s ease both;
    }
    @keyframes barraGrow {
      from { transform: scaleX(0); }
      to   { transform: scaleX(1); }
    }

    /* bloco de destaque avaliação */
    .resultados-avaliacao {
      background: linear-gradient(135deg, var(--verde-escuro), #0e3320);
      border-radius: 16px;
      padding: 3rem;
      display: flex;
      align-items: center;
      gap: 3rem;
      color: var(--branco);
    }
    .avaliacao-numero {
      flex-shrink: 0;
      font-family: 'Playfair Display', serif;
      font-size: 5rem;
      font-weight: 700;
      color: var(--verde-claro);
      line-height: 1;
    }
    .avaliacao-texto h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.35rem;
      margin-bottom: .65rem;
    }
    .avaliacao-texto p {
      font-size: .95rem;
      font-weight: 300;
      line-height: 1.7;
      color: rgba(255,255,255,.78);
    }

    @media (max-width: 900px) {
      .resultados-blocos { grid-template-columns: 1fr; }
      .avaliacao-numero  { font-size: 3.5rem; }
      .resultados-avaliacao { flex-direction: column; gap: 1.5rem; text-align: center; }
    }
    @media (max-width: 540px) {
      .resultados-metricas { grid-template-columns: 1fr 1fr; }
    }

    /* ================================================
       FIM CSS RESULTADOS
    ================================================ */

    /* ================================================
       DISSERTAÇÕES
    ================================================ */
    #dissertacoes { background: var(--neutro-claro); }

    .diss-controles { display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 2rem; align-items: center; }
    .diss-search { flex: 1 1 260px; position: relative; }
    .diss-search input {
      width: 100%; padding: .7rem 1rem .7rem 2.6rem;
      border: 1.5px solid rgba(45,122,80,.25); border-radius: 8px;
      font-family: 'DM Sans', sans-serif; font-size: .9rem;
      color: var(--neutro-escuro); background: var(--branco);
      outline: none; transition: border-color var(--transition);
    }
    .diss-search input:focus { border-color: var(--verde-claro); }
    .diss-search svg {
      position: absolute; left: .8rem; top: 50%; transform: translateY(-50%);
      width: 16px; height: 16px; color: var(--verde-medio); pointer-events: none;
    }
    .diss-filtros { display: flex; flex-wrap: wrap; gap: .5rem; }
    .diss-filtros select {
      padding: .65rem 1rem; border: 1.5px solid rgba(45,122,80,.25); border-radius: 8px;
      font-family: 'DM Sans', sans-serif; font-size: .85rem;
      color: var(--neutro-escuro); background: var(--branco);
      outline: none; cursor: pointer; transition: border-color var(--transition);
    }
    .diss-filtros select:focus { border-color: var(--verde-claro); }

    .diss-sintese {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem; margin-bottom: 2.5rem;
    }
    .diss-stat {
      background: var(--branco); border-radius: var(--radius); padding: 1.25rem;
      text-align: center; border-top: 3px solid var(--verde-claro);
      box-shadow: 0 2px 12px var(--sombra);
    }
    .diss-stat .ds-num { font-family: 'Playfair Display', serif; font-size: 1.9rem; font-weight: 700; color: var(--verde-escuro); line-height: 1; }
    .diss-stat .ds-lbl { font-size: .78rem; color: var(--neutro-medio); margin-top: .35rem; line-height: 1.4; }

    .diss-legendas { display: flex; flex-wrap: wrap; gap: 1rem; margin-bottom: 2rem; }
    .diss-leg { display: flex; align-items: center; gap: .45rem; font-size: .82rem; color: var(--neutro-medio); }
    .diss-leg-dot { width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0; }
    .diss-leg-dot.l1 { background: var(--verde-claro); }
    .diss-leg-dot.l2 { background: #f0a500; }
    .diss-leg-dot.ls  { background: #aaa; }

    .diss-grupo { margin-bottom: 1.5rem; }
    .diss-ano-header {
      display: flex; align-items: center; gap: 1rem;
      background: var(--verde-escuro); color: var(--branco);
      padding: .75rem 1.25rem; border-radius: 8px 8px 0 0;
      cursor: pointer; user-select: none; transition: background var(--transition);
    }
    .diss-ano-header:hover { background: var(--verde-medio); }
    .diss-ano-header h3 { font-family: 'Playfair Display', serif; font-size: 1.05rem; flex: 1; }
    .diss-ano-header .ano-count { background: rgba(255,255,255,.2); border-radius: 20px; padding: .15rem .65rem; font-size: .8rem; }
    .diss-ano-header .ano-chevron { width: 18px; height: 18px; transition: transform var(--transition); flex-shrink: 0; }
    .diss-ano-header.open .ano-chevron { transform: rotate(180deg); }

    .diss-lista { display: none; flex-direction: column; background: var(--branco); border: 1px solid rgba(45,122,80,.15); border-top: none; border-radius: 0 0 8px 8px; }
    .diss-lista.open { display: flex; }

    .diss-item {
      display: flex; align-items: flex-start; gap: 1rem;
      padding: 1rem 1.25rem; border-bottom: 1px solid rgba(45,122,80,.08);
      transition: background var(--transition);
    }
    .diss-item:last-child { border-bottom: none; }
    .diss-item:hover { background: var(--verde-suave); }
    .diss-item.hidden { display: none !important; }

    .diss-num {
      flex-shrink: 0; width: 28px; height: 28px; border-radius: 50%;
      background: var(--verde-suave); color: var(--verde-escuro);
      font-size: .75rem; font-weight: 600;
      display: flex; align-items: center; justify-content: center; margin-top: .1rem;
    }
    .diss-linha-dot { flex-shrink: 0; width: 8px; height: 8px; border-radius: 50%; margin-top: .45rem; }
    .diss-linha-dot.l1 { background: var(--verde-claro); }
    .diss-linha-dot.l2 { background: #f0a500; }
    .diss-linha-dot.ls  { background: #aaa; }

    .diss-info { flex: 1; min-width: 0; }
    .diss-titulo { font-size: .9rem; font-weight: 500; color: var(--neutro-escuro); line-height: 1.4; margin-bottom: .3rem; }
    .diss-meta { font-size: .78rem; color: var(--neutro-medio); font-weight: 300; }
    .diss-meta span { margin-right: .75rem; }
    .diss-data { flex-shrink: 0; font-size: .75rem; color: var(--verde-medio); font-weight: 500; white-space: nowrap; margin-top: .1rem; }

    .diss-vazio { display: none; text-align: center; padding: 3rem; color: var(--neutro-medio); font-size: .95rem; }
    .diss-vazio.show { display: block; }

    @media (max-width: 600px) {
      .diss-controles { flex-direction: column; }
      .diss-filtros { width: 100%; }
      .diss-filtros select { flex: 1; }
      .diss-data { display: none; }
    }

    /* ================================================
       BANNER CAPES NOTA 4
    ================================================ */
    .capes-banner {
      background: var(--verde-escuro);
      border-bottom: 2px solid var(--verde-claro);
      padding: .6rem 2rem;
      text-align: center;
      position: relative;
      z-index: 999;
      margin-top: 74px;
    }
    .capes-banner-inner {
      display: inline-flex;
      align-items: center;
      gap: .75rem;
      flex-wrap: wrap;
      justify-content: center;
    }
    .capes-banner .capes-star {
      font-size: 1rem;
      opacity: .85;
    }
    .capes-banner strong {
      font-size: .88rem;
      font-weight: 600;
      color: #fff;
      letter-spacing: .02em;
    }
    .capes-banner span {
      font-size: .82rem;
      color: rgba(255,255,255,.65);
      font-weight: 300;
    }
    .capes-banner .capes-badge-pill {
      background: var(--verde-claro);
      border-radius: 100px;
      padding: .15rem .75rem;
      font-size: .75rem;
      font-weight: 600;
      color: var(--verde-escuro);
      letter-spacing: .04em;
    }

    /* card CAPES no hero visual */
    .hero-capes-card {
      background: rgba(255,255,255,.07);
      border: 1px solid rgba(76,175,125,.35);
      border-left: 3px solid var(--verde-claro);
      border-radius: var(--radius);
      padding: 1.5rem;
      display: flex;
      align-items: center;
      gap: 1.25rem;
    }
    .hero-capes-nota {
      flex-shrink: 0;
      width: 60px; height: 60px;
      border-radius: 50%;
      background: rgba(76,175,125,.15);
      border: 2px solid var(--verde-claro);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Playfair Display', serif;
      font-size: 2.1rem;
      font-weight: 900;
      color: var(--verde-claro);
      line-height: 1;
    }
    .hero-capes-info strong {
      display: block;
      font-size: .92rem;
      font-weight: 600;
      color: #fff;
      line-height: 1.3;
      margin-bottom: .3rem;
    }
    .hero-capes-info span {
      font-size: .78rem;
      color: rgba(255,255,255,.65);
      font-weight: 300;
    }

    @media (max-width: 540px) {
      .capes-banner { margin-top: 68px; padding: .55rem 1rem; }
      .capes-banner strong, .capes-banner span { font-size: .8rem; }
    }

    /* ================================================
       RODAPÉ
    ================================================ */
    footer {
      background: var(--neutro-escuro);
      color: rgba(255,255,255,.6);
      padding: 3rem 2rem;
    }
    .footer-inner {
      max-width: 1100px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: 2fr 1fr 1fr;
      gap: 3rem;
      align-items: start;
      margin-bottom: 2.5rem;
    }
    .footer-brand h3 {
      font-family: 'Playfair Display', serif;
      color: var(--branco);
      font-size: 1.1rem;
      margin-bottom: .5rem;
    }
    .footer-brand p {
      font-size: .85rem;
      line-height: 1.7;
    }
    .footer-col h4 {
      font-size: .78rem;
      font-weight: 600;
      letter-spacing: .1em;
      text-transform: uppercase;
      color: var(--verde-claro);
      margin-bottom: .85rem;
    }
    .footer-col p {
      font-size: .85rem;
      line-height: 1.7;
    }

    .footer-bottom {
      max-width: 1100px;
      margin: 0 auto;
      padding-top: 2rem;
      border-top: 1px solid rgba(255,255,255,.08);
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 1rem;
      font-size: .82rem;
    }
    .footer-bottom a {
      color: var(--verde-claro);
      transition: opacity .2s;
    }
    .footer-bottom a:hover { opacity: .8; }

    /* ================================================
       ANIMAÇÕES DE ENTRADA (IntersectionObserver)
    ================================================ */
    .reveal {
      opacity: 0;
      transform: translateY(28px);
      transition: opacity .7s ease, transform .7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* ================================================
       RESPONSIVO
    ================================================ */
    @media (max-width: 900px) {
      .nav-links { display: none; }
      .hamburger { display: flex; }

      .hero-inner {
        grid-template-columns: 1fr;
        gap: 3rem;
        padding-top: 6rem;
      }
      .hero-visual { display: none; }

      #sobre .section-inner,
      #introducao .section-inner,
      #campus .section-inner {
        grid-template-columns: 1fr;
        gap: 2.5rem;
      }

      .footer-inner {
        grid-template-columns: 1fr;
        gap: 2rem;
      }
    }

    @media (max-width: 540px) {
      section { padding: 4rem 1.25rem; }
      .nav-inner { padding: .75rem 1.25rem; }
      .hero-title { font-size: 1.85rem; }
      .objetivos-grid { grid-template-columns: 1fr; }
      .footer-bottom { flex-direction: column; text-align: center; }
    }
  </style>
</head>
<body>

  <!-- ================================================
       NAVEGAÇÃO
  ================================================ -->
  <nav id="navbar">
    <div class="nav-inner">
      <!-- logos -->
      <div class="nav-logos">
        <!-- Logo ProfEPT -->
        <img
          src="https://profept.ifes.edu.br/images/ProfEPT/logo_profept.png"
          alt="Logo ProfEPT"
          onerror="this.style.display='none'"
        />
        <div class="nav-sep"></div>
        <!-- Logo IF Goiano -->
        <img
          src="https://www.ifgoiano.edu.br/home/images/logo_2020.png"
          alt="Logo IF Goiano"
          onerror="this.style.display='none'"
        />
      </div>

      <!-- links desktop -->
      <ul class="nav-links">
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#introducao">Introdução</a></li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#campus">Campus Ceres</a></li>
        <li><a href="#resultados">Resultados</a></li>
        <li><a href="#dissertacoes">Dissertações</a></li>
      </ul>

      <!-- hambúrguer mobile -->
      <div class="hamburger" id="hamburger" aria-label="Menu" role="button" tabindex="0">
        <span></span><span></span><span></span>
      </div>
    </div>

    <!-- menu mobile -->
    <div class="mobile-menu" id="mobileMenu">
      <a href="#sobre"      onclick="closeMobileMenu()">Sobre</a>
      <a href="#introducao" onclick="closeMobileMenu()">Introdução</a>
      <a href="#objetivos"  onclick="closeMobileMenu()">Objetivos</a>
      <a href="#campus"     onclick="closeMobileMenu()">Campus Ceres</a>
      <a href="#resultados" onclick="closeMobileMenu()">Resultados</a>
      <a href="#dissertacoes" onclick="closeMobileMenu()">Dissertações</a>
    </div>
  </nav>

  <!-- ================================================
       BANNER CAPES NOTA 4 — destaque institucional
  ================================================ -->
  <div class="capes-banner">
    <div class="capes-banner-inner">
      <span class="capes-star">⭐</span>
      <strong>ProfEPT — Nota 4 na Avaliação Quadrienal da CAPES (2021–2024)</strong>
      <span class="capes-badge-pill">CAPES · Nota 4</span>
      <span>Reconhecimento nacional da excelência do programa</span>
      <span class="capes-star">⭐</span>
    </div>
  </div>

  <!-- ================================================
       HERO
  ================================================ -->
  <section id="hero">
    <div class="hero-bg-circles"></div>
    <div class="hero-grid"></div>

    <div class="hero-inner">
      <!-- conteúdo textual -->
      <div class="hero-content">
        <div class="hero-badge">Mestrado Profissional em Rede Nacional</div>

        <h1 class="hero-title">
          Programa de Pós-Graduação em<br />
          <em>Educação Profissional<br />e Tecnológica</em>
        </h1>

        <p class="hero-subtitle">
          O ProfEPT é um mestrado profissional em rede, ofertado em parceria com
          Institutos Federais de todo o Brasil, comprometido com a formação
          de pesquisadores e educadores que transformam a realidade social.
        </p>

        <a href="#sobre" class="hero-cta">
          Saiba Mais
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
        </a>
      </div>

      <!-- visual decorativo -->
      <div class="hero-visual">
        <!-- card de identidade do programa -->
        <div class="hero-logos-card">
          <div style="text-align:center;">
            <div style="font-family:'Playfair Display',serif; font-size:1.4rem; font-weight:700; color:#fff; letter-spacing:.04em;">ProfEPT</div>
            <div style="font-size:.72rem; color:rgba(255,255,255,.6); margin-top:.3rem; letter-spacing:.06em; text-transform:uppercase;">IF Goiano · Campus Ceres</div>
          </div>
          <div class="v-sep"></div>
          <img
            src="https://www.ifgoiano.edu.br/home/images/logo_2020.png"
            alt="IF Goiano"
            onerror="this.style.display='none'"
          />
        </div>

        <!-- estatísticas -->
        <div class="hero-stats-row">
          <div class="hero-stat-card">
            <div class="stat-number">40</div>
            <div class="stat-label">Unidades associadas em todo o Brasil</div>
          </div>
          <div class="hero-stat-card">
            <div class="stat-number">11</div>
            <div class="stat-label">Professores orientadores no Campus Ceres</div>
          </div>
        </div>

        <div class="hero-stat-card">
          <div class="stat-number">Ceres – GO</div>
          <div class="stat-label">IF Goiano Campus Ceres — unidade associada ao ProfEPT</div>
        </div>

        <!-- Destaque CAPES Nota 4 -->
        <div class="hero-capes-card">
          <div class="hero-capes-nota">4</div>
          <div class="hero-capes-info">
            <strong>Nota 4 na Avaliação CAPES</strong>
            <span>Avaliação Quadrienal 2021–2024 · Reconhecimento de excelência nacional do Mestrado Profissional em EPT</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ================================================
       SOBRE O ProfEPT
  ================================================ -->
  <section id="sobre">
    <div class="section-inner reveal">
      <!-- texto -->
      <div>
        <span class="section-label">Sobre o Programa</span>
        <h2 class="section-title">O que é o ProfEPT?</h2>
        <div class="divider"></div>
        <p class="section-text">
          O Programa de Pós-Graduação em Educação Profissional e Tecnológica (ProfEPT) é um
          mestrado profissional em rede nacional, coordenado pelo Instituto Federal do Espírito
          Santo (IFES) e ofertado em associação com Institutos Federais de todas as regiões do
          País, incluindo o IF Goiano Campus Ceres.
        </p>
        <br />
        <p class="section-text">
          Com foco na formação de mestres aptos a atuar diretamente na Educação Profissional e
          Tecnológica (EPT), o programa articula produção científica, desenvolvimento de
          tecnologias educacionais e reflexão crítica sobre as práticas pedagógicas que permeiam
          a educação pública brasileira. O programa integra pesquisa e prática, incentivando a
          produção de dissertações voltadas à aplicação concreta em contextos educacionais reais.
        </p>
      </div>

      <!-- visual / destaque -->
      <div class="sobre-visual">
        <div class="sobre-visual-block">
          <blockquote>
            "A educação profissional e tecnológica é uma modalidade educacional que perpassa todos
            os níveis da educação nacional, integrando-se às dimensões do trabalho, da ciência e
            da tecnologia."
          </blockquote>
          <cite>— Lei de Diretrizes e Bases da Educação Nacional (LDB), Art. 39</cite>
        </div>
        <div class="sobre-deco"></div>
      </div>
    </div>
  </section>

  <!-- ================================================
       INTRODUÇÃO
  ================================================ -->
  <section id="introducao">
    <div class="section-inner reveal">
      <!-- texto principal -->
      <div>
        <span class="section-label">Contexto Educacional</span>
        <h2 class="section-title">A Educação Profissional e Tecnológica no Brasil</h2>
        <div class="divider"></div>
        <p class="section-text">
          A Educação Profissional e Tecnológica (EPT) constitui um dos pilares fundamentais para
          o desenvolvimento econômico e social do Brasil. Ao integrar formação técnica e humanística,
          ela prepara cidadãos para responder às demandas do mundo do trabalho sem abrir mão da
          formação crítica e integral do ser humano.
        </p>
        <br />
        <p class="section-text">
          Historicamente marcada pela dualidade estrutural entre uma educação para as elites e outra
          voltada para o trabalho manual, a EPT vem sendo ressignificada no contexto da rede federal
          de educação. Os Institutos Federais, desde a sua expansão na década de 2000, assumiram o
          protagonismo na oferta de uma educação pública, gratuita, laica e comprometida com a
          transformação social das regiões onde se inserem.
        </p>
        <br />
        <p class="section-text">
          Nesse cenário, a pesquisa e a formação de professores voltados à EPT tornam-se estratégias
          indispensáveis para garantir uma prática pedagógica reflexiva, inovadora e sensível às
          especificidades locais. O ProfEPT emerge, portanto, como resposta institucional à demanda
          por qualificação dos profissionais que atuam nessa modalidade.
        </p>
      </div>

      <!-- card de destaque -->
      <div>
        <div class="intro-highlight">
          <h3>Por que o ProfEPT importa?</h3>
          <p>
            O programa amplia a capacidade investigativa dos educadores, fortalece a produção de
            conhecimento aplicado e contribui para a consolidação de uma identidade pedagógica
            própria para a Educação Profissional e Tecnológica no Brasil, reconhecendo o trabalho
            como princípio educativo e a pesquisa como eixo estruturante da formação docente.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- ================================================
       OBJETIVOS
  ================================================ -->
  <section id="objetivos">
    <div class="section-inner reveal">
      <span class="section-label">Propósitos</span>
      <h2 class="section-title">Objetivos do Programa</h2>
      <div class="divider"></div>
      <p class="section-text" style="max-width:680px;">
        O ProfEPT é estruturado em torno de objetivos que guiam tanto a produção científica
        quanto a atuação concreta dos egressos nos espaços educacionais.
      </p>

      <div class="objetivos-grid">

        <!-- card 1 -->
        <div class="objetivo-card">
          <div class="objetivo-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 14l9-5-9-5-9 5 9 5z"/>
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 14l6.16-3.422a12 12 0 01.84 4.422c0 4.418-3.582 8-8 8s-8-3.582-8-8c0-1.57.45-3.034 1.22-4.27L12 14z"/>
            </svg>
          </div>
          <h3>Formação de Mestres em EPT</h3>
          <p>
            Qualificar profissionais para atuar na pesquisa, gestão e docência na Educação
            Profissional e Tecnológica, em seus diferentes níveis e modalidades.
          </p>
        </div>

        <!-- card 2 -->
        <div class="objetivo-card">
          <div class="objetivo-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"/>
            </svg>
          </div>
          <h3>Pesquisas Aplicadas</h3>
          <p>
            Fomentar o desenvolvimento de pesquisas com impacto direto na prática educacional,
            produzindo tecnologias e metodologias inovadoras para a EPT.
          </p>
        </div>

        <!-- card 3 -->
        <div class="objetivo-card">
          <div class="objetivo-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"/>
            </svg>
          </div>
          <h3>Fortalecimento da Educação Pública</h3>
          <p>
            Contribuir para o aprimoramento da qualidade da educação pública brasileira,
            reafirmando o papel social dos Institutos Federais.
          </p>
        </div>

        <!-- card 4 -->
        <div class="objetivo-card">
          <div class="objetivo-icon">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.7">
              <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z"/>
            </svg>
          </div>
          <h3>Integração Ensino, Pesquisa e Extensão</h3>
          <p>
            Articular as dimensões do ensino, da pesquisa e da extensão como fundamentos
            indissociáveis da formação profissional e cidadã.
          </p>
        </div>

      </div>
    </div>
  </section>

  <!-- ================================================
       CAMPUS CERES
  ================================================ -->
  <section id="campus">
    <div class="section-inner">
      <div class="campus-text reveal">
        <span class="section-label">Unidade Associada</span>
        <h2 class="section-title">IF Goiano – Campus Ceres</h2>
        <div class="divider"></div>
        <p class="section-text">
          Localizado na cidade de Ceres, no Vale do São Patrício, em Goiás, o Instituto Federal
          Goiano Campus Ceres é referência em educação pública e de qualidade na região
          Centro-Norte do estado. Com mais de seis décadas de história, o campus oferece cursos
          técnicos, graduações e programas de pós-graduação comprometidos com o desenvolvimento
          regional sustentável e a inclusão social.
        </p>
        <br />
        <p class="section-text">
          Como unidade associada do ProfEPT, o Campus Ceres amplia o alcance do programa para a
          realidade goiana, formando educadores e pesquisadores capazes de articular as demandas
          locais com os desafios nacionais da Educação Profissional e Tecnológica, contribuindo
          para a transformação das comunidades que o cercam.
        </p>
      </div>

      <div class="campus-info-cards reveal">

        <div class="campus-info-card">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
          </svg>
          <div>
            <strong>Localização</strong>
            Ceres, Goiás — Vale do São Patrício, região Centro-Norte do estado.
          </div>
        </div>

        <div class="campus-info-card">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/>
          </svg>
          <div>
            <strong>Atuação Regional</strong>
            Referência histórica em educação pública, atendendo municípios do entorno com oferta
            de ensino técnico, superior e pós-graduação.
          </div>
        </div>

        <div class="campus-info-card">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"/>
          </svg>
          <div>
            <strong>ProfEPT no Campus</strong>
            Unidade associada responsável pela oferta local do mestrado profissional, com corpo
            docente qualificado e infraestrutura dedicada à pesquisa.
          </div>
        </div>

        <div class="campus-info-card">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"/>
          </svg>
          <div>
            <strong>Compromisso Social</strong>
            Integração entre ensino, pesquisa e extensão voltada ao desenvolvimento humano e
            tecnológico da região do Vale do São Patrício.
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ================================================
       RESULTADOS E IMPACTOS DO ProfEPT
  ================================================ -->
  <section id="resultados">
    <div class="section-inner reveal">

      <span class="section-label">Dados e Impactos</span>
      <h2 class="section-title">Resultados e Impactos do ProfEPT</h2>
      <div class="divider"></div>
      <p class="section-text" style="max-width:720px; margin-bottom:3rem;">
        Os dados abaixo retratam o perfil dos egressos e os impactos concretos do programa
        na vida profissional, acadêmica e social dos mestrandos formados pelo ProfEPT –
        IF Goiano Campus Ceres.
      </p>

      <!-- Métricas de destaque -->
      <div class="resultados-metricas">
        <div class="metrica-card">
          <div class="metrica-num">100%</div>
          <div class="metrica-label">dos egressos em atividade laboral</div>
        </div>
        <div class="metrica-card">
          <div class="metrica-num">92,7%</div>
          <div class="metrica-label">tiveram aumento salarial após o mestrado</div>
        </div>
        <div class="metrica-card">
          <div class="metrica-num">63,6%</div>
          <div class="metrica-label">publicaram artigos científicos</div>
        </div>
        <div class="metrica-card">
          <div class="metrica-num">72,7%</div>
          <div class="metrica-label">seguiram atuando profissionalmente</div>
        </div>
        <div class="metrica-card">
          <div class="metrica-num">até 30%</div>
          <div class="metrica-label">de reajuste salarial registrado</div>
        </div>
      </div>

      <!-- Blocos temáticos -->
      <div class="resultados-blocos">

        <!-- Perfil Étnico-Racial -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">📊</span> Perfil Étnico-Racial</h3>
          <div class="barra-wrap">
            <div class="barra-item">
              <div class="barra-label"><span>Brancos</span><strong>50,9%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:50.9%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Pardos</span><strong>38,2%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:38.2%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Pretos</span><strong>10,9%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:10.9%"></div></div>
            </div>
          </div>
          <p class="bloco-texto" style="margin-top:1rem;">
            O programa amplia o acesso à pós-graduação e promove inclusão social,
            contemplando diferentes grupos étnico-raciais em sua composição discente.
          </p>
        </div>

        <!-- Identidade de Gênero -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">👥</span> Identidade de Gênero</h3>
          <div class="barra-wrap">
            <div class="barra-item">
              <div class="barra-label"><span>Mulheres cisgênero</span><strong>60%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:60%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Homens cisgênero</span><strong>34,5%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:34.5%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Outras identidades</span><strong>representativo</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:5.5%"></div></div>
            </div>
          </div>
        </div>

        <!-- Inclusão e Diversidade -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">🤝</span> Inclusão e Diversidade</h3>
          <ul>
            <li>76,4% dos egressos não pertencem a grupos minorizados</li>
            <li>12,7% são mulheres mães ou tutoras</li>
            <li>Participação representativa de pessoas com deficiência</li>
            <li>Participação representativa de pessoas negras</li>
          </ul>
        </div>

        <!-- Linhas de Pesquisa -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">🔬</span> Linhas de Pesquisa</h3>
          <div class="barra-wrap">
            <div class="barra-item">
              <div class="barra-label"><span>Práticas Educativas em EPT</span><strong>54,5%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:54.5%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Organização e Memórias de Espaços Pedagógicos</span><strong>45,5%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:45.5%"></div></div>
            </div>
          </div>
        </div>

        <!-- Continuidade Acadêmica -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">🎓</span> Continuidade Acadêmica</h3>
          <div class="barra-wrap">
            <div class="barra-item">
              <div class="barra-label"><span>Atuação profissional</span><strong>72,7%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:72.7%"></div></div>
            </div>
            <div class="barra-item">
              <div class="barra-label"><span>Continuidade nos estudos</span><strong>27,3%</strong></div>
              <div class="barra-track"><div class="barra-fill" style="width:27.3%"></div></div>
            </div>
          </div>
        </div>

        <!-- Impacto Profissional -->
        <div class="resultado-bloco">
          <h3><span class="bloco-emoji">🚀</span> Impacto Profissional</h3>
          <ul>
            <li>Melhoria na posição profissional após a conclusão do mestrado</li>
            <li>Reconhecimento institucional ampliado</li>
            <li>Ampliação de oportunidades de trabalho relatada pelos egressos</li>
            <li>92,7% registraram aumento salarial, com reajustes de até 30%</li>
          </ul>
        </div>

      </div><!-- fim .resultados-blocos -->

      <!-- Bloco de avaliação (destaque final) -->
      <div class="resultados-avaliacao">
        <div class="avaliacao-numero">100%</div>
        <div class="avaliacao-texto">
          <h3>⭐ Avaliação do Programa</h3>
          <p>
            Todos os egressos consultados recomendariam o ProfEPT a outros profissionais da
            Educação Profissional e Tecnológica. Um indicador que reflete a qualidade do programa,
            a relevância das pesquisas desenvolvidas e o impacto real na trajetória de cada egresso.
          </p>
        </div>
      </div>

    </div>
  </section>

  <!-- ================================================
       DISSERTAÇÕES DEFENDIDAS
  ================================================ -->
  <section id="dissertacoes">
    <div class="section-inner reveal">
      <span class="section-label">Produção Acadêmica</span>
      <h2 class="section-title">Dissertações Defendidas</h2>
      <div class="divider"></div>
      <p class="section-text" style="max-width:720px; margin-bottom:2.5rem;">
        Relação oficial das dissertações defendidas no ProfEPT – IF Goiano Campus Ceres,
        organizadas por ano de defesa. Use os filtros abaixo para navegar pela produção acadêmica do programa.
      </p>

      <!-- Síntese numérica -->
      <div class="diss-sintese">
        <div class="diss-stat"><div class="ds-num">122</div><div class="ds-lbl">dissertações defendidas</div></div>
        <div class="diss-stat"><div class="ds-num">7</div><div class="ds-lbl">anos de produção (2019–2025)</div></div>
        <div class="diss-stat"><div class="ds-num">2</div><div class="ds-lbl">linhas de pesquisa</div></div>
        <div class="diss-stat"><div class="ds-num">11</div><div class="ds-lbl">professores orientadores</div></div>
      </div>

      <!-- Legendas -->
      <div class="diss-legendas">
        <div class="diss-leg"><div class="diss-leg-dot l1"></div> Linha 1 – Práticas Educativas em EPT</div>
        <div class="diss-leg"><div class="diss-leg-dot l2"></div> Linha 2 – Organização e Memórias de Espaços Pedagógicos</div>
        <div class="diss-leg"><div class="diss-leg-dot ls"></div> Linha não especificada</div>
      </div>

      <!-- Controles de filtro -->
      <div class="diss-controles">
        <div class="diss-search">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"/><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-4.35-4.35"/></svg>
          <input type="text" id="dissSearch" placeholder="Buscar por título, autor ou orientador…" />
        </div>
        <div class="diss-filtros">
          <select id="filtroAno">
            <option value="">Todos os anos</option>
            <option>2019</option><option>2020</option><option>2021</option>
            <option>2022</option><option>2023</option><option>2024</option><option>2025</option>
          </select>
          <select id="filtroLinha">
            <option value="">Todas as linhas</option>
            <option value="l1">Linha 1</option>
            <option value="l2">Linha 2</option>
          </select>
        </div>
      </div>

      <!-- Lista de dissertações por ano -->
      <div id="dissContainer">

        <!-- 2019 -->
        <div class="diss-grupo" data-ano="2019">
          <div class="diss-ano-header open" onclick="toggleAno(this)">
            <h3>📅 2019</h3><span class="ano-count">17 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista open">
            <div class="diss-item" data-linha="l2" data-texto="paulo de sá filho evasão escolar cursos educação profissional tecnológica distância senai goiás marcos antônio de carvalho">
              <div class="diss-num">1</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">Evasão Escolar em Cursos de Educação Profissional e Tecnológica a Distância no SENAI Goiás: Fatores Intervenientes</div><div class="diss-meta"><span>👤 Paulo de Sá Filho</span><span>🎓 Marcos Antônio de Carvalho</span></div></div>
              <div class="diss-data">16/05/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="flávia alves de castro oliveira evasão escolar ensino técnico profissionalizante instituto federal goiano campus ceres josé carlos moreira de souza">
              <div class="diss-num">2</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">Evasão Escolar no Ensino Técnico Profissionalizante: Um Estudo de Caso no IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Flávia Alves de Castro Oliveira</span><span>🎓 José Carlos Moreira de Souza</span></div></div>
              <div class="diss-data">15/08/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="clécia messias de sousa eficiência monitoria cursos técnicos integrados ensino médio instituto federal goiano campus ceres josé carlos moreira de souza">
              <div class="diss-num">3</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">A Eficiência da Monitoria nos Cursos Técnicos Integrados ao Ensino Médio do IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Clécia Messias de Sousa</span><span>🎓 José Carlos Moreira de Souza</span></div></div>
              <div class="diss-data">23/08/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="altair fábio silvério ribeiro jogo digital educativo possibilidades potencialidades ensino sistemas telecomunicações fernando barbosa matos">
              <div class="diss-num">4</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Jogo Digital Educativo: Possibilidades e Potencialidades ao Ensino de Sistemas de Telecomunicações</div><div class="diss-meta"><span>👤 Altair Fábio Silvério Ribeiro</span><span>🎓 Fernando Barbosa Matos</span></div></div>
              <div class="diss-data">28/08/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="josé roberto cruz e silva objeto de aprendizagem ensino html perspectiva aprendizagem colaborativa avaliação formativa fernando barbosa matos">
              <div class="diss-num">5</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Objeto de Aprendizagem para o Ensino de HTML: Uma Perspectiva de Aprendizagem Colaborativa e Avaliação Formativa</div><div class="diss-meta"><span>👤 José Roberto Cruz e Silva</span><span>🎓 Fernando Barbosa Matos</span></div></div>
              <div class="diss-data">28/08/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="rosângela lopes borges núcleo atendimento pessoas necessidades educacionais específicas obstáculos superações instituto federal goiano marcos fernandes sobrinho">
              <div class="diss-num">6</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Núcleo de Atendimento às Pessoas com Necessidades Educacionais Específicas: Obstáculos e Superações no IF Goiano</div><div class="diss-meta"><span>👤 Rosângela Lopes Borges</span><span>🎓 Marcos Fernandes Sobrinho</span></div></div>
              <div class="diss-data">29/08/2019</div>
            </div>
            <div class="diss-item" data-linha="ls" data-texto="roberta martins mendonça gomes objetos de aprendizagem reflexão uso aulas língua portuguesa emmanuela ferreira de lima">
              <div class="diss-num">7</div><div class="diss-linha-dot ls"></div>
              <div class="diss-info"><div class="diss-titulo">Objetos de Aprendizagem: Reflexão e Uso nas Aulas de Língua Portuguesa</div><div class="diss-meta"><span>👤 Roberta Martins Mendonça Gomes</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div>
              <div class="diss-data">03/09/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="juliana luiza de oliveira canêdo política comunicação educação profissional tecnológica instituto federal juliana cristina da costa fernandes">
              <div class="diss-num">8</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">Política de Comunicação na Educação Profissional e Tecnológica: Proposta para um Instituto Federal</div><div class="diss-meta"><span>👤 Juliana Luiza de Oliveira Canêdo</span><span>🎓 Juliana Cristina da Costa Fernandes</span></div></div>
              <div class="diss-data">29/08/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="natália borba de moraes marques organização curricular cursos técnicos integrados ensino médio currículo integrado jussara de fátima alves campos oliveira">
              <div class="diss-num">9</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">A Organização Curricular dos Cursos Técnicos Integrados ao Ensino Médio: A Busca por um Currículo Integrado</div><div class="diss-meta"><span>👤 Natália Borba de Moraes Marques</span><span>🎓 Jussara de Fátima Alves Campos Oliveira</span></div></div>
              <div class="diss-data">05/09/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="jullyana pimenta borges gonçalves condições curriculares prática educativa inclusiva estudo de caso escola estadual goiás cinthia maria felício">
              <div class="diss-num">10</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Condições Curriculares para uma Prática Educativa Inclusiva: Estudo de Caso em Escola Estadual de Goiás</div><div class="diss-meta"><span>👤 Jullyana Pimenta Borges Gonçalves</span><span>🎓 Cinthia Maria Felício</span></div></div>
              <div class="diss-data">05/09/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="ana paula araújo martins princípios norteadores ept cultura escolar ifg campus itumbiara marco antônio de carvalho">
              <div class="diss-num">11</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">Princípios Norteadores da EPT Presentes na Cultura Escolar: Um Estudo de Caso no IFG – Campus Itumbiara</div><div class="diss-meta"><span>👤 Ana Paula Araújo Martins</span><span>🎓 Marco Antônio de Carvalho</span></div></div>
              <div class="diss-data">05/09/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="gustavo oliveira mendes história memórias pioneiros educação profissional goiás narrativas constituição instituto federal goiano juliana cristina da costa fernandes">
              <div class="diss-num">12</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">História e Memórias dos Pioneiros da Educação Profissional em Goiás: Narrativas da Constituição do IF Goiano</div><div class="diss-meta"><span>👤 Gustavo Oliveira Mendes</span><span>🎓 Juliana Cristina da Costa Fernandes</span></div></div>
              <div class="diss-data">06/09/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="cláudia caetano gonçalves mendes lima ensino híbrido ept conflito mediação pedagógico-didática emmanuela ferreira de lima">
              <div class="diss-num">13</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Ensino Híbrido na EPT: Do Conflito à Mediação Pedagógico-Didática</div><div class="diss-meta"><span>👤 Cláudia Caetano Gonçalves Mendes Lima</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div>
              <div class="diss-data">22/10/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="genaina fernandes guerra metodologia científica ensino médio integrado instituto federal goiano campus ceres matias noll">
              <div class="diss-num">14</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Metodologia Científica no Ensino Médio Integrado: Um Estudo de Caso no IF Goiano Campus Ceres</div><div class="diss-meta"><span>👤 Genaina Fernandes Guerra</span><span>🎓 Matias Noll</span></div></div>
              <div class="diss-data">31/10/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="rayce cristina monteiro parente evasão escolar eja educação jovens adultos integrada educação profissional ifto campus palmas jussara de fátima alves campos oliveira">
              <div class="diss-num">15</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">Evasão Escolar: Uma Realidade no Curso de EJA Integrada à Educação Profissional do IFTO – Campus Palmas</div><div class="diss-meta"><span>👤 Rayce Cristina Monteiro Parente</span><span>🎓 Jussara de Fátima Alves Campos Oliveira</span></div></div>
              <div class="diss-data">20/11/2019</div>
            </div>
            <div class="diss-item" data-linha="l2" data-texto="lara yasmin almeida carvalho constituição cultura escolar perspectiva democrática instituto federal goiano josé carlos moreira de souza">
              <div class="diss-num">16</div><div class="diss-linha-dot l2"></div>
              <div class="diss-info"><div class="diss-titulo">A Constituição de uma Cultura Escolar na Perspectiva Democrática no IF Goiano</div><div class="diss-meta"><span>👤 Lara Yasmin Almeida Carvalho</span><span>🎓 José Carlos Moreira de Souza</span></div></div>
              <div class="diss-data">26/11/2019</div>
            </div>
            <div class="diss-item" data-linha="l1" data-texto="jainer diogo vieira matos catálogo mineral objeto aprendizagem apoiar ensino mineralogia júlio césar ferreira">
              <div class="diss-num">17</div><div class="diss-linha-dot l1"></div>
              <div class="diss-info"><div class="diss-titulo">Catálogo Mineral: Objeto de Aprendizagem para Apoiar o Ensino de Mineralogia</div><div class="diss-meta"><span>👤 Jainer Diogo Vieira Matos</span><span>🎓 Júlio César Ferreira</span></div></div>
              <div class="diss-data">18/12/2019</div>
            </div>
          </div>
        </div>

        <!-- 2020 -->
        <div class="diss-grupo" data-ano="2020">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2020</h3><span class="ano-count">20 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="l1" data-texto="willian rayner lima educação profissional reintegração social presos centro internamento reeducação distrito federal leia adriana da silva santiago"><div class="diss-num">18</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Educação Profissional e a Reintegração Social dos Presos: Um Estudo de Caso no CIR do DF</div><div class="diss-meta"><span>👤 Willian Rayner Lima</span><span>🎓 Leia Adriana da Silva Santiago</span></div></div><div class="diss-data">10/07/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="priscila de lima gomes egressos sistema prisional reinserção convívio social educação profissional leia adriana da silva santiago"><div class="diss-num">19</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Egressos do Sistema Prisional: Há Possibilidade de Reinserção no Convívio Social pela Educação Profissional?</div><div class="diss-meta"><span>👤 Priscila de Lima Gomes</span><span>🎓 Leia Adriana da Silva Santiago</span></div></div><div class="diss-data">10/07/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="gilmar rodrigues morais tecnologia digital gestão escolar formação docente fernando barbosa matos"><div class="diss-num">20</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Tecnologia Digital Aplicada na Gestão Escolar para Promover a Formação Docente</div><div class="diss-meta"><span>👤 Gilmar Rodrigues Morais</span><span>🎓 Fernando Barbosa Matos</span></div></div><div class="diss-data">12/08/2020</div></div>
            <div class="diss-item" data-linha="l2" data-texto="cícero batista dos santos lima acessibilidade curricular inclusão escolar instituto federal goias campus luziânia marco antônio de carvalho"><div class="diss-num">21</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Acessibilidade Curricular: Um Estudo de Caso sobre Inclusão Escolar no IFG – Campus Luziânia</div><div class="diss-meta"><span>👤 Cícero Batista dos Santos Lima</span><span>🎓 Marco Antônio de Carvalho</span></div></div><div class="diss-data">28/08/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="suellem ferreira do amaral oliveira iniciação científica ensino médio técnico integrado instituto federal goiano campus morrinhos emmanuela ferreira de lima"><div class="diss-num">22</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Iniciação Científica no Ensino Médio Técnico Integrado: Um Estudo de Caso no IF Goiano – Campus Morrinhos</div><div class="diss-meta"><span>👤 Suellem Ferreira do Amaral Oliveira</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">20/08/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="kellen de lima silva práticas de leitura ensino médio integrado perspectivas formação omnilateral juliana cristina da costa fernandes"><div class="diss-num">23</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Práticas de Leitura em uma Instituição de Ensino Médio Integrado: Perspectivas para uma Formação Omnilateral</div><div class="diss-meta"><span>👤 Kellen de Lima Silva</span><span>🎓 Juliana Cristina da Costa Fernandes</span></div></div><div class="diss-data">20/08/2020</div></div>
            <div class="diss-item" data-linha="l2" data-texto="sidineya aires de medeiros programa nacional assistência estudantil educação profissional tecnológica if goiano campus morrinhos sangelita miranda franco mariano"><div class="diss-num">24</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Programa Nacional de Assistência Estudantil na EPT: Um Estudo de Caso no IF Goiano – Campus Morrinhos</div><div class="diss-meta"><span>👤 Sidineya Aires de Medeiros</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">04/09/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="giseli cristina da silva schneider desenvolvimento avaliação aplicativo esate escala autoeficácia estudo orientação aprendizagem desempenho escolar fernando barbosa matos"><div class="diss-num">25</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Desenvolvimento e Avaliação do Aplicativo ESATE: Escala de Autoeficácia e sua Correlação com o Desempenho Escolar</div><div class="diss-meta"><span>👤 Giseli Cristina da Silva Schneider</span><span>🎓 Fernando Barbosa Matos</span></div></div><div class="diss-data">31/08/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="marcelo silva oliveira jovem aprendiz ept caso capacitação para o futuro cras marco antônio de carvalho"><div class="diss-num">26</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Jovem Aprendiz e a EPT: O Caso Capacitação para o Futuro em um CRAS</div><div class="diss-meta"><span>👤 Marcelo Silva Oliveira</span><span>🎓 Marco Antônio de Carvalho</span></div></div><div class="diss-data">02/09/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="kamilla assis tavares currículo integrado história institucional formação técnica integrada ensino médio instituto federal marcos fernandes sobrinho"><div class="diss-num">27</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Currículo Integrado e História Institucional: A Formação Técnica Integrada ao Ensino Médio em um IF</div><div class="diss-meta"><span>👤 Kamilla Assis Tavares</span><span>🎓 Marcos Fernandes Sobrinho</span></div></div><div class="diss-data">08/09/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="roberta da silva costa práticas integradoras ensino geografia proposta mediada uso tecnologias ensino médio integrado emmanuela ferreira de lima"><div class="diss-num">28</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Práticas Integradoras no Ensino de Geografia: Uma Proposta Mediada pelo Uso de Tecnologias no EMI</div><div class="diss-meta"><span>👤 Roberta da Silva Costa</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">22/10/2020</div></div>
            <div class="diss-item" data-linha="l2" data-texto="reinaldo araújo gregoldo educação ambiental instituto federal de brasília campus são sebastião concepções práticas gestores professores ensino médio integrado josé carlos moreira de souza"><div class="diss-num">29</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Educação Ambiental no IFB – Campus São Sebastião: Concepções e Práticas de Gestores e Professores do EMI</div><div class="diss-meta"><span>👤 Reinaldo Araújo Gregoldo</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">05/11/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="tássia galvão araújo assis jornalismo científico publicização pesquisas institutos federais estado goiás matias noll"><div class="diss-num">30</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">O Jornalismo Científico como Meio de Publicização de Pesquisas: Um Estudo de Caso nos IFs de Goiás</div><div class="diss-meta"><span>👤 Tássia Galvão Araújo Assis</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">17/11/2020</div></div>
            <div class="diss-item" data-linha="l2" data-texto="patrícia arantes peixoto borges vivências desafios possibilidades avaliações aprendizagem ensino médio integrado ifg campus itumbiara sangelita miranda franco mariano"><div class="diss-num">31</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Vivências, Desafios e Possibilidades das Avaliações de Aprendizagem no EMI: Estudo de Caso no IFG – Campus Itumbiara</div><div class="diss-meta"><span>👤 Patrícia Arantes Peixoto Borges</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">23/11/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="elciane arantes peixoto lunarti utilização lúdico metodologia ativa ensino geografia educação básica nível médio cinthia maria felicio"><div class="diss-num">32</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Utilização do Lúdico como Metodologia Ativa para o Ensino de Geografia na Educação Básica de Nível Médio</div><div class="diss-meta"><span>👤 Elciane Arantes Peixoto Lunarti</span><span>🎓 Cinthia Maria Felicio</span></div></div><div class="diss-data">27/11/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="mariana lucas mendes participação mulheres gestão if goiano campus urutaí perspectiva histórica cristiane maria ribeiro"><div class="diss-num">33</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">A Participação das Mulheres na Gestão do IF Goiano Campus Urutaí: Uma Perspectiva Histórica (1953–2019)</div><div class="diss-meta"><span>👤 Mariana Lucas Mendes</span><span>🎓 Cristiane Maria Ribeiro</span></div></div><div class="diss-data">16/12/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="iasmim ferreira da silva práxis pedagógica educação profissional mediação tecnológica docente cinthia maria felicio"><div class="diss-num">34</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Práxis Pedagógica na Educação Profissional: Mediação Tecnológica Docente</div><div class="diss-meta"><span>👤 Iasmim Ferreira da Silva</span><span>🎓 Cinthia Maria Felicio</span></div></div><div class="diss-data">30/12/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="regiane aparecida da silva propostas práticas educativas formação integral emancipação educação jovens adultos cinthia maria felicio"><div class="diss-num">35</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Propostas de Práticas Educativas para a Formação Integral e Emancipação na EJA</div><div class="diss-meta"><span>👤 Regiane Aparecida da Silva</span><span>🎓 Cinthia Maria Felicio</span></div></div><div class="diss-data">29/12/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="patrícia garcia souza padovani resolução problemas metodologia ativa ensino função afim perspectiva formação integral júlio césar ferreira"><div class="diss-num">36</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Resolução de Problemas: Uma Metodologia Ativa para o Ensino de Função Afim na Perspectiva da Formação Integral</div><div class="diss-meta"><span>👤 Patrícia Garcia Souza Padovani</span><span>🎓 Júlio César Ferreira</span></div></div><div class="diss-data">23/12/2020</div></div>
            <div class="diss-item" data-linha="ls" data-texto="angélica ferreira melo programa institucional iniciação científica desenvolvimento tecnológico instituto federal goiano perfil produção acadêmica evolução estudantes matias noll"><div class="diss-num">37</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Programa Institucional de Iniciação Científica do IF Goiano: Perfil, Produção Acadêmica e Evolução dos Estudantes</div><div class="diss-meta"><span>👤 Angélica Ferreira Melo</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">23/12/2020</div></div>
          </div>
        </div>

        <!-- 2021 -->
        <div class="diss-grupo" data-ano="2021">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2021</h3><span class="ano-count">16 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="ls" data-texto="daiane de oliveira silva comportamento informacional fontes pesquisas estudantes iniciação científica matias noll"><div class="diss-num">38</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Comportamento Informacional ao Utilizar Fontes de Pesquisas: Um Estudo de Caso das Buscas dos Estudantes de IC</div><div class="diss-meta"><span>👤 Daiane de Oliveira Silva</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">28/12/2020</div></div>
            <div class="diss-item" data-linha="l1" data-texto="jordana vilela martins metodologias ativas ensino integrado pensamento computacional metodologia ensino lógica computacional júlio césar ferreira"><div class="diss-num">39</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Metodologias Ativas no Ensino Integrado: Pensamento Computacional como Metodologia de Ensino de Lógica Computacional</div><div class="diss-meta"><span>👤 Jordana Vilela Martins</span><span>🎓 Júlio César Ferreira</span></div></div><div class="diss-data">27/05/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="elisângela ladeira de moura andrade produção textual ensino médio integrado prática pedagógica emancipadora léia adriana da silva santiago"><div class="diss-num">40</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Produção Textual no Ensino Médio Integrado: Em Busca de uma Prática Pedagógica Emancipadora</div><div class="diss-meta"><span>👤 Elisângela Ladeira de Moura Andrade</span><span>🎓 Léia Adriana da Silva Santiago</span></div></div><div class="diss-data">02/07/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="andré carlos francisco relação biblioteca educação profissional tecnológica aprendizado reflexão crítica elis dener lima alves"><div class="diss-num">41</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Relação entre Biblioteca e EPT: Aprendizado e Reflexão Crítica</div><div class="diss-meta"><span>👤 André Carlos Francisco</span><span>🎓 Elis Dener Lima Alves</span></div></div><div class="diss-data">29/07/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="márcia de souza oliveira paes leme alberto educação trabalho reintegração social apac ituiutaba léia adriana da silva santiago"><div class="diss-num">42</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Educação, Trabalho e Reintegração Social na APAC de Ituiutaba/MG</div><div class="diss-meta"><span>👤 Márcia de Souza Oliveira Paes Leme Alberto</span><span>🎓 Léia Adriana da Silva Santiago</span></div></div><div class="diss-data">02/08/2021</div></div>
            <div class="diss-item" data-linha="l2" data-texto="chayene straykyver pastori de lima formação inicial trabalho docente pibid contexto licenciaturas instituto federal goiano campus morrinhos sangelita miranda franco mariano"><div class="diss-num">43</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Formação Inicial e Trabalho Docente: O PIBID no Contexto das Licenciaturas do IF Goiano – Campus Morrinhos</div><div class="diss-meta"><span>👤 Chayene Straykyver Pastori de Lima</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">25/08/2021</div></div>
            <div class="diss-item" data-linha="ls" data-texto="suleny maria silveira novo ensino médio noturno educação profissional tecnológica marcos de moraes sousa"><div class="diss-num">49</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Estudo de Caso sobre uma Aproximação do Novo Ensino Médio Noturno (NEMN) com a EPT</div><div class="diss-meta"><span>👤 Suleny Maria Silveira</span><span>🎓 Marcos de Moraes Sousa</span></div></div><div class="diss-data">26/08/2021</div></div>
            <div class="diss-item" data-linha="ls" data-texto="letícia rodrigues dos santos competência em informação estudantes educação profissional tecnológica instituto federal goiano campus morrinhos emmanuela ferreira de lima"><div class="diss-num">45</div><div class="diss-linha-dot ls"></div><div class="diss-info"><div class="diss-titulo">Competência em Informação dos Estudantes da EPT: Um Estudo de Caso no IF Goiano – Campus Morrinhos</div><div class="diss-meta"><span>👤 Letícia Rodrigues dos Santos</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">31/08/2021</div></div>
            <div class="diss-item" data-linha="l2" data-texto="adenilda rosa da silva junqueira memórias narrativas egressos proeja instituto federal goiano campus iporá josé carlos moreira de souza"><div class="diss-num">44</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Memórias e Narrativas de Egressos/as do PROEJA do IF Goiano – Campus Iporá</div><div class="diss-meta"><span>👤 Adenilda Rosa da Silva Junqueira</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">05/10/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="leoneide paula da costa prática educativa desafios curso técnico meio ambiente instituto tecnológico estado goiás júlio césar ferreira"><div class="diss-num">46</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Prática Educativa e os Desafios do Curso Técnico em Meio Ambiente no ITEGO – GOC</div><div class="diss-meta"><span>👤 Leoneide Paula da Costa</span><span>🎓 Júlio César Ferreira</span></div></div><div class="diss-data">06/10/2021</div></div>
            <div class="diss-item" data-linha="l2" data-texto="suelia da silva araujo influências simulado aprendizagens discentes ensino médio if goiano campus iporá sangelita miranda franco mariano"><div class="diss-num">47</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Influências do Simulado nas Aprendizagens dos Discentes do Ensino Médio do IF Goiano – Campus Iporá</div><div class="diss-meta"><span>👤 Suelia da Silva Araujo</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">26/10/2021</div></div>
            <div class="diss-item" data-linha="l2" data-texto="danyla martins rezende da costa perspectiva discente fatores evasão escolar instituto federal goiano marco antônio de carvalho"><div class="diss-num">48</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Perspectiva do Discente e os Fatores de Evasão Escolar: Estudo de Caso no IF Goiano</div><div class="diss-meta"><span>👤 Danyla Martins Rezende da Costa</span><span>🎓 Marco Antônio de Carvalho</span></div></div><div class="diss-data">27/10/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="leonardo henrique silva competência em informação educação profissional tecnológica papel biblioteca emmanuela ferreira de lima"><div class="diss-num">50</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Competência em Informação na EPT: O Papel da Biblioteca</div><div class="diss-meta"><span>👤 Leonardo Henrique Silva</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">25/11/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="lílian gobbi dutra medeiros ensino propedêutico profissional ensino médio iftm entre o prescrito e o vivido léia adriana da silva santiago"><div class="diss-num">51</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Ensino Propedêutico e Profissional no Ensino Médio do IFTM: Entre o Prescrito e o Vivido</div><div class="diss-meta"><span>👤 Lílian Gobbi Dutra Medeiros</span><span>🎓 Léia Adriana da Silva Santiago</span></div></div><div class="diss-data">29/11/2021</div></div>
            <div class="diss-item" data-linha="l1" data-texto="mirian rodrigues silva vasconcelos design instrucional cursos educação profissional tecnológica educação a distância fernando barbosa matos"><div class="diss-num">52</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Design Instrucional de Cursos na EPT: Um Olhar para a Educação a Distância</div><div class="diss-meta"><span>👤 Mirian Rodrigues Silva Vasconcelos</span><span>🎓 Fernando Barbosa Matos</span></div></div><div class="diss-data">17/12/2021</div></div>
          </div>
        </div>

        <!-- 2022 -->
        <div class="diss-grupo" data-ano="2022">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2022</h3><span class="ano-count">10 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="l1" data-texto="michele da silva valadão fernandes sintomas depressivos qualidade vida escolares ensino médio integrado prevalência fatores matias noll"><div class="diss-num">53</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Sintomas Depressivos e Qualidade de Vida em Escolares do EMI: Prevalência e Fatores Associados</div><div class="diss-meta"><span>👤 Michele da Silva Valadão Fernandes</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">23/02/2022</div></div>
            <div class="diss-item" data-linha="l2" data-texto="luciana helena de lima educação física perspectiva formação omnilateral nível atividade física percepção qualidade vida estudantes iftm campus ituiutaba josé carlos moreira de souza"><div class="diss-num">54</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Educação Física na Perspectiva da Formação Omnilateral e sua Relação com a Qualidade de Vida em Estudantes do IFTM</div><div class="diss-meta"><span>👤 Luciana Helena de Lima</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">24/02/2022</div></div>
            <div class="diss-item" data-linha="l2" data-texto="elias paes de araújo comunidade remanescente quilombos boa nova professor jamil racismo educação não formal empoderamento marco antônio de carvalho"><div class="diss-num">55</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Comunidade Remanescente de Quilombos Boa Nova: Olhares sobre Racismo, Educação Não Formal e Empoderamento</div><div class="diss-meta"><span>👤 Elias Paes de Araújo</span><span>🎓 Marco Antônio de Carvalho</span></div></div><div class="diss-data">29/03/2022</div></div>
            <div class="diss-item" data-linha="l2" data-texto="wolney rodrigues ferreira práticas educativas escola família agrícola goiás pedagogia alternância formação integral estudante marco antônio de carvalho"><div class="diss-num">56</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Práticas Educativas da Escola Família Agrícola de Goiás: Pedagogia da Alternância e Formação Integral</div><div class="diss-meta"><span>👤 Wolney Rodrigues Ferreira</span><span>🎓 Marco Antônio de Carvalho</span></div></div><div class="diss-data">31/03/2022</div></div>
            <div class="diss-item" data-linha="l1" data-texto="regina márcia ferreira silva barreiras prática atividade física estudantes ensino médio integrado pandemia covid matias noll"><div class="diss-num">57</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Barreiras à Prática de Atividade Física em Estudantes do EMI durante a Pandemia da COVID-19</div><div class="diss-meta"><span>👤 Regina Márcia Ferreira Silva</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">04/05/2022</div></div>
            <div class="diss-item" data-linha="l2" data-texto="luana luiza de souza borges autonomia educando educação profissional tecnológica gestão democrático-participativa espaço formativo flávio manoel coelho borges cardoso"><div class="diss-num">58</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Autonomia do Educando na EPT: A Gestão Democrático-Participativa como Espaço Formativo</div><div class="diss-meta"><span>👤 Luana Luiza de Souza Borges</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">28/04/2022</div></div>
            <div class="diss-item" data-linha="l1" data-texto="morgana bruno henrique guimarães biblioteca escolar pesquisa cursos ensino médio profissionalizantes if goiano campus morrinhos fernando barbosa matos"><div class="diss-num">59</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Biblioteca Escolar e a Pesquisa nos Cursos de Ensino Médio Profissionalizantes do IF Goiano – Campus Morrinhos</div><div class="diss-meta"><span>👤 Morgana Bruno Henrique Guimarães</span><span>🎓 Fernando Barbosa Matos</span></div></div><div class="diss-data">02/06/2022</div></div>
            <div class="diss-item" data-linha="l1" data-texto="raquel dark conceição justino propostas pedagógicas ensino química ciências licenciatura adaptação recursos visuais surdos mirelle amaral de são bernado"><div class="diss-num">60</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Propostas Pedagógicas para o Ensino de Química por Estudantes de Licenciatura: Adaptação para Surdos</div><div class="diss-meta"><span>👤 Raquel Dark Conceição Justino</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">27/07/2022</div></div>
            <div class="diss-item" data-linha="l2" data-texto="sarah elayne de freitas rezende fatores evasão escolar cursos técnicos integrados ensino médio marcos de moraes de sousa"><div class="diss-num">61</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Fatores de Evasão Escolar nos Cursos Técnicos Integrados ao Ensino Médio</div><div class="diss-meta"><span>👤 Sarah Elayne de Freitas Rezende</span><span>🎓 Marcos de Moraes de Sousa</span></div></div><div class="diss-data">23/11/2022</div></div>
          </div>
        </div>

        <!-- 2023 -->
        <div class="diss-grupo" data-ano="2023">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2023</h3><span class="ano-count">20 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="l1" data-texto="luiz mário lopes cardoso elo ensino médio integrado componentes curriculares práticas pedagógicas integradoras emmanuela ferreira de lima"><div class="diss-num">62</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Elo entre o Ensino Médio Integrado e seus Componentes Curriculares: Práticas Pedagógicas Integradoras</div><div class="diss-meta"><span>👤 Luiz Mário Lopes Cardoso</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">10/03/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="vânia claudia guimarães extensão educação profissional tecnológica programa meninas cientistas empoderamento feminino mirelle amaral de são bernardo"><div class="diss-num">63</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Extensão na EPT: O Programa Meninas Cientistas e o Empoderamento Feminino</div><div class="diss-meta"><span>👤 Vânia Claudia Guimarães</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">31/03/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="leila coutinho dias da silva atuação tradutor intérprete língua de sinais português tilsp instituto federal goiano percepções estratégias formação omnilateral mirelle amaral de são bernardo"><div class="diss-num">64</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Atuação do TILSP no IF Goiano: Percepções e Estratégias para uma Formação Omnilateral</div><div class="diss-meta"><span>👤 Leila Coutinho Dias da Silva</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">20/04/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="luciana santos da rosa rotina escolar estudantes ensino médio integrado if goiano fatores risco estresse campus iporá emmanuela ferreira de lima"><div class="diss-num">65</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Rotina Escolar dos Estudantes do EMI do IF Goiano e os Fatores de Risco para o Estresse</div><div class="diss-meta"><span>👤 Luciana Santos da Rosa</span><span>🎓 Emmanuela Ferreira de Lima</span></div></div><div class="diss-data">19/05/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="vanilda maria campos formação omnilateral jardim botânico campus rio verde instituto federal goiano ambiente ensino-aprendizagem josé carlos moreira de souza"><div class="diss-num">66</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Formação Omnilateral em Perspectiva: O Jardim Botânico do Campus Rio Verde como Ambiente de Ensino</div><div class="diss-meta"><span>👤 Vanilda Maria Campos</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">27/06/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="lucilene batista ribeiro projeto pedagógico curso técnico meio ambiente integrado ensino médio caminhos currículo integrado flávio manoel coelho borges cardoso"><div class="diss-num">67</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O PPC do Curso Técnico em Meio Ambiente Integrado ao Ensino Médio: Caminhos para o Currículo Integrado</div><div class="diss-meta"><span>👤 Lucilene Batista Ribeiro</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">29/06/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="suelma dos reis pereira alves aprofundando interiorização educação profissional tecnológica if goiano campus ceres impactos egressos guarinos léia adriana da silva santiago"><div class="diss-num">68</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Aprofundando a Interiorização da EPT do IF Goiano Campus Ceres: Impactos Vividos por Egressos de Guarinos</div><div class="diss-meta"><span>👤 Suelma dos Reis Pereira Alves</span><span>🎓 Léia Adriana da Silva Santiago</span></div></div><div class="diss-data">07/07/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="heloisia carneiro de souza fatores associados permanência êxito estudantes cursos técnicos subsequentes concomitantes flávio manoel coelho borges cardoso"><div class="diss-num">69</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Fatores Associados à Permanência e ao Êxito dos Estudantes nos Cursos Técnicos Subsequentes/Concomitantes</div><div class="diss-meta"><span>👤 Heloisia Carneiro de Souza</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">26/07/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="cleonice borges ribeiro instituto federal goiano campus ceres oferta ensino médio integrado interfaces área língua portuguesa sangelita miranda franco mariano"><div class="diss-num">70</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">O IF Goiano – Campus Ceres, a Oferta do Ensino Médio Integrado e Interfaces com a Língua Portuguesa</div><div class="diss-meta"><span>👤 Cleonice Borges Ribeiro</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">28/07/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="naiara maria de sousa camargos processo ensino-aprendizagem tempos pandemia covid perspectivas experiências ensino médio integrado instituto federal goiano campus ceres elis dener lima alves"><div class="diss-num">71</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Processo de Ensino-Aprendizagem em Tempos de Pandemia: Perspectivas do EMI no IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Naiara Maria de Sousa Camargos</span><span>🎓 Elis Dener Lima Alves</span></div></div><div class="diss-data">24/08/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="cristiane borges dos santos interiorização educação profissional tecnológica abrangência geográfica ensino médio integrado if goiano campus iporá elis dener lima alves"><div class="diss-num">72</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Interiorização da EPT: Abrangência Geográfica do EMI do IF Goiano – Campus Iporá</div><div class="diss-meta"><span>👤 Cristiane Borges dos Santos</span><span>🎓 Elis Dener Lima Alves</span></div></div><div class="diss-data">30/08/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="ângela cláudia dias domingues materialização formação omnilateral instituto federal goiano campus trindade discursos desafios proposições josé carlos moreira de souza"><div class="diss-num">73</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Materialização da Formação Omnilateral no IF Goiano – Campus Trindade: Discursos, Desafios e Proposições</div><div class="diss-meta"><span>👤 Ângela Cláudia Dias Domingues</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">30/10/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="denise francisca de sousa criação história em quadrinhos tecnologias digitais perspectivas formação omnilateral mirelle amaral de são bernardo"><div class="diss-num">74</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">A Criação de História em Quadrinhos Utilizando Tecnologias Digitais: Perspectivas da Formação Omnilateral</div><div class="diss-meta"><span>👤 Denise Francisca de Sousa</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">31/10/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="rosita camilo de souza educação humana crítica antirracista ensino história cultura afro-brasileira cursos técnicos integrados rhanya rafaella rodrigues"><div class="diss-num">75</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Educação Humana, Crítica e Antirracista: O Ensino da História e Cultura Afro-Brasileira nos Cursos Técnicos Integrados</div><div class="diss-meta"><span>👤 Rosita Camilo de Souza</span><span>🎓 Rhanya Rafaella Rodrigues</span></div></div><div class="diss-data">01/11/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="wanderleia maria de freitas passado presente história memória associação surdos goiânia asg influência mundo trabalho sangelita miranda franco mariano"><div class="diss-num">76</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Entre o Passado e o Presente: História e Memória da Associação de Surdos de Goiânia e sua Influência no Trabalho</div><div class="diss-meta"><span>👤 Wanderleia Maria de Freitas</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">06/11/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="elton cesar silva morais contribuições reconhecimento expressões faciais ferramenta apoio processo ensino aprendizagem matias noll"><div class="diss-num">77</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Contribuições de Reconhecimento de Expressões Faciais como Ferramenta de Apoio ao Ensino e Aprendizagem</div><div class="diss-meta"><span>👤 Elton Cesar Silva Morais</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">08/11/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="valcione francisca gonçalves silva dimensão formação omnilateral educação escolar indígena povo tapuia rubiataba goiás josé carlos moreira de souza"><div class="diss-num">78</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Dimensão da Formação Omnilateral na Educação Escolar Indígena do Povo Tapuia em Rubiataba (GO)</div><div class="diss-meta"><span>👤 Valcione Francisca Gonçalves Silva</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">10/11/2023</div></div>
            <div class="diss-item" data-linha="l2" data-texto="ramayane bonacin braga meninas digitais cerrado estudo de caso empoderamento feminino computação if goiano campus ceres marcos de moraes sousa"><div class="diss-num">79</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Meninas Digitais no Cerrado: Um Estudo de Caso sobre Empoderamento Feminino na Computação do IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Ramayane Bonacin Braga</span><span>🎓 Marcos de Moraes Sousa</span></div></div><div class="diss-data">07/12/2023</div></div>
            <div class="diss-item" data-linha="l1" data-texto="andré da silva matias impacto fundamentos matemáticos desempenho acadêmico cálculo diferencial integral bacharelado agronomia if goiano mirelle amaral de são bernardo"><div class="diss-num">80</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Impacto dos Fundamentos Matemáticos no Desempenho Acadêmico em Cálculo: Estudo no Curso de Agronomia do IF Goiano</div><div class="diss-meta"><span>👤 André da Silva Matias</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">18/12/2023</div></div>
          </div>
        </div>

        <!-- 2024 -->
        <div class="diss-grupo" data-ano="2024">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2024</h3><span class="ano-count">14 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="l2" data-texto="cristhian chagas ribeiro financiamento pesquisa científica fatores associados submissões aprovações projetos agências fomento pesquisadores if goiano matias noll"><div class="diss-num">81</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Financiamento da Pesquisa Científica: Fatores Associados às Submissões e Aprovações de Projetos de Pesquisa no IF Goiano</div><div class="diss-meta"><span>👤 Cristhian Chagas Ribeiro</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">22/02/2024</div></div>
            <div class="diss-item" data-linha="l1" data-texto="jeferson eduardo silva acesso permanência pessoas pretas pardas indígenas ensino médio integrado curso técnico agropecuária instituto federal goiano campus ceres mirelle amaral de são bernardo"><div class="diss-num">82</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Acesso e Permanência de Pessoas Pretas, Pardas e Indígenas no EMI do Curso Técnico em Agropecuária – Campus Ceres</div><div class="diss-meta"><span>👤 Jeferson Eduardo Silva</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">04/03/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="nicolli godoi pereira qualidade de vida percepção técnicos administrativos educação rede federal educação profissional científica tecnológica matias noll"><div class="diss-num">83</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Qualidade de Vida: Percepção dos Técnicos Administrativos em Educação da Rede Federal de EPT</div><div class="diss-meta"><span>👤 Nicolli Godoi Pereira</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">21/03/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="ana maria galúcio figueira currículo integrado contexto formação politécnica escola ensino técnico estado pará eetepa itaituba sangelita miranda franco mariano"><div class="diss-num">84</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Currículo Integrado no Contexto de Formação Politécnica na EETEPA Itaituba</div><div class="diss-meta"><span>👤 Ana Maria Galúcio Figueira</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">26/04/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="tamires araújo lima participação permanência mulheres cargos gestão if goiano campus iporá sangelita miranda franco mariano"><div class="diss-num">85</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Participação e a Permanência das Mulheres em Cargos de Gestão no IF Goiano – Campus Iporá</div><div class="diss-meta"><span>👤 Tamires Araújo Lima</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">29/04/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="lourenildo targino competência informacional estudantes ensino profissional técnico motivação autoeficácia fontes aprendizagem sangelita miranda franco mariano"><div class="diss-num">86</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Competência Informacional dos Estudantes do Ensino Profissional e Técnico: Motivação, Autoeficácia e Fontes de Aprendizagem</div><div class="diss-meta"><span>👤 Lourenildo Targino</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">24/07/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="adailza alves de sousa crepaldi ensino médio integrado perspectiva formação omnilateral estudo de caso colégio estadual nova crixás sangelita miranda franco mariano"><div class="diss-num">87</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Ensino Médio Integrado na Perspectiva da Formação Omnilateral: Estudo de Caso em Colégio Estadual de Nova Crixás (GO)</div><div class="diss-meta"><span>👤 Adailza Alves de Sousa Crepaldi</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">08/08/2024</div></div>
            <div class="diss-item" data-linha="l1" data-texto="cássia de sousa fonseca meireles ensino médio integrado concepções práticas pedagógicas omnilateralidade flávio manoel coelho borges cardoso"><div class="diss-num">88</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Ensino Médio Integrado: Concepções, Práticas Pedagógicas e Omnilateralidade</div><div class="diss-meta"><span>👤 Cássia de Sousa Fonseca Meireles</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">28/08/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="rodrigo carneiro rodrigues capacitação continuada estratégia gestão pessoas servidores técnicos administrativos if goiano campus iporá jesiel souza silva"><div class="diss-num">89</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Capacitação Continuada como Estratégia de Gestão de Pessoas: Um Estudo com Servidores TAE do IF Goiano – Campus Iporá</div><div class="diss-meta"><span>👤 Rodrigo Carneiro Rodrigues</span><span>🎓 Jesiel Souza Silva</span></div></div><div class="diss-data">07/10/2024</div></div>
            <div class="diss-item" data-linha="l1" data-texto="edmar ferreira gomes ensino médio integrado práticas pedagógicas matemática ciências natureza combinação omnilateralidade flávio manoel coelho borges cardoso"><div class="diss-num">90</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O EMI e as Práticas Pedagógicas de Matemática e Ciências da Natureza: Uma Combinação para a Omnilateralidade</div><div class="diss-meta"><span>👤 Edmar Ferreira Gomes</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">23/10/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="manoel marçal rodrigues neto moradia estudantil if goiano campus ceres espaço formativo memórias estudantes egressos josé carlos moreira de souza"><div class="diss-num">91</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Moradia Estudantil do IF Goiano – Campus Ceres como Espaço Formativo: Memórias de Estudantes Egressos</div><div class="diss-meta"><span>👤 Manoel Marçal Rodrigues Neto</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">30/10/2024</div></div>
            <div class="diss-item" data-linha="l1" data-texto="luciene aparecida correia silva formação mulher curso técnico administração concomitante ead if goiano campus iporá percepções processo profissionalização mirelle amaral de são bernardo"><div class="diss-num">92</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Formação da Mulher no Curso Técnico em Administração EaD do IF Goiano Campus Iporá: Percepções sobre Profissionalização</div><div class="diss-meta"><span>👤 Luciene Aparecida Correia Silva</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">31/10/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="viviany gonçalves de lima percepção docente importância educação ambiental projetos extensão if goiano campus iporá fátima suely cunha"><div class="diss-num">93</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Percepção Docente sobre a Importância da Educação Ambiental nos Projetos de Extensão do IF Goiano Campus Iporá</div><div class="diss-meta"><span>👤 Viviany Gonçalves de Lima</span><span>🎓 Fátima Suely Cunha</span></div></div><div class="diss-data">06/11/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="eliana aparecida da silva fatores associados equidade gênero poder instituições ensino percepções desafios institutos federais goiás flávio manoel coelho borges cardoso"><div class="diss-num">94</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Fatores Associados à Equidade de Gênero e Poder em IFs de Goiás: Percepções e Desafios</div><div class="diss-meta"><span>👤 Eliana Aparecida da Silva</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">26/11/2024</div></div>
          </div>
        </div>

        <!-- 2025 -->
        <div class="diss-grupo" data-ano="2025">
          <div class="diss-ano-header" onclick="toggleAno(this)">
            <h3>📅 2025</h3><span class="ano-count">25 dissertações</span>
            <svg class="ano-chevron" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2.5"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </div>
          <div class="diss-lista">
            <div class="diss-item" data-linha="l1" data-texto="paulo rogério vitor da cruz trajetórias femininas relatos experiências professoras-gestoras if goiano jesiel souza silva"><div class="diss-num">95</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Trajetórias Femininas: Relatos das Experiências Vivenciadas pelas Professoras-Gestoras do IF Goiano</div><div class="diss-meta"><span>👤 Paulo Rogério Vitor da Cruz</span><span>🎓 Jesiel Souza Silva</span></div></div><div class="diss-data">28/11/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="alda vivianne moreira santana martins panorama nacional divisão sexual trabalho institutos federais flávio manoel coelho borges cardoso"><div class="diss-num">96</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Panorama Nacional da Divisão Sexual do Trabalho nos Institutos Federais</div><div class="diss-meta"><span>👤 Alda Vivianne Moreira Santana Martins</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">29/11/2024</div></div>
            <div class="diss-item" data-linha="l1" data-texto="woska pires da costa fatores associados atuação pesquisadores iniciação científica tecnológica marcos de moraes sousa"><div class="diss-num">97</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Fatores Associados à Atuação dos Pesquisadores na Iniciação Científica e Tecnológica</div><div class="diss-meta"><span>👤 Woska Pires da Costa</span><span>🎓 Marcos de Moraes Sousa</span></div></div><div class="diss-data">29/11/2024</div></div>
            <div class="diss-item" data-linha="l2" data-texto="marinéia moreira da silva impactos formação profissional tecnológica narrativas mulheres município itapuranga goiás fátima suely ribeiro cunha"><div class="diss-num">98</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Os Impactos da Formação Profissional e Tecnológica a Partir das Narrativas das Mulheres em Itapuranga-GO</div><div class="diss-meta"><span>👤 Marinéia Moreira da Silva</span><span>🎓 Fátima Suely Ribeiro Cunha</span></div></div><div class="diss-data">18/02/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="vinícius de souza minervino sequência didática investigação matemática contribuições educação financeira ensino técnico integrado médio júlio césar ferreira"><div class="diss-num">99</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Sequência Didática Baseada em Investigação Matemática: Contribuições para a Educação Financeira no Ensino Técnico</div><div class="diss-meta"><span>👤 Vinícius de Souza Minervino</span><span>🎓 Júlio César Ferreira</span></div></div><div class="diss-data">14/03/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="eduardo dias qualidade de vida percepção docentes rede federal educação profissional científica tecnológica matias noll"><div class="diss-num">100</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Qualidade de Vida: Percepção dos Docentes da Rede Federal de Educação Profissional, Científica e Tecnológica</div><div class="diss-meta"><span>👤 Eduardo Dias</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">13/03/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="bruna fortunato dos santos marinho adoecimento mental trabalhadores educação rhanya rafaella rodrigues"><div class="diss-num">101</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Adoecimento Mental em Trabalhadores da Educação</div><div class="diss-meta"><span>👤 Bruna Fortunato dos Santos Marinho</span><span>🎓 Rhanya Rafaella Rodrigues</span></div></div><div class="diss-data">01/04/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="tiago gebrim ensino crítico pós-verdade análise recepção uso notícias estudantes ensino médio integrado campus ceres if goiano mirelle amaral de são bernardo"><div class="diss-num">102</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Ensino Crítico e Pós-Verdade: Uma Análise da Recepção e Uso de Notícias pelos Estudantes do EMI no Campus Ceres</div><div class="diss-meta"><span>👤 Tiago Gebrim</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">16/04/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="claudete madalena valadão políticas públicas permanência estudantil redução evasão ensino médio integrado if goiano rhanya rafaella rodrigues"><div class="diss-num">103</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Segurando as Mãos que Escapam: O Papel das Políticas de Permanência na Redução da Evasão no EMI do IF Goiano</div><div class="diss-meta"><span>👤 Claudete Madalena Valadão</span><span>🎓 Rhanya Rafaella Rodrigues</span></div></div><div class="diss-data">22/04/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="gleusa grigório dos santos funções executivas associadas rendimento acadêmico ensino médio integrado rhanya rafaella rodrigues"><div class="diss-num">104</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Funções Executivas Associadas ao Rendimento Acadêmico no Contexto do Ensino Médio Integrado</div><div class="diss-meta"><span>👤 Gleusa Grigório dos Santos</span><span>🎓 Rhanya Rafaella Rodrigues</span></div></div><div class="diss-data">25/04/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="rodrigo do nascimento coelho saúde segurança trabalho formação ciências agrárias educação profissional tecnológica if goiano jesiel souza silva"><div class="diss-num">105</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Saúde e Segurança do Trabalho na Formação em Ciências Agrárias da EPT do IF Goiano</div><div class="diss-meta"><span>👤 Rodrigo do Nascimento Coelho</span><span>🎓 Jesiel Souza Silva</span></div></div><div class="diss-data">29/04/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="keila josé alves educação profissional tecnológica espaço transgressão caminhos formação antirracista mirelle amaral de são bernardo"><div class="diss-num">106</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Educação Profissional e Tecnológica como Espaço de Transgressão: Caminhos para uma Formação Antirracista</div><div class="diss-meta"><span>👤 Keila José Alves</span><span>🎓 Mirelle Amaral de São Bernardo</span></div></div><div class="diss-data">30/04/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="websa paula souza silva desenvolvimento sequência didática compreensão leitora artigos científicos ensino médio integrado rhanya rafaella rodrigues"><div class="diss-num">107</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Desenvolvimento de uma Sequência Didática para a Compreensão Leitora de Artigos Científicos no EMI</div><div class="diss-meta"><span>👤 Websa Paula Souza Silva</span><span>🎓 Rhanya Rafaella Rodrigues</span></div></div><div class="diss-data">12/05/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="tiago rodrigues galvão políticas públicas gestão educacional enfrentamento evasão escolar cursos técnicos agropecuária integrados ensino médio if goiano marcos moraes de sousa"><div class="diss-num">108</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Políticas Públicas e Gestão Educacional no Enfrentamento da Evasão Escolar nos Cursos Técnicos em Agropecuária do IF Goiano</div><div class="diss-meta"><span>👤 Tiago Rodrigues Galvão</span><span>🎓 Marcos Moraes de Sousa</span></div></div><div class="diss-data">30/05/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="divino pereira marques educação profissional tecnológica trabalho perspectivas emancipação jovens trabalhadores área agropecuária instituto federal goiano campus ceres josé carlos moreira de souza"><div class="diss-num">109</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A EPT e o Trabalho: Perspectivas de Emancipação de Jovens Trabalhadores da Área Agropecuária no IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Divino Pereira Marques</span><span>🎓 José Carlos Moreira de Souza</span></div></div><div class="diss-data">17/06/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="adriane gomes araújo tavares trabalho pedagógico tecnologias relações inteligência artificial educação profissional tecnológica natalia carvalhaes de oliveira"><div class="diss-num">110</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Trabalho Pedagógico com Tecnologias: Relações entre Inteligência Artificial e a Educação Profissional e Tecnológica</div><div class="diss-meta"><span>👤 Adriane Gomes Araújo Tavares</span><span>🎓 Natalia Carvalhaes de Oliveira</span></div></div><div class="diss-data">26/06/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="pedro henrique oliveira de miranda práticas reutilização recombinação pensamento computacional sequência didática curso técnico informática para internet integrado médio júlio césar ferreira"><div class="diss-num">111</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Práticas de Reutilização e Pensamento Computacional: Uma Sequência Didática para o Curso Técnico em Informática</div><div class="diss-meta"><span>👤 Pedro Henrique Oliveira de Miranda</span><span>🎓 Júlio César Ferreira</span></div></div><div class="diss-data">27/06/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="fernando josé alvarenga de moraes influência demografia permanência alunos ead flávio manoel coelho borges cardoso"><div class="diss-num">112</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">A Influência da Demografia na Permanência dos Alunos na EaD</div><div class="diss-meta"><span>👤 Fernando José Alvarenga de Moraes</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">11/09/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="marcia campos de jesus escola família agrícola uirapuru contribuição formação permanência jovem trabalhador campo fátima suely ribeiro cunha"><div class="diss-num">113</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Escola Família Agrícola de Uirapuru e sua Contribuição na Formação e Permanência do Jovem Trabalhador do/no Campo</div><div class="diss-meta"><span>👤 Marcia Campos de Jesus</span><span>🎓 Fátima Suely Ribeiro Cunha</span></div></div><div class="diss-data">03/10/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="larissa adriana da silveira castilho silva práticas de leitura desenvolvimento competência leitora estudantes 1 série ensino médio técnico integrado campus ceres denise dias"><div class="diss-num">114</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Práticas de Leitura: Desenvolvimento da Competência Leitora dos Estudantes do EMI – Campus Ceres</div><div class="diss-meta"><span>👤 Larissa Adriana da Silveira Castilho Silva</span><span>🎓 Denise Dias</span></div></div><div class="diss-data">30/10/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="letícia rejane carvalhaes alvarenga roncolato fatores associados permanência ensino médio integrado instituto federal goiano sangelita miranda franco mariano"><div class="diss-num">115</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Fatores Associados à Permanência no Ensino Médio Integrado do Instituto Federal Goiano</div><div class="diss-meta"><span>👤 Letícia Rejane Carvalhaes Alvarenga Roncolato</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">31/10/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="fernanda dias de andrade lima letramento literário método recepcional ensino formação estudante leitor 1 série educação profissional tecnológica denise dias"><div class="diss-num">116</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">Letramento Literário e Método Recepcional de Ensino: Caminhos para a Formação de Estudante-Leitor na EPT</div><div class="diss-meta"><span>👤 Fernanda Dias de Andrade Lima</span><span>🎓 Denise Dias</span></div></div><div class="diss-data">31/10/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="naiane queiroz ribeiro prevalência fatores associados perpetração vitimização violência psicológica física sexual namoro adolescente matias noll"><div class="diss-num">117</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Prevalência e Fatores Associados à Violência Psicológica, Física e Sexual no Namoro Adolescente</div><div class="diss-meta"><span>👤 Naiane Queiroz Ribeiro</span><span>🎓 Matias Noll</span></div></div><div class="diss-data">05/11/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="sonia maria gomes da silveira pesquisa autobiográfica estudantes curso técnico agropecuária integrado ensino médio sentidos formação escolar gustavo lopes ferreira"><div class="diss-num">118</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Pesquisa (Auto)Biográfica com Estudantes do Curso Técnico em Agropecuária: Sentidos Atribuídos à Formação Escolar</div><div class="diss-meta"><span>👤 Sonia Maria Gomes da Silveira</span><span>🎓 Gustavo Lopes Ferreira</span></div></div><div class="diss-data">07/11/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="guilherme nascimento roncolato fatores associados reprovação ensino médio integrado instituto federal goiano sangelita miranda franco mariano"><div class="diss-num">119</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Fatores Associados à Reprovação no Ensino Médio Integrado do Instituto Federal Goiano</div><div class="diss-meta"><span>👤 Guilherme Nascimento Roncolato</span><span>🎓 Sangelita Miranda Franco Mariano</span></div></div><div class="diss-data">10/11/2025</div></div>
            <div class="diss-item" data-linha="l1" data-texto="fátima da conceição moreira ensino geometria espacial emi quase experimento práticas integradas if goiano campus ceres flávio manoel coelho borges cardoso"><div class="diss-num">120</div><div class="diss-linha-dot l1"></div><div class="diss-info"><div class="diss-titulo">O Ensino de Geometria Espacial do EMI: Um Quase Experimento com Práticas Integradas no IF Goiano – Campus Ceres</div><div class="diss-meta"><span>👤 Fátima da Conceição Moreira</span><span>🎓 Flávio Manoel Coelho Borges Cardoso</span></div></div><div class="diss-data">14/11/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="adriel josé pereira vida formação estudantes programa moradia estudantil if goiano campus ceres perspectiva autobiográfica gustavo lopes ferreira"><div class="diss-num">121</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">Vida e Formação de Estudantes do Programa de Moradia Estudantil do IF Goiano – Campus Ceres: Uma Perspectiva Autobiográfica</div><div class="diss-meta"><span>👤 Adriel José Pereira</span><span>🎓 Gustavo Lopes Ferreira</span></div></div><div class="diss-data">14/11/2025</div></div>
            <div class="diss-item" data-linha="l2" data-texto="halleson lacerda lima impacto mobilidade urbana evasão escolar cursos técnicos enfermagem distrito federal jesiel souza silva"><div class="diss-num">122</div><div class="diss-linha-dot l2"></div><div class="diss-info"><div class="diss-titulo">O Impacto da Mobilidade Urbana na Evasão Escolar de Cursos Técnicos em Enfermagem do DF</div><div class="diss-meta"><span>👤 Halleson Lacerda Lima</span><span>🎓 Jesiel Souza Silva</span></div></div><div class="diss-data">21/11/2025</div></div>
          </div>
        </div>

      </div><!-- fim #dissContainer -->

      <div class="diss-vazio" id="dissVazio">Nenhuma dissertação encontrada para os filtros selecionados.</div>

    </div>
  </section>

  <!-- ================================================
       RODAPÉ
  ================================================ -->
  <footer>
    <div class="footer-inner">
      <div class="footer-brand">
        <h3>ProfEPT – IF Goiano Campus Ceres</h3>
        <p>
          Programa de Pós-Graduação em Educação Profissional e Tecnológica.<br />
          Unidade associada: Instituto Federal Goiano – Campus Ceres, Goiás.
        </p>
      </div>

      <div class="footer-col">
        <h4>Programa</h4>
        <p>ProfEPT — Mestrado Profissional em Educação Profissional e Tecnológica</p>
      </div>

      <div class="footer-col">
        <h4>Instituição</h4>
        <p>
          IF Goiano Campus Ceres<br />
          Ceres – Goiás – Brasil
        </p>
      </div>
    </div>

    <div class="footer-bottom">
      <span>© <span id="ano"></span> IF Goiano Campus Ceres · ProfEPT. Todos os direitos reservados.</span>
      <span>Autora: <strong style="color:#fff;">Verônica dos Santos</strong> &nbsp;·&nbsp; Desenvolvido por <strong style="color:#fff;">Lázaro Furtado</strong></span>
    </div>
  </footer>

  <!-- ================================================
       JAVASCRIPT
  ================================================ -->
  <script>
    /* --- Ano dinâmico --- */
    document.getElementById('ano').textContent = new Date().getFullYear();

    /* --- Nav shadow ao rolar --- */
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      navbar.classList.toggle('scrolled', window.scrollY > 20);
    });

    /* --- Menu hambúrguer --- */
    const hamburger   = document.getElementById('hamburger');
    const mobileMenu  = document.getElementById('mobileMenu');

    hamburger.addEventListener('click', () => {
      hamburger.classList.toggle('open');
      mobileMenu.classList.toggle('open');
    });
    hamburger.addEventListener('keydown', e => {
      if (e.key === 'Enter' || e.key === ' ') hamburger.click();
    });

    function closeMobileMenu() {
      hamburger.classList.remove('open');
      mobileMenu.classList.remove('open');
    }

    /* --- Animações reveal com IntersectionObserver --- */
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12 });

    reveals.forEach(el => observer.observe(el));

    /* --- Dissertações: accordion por ano --- */
    function toggleAno(header) {
      header.classList.toggle('open');
      const lista = header.nextElementSibling;
      lista.classList.toggle('open');
    }

    /* --- Dissertações: filtros --- */
    const searchInput  = document.getElementById('dissSearch');
    const filtroAno    = document.getElementById('filtroAno');
    const filtroLinha  = document.getElementById('filtroLinha');
    const dissVazio    = document.getElementById('dissVazio');

    function applyFilters() {
      const q      = searchInput.value.toLowerCase().trim();
      const ano    = filtroAno.value;
      const linha  = filtroLinha.value;

      const grupos = document.querySelectorAll('.diss-grupo');
      let totalVisible = 0;

      grupos.forEach(grupo => {
        const grupoAno = grupo.dataset.ano;
        const items    = grupo.querySelectorAll('.diss-item');
        let grupoVisible = 0;

        items.forEach(item => {
          const itemLinha = item.dataset.linha;
          const itemTexto = item.dataset.texto;
          const tituloEl  = item.querySelector('.diss-titulo');
          const metaEl    = item.querySelector('.diss-meta');
          const fullText  = (itemTexto + ' ' + (tituloEl ? tituloEl.textContent : '') + ' ' + (metaEl ? metaEl.textContent : '')).toLowerCase();

          const matchQ     = !q     || fullText.includes(q);
          const matchLinha = !linha || itemLinha === linha;
          const matchAno   = !ano   || grupoAno === ano;

          if (matchQ && matchLinha && matchAno) {
            item.classList.remove('hidden');
            grupoVisible++;
          } else {
            item.classList.add('hidden');
          }
        });

        // mostrar/ocultar grupo inteiro
        const header = grupo.querySelector('.diss-ano-header');
        const lista  = grupo.querySelector('.diss-lista');

        if (grupoVisible === 0 || (ano && grupoAno !== ano)) {
          grupo.style.display = 'none';
        } else {
          grupo.style.display = '';
          // se há busca ativa, abrir automaticamente
          if (q || linha) {
            header.classList.add('open');
            lista.classList.add('open');
          }
          totalVisible += grupoVisible;
        }
      });

      dissVazio.classList.toggle('show', totalVisible === 0);
    }

    searchInput.addEventListener('input', applyFilters);
    filtroAno.addEventListener('change', applyFilters);
    filtroLinha.addEventListener('change', applyFilters);
  </script>
</body>
</html>
