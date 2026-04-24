<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mathieu PODEVIN - Portfolio Réseaux & Cybersécurité</title>
    <link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

        :root {
            --bg:      #07090d;
            --bg2:     #0c0f15;
            --bg3:     #12151d;
            --bg4:     #181c26;
            --accent:  #00e5ff;
            --accent2: #00ff9d;
            --accent3: #ff4d6d;
            --purple:  #a78bfa;
            --text:    #e2e8f0;
            --muted:   #64748b;
            --border:  rgba(0,229,255,0.12);
            --border2: rgba(0,229,255,0.25);
            --mono:    'Space Mono', monospace;
            --display: 'Syne', sans-serif;
        }

        html { scroll-behavior: smooth; }

        body {
            background: var(--bg);
            color: var(--text);
            font-family: var(--display);
            overflow-x: hidden;
            cursor: none;
        }

        /* ─── CURSOR ─── */
        #cur  { width:10px;height:10px;background:var(--accent);border-radius:50%;position:fixed;pointer-events:none;z-index:9999;transform:translate(-50%,-50%);transition:transform .1s,background .2s;mix-blend-mode:screen; }
        #curR { width:32px;height:32px;border:1px solid var(--accent);border-radius:50%;position:fixed;pointer-events:none;z-index:9998;transform:translate(-50%,-50%);transition:all .12s ease;opacity:.4; }

        /* ─── SCANLINES ─── */
        body::before {
            content:'';position:fixed;inset:0;
            background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(0,0,0,.03) 2px,rgba(0,0,0,.03) 4px);
            pointer-events:none;z-index:9000;
        }

        /* ─── GRID BG ─── */
        .grid-bg {
            position:fixed;inset:0;pointer-events:none;z-index:0;
            background-image:
                linear-gradient(rgba(0,229,255,.025) 1px,transparent 1px),
                linear-gradient(90deg,rgba(0,229,255,.025) 1px,transparent 1px);
            background-size:64px 64px;
            mask-image:radial-gradient(ellipse 70% 70% at 50% 40%,black,transparent);
        }

        /* ─── NAV ─── */
        .navbar {
            position:fixed;top:0;left:0;right:0;z-index:500;
            display:flex;align-items:center;justify-content:space-between;
            padding:1rem 4rem;
            background:rgba(7,9,13,.88);
            backdrop-filter:blur(16px);
            border-bottom:1px solid var(--border);
        }
        .nav-brand {
            font-family:var(--mono);font-size:.85rem;color:var(--accent);
            letter-spacing:.25em;display:flex;align-items:center;gap:.5rem;
        }
        .nav-brand::before { content:'>';color:var(--muted); }
        .nav-menu { display:flex;gap:2.5rem;list-style:none; }
        .nav-link {
            font-family:var(--mono);font-size:.72rem;letter-spacing:.12em;
            text-transform:uppercase;color:var(--muted);text-decoration:none;
            transition:color .2s;position:relative;
        }
        .nav-link::after {
            content:'';position:absolute;bottom:-3px;left:0;width:0;height:1px;
            background:var(--accent);transition:width .3s;
        }
        .nav-link:hover { color:var(--accent); }
        .nav-link:hover::after { width:100%; }
        .hamburger { display:none;flex-direction:column;gap:5px;cursor:pointer; }
        .hamburger span { width:22px;height:2px;background:var(--text);display:block; }

        /* ─── HERO ─── */
        .hero {
            min-height:100vh;display:flex;align-items:center;
            padding:8rem 4rem 4rem;position:relative;overflow:hidden;
        }
        .hero-glow {
            position:absolute;width:700px;height:700px;
            background:radial-gradient(circle,rgba(0,229,255,.05) 0%,transparent 65%);
            top:50%;left:50%;transform:translate(-50%,-50%);
            animation:glow 5s ease-in-out infinite;pointer-events:none;
        }
        @keyframes glow { 0%,100%{opacity:.6;transform:translate(-50%,-50%) scale(1)} 50%{opacity:1;transform:translate(-50%,-50%) scale(1.08)} }

        .hero-layout { display:grid;grid-template-columns:1fr 320px;gap:4rem;align-items:center;position:relative;z-index:1;width:100%;max-width:1200px; }

        .hero-eyebrow {
            font-family:var(--mono);font-size:.72rem;color:var(--accent);
            letter-spacing:.3em;text-transform:uppercase;margin-bottom:1.5rem;
            display:flex;align-items:center;gap:.75rem;
        }
        .hero-eyebrow::before { content:'';display:inline-block;width:28px;height:1px;background:var(--accent); }

        .hero-name {
            font-size:clamp(3rem,6vw,5.5rem);font-weight:800;
            letter-spacing:-.03em;line-height:1;margin-bottom:.5rem;
            color:var(--text);
        }
        .hero-name span { color:var(--accent); }

        .hero-role {
            font-family:var(--mono);font-size:1rem;color:var(--muted);
            margin:1.5rem 0;line-height:1.7;
        }
        .hero-role .hl { color:var(--accent2); }
        .hero-role .hl2 { color:var(--purple); }

        .hero-btns { display:flex;gap:1rem;flex-wrap:wrap;margin-top:2rem; }

        .btn {
            padding:.85rem 2rem;font-family:var(--mono);font-size:.75rem;
            letter-spacing:.12em;text-transform:uppercase;cursor:pointer;
            text-decoration:none;display:inline-block;transition:all .2s;border:none;
            clip-path:polygon(0 0,calc(100% - 10px) 0,100% 10px,100% 100%,10px 100%,0 calc(100% - 10px));
        }
        .btn-primary { background:var(--accent);color:var(--bg);font-weight:700; }
        .btn-primary:hover { background:#33ecff;transform:translateY(-2px); }
        .btn-outline { background:transparent;color:var(--text);border:1px solid rgba(255,255,255,.15); }
        .btn-outline:hover { border-color:var(--accent);color:var(--accent);transform:translateY(-2px); }

        /* Terminal */
        .terminal {
            background:var(--bg2);border:1px solid var(--border);
            border-radius:8px;overflow:hidden;font-family:var(--mono);font-size:.72rem;
        }
        .term-bar {
            background:var(--bg3);padding:.55rem 1rem;
            display:flex;align-items:center;gap:.45rem;
            border-bottom:1px solid var(--border);
        }
        .term-dot { width:9px;height:9px;border-radius:50%; }
        .term-title { font-size:.65rem;color:var(--muted);margin-left:.4rem; }
        .term-body { padding:1rem;line-height:2; }
        .tl { display:flex;gap:.5rem; }
        .tp { color:var(--accent); }
        .tc { color:var(--text); }
        .to { color:var(--muted); }
        .tok { color:var(--accent2); }
        .ti { color:var(--purple); }
        .tw { color:#fbbf24; }
        .tc2 { display:inline-block;width:7px;height:13px;background:var(--accent);animation:blink 1s step-end infinite;vertical-align:middle; }
        @keyframes blink { 0%,100%{opacity:1}50%{opacity:0} }

        .hero-status {
            position:absolute;bottom:2.5rem;right:4rem;
            display:flex;align-items:center;gap:.5rem;
            font-family:var(--mono);font-size:.68rem;color:var(--muted);
        }
        .status-dot { width:7px;height:7px;background:var(--accent2);border-radius:50%;animation:blink 1.5s ease-in-out infinite; }

        .scroll-hint {
            position:absolute;bottom:2.5rem;left:4rem;
            display:flex;align-items:center;gap:.75rem;
            font-family:var(--mono);font-size:.68rem;color:var(--muted);letter-spacing:.15em;
        }
        .scroll-line { width:36px;height:1px;background:var(--muted);overflow:hidden;position:relative; }
        .scroll-line::after {
            content:'';position:absolute;left:-100%;top:0;width:100%;height:100%;
            background:var(--accent);animation:slide 2s ease-in-out infinite;
        }
        @keyframes slide { 0%{left:-100%}100%{left:100%} }

        /* ─── SECTIONS ─── */
        section { padding:6rem 4rem;position:relative;z-index:1; }
        .container { max-width:1200px;margin:0 auto; }
        .section-label { font-family:var(--mono);font-size:.68rem;letter-spacing:.3em;text-transform:uppercase;color:var(--accent);margin-bottom:.6rem; }
        .section-title { font-size:clamp(1.8rem,3.5vw,2.8rem);font-weight:800;letter-spacing:-.03em;margin-bottom:.75rem; }
        .section-line { width:52px;height:2px;background:var(--accent);margin-bottom:3rem;border-radius:0; }
        .section-subtitle { color:var(--muted);font-size:.9rem;margin-bottom:3rem;max-width:600px; }

        /* ─── ABOUT ─── */
        .about { background:var(--bg2);border-top:1px solid var(--border);border-bottom:1px solid var(--border); }
        .about-grid { display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:start; }
        .about-text { color:var(--muted);font-size:.95rem;line-height:1.85; }
        .about-text p+p { margin-top:1.25rem; }
        .about-text strong { color:var(--text); }

        .about-cards { display:grid;grid-template-columns:1fr 1fr;gap:1rem; }
        .about-card {
            background:var(--bg3);border:1px solid var(--border);
            padding:1.25rem;transition:border-color .3s;
            border-left:3px solid var(--accent);border-radius:0;
        }
        .about-card:nth-child(2) { border-left-color:var(--accent2); }
        .about-card:nth-child(3) { border-left-color:var(--purple); }
        .about-card:nth-child(4) { border-left-color:var(--accent3); }
        .about-card:hover { border-color:var(--border2); }
        .about-card-icon { font-size:.9rem;color:var(--accent);margin-bottom:.5rem; }
        .about-card:nth-child(2) .about-card-icon { color:var(--accent2); }
        .about-card:nth-child(3) .about-card-icon { color:var(--purple); }
        .about-card:nth-child(4) .about-card-icon { color:var(--accent3); }
        .about-card h4 { font-size:.75rem;font-family:var(--mono);color:var(--muted);letter-spacing:.1em;text-transform:uppercase;margin-bottom:.3rem; }
        .about-card p { font-size:.88rem;color:var(--text);font-weight:600; }
        .about-card small { font-size:.78rem;color:var(--muted);display:block;margin-top:.2rem; }

        /* ─── EXPERIENCE ─── */
        .timeline { position:relative;padding-left:2rem; }
        .timeline::before { content:'';position:absolute;left:0;top:0;bottom:0;width:1px;background:var(--border2); }
        .timeline-item { position:relative;margin-bottom:2.5rem; }
        .timeline-item::before {
            content:'';position:absolute;left:-2.35rem;top:.4rem;
            width:10px;height:10px;background:var(--accent);border-radius:50%;
            box-shadow:0 0 0 3px rgba(0,229,255,.15);
        }
        .timeline-content { background:var(--bg2);border:1px solid var(--border);padding:1.5rem 1.75rem;transition:border-color .3s; }
        .timeline-content:hover { border-color:var(--border2); }
        .timeline-header { display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:.75rem;flex-wrap:wrap;gap:.5rem; }
        .timeline-title { font-size:1rem;font-weight:700;color:var(--text); }
        .timeline-date { font-family:var(--mono);font-size:.68rem;color:var(--accent);letter-spacing:.1em;padding:.25rem .75rem;background:rgba(0,229,255,.08);border:1px solid rgba(0,229,255,.2); }
        .timeline-org { font-family:var(--mono);font-size:.72rem;color:var(--accent2);letter-spacing:.08em;margin-bottom:.75rem; }
        .timeline-list { list-style:none;display:flex;flex-direction:column;gap:.4rem; }
        .timeline-list li { font-size:.85rem;color:var(--muted);padding-left:1rem;position:relative; }
        .timeline-list li::before { content:'▸';position:absolute;left:0;color:var(--accent);font-size:.7rem; }

        /* ─── SKILLS ─── */
        .skills { background:var(--bg2);border-top:1px solid var(--border);border-bottom:1px solid var(--border); }
        .skills-grid { display:grid;grid-template-columns:repeat(3,1fr);gap:1.25rem; }
        .skill-card {
            background:var(--bg);border:1px solid var(--border);padding:1.5rem;
            transition:all .3s;position:relative;overflow:hidden;
        }
        .skill-card::before {
            content:'';position:absolute;inset:0;
            background:linear-gradient(135deg,rgba(0,229,255,.03) 0%,transparent 100%);
            opacity:0;transition:opacity .3s;
        }
        .skill-card:hover { border-color:rgba(0,229,255,.45);transform:translateY(-3px); }
        .skill-card:hover::before { opacity:1; }
        .skill-card-icon {
            width:36px;height:36px;display:flex;align-items:center;justify-content:center;
            background:rgba(0,229,255,.08);border:1px solid rgba(0,229,255,.15);
            margin-bottom:.9rem;font-size:.9rem;
        }
        .skill-card h3 { font-size:.88rem;font-weight:700;margin-bottom:.4rem;color:var(--text); }
        .skill-card p { font-size:.78rem;color:var(--muted);line-height:1.6;margin-bottom:.75rem; }
        .tags { display:flex;flex-wrap:wrap;gap:.35rem;margin-top:.6rem; }
        .tag {
            font-family:var(--mono);font-size:.62rem;padding:.18rem .55rem;
            background:rgba(0,229,255,.07);border:1px solid rgba(0,229,255,.15);
            color:var(--accent);letter-spacing:.04em;
        }
        .tag.g { background:rgba(0,255,157,.07);border-color:rgba(0,255,157,.15);color:var(--accent2); }
        .tag.r { background:rgba(255,77,109,.07);border-color:rgba(255,77,109,.15);color:var(--accent3); }
        .tag.p { background:rgba(167,139,250,.07);border-color:rgba(167,139,250,.15);color:var(--purple); }
        .tag.y { background:rgba(251,191,36,.07);border-color:rgba(251,191,36,.15);color:#fbbf24; }

        /* ─── PROJECTS ─── */
        .projects-grid { display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:1.25rem; }
        .project-card {
            background:var(--bg2);border:1px solid var(--border);
            overflow:hidden;transition:all .3s;
        }
        .project-card.featured { grid-column:1/-1; }
        .project-card:hover { border-color:var(--border2);transform:translateY(-3px); }
        .project-card::before {
            content:'';display:block;height:2px;
            background:linear-gradient(90deg,var(--accent),transparent);
            opacity:0;transition:opacity .3s;
        }
        .project-card:hover::before { opacity:1; }
        .project-header { display:flex;gap:1rem;align-items:flex-start;padding:1.5rem 1.75rem 0; }
        .project-icon {
            width:38px;height:38px;min-width:38px;display:flex;align-items:center;justify-content:center;
            background:rgba(0,229,255,.08);border:1px solid rgba(0,229,255,.15);
            color:var(--accent);font-size:.85rem;
        }
        .project-num { font-family:var(--mono);font-size:.62rem;color:var(--accent);letter-spacing:.2em;margin-bottom:.4rem; }
        .project-title { font-size:.95rem;font-weight:700;color:var(--text);margin-bottom:.5rem; }
        .project-summary { font-size:.82rem;color:var(--muted);line-height:1.7;padding:0 1.75rem;margin-top:.75rem; }
        .project-tags-row { padding:.75rem 1.75rem 0; }
        .project-actions { padding:1.25rem 1.75rem;display:flex;gap:.75rem;flex-wrap:wrap; }

        .btn-expand {
            background:transparent;border:1px solid var(--border);color:var(--muted);
            font-family:var(--mono);font-size:.68rem;letter-spacing:.1em;text-transform:uppercase;
            padding:.45rem 1rem;cursor:pointer;transition:all .2s;clip-path:none;
        }
        .btn-expand:hover { border-color:var(--accent);color:var(--accent); }
        .btn-expand i { margin-left:.4rem;transition:transform .3s; }
        .btn-expand.open i { transform:rotate(180deg); }

        .project-details {
            display:none;border-top:1px solid var(--border);padding:1.5rem 1.75rem;
        }
        .project-details.open { display:block; }
        .detail-section { margin-bottom:1.25rem; }
        .detail-section:last-child { margin-bottom:0; }
        .detail-section h4 { font-family:var(--mono);font-size:.72rem;color:var(--accent);letter-spacing:.1em;text-transform:uppercase;margin-bottom:.6rem;display:flex;align-items:center;gap:.5rem; }
        .detail-section p,.detail-section li { font-size:.82rem;color:var(--muted);line-height:1.75; }
        .detail-section ul { list-style:none;display:flex;flex-direction:column;gap:.3rem;padding-left:.75rem; }
        .detail-section li::before { content:'▸ ';color:var(--accent);font-size:.7rem; }
        .detail-section code { font-family:var(--mono);font-size:.72rem;background:rgba(0,229,255,.08);padding:.1rem .35rem;color:var(--accent2); }
        .detail-section strong { color:var(--text); }
        .doc-links { list-style:none;padding:0;display:flex;flex-direction:column;gap:.5rem; }
        .doc-links li::before { display:none; }
        .doc-links a { font-family:var(--mono);font-size:.72rem;color:var(--accent2);text-decoration:none;display:flex;align-items:center;gap:.5rem;transition:color .2s; }
        .doc-links a:hover { color:var(--accent); }
        .stage-link { font-family:var(--mono);font-size:.68rem;color:var(--accent2);text-decoration:none;margin-left:.4rem; }
        .schema-image { max-width:100%;border:1px solid var(--border);margin-top:.5rem; }

        /* ─── CERTS ─── */
        .certs-grid { display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:1rem; }
        .cert-card {
            background:var(--bg2);border:1px solid var(--border);
            padding:1.5rem 1rem;text-align:center;transition:all .3s;
        }
        .cert-card:hover { border-color:rgba(0,229,255,.4);transform:translateY(-3px); }
        .cert-icon { font-size:1.6rem;margin-bottom:.75rem;color:var(--accent); }
        .cert-name { font-family:var(--mono);font-size:.78rem;font-weight:700;color:var(--accent2);margin-bottom:.25rem; }
        .cert-org { font-size:.72rem;color:var(--muted);font-family:var(--mono); }

        /* ─── CONTACT ─── */
        .contact-section { background:var(--bg2);border-top:1px solid var(--border); }
        .contact-grid { display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:start; }
        .contact-sub { color:var(--muted);font-size:.9rem;line-height:1.8;margin-bottom:2rem; }
        .contact-links { display:flex;flex-direction:column;gap:.75rem; }
        .contact-link {
            display:flex;align-items:center;gap:.9rem;text-decoration:none;
            color:var(--text);font-family:var(--mono);font-size:.78rem;
            padding:.7rem 1rem;border:1px solid var(--border);background:var(--bg);
            transition:all .2s;
        }
        .contact-link:hover { border-color:var(--border2);color:var(--accent);transform:translateX(4px); }
        .contact-link-icon { color:var(--accent);width:16px;text-align:center; }
        .form-group { margin-bottom:1rem; }
        .form-label { display:block;font-family:var(--mono);font-size:.65rem;color:var(--muted);letter-spacing:.15em;text-transform:uppercase;margin-bottom:.4rem; }
        .form-input,.form-textarea {
            width:100%;background:var(--bg);border:1px solid var(--border);
            color:var(--text);padding:.7rem 1rem;
            font-family:var(--mono);font-size:.78rem;outline:none;
            transition:border-color .2s;border-radius:0;
        }
        .form-input:focus,.form-textarea:focus { border-color:var(--accent); }
        .form-textarea { resize:vertical;min-height:110px; }

        /* ─── FOOTER ─── */
        footer {
            padding:1.75rem 4rem;border-top:1px solid var(--border);
            display:flex;justify-content:space-between;align-items:center;
            position:relative;z-index:1;
        }
        .footer-left { font-family:var(--mono);font-size:.68rem;color:var(--muted); }
        .footer-left span { color:var(--accent); }
        .footer-links { display:flex;gap:1.5rem; }
        .footer-links a { font-family:var(--mono);font-size:.68rem;color:var(--muted);text-decoration:none;transition:color .2s; }
        .footer-links a:hover { color:var(--accent); }

        /* ─── RESPONSIVE ─── */
        @media(max-width:900px){
            .navbar{padding:1rem 1.5rem;}
            .nav-menu{display:none;position:absolute;top:100%;left:0;right:0;background:var(--bg2);border-bottom:1px solid var(--border);flex-direction:column;gap:0;padding:1rem 0;}
            .nav-menu.open{display:flex;}
            .nav-link{padding:.75rem 2rem;display:block;}
            .hamburger{display:flex;}
            .hero{padding:7rem 1.5rem 4rem;}
            .hero-layout{grid-template-columns:1fr;}
            .terminal{display:none;}
            section{padding:4rem 1.5rem;}
            .about-grid,.contact-grid{grid-template-columns:1fr;}
            .skills-grid{grid-template-columns:repeat(2,1fr);}
            .projects-grid{grid-template-columns:1fr;}
            .project-card.featured{grid-column:1;}
            footer{padding:1.5rem;flex-direction:column;gap:1rem;}
        }
        @media(max-width:600px){
            .about-cards,.certs-grid{grid-template-columns:1fr;}
            .skills-grid{grid-template-columns:1fr;}
        }
    </style>
</head>
<body>
<div class="grid-bg"></div>
<div id="cur"></div>
<div id="curR"></div>

<!-- ─── NAV ─── -->
<nav class="navbar">
    <div class="nav-brand">MP_PORTFOLIO</div>
    <ul class="nav-menu" id="navMenu">
        <li><a href="#accueil"     class="nav-link">Accueil</a></li>
        <li><a href="#apropos"     class="nav-link">À propos</a></li>
        <li><a href="#experience"  class="nav-link">Expérience</a></li>
        <li><a href="#competences" class="nav-link">Compétences</a></li>
        <li><a href="#projets"     class="nav-link">Projets</a></li>
        <li><a href="#contact"     class="nav-link">Contact</a></li>
    </ul>
    <div class="hamburger" id="burger">
        <span></span><span></span><span></span>
    </div>
</nav>

<!-- ─── HERO ─── -->
<section id="accueil" class="hero">
    <div class="hero-glow"></div>
    <div class="hero-layout container">
        <div class="hero-left">
            <div class="hero-eyebrow">Disponible pour alternance</div>
            <h1 class="hero-name">
                MATHIEU<br>
                PODEVIN<span style="color:var(--accent)">.</span>
            </h1>
            <p class="hero-role">
                Étudiant <span class="hl">Réseaux &amp; Cybersécurité</span><br>
                <span class="hl2">BTS SIO SISR</span> · Infrastructure · Administration Systèmes
            </p>
            <div class="hero-btns">
                <a href="#projets" class="btn btn-primary">Voir mes projets</a>
                <a href="#contact" class="btn btn-outline">Me contacter</a>
            </div>
        </div>
        <div class="terminal">
            <div class="term-bar">
                <div class="term-dot" style="background:#ff5f57"></div>
                <div class="term-dot" style="background:#febc2e"></div>
                <div class="term-dot" style="background:#28c840"></div>
                <span class="term-title">~/mathieu-podevin</span>
            </div>
            <div class="term-body">
                <div class="tl"><span class="tp">$</span><span class="tc">whoami</span></div>
                <div class="tl"><span class="tok">→ Mathieu PODEVIN</span></div>
                <div class="tl"><span class="to">  BTS SIO SISR</span></div>
                <div class="tl" style="margin-top:.4rem"><span class="tp">$</span><span class="tc">cat stages.txt</span></div>
                <div class="tl"><span class="ti">→ CHU · Base Aérienne</span></div>
                <div class="tl" style="margin-top:.4rem"><span class="tp">$</span><span class="tc">ls certifications/</span></div>
                <div class="tl"><span class="tw">→ CiscoPacketTracer</span></div>
                <div class="tl"><span class="tw">→ Habilitation_élec</span></div>
                <div class="tl" style="margin-top:.4rem">
                    <span class="tp">$</span><span class="tc2"></span>
                </div>
            </div>
        </div>
    </div>
    <div class="hero-status">
        <div class="status-dot"></div>
        Systèmes opérationnels · En recherche d'alternance
    </div>
    <div class="scroll-hint">
        <div class="scroll-line"></div>
        Défiler
    </div>
</section>

<!-- ─── À PROPOS ─── -->
<section id="apropos" class="about">
    <div class="container">
        <div class="section-label">// 01. À propos</div>
        <h2 class="section-title">Qui suis-je ?</h2>
        <div class="section-line"></div>
        <div class="about-grid">
            <div class="about-text">
                <p>Passionné par les <strong>infrastructures réseau</strong> et la <strong>cybersécurité</strong>, je prépare un BTS SIO option SISR avec l'objectif de devenir <strong>Architecte infrastructure</strong> ou <strong>Architecte SSI</strong>.</p>
                <p>Mes stages dans un <strong>environnement hospitalier</strong> et sur une <strong>base aérienne</strong> m'ont confronté à des infrastructures critiques exigeant rigueur, confidentialité et haute disponibilité — des contraintes qui me correspondent parfaitement.</p>

            </div>
            <div class="about-cards">
                <div class="about-card">
                    <div class="about-card-icon"><i class="fas fa-graduation-cap"></i></div>
                    <h4>Formation</h4>
                    <p>BTS SIO SISR</p>
                    <small>2024 – 2026</small>
                </div>
                <div class="about-card">
                    <div class="about-card-icon"><i class="fas fa-bullseye"></i></div>
                    <h4>Objectif</h4>
                    <p>Architecte Infra / SSI</p>
                    <small>Spécialisation cybersécurité</small>
                </div>
                <div class="about-card">
                    <div class="about-card-icon"><i class="fas fa-hospital"></i></div>
                    <h4>Stage 1</h4>
                    <p>CHU · Milieu hospitalier</p>
                    <small>Infrastructure critique</small>
                </div>
                <div class="about-card">
                    <div class="about-card-icon"><i class="fas fa-fighter-jet"></i></div>
                    <h4>Stage 2</h4>
                    <p>Base Aérienne</p>
                    <small>Environnement militaire</small>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- ─── EXPÉRIENCE ─── -->
<section id="experience">
    <div class="container">
        <div class="section-label">// 02. Expérience</div>
        <h2 class="section-title">Stages professionnels</h2>
        <div class="section-line"></div>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-content">
                    <div class="timeline-header">
                        <div>
                            <div class="timeline-title">Stage 1 — CHU de Barbezieux</div>
                            <div class="timeline-org"><i class="fas fa-hospital" style="margin-right:.4rem"></i>Centre Hospitalier · Barbezieux · Infrastructure médicale</div>
                        </div>
                        <div class="timeline-date">À compléter</div>
                    </div>
                    <ul class="timeline-list">
                        <li>Intervention sur infrastructure réseau en environnement critique (haute disponibilité)</li>
                        <li>Gestion et administration de systèmes en milieu médical sécurisé</li>
                        <li>À compléter avec tes missions</li>
                    </ul>
                </div>
            </div>
            <div class="timeline-item">
                <div class="timeline-content">
                    <div class="timeline-header">
                        <div>
                            <div class="timeline-title">Stage 2 — Base Aérienne 709 de Cognac</div>
                            <div class="timeline-org"><i class="fas fa-fighter-jet" style="margin-right:.4rem"></i>Armée de l'Air · Cognac · Environnement militaire sécurisé</div>
                        </div>
                        <div class="timeline-date">À compléter</div>
                    </div>
                    <ul class="timeline-list">
                        <li>Administration systèmes et réseaux en contexte de sécurité renforcée</li>
                        <li>Respect des protocoles de sécurité militaires (confidentialité, traçabilité)</li>
                        <li>À compléter avec tes missions</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- ─── COMPÉTENCES ─── -->
<section id="competences" class="skills">
    <div class="container">
        <div class="section-label">// 03. Compétences</div>
        <h2 class="section-title">Arsenal technique</h2>
        <div class="section-line"></div>
        <div class="skills-grid">
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-server"></i></div>
                <h3>Virtualisation</h3>
                <p>Déploiement et gestion d'environnements virtualisés pour labs et production.</p>
                <div class="tags">
                    <span class="tag">Proxmox</span>
                    <span class="tag">VMware</span>
                    <span class="tag">VirtualBox</span>
                </div>
            </div>
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-shield-alt"></i></div>
                <h3>Pare-feu &amp; Sécurité</h3>
                <p>Configuration de règles de filtrage, NAT et politiques de sécurité réseau.</p>
                <div class="tags">
                    <span class="tag r">pfSense</span>
                    <span class="tag r">iptables</span>
                    <span class="tag r">nftables</span>
                </div>
            </div>
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-network-wired"></i></div>
                <h3>Réseaux</h3>
                <p>Conception et administration d'infrastructures réseau segmentées et sécurisées.</p>
                <div class="tags">
                    <span class="tag">VLAN</span>
                    <span class="tag">DNS</span>
                    <span class="tag">DHCP</span>
                    <span class="tag">IPv4/IPv6</span>
                    <span class="tag">VPN</span>
                </div>
            </div>
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-desktop"></i></div>
                <h3>Systèmes</h3>
                <p>Administration de systèmes d'exploitation serveur et postes clients.</p>
                <div class="tags">
                    <span class="tag g">Linux Debian</span>
                    <span class="tag g">Ubuntu</span>
                    <span class="tag">Windows Server</span>
                </div>
            </div>
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-chart-line"></i></div>
                <h3>Supervision</h3>
                <p>Monitoring temps réel, alerting et tableaux de bord d'infrastructure.</p>
                <div class="tags">
                    <span class="tag p">Zabbix</span>
                    <span class="tag p">Prometheus</span>
                    <span class="tag p">Grafana</span>
                </div>
            </div>
            <div class="skill-card">
                <div class="skill-card-icon"><i class="fas fa-code"></i></div>
                <h3>Scripting &amp; DevOps</h3>
                <p>Automatisation des tâches d'administration et déploiement d'infrastructure.</p>
                <div class="tags">
                    <span class="tag y">Bash</span>
                    <span class="tag y">PowerShell</span>
                    <span class="tag y">Docker</span>
                    <span class="tag y">Terraform</span>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- ─── PROJETS ─── -->
<section id="projets">
    <div class="container">
        <div class="section-label">// 04. Projets</div>
        <h2 class="section-title">Mes réalisations</h2>
        <div class="section-line"></div>
        <p class="section-subtitle">Projets réalisés en formation, en stage et en autodidacte.</p>

        <div class="projects-grid">

            <!-- PROJET 01 - Sécurisation commutateur -->
            <div class="project-card featured">
                <div class="project-header">
                    <div class="project-icon"><i class="fas fa-shield-alt"></i></div>
                    <div>
                        <div class="project-num">// PROJET_01</div>
                        <div class="project-title">Sécurisation d'un commutateur Cisco — Attaques & Contre-mesures</div>
                    </div>
                </div>
                <p class="project-summary">
                    Configuration sécurisée d'un commutateur Cisco (VLANs, SSH, Port Security) puis simulation d'attaques réseau réelles (MAC Flooding, DHCP Starvation, usurpation DHCP) avec mise en place des contre-mesures adaptées. Réalisé sous Packet Tracer et sur infrastructure physique en labo.
                </p>
                <div class="project-tags-row">
                    <div class="tags">
                        <span class="tag">Cisco</span>
                        <span class="tag">VLAN</span>
                        <span class="tag r">MAC Flooding</span>
                        <span class="tag r">DHCP Starvation</span>
                        <span class="tag">Port Security</span>
                        <span class="tag g">SSH</span>
                        <span class="tag p">DHCP Snooping</span>
                        <span class="tag">Packet Tracer</span>
                        <span class="tag y">Kali Linux</span>
                    </div>
                </div>
                <div class="project-actions">
                    <button class="btn-expand" onclick="toggleDetail(this)">Voir les détails <i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="project-details">
                    <div class="detail-section">
                        <h4><i class="fas fa-bullseye"></i> Objectif</h4>
                        <p>Appliquer les préconisations de sécurité de l'ANSSI sur un commutateur Cisco, puis simuler des attaques réseau réelles afin de comprendre les vulnérabilités et mettre en œuvre les contre-mesures appropriées.</p>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-cogs"></i> Partie 1 — Configuration sécurisée (Packet Tracer)</h4>
                        <ul>
                            <li>Configuration initiale du commutateur 2960 : nom d'hôte, mots de passe chiffrés, bannière</li>
                            <li>Création du VLAN 99 <code>AdministrationMATHIEU</code> (192.168.99.0/24) sur les ports Fa0/1 à Fa0/6 — séparation du trafic d'administration</li>
                            <li>Création du VLAN 50 <code>PRODUCTION</code> (192.168.50.0/24) sur les ports Fa0/7 à Fa0/12</li>
                            <li>Vérification de la communication entre les PC du VLAN 50</li>
                            <li>Génération d'une paire de clés RSA 2048 bits pour SSH</li>
                            <li>Configuration des lignes VTY en SSH v2 uniquement avec authentification locale</li>
                            <li>Test de connexion Telnet (refusé) puis SSH (autorisé) depuis le VLAN d'administration</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-bug"></i> Partie 2 — Attaque MAC Flooding</h4>
                        <ul>
                            <li>Vérification du fonctionnement normal : le trafic unicast entre deux VM n'est pas interceptable par une VM tierce grâce à la table CAM du commutateur</li>
                            <li>Lancement de l'attaque avec <code>sudo macof -i [interface]</code> depuis Kali Linux</li>
                            <li>Constat : saturation de la table CAM → le commutateur bascule en mode hub → le trafic devient captu rable par l'attaquant (Wireshark)</li>
                            <li>Contre-mesure : activation du Port Security sur les ports VLAN 50, limite de 10 adresses MAC par port, mode <code>restrict</code> (notification sans désactivation), apprentissage <code>sticky</code> (mémorisation permanente)</li>
                            <li>Vérification : l'attaque est neutralisée, les nouvelles adresses MAC sont ignorées</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-bug"></i> Partie 3 — Attaque DHCP Starvation</h4>
                        <ul>
                            <li>Configuration d'un serveur DHCP sur Debian et d'un client DHCP sur une VM</li>
                            <li>Lancement de l'attaque avec <code>yersinia</code> depuis Kali : épuisement du pool d'adresses IP en quelques secondes</li>
                            <li>Constat : le client légitime ne peut plus obtenir d'adresse IP</li>
                            <li>Contre-mesure : limitation à 3 requêtes DHCP par seconde sur les ports du VLAN 50 via DHCP Snooping</li>
                            <li>Vérification : l'attaque est fortement ralentie et inefficace</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-bug"></i> Partie 4 — Usurpation de serveur DHCP</h4>
                        <ul>
                            <li>Déploiement d'un serveur DHCP pirate couplé à une attaque DoS sur le DHCP légitime</li>
                            <li>Le serveur DHCP attaquant prend la main et distribue de fausses configurations réseau</li>
                            <li>Contre-mesure : configuration des ports de confiance (<em>trusted ports</em>) via DHCP Snooping — seul le port connecté au serveur DHCP officiel est déclaré trusted</li>
                            <li>Vérification : les réponses DHCP provenant de ports non-trusted sont bloquées</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-tools"></i> Technologies utilisées</h4>
                        <ul>
                            <li>Cisco Packet Tracer (simulation) + commutateur physique (labo)</li>
                            <li>Cisco IOS CLI (configuration commutateur)</li>
                            <li>Kali Linux — <code>macof</code>, <code>yersinia</code>, Wireshark</li>
                            <li>Debian 13 (serveur DHCP)</li>
                            <li>Fonctionnalités : Port Security, DHCP Snooping, SSH v2, VLANs 802.1Q</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-check-circle"></i> Résultats</h4>
                        <p>Infrastructure sécurisée opérationnelle : VLAN d'administration isolé, accès SSH v2 uniquement, Port Security actif sur VLAN 50, DHCP Snooping configuré avec trusted ports. Les trois attaques simulées (MAC Flooding, DHCP Starvation, usurpation DHCP) ont été reproduites avec succès puis neutralisées par les contre-mesures adaptées, avec documentation complète des captures Wireshark.</p>
                    </div>
                </div>
            </div>

            <!-- PROJET 02 - Supervision Zabbix -->
            <div class="project-card">
                <div class="project-header">
                    <div class="project-icon"><i class="fas fa-chart-line"></i></div>
                    <div>
                        <div class="project-num">// PROJET_02</div>
                        <div class="project-title">Supervision d'infrastructure avec Zabbix — Windows Server, pfSense & Clients</div>
                    </div>
                </div>
                <p class="project-summary">Déploiement de Zabbix sur Debian pour superviser en temps réel un Windows Server 2022 (DHCP, DNS, AD), un routeur pfSense et des postes clients. Mise en place de seuils d'alerte, tableaux de bord et notifications automatiques par e-mail.</p>
                <div class="project-tags-row">
                    <div class="tags">
                        <span class="tag p">Zabbix</span>
                        <span class="tag">Debian</span>
                        <span class="tag">Windows Server 2022</span>
                        <span class="tag">pfSense</span>
                        <span class="tag g">SNMP</span>
                        <span class="tag g">Active Directory</span>
                        <span class="tag p">Grafana-style Dashboard</span>
                        <span class="tag y">Alerting</span>
                    </div>
                </div>
                <div class="project-actions">
                    <button class="btn-expand" onclick="toggleDetail(this)">Voir les détails <i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="project-details">
                    <div class="detail-section">
                        <h4><i class="fas fa-bullseye"></i> Objectif</h4>
                        <p>Mettre en place une supervision centralisée du système d'information du centre de formation CFC via Zabbix, afin de monitorer en temps réel les ressources système, les services critiques et la disponibilité réseau, avec alerting automatique en cas d'incident.</p>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-server"></i> Infrastructure supervisée</h4>
                        <ul>
                            <li><strong>Serveur Windows 2022</strong> : disponibilité réseau (alerte critique si indisponible), CPU/RAM (warning 80%, critique 90%), partitions disque (warning 70%, critique 85%), statut DHCP et nombre d'adresses restantes (warning 5, critique 2), statut DNS, temps de réponse (warning 500ms, critique 1000ms)</li>
                            <li><strong>Routeur pfSense</strong> : état actif, taux CPU/RAM, bande passante en temps réel sur toutes les interfaces réseau</li>
                            <li><strong>Postes clients</strong> : disponibilité (ping), espace disque (warning 70%, critique 85%)</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-cogs"></i> Mise en œuvre</h4>
                        <ul>
                            <li>Installation de Zabbix Server sur VM Debian non graphique avec base de données et interface web</li>
                            <li>Déploiement des agents Zabbix sur Windows Server 2022 et postes clients</li>
                            <li>Configuration SNMP sur pfSense pour la remontée des métriques réseau</li>
                            <li>Création des items, triggers et actions pour chaque seuil d'alerte défini</li>
                            <li>Paramétrage de l'envoi d'alertes automatiques par e-mail</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-tachometer-alt"></i> Tableaux de bord & visualisation</h4>
                        <ul>
                            <li>Tableau de bord Zabbix synthétique avec widgets de statut, graphiques CPU/RAM/Disque en temps réel</li>
                            <li>Graphiques de bande passante par interface pfSense</li>
                            <li>Vue d'ensemble des déclencheurs actifs et historique des incidents</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-flask"></i> Tests & validation</h4>
                        <ul>
                            <li>Simulation d'arrêt du service DHCP → alerte critique déclenchée et e-mail reçu</li>
                            <li>Surcharge CPU artificielle → passage warning puis critique détecté</li>
                            <li>Coupure réseau simulée → indisponibilité remontée immédiatement dans Zabbix</li>
                            <li>Épuisement du pool DHCP → alertes sur le nombre d'adresses restantes validées</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-tools"></i> Technologies utilisées</h4>
                        <ul>
                            <li>Zabbix Server (Debian 13, interface web + base de données)</li>
                            <li>Zabbix Agent (Windows Server 2022 & postes clients)</li>
                            <li>SNMP (supervision pfSense)</li>
                            <li>Windows Server 2022 (DHCP, DNS, Active Directory)</li>
                            <li>pfSense (routeur pare-feu)</li>
                            <li>SMTP (alerting e-mail automatique)</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-check-circle"></i> Résultats</h4>
                        <p>Infrastructure de supervision opérationnelle couvrant l'ensemble du SI du CFC. Collecte de métriques en temps réel sur 3 types d'équipements, triggers configurés sur seuils critiques avec 2 niveaux de sévérité, alerting e-mail fonctionnel et testé. Toutes les pannes simulées ont été détectées et les alertes générées dans les délais attendus.</p>
                    </div>
                </div>
            </div>

            <!-- PROJET 03 - Windows Server 2022 / AD -->
            <div class="project-card">
                <div class="project-header">
                    <div class="project-icon"><i class="fas fa-users-cog"></i></div>
                    <div>
                        <div class="project-num">// PROJET_03</div>
                        <div class="project-title">Infrastructure Active Directory — Windows Server 2022, GPO, RADIUS & Logs</div>
                    </div>
                </div>
                <p class="project-summary">Déploiement complet d'une infrastructure Windows Server 2022 pour un centre de formation : Active Directory, DHCP, DNS, GPO, partages réseau avec quotas, accès Wi-Fi via portail captif RADIUS, et collecte des logs de connexion internet.</p>
                <div class="project-tags-row">
                    <div class="tags">
                        <span class="tag">Windows Server 2022</span>
                        <span class="tag g">Active Directory</span>
                        <span class="tag">GPO</span>
                        <span class="tag">pfSense</span>
                        <span class="tag p">RADIUS</span>
                        <span class="tag">DHCP / DNS</span>
                        <span class="tag r">Wi-Fi captif</span>
                        <span class="tag y">Debian</span>
                    </div>
                </div>
                <div class="project-actions">
                    <button class="btn-expand" onclick="toggleDetail(this)">Voir les détails <i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="project-details">
                    <div class="detail-section">
                        <h4><i class="fas fa-bullseye"></i> Objectif</h4>
                        <p>Mettre en place l'infrastructure complète d'un centre de formation fictif « CFC » accueillant 210 élèves, 50 stagiaires et une trentaine de permanents : gestion centralisée des utilisateurs, des droits d'accès, des ressources partagées, de la sécurité Wi-Fi et de la traçabilité des connexions internet.</p>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-sitemap"></i> Active Directory & Partages</h4>
                        <ul>
                            <li>Déploiement Windows Server 2022 : contrôleur de domaine <code>cfc.educ</code>, rôles DHCP et DNS</li>
                            <li>Création des UO hiérarchiques : élèves (3 promotions), stagiaires, formateurs, direction, administration, informatique, intervenants</li>
                            <li>Structure de partages sur disque dédié : répertoires personnels élèves, espaces communs par promotion, espace formateurs, dossier administratif</li>
                            <li>Droits d'accès granulaires par groupe : lecture seule, lecture/écriture, contrôle total selon profil</li>
                            <li>Redirection du dossier <em>Documents</em> des formateurs permanents vers le serveur</li>
                            <li>Mapping automatique des lecteurs réseau selon le profil utilisateur</li>
                            <li>Quotas 100 Mio et filtrage fichiers audio/vidéo sur les dossiers personnels élèves (FSRM)</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-shield-alt"></i> GPO déployées</h4>
                        <ul>
                            <li>Fond d'écran commun pour tous les élèves, personnalisé pour les 3ème année</li>
                            <li>Droits administrateur local réservés aux membres du service informatique uniquement</li>
                            <li>Installation automatique de 7zip (<code>.msi</code>) sur tous les postes élèves via GPO</li>
                            <li>Installation de VLC (<code>.exe</code>) via script GPO sur tous les postes</li>
                            <li>Restriction du panneau de configuration et personnalisation du menu Démarrer pour stagiaires et intervenants</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-network-wired"></i> Infrastructure réseau & pfSense</h4>
                        <ul>
                            <li>Intégration d'un routeur pfSense comme passerelle WAN pour le serveur et les postes clients</li>
                            <li>Jonction d'un poste Debian au domaine Active Directory (authentification via Kerberos + SSSD)</li>
                            <li>Sauvegarde automatisée du serveur sur disque SATA dédié avec test de restauration granulaire</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-wifi"></i> Accès Wi-Fi & RADIUS</h4>
                        <ul>
                            <li>Configuration d'une borne Wi-Fi avec portail captif pfSense</li>
                            <li>Authentification des utilisateurs du domaine via serveur RADIUS couplé à l'Active Directory</li>
                            <li>Accès invités via vouchers à durée limitée, restreints à internet uniquement</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-scroll"></i> Collecte des logs internet</h4>
                        <ul>
                            <li>Mise en place d'un outil de journalisation des connexions internet : URL visitée, adresse IP, heure de connexion/déconnexion</li>
                            <li>Enregistrement de l'association IP ↔ identifiant utilisateur avec horodatage</li>
                            <li>Outil de rapprochement des deux fichiers de logs : traçabilité complète par utilisateur</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-tools"></i> Technologies utilisées</h4>
                        <ul>
                            <li>Windows Server 2022 (AD DS, DHCP, DNS, FSRM)</li>
                            <li>Windows 10/11 (postes clients, jonction domaine)</li>
                            <li>pfSense (routeur pare-feu, portail captif, RADIUS)</li>
                            <li>Debian (poste client Linux, authentification AD)</li>
                            <li>GPO, PowerShell (déploiement logiciels, scripts)</li>
                            <li>Windows Server Backup (sauvegarde automatisée)</li>
                        </ul>
                    </div>

                    <div class="detail-section">
                        <h4><i class="fas fa-check-circle"></i> Résultats</h4>
                        <p>Infrastructure complète opérationnelle : domaine <code>cfc.educ</code> configuré, 6 profils utilisateurs testés avec droits validés, 5 GPO fonctionnelles, partages et quotas actifs. Accès Wi-Fi sécurisé avec authentification AD et vouchers invités. Sauvegarde planifiée avec restauration granulaire testée. Logs de connexion internet collectés et exploitables.</p>
                    </div>
                </div>
            </div>

        </div>
    </div>
</section>

<!-- ─── CERTIFICATIONS ─── -->
<section style="padding-top:0;position:relative;z-index:1;">
    <div class="container">
        <div class="section-label">// 05. Certifications</div>
        <h2 class="section-title">Reconnaissances</h2>
        <div class="section-line"></div>
        <div class="certs-grid">
            <div class="cert-card">
                <div class="cert-icon"><i class="fas fa-network-wired"></i></div>
                <div class="cert-name">Cisco Packet Tracer</div>
                <div class="cert-org">Cisco Networking Academy</div>
            </div>
            <div class="cert-card">
                <div class="cert-icon"><i class="fas fa-bolt"></i></div>
                <div class="cert-name">Habilitation Électrique</div>
                <div class="cert-org">Certification professionnelle</div>
            </div>
            <div class="cert-card">
                <div class="cert-icon"><i class="fas fa-graduation-cap"></i></div>
                <div class="cert-name">Bac Pro SN</div>
                <div class="cert-org">Systèmes Numériques</div>
            </div>
            <div class="cert-card">
                <div class="cert-icon"><i class="fas fa-laptop-code"></i></div>
                <div class="cert-name">Certification PIX</div>
                <div class="cert-org">Compétences numériques</div>
            </div>
        </div>
    </div>
</section>

<!-- ─── CONTACT ─── -->
<section id="contact" class="contact-section">
    <div class="container">
        <div class="section-label">// 06. Contact</div>
        <h2 class="section-title">Travaillons ensemble</h2>
        <div class="section-line"></div>
        <div class="contact-grid">
            <div>
                <p class="contact-sub">
                    À la recherche d'une alternance en administration systèmes et réseaux pour préparer un Bachelor en infrastructure. Disponible pour toute opportunité ou échange.
                </p>
                <div class="contact-links">
                    <a href="mailto:mat41.podevin@gmail.com" class="contact-link">
                        <span class="contact-link-icon"><i class="fas fa-envelope"></i></span>
                        <span>mat41.podevin@gmail.com</span>
                    </a>
                    <a href="#" class="contact-link">
                        <span class="contact-link-icon"><i class="fas fa-map-marker-alt"></i></span>
                        <span>France · Remote OK · Alternance</span>
                    </a>
                </div>
            </div>
            <div>
                <div class="form-group">
                    <label class="form-label">Nom</label>
                    <input type="text" class="form-input" placeholder="Jean Dupont">
                </div>
                <div class="form-group">
                    <label class="form-label">Email</label>
                    <input type="email" class="form-input" placeholder="jean@entreprise.fr">
                </div>
                <div class="form-group">
                    <label class="form-label">Message</label>
                    <textarea class="form-textarea" placeholder="Décrivez votre besoin ou opportunité..."></textarea>
                </div>
                <button class="btn btn-primary" style="width:100%;text-align:center;">Envoyer</button>
            </div>
        </div>
    </div>
</section>

<!-- ─── FOOTER ─── -->
<footer>
    <div class="footer-left">© 2025 <span>Mathieu PODEVIN</span> · Tous droits réservés</div>
    <div class="footer-links">
        <a href="#">CV PDF</a>
    </div>
</footer>

<script>
const cur = document.getElementById('cur');
const curR = document.getElementById('curR');
let mx=0,my=0,rx=0,ry=0;

document.addEventListener('mousemove',e=>{
    mx=e.clientX;my=e.clientY;
    cur.style.left=mx+'px';cur.style.top=my+'px';
});
(function loop(){
    rx+=(mx-rx)*.12;ry+=(my-ry)*.12;
    curR.style.left=rx+'px';curR.style.top=ry+'px';
    requestAnimationFrame(loop);
})();

document.querySelectorAll('a,button,.skill-card,.project-card,.cert-card').forEach(el=>{
    el.addEventListener('mouseenter',()=>{cur.style.transform='translate(-50%,-50%) scale(2)';curR.style.opacity='.8';curR.style.transform='translate(-50%,-50%) scale(1.4)';});
    el.addEventListener('mouseleave',()=>{cur.style.transform='translate(-50%,-50%) scale(1)';curR.style.opacity='.4';curR.style.transform='translate(-50%,-50%) scale(1)';});
});

document.getElementById('burger').addEventListener('click',()=>{
    document.getElementById('navMenu').classList.toggle('open');
});

function toggleDetail(btn){
    const card = btn.closest('.project-card');
    const detail = card.querySelector('.project-details');
    detail.classList.toggle('open');
    btn.classList.toggle('open');
    btn.innerHTML = detail.classList.contains('open')
        ? 'Réduire <i class="fas fa-chevron-down"></i>'
        : 'Voir les détails <i class="fas fa-chevron-down"></i>';
}
</script>
</body>
</html>
