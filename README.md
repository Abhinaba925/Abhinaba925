<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>README Preview — Abhinaba Ghosh</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Inter:wght@300;400;500;600;700&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    background: #0d1117;
    color: #e6edf3;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
    line-height: 1.6;
    padding: 2rem;
  }
  .container {
    max-width: 880px;
    margin: 0 auto;
    background: #0d1117;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 3rem;
  }
  h2 {
    font-size: 1.4rem;
    color: #e6edf3;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid #21262d;
    margin: 2.5rem 0 1rem;
    font-family: 'JetBrains Mono', monospace;
  }
  h2 code {
    background: none;
    padding: 0;
    font-size: inherit;
    color: #e6edf3;
  }
  h3 {
    font-size: 1.1rem;
    color: #e6edf3;
    margin: 1.5rem 0 0.5rem;
    font-family: 'JetBrains Mono', monospace;
  }
  h3 code {
    background: none;
    padding: 0;
    font-size: inherit;
    color: #e6edf3;
  }
  h4 { font-size: 1rem; color: #e6edf3; margin: 0.8rem 0 0.4rem; }
  p { color: #8b949e; margin: 0.6rem 0; font-size: 0.95rem; }
  b, strong { color: #e6edf3; }
  a { color: #58a6ff; text-decoration: none; }
  a:hover { text-decoration: underline; }
  blockquote {
    border-left: 3px solid #00ff9d;
    padding: 0.2rem 1rem;
    margin: 1rem 0;
    color: #8b949e;
  }
  blockquote em { color: #00ff9d; }
  code {
    background: #161b22;
    padding: 0.15rem 0.4rem;
    border-radius: 4px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.85rem;
    color: #00ff9d;
  }
  pre {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 1.2rem;
    overflow-x: auto;
    margin: 1rem 0;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.82rem;
    line-height: 1.5;
    color: #8b949e;
  }
  img { max-width: 100%; border-radius: 6px; }
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 1rem 0;
  }
  td {
    padding: 1rem;
    vertical-align: top;
    border: 1px solid #21262d;
    background: #0d1117;
  }
  .center { text-align: center; }
  .badges { display: flex; gap: 6px; flex-wrap: wrap; justify-content: center; margin: 0.5rem 0; }
  .badge {
    display: inline-block;
    padding: 0.2rem 0.6rem;
    border-radius: 3px;
    font-size: 0.7rem;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 600;
    letter-spacing: 0.5px;
  }
  .inline-code-tags {
    display: inline-block;
    background: #161b22;
    padding: 0.1rem 0.5rem;
    border-radius: 3px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    color: #7a8ba7;
    margin: 0.15rem;
  }
  .separator {
    height: 1px;
    background: linear-gradient(to right, transparent, #30363d, transparent);
    margin: 2rem 0;
  }
  .header-banner {
    width: 100%;
    height: 200px;
    background: linear-gradient(135deg, #0d1117 0%, #003320 50%, #002a3a 100%);
    border-radius: 6px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-bottom: 1.5rem;
    position: relative;
    overflow: hidden;
  }
  .header-banner::before {
    content: '';
    position: absolute;
    inset: 0;
    background: radial-gradient(ellipse at 50% 50%, rgba(0,255,157,0.08) 0%, transparent 70%);
  }
  .header-banner h1 {
    font-size: 2.8rem;
    font-weight: 700;
    color: #e2e8f0;
    position: relative;
    z-index: 1;
  }
  .header-banner .sub {
    font-size: 0.85rem;
    color: #7a8ba7;
    font-family: 'JetBrains Mono', monospace;
    position: relative;
    z-index: 1;
    margin-top: 0.3rem;
  }
  .typing-line {
    font-family: 'JetBrains Mono', monospace;
    font-size: 1.1rem;
    color: #00ff9d;
    margin: 1rem 0;
  }
  .stat-badges {
    display: flex;
    gap: 8px;
    justify-content: center;
    margin: 1rem 0;
  }
  .stat-badge {
    background: #0d1117;
    border: 1px solid #30363d;
    padding: 0.25rem 0.8rem;
    border-radius: 4px;
    font-size: 0.72rem;
    font-family: 'JetBrains Mono', monospace;
  }
  .stat-badge .label { color: #7a8ba7; }
  .stat-badge .value { color: #00ff9d; font-weight: 700; }
  .stat-badge.gold .value { color: #fbbf24; }
  .stat-badge.cyan .value { color: #00e5ff; }

  .stats-row {
    display: flex;
    justify-content: center;
    gap: 12px;
    flex-wrap: wrap;
    margin: 1.5rem 0;
  }
  .stat-card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 1rem 1.5rem;
    min-width: 280px;
    height: 160px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #7a8ba7;
    font-size: 0.85rem;
    font-family: 'JetBrains Mono', monospace;
  }

  .project-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
    margin: 1.5rem 0;
  }
  .project-card {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 1.2rem;
  }
  .project-card h4 { margin-top: 0; font-size: 0.95rem; }
  .project-card p { font-size: 0.82rem; }

  .tech-section {
    margin: 0.8rem 0;
  }
  .tech-section summary {
    cursor: pointer;
    font-weight: 600;
    color: #e6edf3;
    font-size: 0.95rem;
    padding: 0.4rem 0;
  }
  .tech-badges {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    margin: 0.8rem 0;
  }
  .tech-badge {
    background: #0d1117;
    border: 1px solid #30363d;
    padding: 0.4rem 0.8rem;
    border-radius: 4px;
    font-size: 0.78rem;
    font-family: 'JetBrains Mono', monospace;
    color: #8b949e;
  }

  .journey-ascii {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 1.5rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.8rem;
    line-height: 1.6;
    color: #7a8ba7;
    overflow-x: auto;
  }
  .journey-ascii .highlight { color: #00ff9d; }
  .journey-ascii .cyan { color: #00e5ff; }
  .journey-ascii .gold { color: #fbbf24; }
  .journey-ascii .white { color: #e6edf3; }

  .chess-section {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
    margin: 1rem 0;
  }
  .chess-left {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 2rem;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .chess-gif {
    width: 300px;
    border-radius: 8px;
    margin-bottom: 1rem;
    border: 1px solid #30363d;
  }
  .chess-right {
    background: #161b22;
    border: 1px solid #21262d;
    border-radius: 8px;
    padding: 0;
    overflow: hidden;
  }

  .contact-section {
    text-align: center;
    padding: 2rem 0;
  }
  .contact-badges {
    display: flex;
    gap: 8px;
    justify-content: center;
    margin: 1.5rem 0;
  }
  .contact-badge {
    background: #0d1117;
    border: 1px solid #30363d;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    font-size: 0.82rem;
    font-family: 'JetBrains Mono', monospace;
    color: #8b949e;
    transition: all 0.3s;
  }
  .contact-badge:hover {
    border-color: #00ff9d;
    color: #00ff9d;
  }

  .footer-wave {
    width: 100%;
    height: 80px;
    background: linear-gradient(135deg, #0d1117 0%, #003320 50%, #002a3a 100%);
    border-radius: 6px;
    margin-top: 2rem;
  }

  .pv-badge {
    font-size: 0.7rem;
    color: #3e4c63;
    font-family: 'JetBrains Mono', monospace;
  }

  @media (max-width: 768px) {
    .project-grid { grid-template-columns: 1fr; }
    .chess-section { grid-template-columns: 1fr; }
    .container { padding: 1.5rem; }
  }
</style>
</head>
<body>
<div class="container">

  <!-- HEADER -->
  <div class="header-banner">
    <h1>Abhinaba Ghosh</h1>
    <div class="sub">$ researcher | engineer | first-principles thinker</div>
  </div>

  <div class="center">
    <div class="typing-line">> Building at the intersection of ML · Physics · Finance</div>
    <div class="stat-badges">
      <span class="stat-badge"><span class="label">CSIR-NET JRF </span><span class="value">AIR 90</span></span>
      <span class="stat-badge cyan"><span class="label">GATE </span><span class="value">Physics & Mathematics</span></span>
      <span class="stat-badge gold"><span class="label">IEEE </span><span class="value">Published</span></span>
    </div>
    <div class="stats-row">
      <div class="stat-card">📊 GitHub Stats Card</div>
      <div class="stat-card">📊 Top Languages Card</div>
    </div>
  </div>

  <div class="separator"></div>

  <!-- WHOAMI -->
  <h3><code>$ whoami</code></h3>
  <div style="display:flex;gap:2rem;align-items:start;margin-top:1rem;">
    <div style="flex:1;">
      <p>I'm a researcher and engineer driven by a <strong>first-principles approach</strong> — leveraging deep mathematical structures to build robust, intelligent, data-driven solutions.</p>
      <p>From modeling the laws of nature at <strong>IISER Kolkata</strong>, to engineering real-world optical systems at <strong>IIT Delhi</strong>, to pushing the frontiers of AI at <strong>IIT Bombay's C-MInDS</strong> — my journey has always been about tackling complex problems at their core.</p>
      <blockquote><em>"Understand the physics beneath the math, and the math beneath the code."</em></blockquote>
    </div>
    <div class="stat-card" style="min-width:350px;height:auto;padding:0.8rem;">📊 GitHub Streak Stats</div>
  </div>

  <div class="separator"></div>

  <!-- CURRENTLY BUILDING -->
  <h2><code>🚀 What I'm Currently Building</code></h2>
  <div class="project-grid">
    <div class="project-card">
      <h4>📈 Quant Finance</h4>
      <p>Backtesting <strong>algorithmic trading strategies</strong> — finding alpha through statistical rigor and systematic execution.</p>
      <div style="margin-top:0.8rem;">
        <span class="inline-code-tags">Python</span>
        <span class="inline-code-tags">Pandas</span>
        <span class="inline-code-tags">Backtesting</span>
        <span class="inline-code-tags">Time-Series</span>
      </div>
    </div>
    <div class="project-card">
      <h4>📡 Quantum × Wireless</h4>
      <p>Architecting a framework using <strong>Quantum Optimization & Spintronics</strong> to solve NP-Hard problems in wireless systems.</p>
      <div style="margin-top:0.8rem;">
        <span class="inline-code-tags">Qiskit</span>
        <span class="inline-code-tags">Optimization</span>
        <span class="inline-code-tags">Spintronics</span>
      </div>
    </div>
    <div class="project-card">
      <h4>🧠 Core AI / ML</h4>
      <p>Exploring the frontiers of <strong>NLP</strong> and <strong>Quantum-enhanced Machine Learning</strong> — where language models meet quantum circuits.</p>
      <div style="margin-top:0.8rem;">
        <span class="inline-code-tags">LangChain</span>
        <span class="inline-code-tags">PyTorch</span>
        <span class="inline-code-tags">Quantum ML</span>
      </div>
    </div>
  </div>

  <div class="separator"></div>

  <!-- TECH STACK -->
  <h2><code>🛠️ Tech Stack</code></h2>

  <div class="tech-section">
    <details open>
      <summary>&nbsp;Machine Learning & Data Science</summary>
      <div class="tech-badges">
        <span class="tech-badge">🐍 Python</span>
        <span class="tech-badge">🔥 PyTorch</span>
        <span class="tech-badge">📐 TensorFlow</span>
        <span class="tech-badge">📊 scikit-learn</span>
        <span class="tech-badge">🔗 LangChain</span>
        <span class="tech-badge">🧮 NumPy</span>
        <span class="tech-badge">🐼 Pandas</span>
      </div>
    </details>
  </div>
  <div class="tech-section">
    <details open>
      <summary>&nbsp;Scientific & Quantum Computing</summary>
      <div class="tech-badges">
        <span class="tech-badge">⚛️ Qiskit</span>
        <span class="tech-badge">📐 MATLAB</span>
        <span class="tech-badge">📝 LaTeX</span>
      </div>
    </details>
  </div>
  <div class="tech-section">
    <details open>
      <summary>&nbsp;Core Programming & DevOps</summary>
      <div class="tech-badges">
        <span class="tech-badge">C</span>
        <span class="tech-badge">C++</span>
        <span class="tech-badge">MySQL</span>
        <span class="tech-badge">Git</span>
        <span class="tech-badge">Docker</span>
        <span class="tech-badge">Linux</span>
        <span class="tech-badge">Bash</span>
      </div>
    </details>
  </div>

  <div class="separator"></div>

  <!-- JOURNEY -->
  <h2><code>🎓 The Journey</code></h2>
  <div class="journey-ascii">
┌─────────────────────────────────────────────────────────────────────────┐<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;<span class="highlight">⚛️  IISER Kolkata</span> ─── <span class="white">BS-MS Physics</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;Modeled fundamental laws of nature. Discovered a deeper&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;passion for Mathematics & Machine Learning.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;<span class="cyan">📡 IIT Delhi</span> ─── <span class="white">M.Tech</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;Built a Free-Space Optical (FSO) link @ <span class="white">1 Gbps</span> from scratch.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;Published & presented at <span class="gold">IEEE ANTS</span>.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;<span class="highlight">🧠 IIT Bombay</span> ─── <span class="white">C-MInDS Research Staff</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="highlight">← NOW</span>&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;Machine Learning • Probabilistic Models • NLP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;Quantum Computing • Quantitative Finance&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;<span class="gold">🏆 National Achievements</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── CSIR-NET (JRF): <span class="highlight">All India Rank 90</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── GATE: Qualified in <span class="cyan">Physics & Mathematics</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│<br>
└─────────────────────────────────────────────────────────────────────────┘
  </div>

  <div class="separator"></div>

  <!-- BEYOND THE CODE -->
  <h2><code>♟️ Beyond the Code</code></h2>
  <div class="chess-section">
    <div class="chess-left">
      <div style="font-size:3rem;margin-bottom:0.5rem;">♞</div>
      <p><strong>Avid Chess Player</strong> ♟️</p>
      <p style="font-size:0.82rem;">Strategic thinking on 64 squares — pattern recognition and deep calculation that directly complements building robust systems.</p>
      <br>
      <span class="contact-badge" style="color:#00ff9d;border-color:#00ff9d;">Challenge me on Chess.com →</span>
    </div>
    <div class="chess-right">
      <pre style="margin:0;border:none;border-radius:0;font-size:0.78rem;line-height:1.55;"><code style="background:none;padding:0;color:#8b949e;"><span style="color:#ff7b72;">class</span> <span style="color:#00e5ff;">Abhinaba</span>:
    <span style="color:#7a8ba7;">"""Beyond the terminal."""</span>

    <span style="color:#ff7b72;">def</span> <span style="color:#d2a8ff;">__init__</span>(<span style="color:#ffa657;">self</span>):
        self.location  = <span style="color:#a5d6ff;">"India"</span>
        self.education = [
            <span style="color:#a5d6ff;">"BS-MS Physics, IISER Kolkata"</span>,
            <span style="color:#a5d6ff;">"M.Tech, IIT Delhi"</span>,
        ]
        self.current   = <span style="color:#a5d6ff;">"Research Staff @ C-MInDS, IIT Bombay"</span>
        self.interests = [
            <span style="color:#a5d6ff;">"Quantum Computing"</span>,
            <span style="color:#a5d6ff;">"Machine Learning"</span>,
            <span style="color:#a5d6ff;">"Quantitative Finance"</span>,
            <span style="color:#a5d6ff;">"Chess ♟️"</span>,
            <span style="color:#a5d6ff;">"ArXiv deep-dives"</span>,
        ]

    <span style="color:#ff7b72;">def</span> <span style="color:#d2a8ff;">motto</span>(<span style="color:#ffa657;">self</span>):
        <span style="color:#ff7b72;">return</span> <span style="color:#a5d6ff;">"Break it. Understand it. Build it better."</span></code></pre>
    </div>
  </div>

  <div class="separator"></div>

  <!-- CONTACT -->
  <div class="contact-section">
    <h2><code>🤝 Let's Collaborate</code></h2>
    <p>I'm always open to discussing <strong>Quantitative Finance</strong>, <strong>NLP</strong>, and <strong>Quantum Machine Learning</strong>.</p>
    <div class="contact-badges">
      <a href="mailto:abhinabaghosh.iit@gmail.com"><span class="contact-badge">📧 Gmail</span></a>
      <a href="https://www.linkedin.com/in/abhinaba-ghosh-293a83155/"><span class="contact-badge">💼 LinkedIn</span></a>
      <a href="https://www.chess.com/member/abhinabaghosh"><span class="contact-badge">♟ Chess.com</span></a>
    </div>
    <div class="pv-badge">👁️ profile views counter</div>
  </div>

  <div class="footer-wave"></div>

</div>
</body>
</html>
