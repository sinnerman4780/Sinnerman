[SINNERMAN — Streamer Warzone 2.html](https://github.com/user-attachments/files/30520209/SINNERMAN.Streamer.Warzone.2.html)
<!DOCTYPE html>
<!-- saved from url=(0086)https://preview.unstoppabledomains.fun/e7e46f5e-fe3b-4d8e-80c8-172472c097cf/index.html -->
<html lang="it"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>SINNERMAN — Streamer Warzone</title>
  <meta name="description" content="SINNERMAN — Streamer Warzone su Twitch. Audace, ribelle, grintoso. Seguimi su Twitch e Instagram.">

  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns=&#39;http://www.w3.org/2000/svg&#39; viewBox=&#39;0 0 64 64&#39;%3E%3Crect width=&#39;64&#39; height=&#39;64&#39; fill=&#39;%23000&#39;/%3E%3Ctext x=&#39;50%25&#39; y=&#39;54%25&#39; font-size=&#39;38&#39; text-anchor=&#39;middle&#39; dominant-baseline=&#39;middle&#39; font-family=&#39;Arial Black,sans-serif&#39; font-weight=&#39;900&#39; fill=&#39;%23e60000&#39;%3ES%3C/text%3E%3C/svg%3E">

  <!-- Open Graph -->
  <meta property="og:title" content="SINNERMAN — Streamer Warzone">
  <meta property="og:description" content="Audace, ribelle, grintoso. Seguimi su Twitch: twitch.tv/sinnerman_80">
  <meta property="og:image" content="https://placehold.co/1200x630/0a0a0a/e60000?text=SINNERMAN">
  <meta property="og:url" content="https://sinnerman.brave">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="SINNERMAN — Streamer Warzone">
  <meta name="twitter:description" content="Audace, ribelle, grintoso. Seguimi su Twitch: twitch.tv/sinnerman_80">
  <meta name="twitter:image" content="https://placehold.co/1200x630/0a0a0a/e60000?text=SINNERMAN">

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,400;0,700;0,900;1,900&family=Barlow:wght@400;600;700&display=swap');

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --red: #e60000;
      --red-dim: #a00000;
      --bg: #060606;
      --bg2: #0e0e0e;
      --bg3: #141414;
      --text: #f0f0f0;
      --muted: #888;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Barlow', sans-serif;
      overflow-x: hidden;
    }

    /* ── NOISE OVERLAY ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 9999;
      opacity: .45;
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 clamp(1.5rem, 5vw, 4rem);
      height: 64px;
      background: rgba(6,6,6,.92);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(230,0,0,.15);
    }

    .nav-logo {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: 1.6rem;
      letter-spacing: .05em;
      color: var(--text);
      text-decoration: none;
    }
    .nav-logo span { color: var(--red); }

    .nav-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }
    .nav-links a {
      color: var(--muted);
      text-decoration: none;
      font-size: .85rem;
      font-weight: 600;
      letter-spacing: .1em;
      text-transform: uppercase;
      transition: color .2s;
    }
    .nav-links a:hover { color: var(--red); }

    .nav-cta {
      background: var(--red);
      color: #fff !important;
      padding: .45rem 1.1rem;
      border-radius: 3px;
      font-weight: 700 !important;
      letter-spacing: .08em;
      transition: background .2s !important;
    }
    .nav-cta:hover { background: #ff1a1a !important; color: #fff !important; }

    /* ── HERO ── */
    .hero {
      min-height: 100vh;
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 2rem;
      padding: 100px clamp(1.5rem, 6vw, 6rem) 4rem;
      position: relative;
      overflow: hidden;
    }

    .hero::after {
      content: '';
      position: absolute;
      inset: 0;
      background: radial-gradient(ellipse 60% 70% at 80% 50%, rgba(230,0,0,.12) 0%, transparent 70%);
      pointer-events: none;
    }

    .hero-text { position: relative; z-index: 2; }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: rgba(230,0,0,.12);
      border: 1px solid rgba(230,0,0,.35);
      color: var(--red);
      font-size: .75rem;
      font-weight: 700;
      letter-spacing: .15em;
      text-transform: uppercase;
      padding: .35rem .9rem;
      border-radius: 2px;
      margin-bottom: 1.5rem;
    }
    .hero-badge .dot {
      width: 8px; height: 8px;
      background: var(--red);
      border-radius: 50%;
      animation: pulse 1.5s ease-in-out infinite;
    }
    @keyframes pulse {
      0%,100% { opacity: 1; transform: scale(1); }
      50% { opacity: .4; transform: scale(.7); }
    }

    .hero h1 {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-style: italic;
      font-size: clamp(4.5rem, 10vw, 9rem);
      line-height: .9;
      letter-spacing: -.02em;
      text-transform: uppercase;
      color: #fff;
    }
    .hero h1 .red { color: var(--red); }

    .hero-sub {
      margin-top: 1.5rem;
      font-size: clamp(1rem, 1.5vw, 1.2rem);
      color: var(--muted);
      font-weight: 400;
      max-width: 420px;
      line-height: 1.6;
    }

    .hero-actions {
      margin-top: 2.5rem;
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: var(--red);
      color: #fff;
      text-decoration: none;
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 700;
      font-size: 1.05rem;
      letter-spacing: .08em;
      text-transform: uppercase;
      padding: .8rem 2rem;
      border-radius: 3px;
      transition: background .2s, transform .2s;
    }
    .btn-primary:hover { background: #ff1a1a; transform: translateY(-2px); }

    .btn-ghost {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: transparent;
      border: 1px solid rgba(255,255,255,.2);
      color: var(--text);
      text-decoration: none;
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 700;
      font-size: 1.05rem;
      letter-spacing: .08em;
      text-transform: uppercase;
      padding: .8rem 2rem;
      border-radius: 3px;
      transition: border-color .2s, transform .2s;
    }
    .btn-ghost:hover { border-color: var(--red); color: var(--red); transform: translateY(-2px); }

    /* ── HERO IMAGE ── */
    .hero-image-wrap {
      position: relative;
      z-index: 2;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .hero-img-frame {
      position: relative;
      width: min(420px, 90%);
    }

    .hero-img-frame::before {
      content: '';
      position: absolute;
      inset: -3px;
      background: linear-gradient(135deg, var(--red) 0%, transparent 50%, var(--red) 100%);
      border-radius: 6px;
      z-index: -1;
    }

    .hero-img-frame::after {
      content: '';
      position: absolute;
      bottom: -20px;
      left: 10%;
      right: 10%;
      height: 40px;
      background: var(--red);
      filter: blur(30px);
      opacity: .5;
      z-index: -2;
    }

    .hero-img-frame img {
      width: 100%;
      height: auto;
      display: block;
      border-radius: 4px;
      object-fit: cover;
      filter: contrast(1.05) saturate(1.1);
    }

    .hero-img-tag {
      position: absolute;
      bottom: -14px;
      right: -14px;
      background: var(--red);
      color: #fff;
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: .75rem;
      letter-spacing: .12em;
      text-transform: uppercase;
      padding: .4rem .8rem;
      border-radius: 2px;
    }

    /* ── STATS BAR ── */
    .stats-bar {
      background: var(--bg2);
      border-top: 1px solid rgba(230,0,0,.2);
      border-bottom: 1px solid rgba(230,0,0,.2);
      padding: 1.8rem clamp(1.5rem, 6vw, 6rem);
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      gap: 1.5rem;
    }

    .stat {
      text-align: center;
    }
    .stat-value {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: clamp(2rem, 3.5vw, 2.8rem);
      color: var(--red);
      line-height: 1;
    }
    .stat-label {
      font-size: .75rem;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: .12em;
      margin-top: .3rem;
    }

    /* ── SECTIONS ── */
    section {
      padding: 6rem clamp(1.5rem, 6vw, 6rem);
    }

    .section-tag {
      font-size: .7rem;
      font-weight: 700;
      letter-spacing: .2em;
      text-transform: uppercase;
      color: var(--red);
      margin-bottom: .8rem;
    }

    .section-title {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-style: italic;
      font-size: clamp(2.5rem, 5vw, 4rem);
      text-transform: uppercase;
      line-height: 1;
      color: #fff;
    }

    /* ── CHI SONO ── */
    #chi-sono {
      background: var(--bg2);
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 4rem;
      align-items: center;
    }

    .about-img-wrap {
      position: relative;
    }

    .about-img-frame {
      position: relative;
      overflow: hidden;
      border-radius: 4px;
    }

    .about-img-frame::before {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 4px;
      height: 100%;
      background: var(--red);
      z-index: 2;
    }

    .about-img-frame img {
      width: 100%;
      max-height: 520px;
      object-fit: cover;
      object-position: center top;
      display: block;
      filter: grayscale(15%) contrast(1.05);
    }

    .about-img-overlay {
      position: absolute;
      bottom: 0; left: 0; right: 0;
      height: 40%;
      background: linear-gradient(to top, rgba(6,6,6,.9), transparent);
    }

    .about-text .section-title { margin-bottom: 1.5rem; }

    .about-text p {
      color: var(--muted);
      line-height: 1.75;
      margin-bottom: 1rem;
      font-size: 1rem;
    }
    .about-text p strong { color: var(--text); }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: .6rem;
      margin-top: 2rem;
    }
    .tag {
      background: rgba(230,0,0,.08);
      border: 1px solid rgba(230,0,0,.25);
      color: var(--red);
      font-size: .75rem;
      font-weight: 700;
      letter-spacing: .1em;
      text-transform: uppercase;
      padding: .35rem .8rem;
      border-radius: 2px;
    }

    /* ── WARZONE ── */
    #warzone {
      background: var(--bg);
      position: relative;
      overflow: hidden;
    }

    #warzone::before {
      content: 'WARZONE';
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: clamp(8rem, 20vw, 18rem);
      color: rgba(230,0,0,.04);
      white-space: nowrap;
      pointer-events: none;
      letter-spacing: -.02em;
    }

    .warzone-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-end;
      margin-bottom: 3rem;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: var(--bg3);
      border: 1px solid rgba(255,255,255,.05);
      border-radius: 4px;
      padding: 2rem;
      transition: border-color .25s, transform .25s;
      position: relative;
      overflow: hidden;
    }
    .card::before {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 3px;
      background: var(--red);
      transform: scaleX(0);
      transform-origin: left;
      transition: transform .3s;
    }
    .card:hover { border-color: rgba(230,0,0,.3); transform: translateY(-4px); }
    .card:hover::before { transform: scaleX(1); }

    .card-icon {
      font-size: 2.2rem;
      margin-bottom: 1rem;
      display: block;
    }
    .card h3 {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: 1.4rem;
      text-transform: uppercase;
      margin-bottom: .6rem;
      color: #fff;
    }
    .card p {
      color: var(--muted);
      font-size: .9rem;
      line-height: 1.6;
    }

    /* ── TWITCH SECTION ── */
    #stream {
      background: var(--bg2);
      text-align: center;
    }

    #stream .section-title { margin-bottom: 1rem; }

    .stream-desc {
      color: var(--muted);
      font-size: 1.05rem;
      max-width: 540px;
      margin: 0 auto 2.5rem;
      line-height: 1.7;
    }

    .stream-box {
      max-width: 680px;
      margin: 0 auto;
      background: var(--bg3);
      border: 1px solid rgba(230,0,0,.2);
      border-radius: 6px;
      padding: 3rem 2rem;
      position: relative;
      overflow: hidden;
    }

    .stream-box::before {
      content: '';
      position: absolute;
      inset: 0;
      background: radial-gradient(ellipse at center, rgba(230,0,0,.06) 0%, transparent 70%);
    }

    .twitch-logo {
      font-size: 3.5rem;
      display: block;
      margin-bottom: 1rem;
    }

    .stream-box h3 {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: 1.8rem;
      text-transform: uppercase;
      margin-bottom: .6rem;
    }

    .stream-box p {
      color: var(--muted);
      font-size: .95rem;
      margin-bottom: 1.8rem;
      line-height: 1.6;
      font-style: italic;
    }

    /* ── GALLERY ── */
    #gallery {
      background: var(--bg);
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-top: 2.5rem;
    }

    .gallery-item {
      border-radius: 4px;
      overflow: hidden;
      position: relative;
      aspect-ratio: 16/9;
    }
    .gallery-item.tall { grid-row: span 2; aspect-ratio: auto; }

    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      filter: saturate(.9) contrast(1.05);
      transition: transform .4s, filter .4s;
    }
    .gallery-item:hover img {
      transform: scale(1.04);
      filter: saturate(1.1) contrast(1.1);
    }

    .gallery-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(to top, rgba(0,0,0,.7) 0%, transparent 50%);
    }

    /* ── FOLLOW CTA ── */
    #follow {
      background: var(--bg);
      text-align: center;
      padding: 7rem clamp(1.5rem, 6vw, 6rem);
      position: relative;
      overflow: hidden;
    }

    #follow::before {
      content: '';
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      width: 600px; height: 600px;
      background: radial-gradient(circle, rgba(230,0,0,.1) 0%, transparent 70%);
      pointer-events: none;
    }

    #follow .section-title {
      font-size: clamp(3rem, 7vw, 6rem);
      margin-bottom: 1rem;
    }

    #follow p {
      color: var(--muted);
      font-size: 1.1rem;
      max-width: 480px;
      margin: 0 auto 2.5rem;
      line-height: 1.7;
    }

    .follow-buttons {
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .btn-ig {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: linear-gradient(135deg, #833ab4, #fd1d1d, #fcb045);
      color: #fff;
      text-decoration: none;
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 700;
      font-size: 1.05rem;
      letter-spacing: .08em;
      text-transform: uppercase;
      padding: .8rem 2rem;
      border-radius: 3px;
      transition: opacity .2s, transform .2s;
    }
    .btn-ig:hover { opacity: .9; transform: translateY(-2px); }

    .btn-discord {
      display: inline-flex;
      align-items: center;
      gap: .5rem;
      background: #5865F2;
      color: #fff;
      text-decoration: none;
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 700;
      font-size: 1.05rem;
      letter-spacing: .08em;
      text-transform: uppercase;
      padding: .8rem 2rem;
      border-radius: 3px;
      transition: background .2s, transform .2s;
    }
    .btn-discord:hover { background: #4752c4; transform: translateY(-2px); }

    /* ── FOOTER ── */
    footer {
      background: var(--bg2);
      border-top: 1px solid rgba(255,255,255,.05);
      padding: 2rem clamp(1.5rem, 6vw, 6rem);
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .footer-logo {
      font-family: 'Barlow Condensed', sans-serif;
      font-weight: 900;
      font-size: 1.3rem;
      letter-spacing: .05em;
      color: var(--text);
    }
    .footer-logo span { color: var(--red); }

    footer p {
      color: var(--muted);
      font-size: .8rem;
    }

    .footer-socials {
      display: flex;
      gap: 1rem;
    }
    .footer-socials a {
      color: var(--muted);
      text-decoration: none;
      font-size: .82rem;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: .08em;
      transition: color .2s;
    }
    .footer-socials a:hover { color: var(--red); }

    /* ── RESPONSIVE ── */
    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
        text-align: center;
        padding-bottom: 3rem;
      }
      .hero-text { order: 2; }
      .hero-image-wrap { order: 1; margin-bottom: 1rem; }
      .hero-sub { margin: 1.5rem auto 0; }
      .hero-actions { justify-content: center; }
      #chi-sono {
        grid-template-columns: 1fr;
        gap: 2.5rem;
      }
      .about-img-wrap { order: -1; }
    }

    @media (max-width: 600px) {
      nav { padding: 0 1.2rem; }
      .nav-links { display: none; }
      .gallery-grid { grid-template-columns: 1fr; }
      .gallery-item.tall { grid-row: span 1; }
      .stats-bar { gap: 1rem; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav aria-label="Navigazione principale">
    <a href="https://preview.unstoppabledomains.fun/e7e46f5e-fe3b-4d8e-80c8-172472c097cf/index.html#" class="nav-logo">SINNER<span>MAN</span></a>
    <ul class="nav-links">
      <li><a href="https://preview.unstoppabledomains.fun/e7e46f5e-fe3b-4d8e-80c8-172472c097cf/index.html#chi-sono">Chi sono</a></li>
      <li><a href="https://preview.unstoppabledomains.fun/e7e46f5e-fe3b-4d8e-80c8-172472c097cf/index.html#warzone">Warzone</a></li>
      <li><a href="https://preview.unstoppabledomains.fun/e7e46f5e-fe3b-4d8e-80c8-172472c097cf/index.html#stream">Stream</a></li>
      <li><a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener" class="nav-cta">🟣 Twitch</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero" aria-label="Hero">
    <div class="hero-text">
      <div class="hero-badge">
        <span class="dot"></span>
        Streamer su Twitch
      </div>
      <h1>SINNER<br><span class="red">MAN</span></h1>
      <p class="hero-sub">
        Warzone. Niente regole, niente filtri.<br>
        Gioco quando voglio, come voglio.
      </p>
      <div class="hero-actions">
        <a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener" class="btn-primary">🟣 Seguimi su Twitch</a>
        <a href="https://www.instagram.com/sinnerman_80/" target="_blank" rel="noopener" class="btn-ghost">📸 Instagram</a>
      </div>
    </div>
    <div class="hero-image-wrap">
      <div class="hero-img-frame">
        <img src="./SINNERMAN — Streamer Warzone 2_files/core-turn-6109164bfd848ae41e22099f15dfcf3318ee502041f91682dcb64d1d4b404446-0-7d2b23e90e847d39ed794b8424ceb927012c5d95f0384e0499462c213e7ba504.jpg" alt="Sinnerman — Streamer Warzone">
      </div>
    </div>
  </section>

  <!-- STATS BAR -->
  <div class="stats-bar" aria-label="Statistiche">
    <div class="stat">
      <div class="stat-value">WARZONE</div>
      <div class="stat-label">Main Game</div>
    </div>
    <div class="stat">
      <div class="stat-value">24/7</div>
      <div class="stat-label">Sempre in zona</div>
    </div>
    <div class="stat">
      <div class="stat-value">0</div>
      <div class="stat-label">Filtri</div>
    </div>
    <div class="stat">
      <div class="stat-value">100%</div>
      <div class="stat-label">Adrenalina</div>
    </div>
  </div>

  <!-- CHI SONO -->
  <section id="chi-sono" aria-label="Chi sono">
    <div class="about-img-wrap">
      <div class="about-img-frame">
        <img src="./SINNERMAN — Streamer Warzone 2_files/core-turn-6109164bfd848ae41e22099f15dfcf3318ee502041f91682dcb64d1d4b404446-0-7d2b23e90e847d39ed794b8424ceb927012c5d95f0384e0499462c213e7ba504.jpg" alt="Sinnerman — streamer Warzone">
        <div class="about-img-overlay"></div>
      </div>
    </div>
    <div class="about-text">
      <p class="section-tag">// Chi sono</p>
      <h2 class="section-title">Ribelle.<br>Grintoso.<br>Senza paura.</h2>
      <p>Mi chiamo <strong>Sinnerman</strong> e vivo per il gaming. Non sono il tipo da programmino fisso e orario prestabilito — mi connetto quando l'istinto mi chiama e do il massimo ogni singola sessione.</p>
      <p>Su Twitch trovi <strong>Warzone puro</strong>: strategie aggressive, giocate folli, e zero cagate. Niente filler, niente hype artificiale — solo gameplay autentico e comunità reale.</p>
      <p>Unisciti alla crew. O prenditi una pallottola in fronte.</p>
      <div class="tags">
        <span class="tag">Warzone</span>
        <span class="tag">FPS</span>
        <span class="tag">No Filter</span>
        <span class="tag">Twitch</span>
        <span class="tag">Gaming</span>
        <span class="tag">Ribelle</span>
      </div>
    </div>
  </section>

  <!-- WARZONE -->
  <section id="warzone" aria-label="Warzone">
    <div class="warzone-header">
      <div>
        <p class="section-tag">// Il mio arsenale</p>
        <h2 class="section-title">Warzone.<br>Il mio campo di battaglia.</h2>
      </div>
      <a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener" class="btn-primary">Tutti gli stream →</a>
    </div>
    <div class="cards-grid">
      <div class="card">
        <span class="card-icon">🎯</span>
        <h3>Warzone</h3>
        <p>Il mio gioco principale. Drop aggressivi, loadout curati, mentalità da predatore. Ogni partita è una guerra vera.</p>
      </div>
      <div class="card">
        <span class="card-icon">🔥</span>
        <h3>High Kill Games</h3>
        <p>Non mi accontento di sopravvivere. Vado a caccia, elimino, domino. I numeri parlano.</p>
      </div>
      <div class="card">
        <span class="card-icon">💀</span>
        <h3>No Rules</h3>
        <p>Niente meta forzato, niente campeggio, niente scuse. Gioco aggressivo, sempre.</p>
      </div>
      <div class="card">
        <span class="card-icon">🎙️</span>
        <h3>Crew &amp; Community</h3>
        <p>La community è tutto. Scrivimi, gioca con me, unisciti alla gang. Sinnerman non lavora da solo.</p>
      </div>
    </div>
  </section>

  <!-- STREAM -->
  <section id="stream" aria-label="Stream su Twitch">
    <p class="section-tag">// Live su Twitch</p>
    <h2 class="section-title">Quando l'adrenalina chiama.</h2>
    <p class="stream-desc">
      Non ho orari fissi. Mi connetto quando voglio, e quando sono live, sono al 100%.
      Seguimi su Twitch per non perderti neanche uno stream.
    </p>
    <div class="stream-box">
      <span class="twitch-logo">🟣</span>
      <h3>twitch.tv/sinnerman_80</h3>
      <p>«Mi collego quando l'istinto lo chiede. Nessun copione, nessun orario. Solo gameplay puro.»</p>
      <a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener" class="btn-primary">Apri Twitch</a>
    </div>
  </section>

  <!-- FOLLOW CTA -->
  <section id="follow" aria-label="Seguimi">
    <p class="section-tag">// Entra nella crew</p>
    <h2 class="section-title">Entra a far parte<br>della <span style="color:var(--red)">Bad Company</span></h2>
    <p>Seguimi su Twitch, Instagram e Discord. La guerra non aspetta.</p>
    <div class="follow-buttons">
      <a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener" class="btn-primary">🟣 Twitch</a>
      <a href="https://www.instagram.com/sinnerman_80/" target="_blank" rel="noopener" class="btn-ig">📸 Instagram</a>
      <a href="https://discord.com/channels/@me" target="_blank" rel="noopener" class="btn-discord">💬 Discord</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-logo">SINNER<span>MAN</span></div>
    <p>© 2025 Sinnerman · sinnerman.brave</p>
    <div class="footer-socials">
      <a href="https://www.twitch.tv/sinnerman_80" target="_blank" rel="noopener">Twitch</a>
      <a href="https://www.instagram.com/sinnerman_80/" target="_blank" rel="noopener">Instagram</a>
      <a href="https://discord.com/channels/@me" target="_blank" rel="noopener">Discord</a>
    </div>
  </footer>

<!-- ud-freemium-badge:start -->
<style>.ud-freemium-badge-dismiss{background:none;border:none;cursor:pointer;padding:0;margin-left:8px;display:inline-flex;align-items:center;color:rgba(255,255,255,0.6);transition:color 0.15s}.ud-freemium-badge-dismiss:hover{color:#fff}.ud-freemium-modal-overlay{visibility:hidden;opacity:0;transition:opacity 0.15s}.ud-freemium-modal-overlay.ud-visible{visibility:visible;opacity:1}.ud-freemium-modal{background:rgba(20,20,20,0.85);-webkit-backdrop-filter:blur(20px);backdrop-filter:blur(20px);border:1px solid rgba(255,255,255,0.15);border-radius:16px;box-shadow:0 8px 32px rgba(0,0,0,0.4);color:#fff;padding:28px 24px;max-width:360px;width:calc(100% - 32px);text-align:center}.ud-freemium-modal h3{margin:0 0 8px;font-size:16px;font-weight:600}.ud-freemium-modal p{margin:0 0 20px;font-size:13px;line-height:1.5;color:rgba(255,255,255,0.75)}.ud-freemium-modal-cta{display:inline-block;padding:10px 24px;background:#00C9FF;color:#000;font-size:13px;font-weight:600;border-radius:20px;text-decoration:none;transition:background 0.15s}.ud-freemium-modal-cta:hover{background:#33d4ff}.ud-freemium-modal-close{display:block;margin:12px auto 0;background:none;border:none;color:rgba(255,255,255,0.5);font-size:12px;cursor:pointer;padding:4px}.ud-freemium-modal-close:hover{color:#fff}@media(max-width:480px){.ud-freemium-badge a{padding:4px 8px !important;font-size:11px !important;gap:4px !important}.ud-freemium-badge svg{width:14px !important;height:14px !important}.ud-freemium-badge-dismiss{margin-left:4px}}</style>
<div class="ud-freemium-badge" style="position:fixed !important;bottom:12px !important;right:12px !important;z-index:2147483647 !important;font-family:-apple-system,BlinkMacSystemFont,&#39;Segoe UI&#39;,Roboto,sans-serif;">
  <div style="display:inline-flex;align-items:center;gap:6px;padding:6px 6px 6px 12px;background:rgba(0,0,0,0.45);-webkit-backdrop-filter:blur(12px);backdrop-filter:blur(12px);color:#fff;font-size:12px;font-weight:500;border-radius:20px;box-shadow:0 2px 12px rgba(0,0,0,0.25);border:1px solid rgba(255,255,255,0.15);">
    <a href="https://unstoppabledomains.com/products/ai-credits" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:6px;color:#fff;text-decoration:none;">
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 196 196"><path fill="#00C9FF" d="M187.833 19.1494V81.1034L8.16666 154.322L187.833 19.1494Z"></path><path fill="rgba(255,255,255,0.9)" d="M154.146 16.3333V123.345C154.146 154.45 129.008 179.667 98 179.667C66.9924 179.667 41.8542 154.45 41.8542 123.345V78.2873L75.5417 59.7011V123.345C75.5417 128.573 77.6121 133.587 81.2973 137.284C84.9826 140.981 89.981 143.057 95.1927 143.057C100.405 143.057 105.403 140.981 109.088 137.284C112.773 133.587 114.844 128.573 114.844 123.345V38.0172L154.146 16.3333Z"></path></svg>
      Made with Unstoppable Domains
    </a>
    <button class="ud-freemium-badge-dismiss" onclick="document.getElementById(&#39;ud-freemium-modal&#39;).classList.add(&#39;ud-visible&#39;)" aria-label="About this watermark">
      <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
    </button>
  </div>
</div>
<div id="ud-freemium-modal" class="ud-freemium-modal-overlay" style="position:fixed !important;inset:0 !important;z-index:2147483647 !important;display:flex !important;align-items:center !important;justify-content:center !important;background:rgba(0,0,0,0.5);-webkit-backdrop-filter:blur(4px);backdrop-filter:blur(4px);font-family:-apple-system,BlinkMacSystemFont,&#39;Segoe UI&#39;,Roboto,sans-serif;" onclick="if(event.target===this)this.classList.remove(&#39;ud-visible&#39;)">
  <div class="ud-freemium-modal">
    <h3>Remove this watermark</h3>
    <p>This site was built with Unstoppable Domains AI Site Builder. The site owner can remove this watermark by subscribing to an AI Credits plan.</p>
    <a href="https://unstoppabledomains.com/products/ai-credits" target="_blank" rel="noopener noreferrer" class="ud-freemium-modal-cta">View Plans</a>
    <button class="ud-freemium-modal-close" onclick="this.closest(&#39;.ud-freemium-modal-overlay&#39;).classList.remove(&#39;ud-visible&#39;)">Dismiss</button>
  </div>
</div>
<!-- ud-freemium-badge:end -->


</body></html>
