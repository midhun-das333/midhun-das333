<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hi, I'm Midhun — Portfolio Intro</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f7fafc; --card:#ffffff; --muted:#6b7280; --accent:#0ea5a4; --line:#e6eef0;
      --blue:#0b63a7; --green:#059669; --orange:#ef7430; --pink:#be185d;
      --shadow: 0 6px 24px rgba(11,27,44,0.06);
    }
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;margin:0;background:linear-gradient(0deg, #f7fafc, #ffffff);color:#0f172a}
    .container{max-width:980px;margin:36px auto;padding:28px}
    .hero{display:flex;gap:20px;align-items:center}
    .avatar{width:88px;height:88px;border-radius:14px;background:linear-gradient(135deg,#06b6d4,#3b82f6);display:flex;align-items:center;justify-content:center;color:white;font-weight:800;font-size:32px;box-shadow:var(--shadow)}
    h1{margin:0;font-size:28px}
    .tagline{color:var(--muted);margin-top:6px}
    .actions{margin-left:auto;display:flex;gap:10px}
    .btn{background:var(--card);border:1px solid var(--line);padding:8px 12px;border-radius:8px;text-decoration:none;color:inherit;font-weight:600;box-shadow:var(--shadow)}
    .btn.primary{background:var(--accent);color:white;border:none}

    .divider{height:1px;background:var(--line);margin:22px 0;border-radius:4px}

    .section{background:var(--card);padding:18px;border-radius:12px;box-shadow:var(--shadow);margin-bottom:18px}
    .section h2{display:flex;align-items:center;gap:10px;margin:0 0 12px;font-size:18px}
    .about-list{margin:0;padding-left:18px;color:var(--muted)}

    .tech-badges{display:flex;flex-wrap:wrap;gap:10px}
    .badge{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:8px;background:#0f172a;color:white;font-weight:700;font-size:13px}
    .badge.django{background:#0f6b48}
    .badge.html{background:#e44d26}
    .badge.css{background:#2074c6}
    .badge.js{background:#f7df1e;color:#111}
    .badge.python{background:#3776ab}
    .badge.mysql{background:#00758f}

    .stack-row{display:flex;gap:10px;flex-wrap:wrap}

    /* mini card for most used languages */
    .mini-card{max-width:420px;padding:20px;border-radius:8px;background:#0b1220;color:#cbd5e1}
    .mini-title{font-weight:700;margin-bottom:12px;color:#acc3d9}
    .bars{display:flex;flex-direction:column;gap:10px}
    .bar{display:flex;align-items:center;gap:12px}
    .bar .label{width:110px;font-size:13px;color:#9bb0c8}
    .bar .track{flex:1;height:12px;background:rgba(255,255,255,0.06);border-radius:6px;overflow:hidden}
    .bar .fill{height:100%;border-radius:6px}
    .fill.java{width:36.66%;background:var(--orange)}
    .fill.python{width:36.34%;background:var(--blue)}
    .fill.html{width:16.76%;background:var(--pink)}
    .fill.css{width:10.24%;background:var(--green)}

    /* responsive */
    @media (max-width:760px){
      .hero{flex-direction:column;align-items:flex-start}
      .actions{margin-left:0;width:100%;justify-content:flex-start}
    }

    /* small helpers */
    .muted{color:var(--muted)}
    .inline-link{color:var(--blue);text-decoration:none;font-weight:700}
  </style>
</head>
<body>
  <div class="container">
    <div class="hero">
      <div class="avatar">MD</div>
      <div>
        <h1>👋 Hi, I'm <strong>Midhun Das</strong></h1>
        <div class="tagline">🎓 Electronics & Communication • Frontend Developer • <span class="muted">HTML & CSS</span></div>
      </div>
      <div class="actions">
        <a class="btn" href="#projects">Projects</a>
        <a class="btn primary" href="#contact">Contact</a>
      </div>
    </div>

    <div class="divider"></div>

    <div class="section" id="about">
      <h2>🧠 About Me</h2>
      <ul class="about-list">
        <li>Final year ECE student at Cochin University — passionate about clean UI and front-end development.</li>
        <li>Building simple, accessible websites using pure HTML & CSS.</li>
        <li>Currently working on personal projects to strengthen UI & responsive design skills.</li>
      </ul>
    </div>

    <div class="section" id="tech">
      <h2>🔧 Tech Stack</h2>
      <div class="tech-badges">
        <div class="badge flutter">FLUTTER</div>
        <div class="badge django">DJANGO</div>
        <div class="badge html">HTML5</div>
        <div class="badge css">CSS3</div>
        <div class="badge java">JAVA</div>
        <div class="badge python">PYTHON</div>
        <div class="badge fastapi">FASTAPI</div>
        <div class="badge js">JAVASCRIPT</div>
        <div class="badge mysql">MYSQL</div>
        <div class="badge postgres">POSTGRESQL</div>
      </div>
    </div>

    <div class="section" id="most-used">
      <h2>📊 Most Used Languages</h2>
      <div style="display:flex;gap:18px;flex-wrap:wrap;align-items:flex-start">
        <div class="mini-card">
          <div class="mini-title">Most Used Languages</div>
          <div class="bars">
            <div class="bar"><div class="label">Java <span style="color:#f59e0b">36.66%</span></div><div class="track"><div class="fill java"></div></div></div>
            <div class="bar"><div class="label">Python <span style="color:#3b82f6">36.34%</span></div><div class="track"><div class="fill python"></div></div></div>
            <div class="bar"><div class="label">HTML <span style="color:#d946ef">16.76%</span></div><div class="track"><div class="fill html"></div></div></div>
            <div class="bar"><div class="label">CSS <span style="color:#10b981">10.24%</span></div><div class="track"><div class="fill css"></div></div></div>
          </div>
        </div>

        <div style="flex:1;min-width:220px">
          <h3 style="margin:0 0 10px">📁 Featured Project</h3>
          <p class="muted">Calculator — Simple responsive calculator built with HTML & CSS. Clean UI and works across devices.</p>
          <p style="margin-top:12px"><a class="inline-link" href="https://github.com/midhun-das333/Calculator">View on GitHub</a></p>
        </div>
      </div>
    </div>

    <div class="section" id="contact">
      <h2>📫 Contact</h2>
      <p class="muted">Email: <strong>midhun@example.com</strong> • GitHub: <a class="inline-link" href="https://github.com/midhun-das333">midhun-das333</a></p>
    </div>
  </div>
</body>
</html>
