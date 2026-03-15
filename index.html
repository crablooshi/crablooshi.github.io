<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CRABLOOSHI</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Bebas+Neue&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #080810;
      --surface: #0e0e1a;
      --border: #1e1e36;
      --accent1: #b06cff;
      --accent2: #00e5ff;
      --accent3: #ff4fd8;
      --text: #e8e8f0;
      --muted: #6868a0;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body { background: var(--bg); color: var(--text); font-family: 'DM Sans', sans-serif; overflow-x: hidden; cursor: none; }

    #cursor { position: fixed; width: 12px; height: 12px; background: var(--accent2); border-radius: 50%; pointer-events: none; z-index: 9999; transform: translate(-50%,-50%); mix-blend-mode: screen; }
    #cursor-ring { position: fixed; width: 36px; height: 36px; border: 1.5px solid var(--accent1); border-radius: 50%; pointer-events: none; z-index: 9998; transform: translate(-50%,-50%); transition: width .2s, height .2s, border-color .2s; }

    body::before { content:''; position:fixed; inset:0; background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='1'/%3E%3C/svg%3E"); opacity:.035; pointer-events:none; z-index:1000; }

    nav { position:fixed; top:0; left:0; right:0; z-index:500; display:flex; align-items:center; justify-content:space-between; padding:1.2rem 3rem; background:linear-gradient(to bottom,rgba(8,8,16,.95),transparent); backdrop-filter:blur(4px); }
    .nav-logo { font-family:'Bebas Neue',sans-serif; font-size:1.6rem; letter-spacing:.12em; background:linear-gradient(135deg,var(--accent1),var(--accent2)); -webkit-background-clip:text; -webkit-text-fill-color:transparent; text-decoration:none; }
    .nav-links { display:flex; gap:2.2rem; list-style:none; }
    .nav-links a { font-family:'Space Mono',monospace; font-size:.75rem; letter-spacing:.15em; text-transform:uppercase; color:var(--muted); text-decoration:none; transition:color .2s; position:relative; }
    .nav-links a::after { content:''; position:absolute; bottom:-4px; left:0; right:0; height:1px; background:var(--accent2); transform:scaleX(0); transition:transform .2s; }
    .nav-links a:hover { color:var(--accent2); }
    .nav-links a:hover::after { transform:scaleX(1); }

    #hero { min-height:100vh; display:flex; flex-direction:column; justify-content:center; padding:0 3rem; position:relative; overflow:hidden; }
    .hero-grid { position:absolute; inset:0; background-image:linear-gradient(rgba(176,108,255,.07) 1px,transparent 1px),linear-gradient(90deg,rgba(176,108,255,.07) 1px,transparent 1px); background-size:60px 60px; animation:gridPulse 8s ease-in-out infinite; }
    @keyframes gridPulse { 0%,100%{opacity:.6}50%{opacity:1} }
    .hero-glow { position:absolute; width:700px; height:700px; border-radius:50%; background:radial-gradient(circle,rgba(176,108,255,.18) 0%,transparent 70%); top:-200px; right:-200px; animation:float 10s ease-in-out infinite; }
    .hero-glow2 { position:absolute; width:400px; height:400px; border-radius:50%; background:radial-gradient(circle,rgba(0,229,255,.12) 0%,transparent 70%); bottom:0; left:10%; animation:float 14s ease-in-out infinite reverse; }
    @keyframes float { 0%,100%{transform:translateY(0)}50%{transform:translateY(-40px)} }
    .hero-content { position:relative; z-index:2; max-width:900px; }
    .hero-eyebrow { font-family:'Space Mono',monospace; font-size:.75rem; letter-spacing:.3em; text-transform:uppercase; color:var(--accent2); margin-bottom:1.2rem; opacity:0; animation:fadeUp .8s .2s forwards; }
    .hero-name { font-family:'Bebas Neue',sans-serif; font-size:clamp(5rem,14vw,12rem); line-height:.9; letter-spacing:.04em; background:linear-gradient(135deg,#fff 30%,var(--accent1) 70%,var(--accent2) 100%); -webkit-background-clip:text; -webkit-text-fill-color:transparent; opacity:0; animation:fadeUp .8s .4s forwards; }
    .hero-sub { margin-top:1.8rem; font-size:1.1rem; font-weight:300; color:var(--muted); max-width:520px; line-height:1.7; opacity:0; animation:fadeUp .8s .6s forwards; }
    .hero-sub strong { color:var(--text); font-weight:500; }
    .hero-tags { display:flex; gap:.8rem; flex-wrap:wrap; margin-top:2.2rem; opacity:0; animation:fadeUp .8s .8s forwards; }
    .tag { font-family:'Space Mono',monospace; font-size:.72rem; letter-spacing:.1em; padding:.35rem .9rem; border-radius:2px; border:1px solid; }
    .tag-purple { border-color:var(--accent1); color:var(--accent1); }
    .tag-cyan   { border-color:var(--accent2); color:var(--accent2); }
    .tag-pink   { border-color:var(--accent3); color:var(--accent3); }
    .scroll-hint { position:absolute; bottom:2.5rem; left:3rem; font-family:'Space Mono',monospace; font-size:.68rem; letter-spacing:.2em; color:var(--muted); text-transform:uppercase; display:flex; align-items:center; gap:1rem; opacity:0; animation:fadeUp .8s 1.2s forwards; }
    .scroll-line { display:block; width:40px; height:1px; background:linear-gradient(90deg,var(--accent1),transparent); animation:expand 2s ease-in-out infinite; }
    @keyframes expand { 0%,100%{width:40px}50%{width:70px} }
    @keyframes fadeUp { from{opacity:0;transform:translateY(24px)} to{opacity:1;transform:translateY(0)} }

    section { padding:7rem 3rem; position:relative; }
    .section-label { font-family:'Space Mono',monospace; font-size:.7rem; letter-spacing:.3em; text-transform:uppercase; color:var(--accent2); margin-bottom:1rem; }
    .section-title { font-family:'Bebas Neue',sans-serif; font-size:clamp(2.8rem,6vw,5rem); letter-spacing:.06em; line-height:1; margin-bottom:3rem; }

    #about { background:var(--surface); }
    .about-grid { display:grid; grid-template-columns:1fr 1fr; gap:5rem; align-items:start; }
    .about-body { font-size:1.05rem; line-height:1.9; color:var(--muted); }
    .about-body p+p { margin-top:1.2rem; }
    .about-body strong { color:var(--text); font-weight:500; }
    .stat-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; }
    .stat-card { background:var(--bg); border:1px solid var(--border); padding:1.6rem; position:relative; overflow:hidden; transition:border-color .3s,transform .3s; }
    .stat-card::before { content:''; position:absolute; top:0; left:0; right:0; height:2px; background:linear-gradient(90deg,var(--accent1),var(--accent2)); transform:scaleX(0); transition:transform .3s; }
    .stat-card:hover { border-color:var(--accent1); transform:translateY(-4px); }
    .stat-card:hover::before { transform:scaleX(1); }
    .stat-number { font-family:'Bebas Neue',sans-serif; font-size:3.5rem; background:linear-gradient(135deg,var(--accent1),var(--accent2)); -webkit-background-clip:text; -webkit-text-fill-color:transparent; line-height:1; }
    .stat-label { font-family:'Space Mono',monospace; font-size:.7rem; letter-spacing:.15em; text-transform:uppercase; color:var(--muted); margin-top:.4rem; }

    .skills-list { display:flex; flex-direction:column; gap:1.4rem; max-width:700px; }
    .skill-header { display:flex; justify-content:space-between; font-family:'Space Mono',monospace; font-size:.78rem; letter-spacing:.1em; color:var(--text); margin-bottom:.5rem; }
    .skill-pct { color:var(--accent2); }
    .skill-bar-track { height:3px; background:var(--border); border-radius:2px; overflow:hidden; }
    .skill-bar-fill { height:100%; background:linear-gradient(90deg,var(--accent1),var(--accent2)); border-radius:2px; transform:scaleX(0); transform-origin:left; transition:transform 1.2s cubic-bezier(.16,1,.3,1); }
    .project-cards { display:grid; grid-template-columns:repeat(auto-fill,minmax(280px,1fr)); gap:1.5rem; margin-top:4rem; }
    .project-card { background:var(--surface); border:1px solid var(--border); padding:2rem; position:relative; overflow:hidden; transition:border-color .3s,transform .3s; }
    .project-card::after { content:''; position:absolute; inset:0; background:linear-gradient(135deg,rgba(176,108,255,.05),rgba(0,229,255,.05)); opacity:0; transition:opacity .3s; }
    .project-card:hover { border-color:var(--accent2); transform:translateY(-6px); }
    .project-card:hover::after { opacity:1; }
    .project-icon { font-size:2rem; margin-bottom:1rem; display:block; }
    .project-name { font-family:'Bebas Neue',sans-serif; font-size:1.5rem; letter-spacing:.08em; color:var(--text); margin-bottom:.5rem; }
    .project-desc { font-size:.9rem; line-height:1.6; color:var(--muted); }
    .project-chips { display:flex; flex-wrap:wrap; gap:.5rem; margin-top:1.2rem; }
    .chip { font-family:'Space Mono',monospace; font-size:.65rem; padding:.2rem .6rem; background:rgba(176,108,255,.1); border:1px solid rgba(176,108,255,.25); color:var(--accent1); border-radius:2px; }

    /* ── Music ── */
    #music { background:var(--surface); }
    .music-layout { display:grid; grid-template-columns:1fr 1fr; gap:3rem; align-items:start; }
    .spotify-stack { display:flex; flex-direction:column; gap:.6rem; }
    .stack-label { font-family:'Space Mono',monospace; font-size:.68rem; letter-spacing:.2em; text-transform:uppercase; color:var(--muted); margin-bottom:.25rem; }

    /* Track card */
    .track-card { display:flex; align-items:center; gap:1rem; padding:.75rem 1rem; border:1px solid var(--border); background:var(--bg); text-decoration:none; transition:border-color .25s, background .25s, transform .25s; }
    .track-card:hover { border-color:var(--accent1); background:rgba(176,108,255,.06); transform:translateX(4px); }
    .track-art { width:48px; height:48px; flex-shrink:0; border-radius:2px; object-fit:cover; }
    .track-meta { flex:1; min-width:0; }
    .track-name { font-size:.92rem; font-weight:500; color:var(--text); white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
    .track-sub { font-family:'Space Mono',monospace; font-size:.62rem; letter-spacing:.08em; color:var(--muted); margin-top:.2rem; }
    .track-arrow { font-size:.9rem; color:var(--accent1); flex-shrink:0; }

    /* Album card */
    .album-card { display:flex; align-items:center; gap:1.2rem; padding:1rem 1.2rem; border:1px solid var(--border); background:var(--bg); text-decoration:none; transition:border-color .25s, background .25s, transform .25s; }
    .album-card:hover { border-color:var(--accent2); background:rgba(0,229,255,.04); transform:translateX(4px); }
    .album-art { width:72px; height:72px; flex-shrink:0; border-radius:2px; object-fit:cover; }
    .album-meta { flex:1; min-width:0; }
    .album-name { font-family:'Bebas Neue',sans-serif; font-size:1.3rem; letter-spacing:.08em; color:var(--text); }
    .album-sub { font-family:'Space Mono',monospace; font-size:.62rem; letter-spacing:.08em; color:var(--muted); margin-top:.3rem; }
    .album-arrow { font-size:.9rem; color:var(--accent2); flex-shrink:0; }

    /* Artist card */
    .artist-card { display:flex; align-items:center; gap:1.2rem; padding:1.2rem 1.4rem; border:1px solid var(--border); background:var(--bg); text-decoration:none; transition:border-color .25s, background .25s; }
    .artist-card:hover { border-color:var(--accent3); background:rgba(255,79,216,.04); }
    .artist-img { width:72px; height:72px; border-radius:50%; object-fit:cover; flex-shrink:0; border:2px solid var(--border); }
    .artist-meta { flex:1; }
    .artist-name-txt { font-family:'Bebas Neue',sans-serif; font-size:1.6rem; letter-spacing:.1em; color:var(--text); }
    .artist-listeners { font-family:'Space Mono',monospace; font-size:.65rem; letter-spacing:.1em; color:var(--muted); margin-top:.25rem; }
    .artist-arrow { font-size:.9rem; color:var(--accent3); flex-shrink:0; }

    .music-right { position:sticky; top:7rem; display:flex; flex-direction:column; gap:2rem; }
    .artist-label { font-family:'Space Mono',monospace; font-size:.68rem; letter-spacing:.2em; text-transform:uppercase; color:var(--accent2); margin-bottom:.5rem; }
    .tools-box { background:var(--bg); border:1px solid var(--border); padding:1.5rem 1.8rem; }
    .tools-box-label { font-family:'Space Mono',monospace; font-size:.68rem; letter-spacing:.2em; text-transform:uppercase; color:var(--accent2); margin-bottom:1rem; }
    .tools-row { display:flex; gap:.7rem; flex-wrap:wrap; }

    /* ── Contact ── */
    #contact { text-align:center; padding:8rem 3rem; position:relative; overflow:hidden; }
    .contact-glow { position:absolute; top:50%; left:50%; transform:translate(-50%,-50%); width:600px; height:600px; border-radius:50%; background:radial-gradient(circle,rgba(176,108,255,.1) 0%,transparent 70%); pointer-events:none; }
    .contact-title { font-family:'Bebas Neue',sans-serif; font-size:clamp(3rem,8vw,7rem); letter-spacing:.06em; line-height:1; background:linear-gradient(135deg,#fff,var(--accent1),var(--accent3)); -webkit-background-clip:text; -webkit-text-fill-color:transparent; margin-bottom:1.5rem; position:relative; }
    .contact-sub { font-size:1rem; color:var(--muted); max-width:420px; margin:0 auto 3rem; line-height:1.7; position:relative; }
    .socials { display:flex; justify-content:center; gap:1rem; flex-wrap:wrap; position:relative; }
    .social-btn { font-family:'Space Mono',monospace; font-size:.78rem; letter-spacing:.1em; text-transform:uppercase; padding:.85rem 2rem; border:1px solid var(--border); background:transparent; color:var(--text); cursor:pointer; text-decoration:none; transition:background .2s,border-color .2s,color .2s,transform .2s; display:inline-flex; align-items:center; gap:.6rem; }
    .social-btn:hover { background:rgba(176,108,255,.1); border-color:var(--accent1); color:var(--accent1); transform:translateY(-3px); }

    footer { background:var(--surface); border-top:1px solid var(--border); padding:2rem 3rem; display:flex; align-items:center; justify-content:space-between; }
    .footer-logo { font-family:'Bebas Neue',sans-serif; font-size:1.2rem; letter-spacing:.15em; background:linear-gradient(135deg,var(--accent1),var(--accent2)); -webkit-background-clip:text; -webkit-text-fill-color:transparent; }
    .footer-copy { font-family:'Space Mono',monospace; font-size:.65rem; letter-spacing:.1em; color:var(--muted); }

    .reveal { opacity:0; transform:translateY(32px); transition:opacity .8s,transform .8s; }
    .reveal.visible { opacity:1; transform:translateY(0); }

    @media(max-width:768px){
      nav{padding:1rem 1.5rem;} .nav-links{display:none;}
      section{padding:5rem 1.5rem;} #hero{padding:0 1.5rem;}
      .about-grid,.music-layout{grid-template-columns:1fr;gap:2.5rem;}
      .scroll-hint{left:1.5rem;} .music-right{position:static;}
      footer{flex-direction:column;gap:1rem;text-align:center;}
    }
  </style>
</head>
<body>

  <div id="cursor"></div>
  <div id="cursor-ring"></div>

  <nav>
    <a href="#hero" class="nav-logo">CRABLOOSHI</a>
    <ul class="nav-links">
      <li><a href="#about">About</a></li>
      <li><a href="#gamedev">Game Dev</a></li>
      <li><a href="#music">Music</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <div class="hero-grid"></div>
    <div class="hero-glow"></div>
    <div class="hero-glow2"></div>
    <div class="hero-content">
      <p class="hero-eyebrow">// Technical Artist &amp; Music Producer</p>
      <h1 class="hero-name">CRAB&shy;LOOSHI</h1>
      <p class="hero-sub"><strong>7 years</strong> building worlds through shaders, VFX &amp; technical art — and crafting sounds that hit just as hard.</p>
      <div class="hero-tags">
        <span class="tag tag-purple">Technical Art</span>
        <span class="tag tag-cyan">Game Dev</span>
        <span class="tag tag-pink">Music Production</span>
        <span class="tag tag-purple">Shaders</span>
        <span class="tag tag-cyan">VFX</span>
      </div>
    </div>
    <div class="scroll-hint"><span class="scroll-line"></span>Scroll to explore</div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="reveal">
      <p class="section-label">// 01 — About</p>
      <h2 class="section-title">WHO I AM</h2>
    </div>
    <div class="about-grid reveal">
      <div class="about-body">
        <p>I'm <strong>Crablooshi</strong> — a technical artist and game developer with <strong>7 years</strong> of experience living at the intersection of code, art, and craft. My work focuses on bringing visual ideas to life through shaders, VFX pipelines, and procedural systems that make games feel alive.</p>
        <p>When I'm not deep in a render pipeline, I'm producing music — blending texture, space, and rhythm into something that moves people. Both disciplines share the same obsession: making something feel effortless while hiding how hard it was to build.</p>
        <p>I'm driven by craft, detail, and the satisfaction of pushing creative tools to their limits.</p>
      </div>
      <div class="stat-grid">
        <div class="stat-card"><div class="stat-number">7+</div><div class="stat-label">Years in Game Dev</div></div>
        <div class="stat-card"><div class="stat-number">62K</div><div class="stat-label">Monthly Listeners</div></div>
        <div class="stat-card"><div class="stat-number">♫</div><div class="stat-label">Music Producer</div></div>
        <div class="stat-card"><div class="stat-number">1</div><div class="stat-label">Unique Vision</div></div>
      </div>
    </div>
  </section>

  <!-- GAME DEV -->
  <section id="gamedev">
    <div class="reveal">
      <p class="section-label">// 02 — Game Development</p>
      <h2 class="section-title">TECHNICAL ART</h2>
    </div>
    <div class="skills-list reveal" id="skillsContainer">
      <div class="skill-row">
        <div class="skill-header"><span>Shader Development</span><span class="skill-pct">95%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.95"></div></div>
      </div>
      <div class="skill-row">
        <div class="skill-header"><span>VFX &amp; Particle Systems</span><span class="skill-pct">90%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.90"></div></div>
      </div>
      <div class="skill-row">
        <div class="skill-header"><span>Procedural Generation</span><span class="skill-pct">85%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.85"></div></div>
      </div>
      <div class="skill-row">
        <div class="skill-header"><span>Lighting &amp; Post-Processing</span><span class="skill-pct">88%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.88"></div></div>
      </div>
      <div class="skill-row">
        <div class="skill-header"><span>3D Modeling &amp; Texturing</span><span class="skill-pct">80%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.80"></div></div>
      </div>
      <div class="skill-row">
        <div class="skill-header"><span>Pipeline &amp; Tools Dev</span><span class="skill-pct">78%</span></div>
        <div class="skill-bar-track"><div class="skill-bar-fill" style="--w:0.78"></div></div>
      </div>
    </div>
    <div class="project-cards reveal">
      <div class="project-card">
        <span class="project-icon">🌊</span>
        <div class="project-name">FLUID DYNAMICS VFX</div>
        <p class="project-desc">Real-time fluid simulation shader using compute shaders and noise-driven displacement. Built for a AAA-style water system.</p>
        <div class="project-chips"><span class="chip">HLSL</span><span class="chip">Unity URP</span><span class="chip">Compute Shaders</span></div>
      </div>
      <div class="project-card">
        <span class="project-icon">✨</span>
        <div class="project-name">STYLIZED PARTICLE SYSTEMS</div>
        <p class="project-desc">Modular VFX library with 40+ reusable effects. Destruction, magic, weather — all performance-budget-aware and artist-friendly.</p>
        <div class="project-chips"><span class="chip">Niagara</span><span class="chip">UE5</span><span class="chip">HLSL</span></div>
      </div>
      <div class="project-card">
        <span class="project-icon">🔷</span>
        <div class="project-name">PROCEDURAL TERRAIN SYSTEM</div>
        <p class="project-desc">GPU-accelerated procedural world generation with biome blending, erosion simulation, and runtime LOD management.</p>
        <div class="project-chips"><span class="chip">C#</span><span class="chip">Unity</span><span class="chip">Compute</span></div>
      </div>
    </div>
  </section>

  <!-- MUSIC -->
  <section id="music">
    <div class="reveal">
      <p class="section-label">// 03 — Music</p>
      <h2 class="section-title">SOUNDS</h2>
    </div>
    <div class="music-layout reveal">

      <!-- Left: tracks + album -->
      <div class="spotify-stack">
        <p class="stack-label">// Top Tracks</p>

        <a class="track-card" href="https://open.spotify.com/track/6H2BwbFsJKtYb4lWJTNKFH" target="_blank" rel="noopener">
          <img class="track-art" src="https://i.scdn.co/image/ab67616d00004851945427c5110f728e262dd0a0" alt="TITLE WAVE" />
          <div class="track-meta">
            <div class="track-name">TITLE WAVE</div>
            <div class="track-sub">Crablooshi · 1,719,973 plays</div>
          </div>
          <span class="track-arrow">↗</span>
        </a>

        <a class="track-card" href="https://open.spotify.com/track/3lnFfn8UR14Sf4yGdSiLo4" target="_blank" rel="noopener">
          <img class="track-art" src="https://i.scdn.co/image/ab67616d00004851fe774a9c6a765af36302da52" alt="READ BY THE BOOK" />
          <div class="track-meta">
            <div class="track-name">READ BY THE BOOK</div>
            <div class="track-sub">Crablooshi · 1,576,894 plays</div>
          </div>
          <span class="track-arrow">↗</span>
        </a>

        <a class="track-card" href="https://open.spotify.com/track/7iQwKAbTqHpg59SDoWCBIk" target="_blank" rel="noopener">
          <img class="track-art" src="https://i.scdn.co/image/ab67616d00004851fe774a9c6a765af36302da52" alt="PHIGHT!" />
          <div class="track-meta">
            <div class="track-name">PHIGHT!</div>
            <div class="track-sub">Crablooshi · 1,454,950 plays</div>
          </div>
          <span class="track-arrow">↗</span>
        </a>

        <a class="track-card" href="https://open.spotify.com/track/2VH3nNr0bsxLCHoI2GFQFY" target="_blank" rel="noopener">
          <img class="track-art" src="https://i.scdn.co/image/ab67616d00004851fe774a9c6a765af36302da52" alt="ARTIFACTUAL RECOLLECTION" />
          <div class="track-meta">
            <div class="track-name">ARTIFACTUAL RECOLLECTION</div>
            <div class="track-sub">Crablooshi · 760,051 plays</div>
          </div>
          <span class="track-arrow">↗</span>
        </a>

        <a class="track-card" href="https://open.spotify.com/track/3t3VxRCxPqLMSiJjqyuS4Y" target="_blank" rel="noopener">
          <img class="track-art" src="https://i.scdn.co/image/ab67616d00004851945427c5110f728e262dd0a0" alt="TTYL" />
          <div class="track-meta">
            <div class="track-name">TTYL</div>
            <div class="track-sub">Crablooshi · 498,202 plays</div>
          </div>
          <span class="track-arrow">↗</span>
        </a>

        <p class="stack-label" style="margin-top:1.2rem">// Latest Album</p>
        <a class="album-card" href="https://open.spotify.com/album/03tJOCcUHpW9SeeFyQ7DOf" target="_blank" rel="noopener">
          <img class="album-art" src="https://i.scdn.co/image/ab67616d00001e02f78fa412b0f22e9a0642ec8c" alt="practice makes purpose" />
          <div class="album-meta">
            <div class="album-name">PRACTICE MAKES PURPOSE</div>
            <div class="album-sub">Album · 2025 · 10 tracks</div>
          </div>
          <span class="album-arrow">↗</span>
        </a>
      </div>

      <!-- Right: artist card + tools -->
      <div class="music-right">
        <div>
          <p class="artist-label">// Artist Profile</p>
          <a class="artist-card" href="https://open.spotify.com/artist/1U48URcCGBPG5cdmGbgA4P" target="_blank" rel="noopener">
            <img class="artist-img" src="https://i.scdn.co/image/ab67616100005174d1efe54cb8e1a64b88dfd2a0" alt="Crablooshi" />
            <div class="artist-meta">
              <div class="artist-name-txt">CRABLOOSHI</div>
              <div class="artist-listeners">62,408 monthly listeners</div>
            </div>
            <span class="artist-arrow">↗</span>
          </a>
        </div>
        <div class="tools-box">
          <p class="tools-box-label">// Made with</p>
          <div class="tools-row">
            <span class="tag tag-pink">FL Studio</span>
            <span class="tag tag-cyan">Ableton</span>
          </div>
        </div>
      </div>

    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="contact-glow"></div>
    <div class="reveal">
      <h2 class="contact-title">LET'S<br>CONNECT</h2>
      <p class="contact-sub">Open to collabs, projects, and conversations — game dev or music.</p>
      <div class="socials">
        <a href="https://open.spotify.com/artist/1U48URcCGBPG5cdmGbgA4P" target="_blank" rel="noopener" class="social-btn">🎵 Spotify</a>
        <a href="https://www.linkedin.com/in/conor-w-32177a3b7/" target="_blank" rel="noopener" class="social-btn">💼 LinkedIn</a>
        <a href="https://github.com/crablooshi" target="_blank" rel="noopener" class="social-btn">📁 GitHub</a>
      </div>
    </div>
  </section>

  <footer>
    <span class="footer-logo">CRABLOOSHI</span>
    <span class="footer-copy">© 2026 — Built with code &amp; caffeine</span>
  </footer>

  <script>
    const cursor = document.getElementById('cursor');
    const ring   = document.getElementById('cursor-ring');
    let mx=0,my=0,rx=0,ry=0;
    document.addEventListener('mousemove',e=>{mx=e.clientX;my=e.clientY;});
    (function loop(){
      cursor.style.left=mx+'px'; cursor.style.top=my+'px';
      rx+=(mx-rx)*.12; ry+=(my-ry)*.12;
      ring.style.left=rx+'px'; ring.style.top=ry+'px';
      requestAnimationFrame(loop);
    })();

    const io=new IntersectionObserver(entries=>entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('visible');}),{threshold:.1});
    document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

    const skillIO=new IntersectionObserver(entries=>entries.forEach(e=>{
      if(e.isIntersecting) e.target.querySelectorAll('.skill-bar-fill').forEach(b=>{ b.style.transform=`scaleX(${b.style.getPropertyValue('--w')})`; });
    }),{threshold:.3});
    const sc=document.getElementById('skillsContainer');
    if(sc) skillIO.observe(sc);
  </script>
</body>
</html>
