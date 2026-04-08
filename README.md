
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MBlackwell | IT • Cyber • Development</title>
  <style>
    :root {
      --bg: #0b0f14;
      --card: #121821;
      --text: #e7edf3;
      --muted: #9fb0c3;
      --accent: #3ddc97;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
      background: radial-gradient(1200px 600px at 20% -10%, #0f1724, var(--bg));
      color: var(--text);
      line-height: 1.6;
    }
    header {
      padding: 5rem 2rem 3rem;
      text-align: center;
    }
    header h1 { font-size: 2.6rem; letter-spacing: 0.5px; }
    header p { color: var(--muted); max-width: 720px; margin: 1rem auto 2rem; }
    .cta a {
      display: inline-block;
      margin: 0.25rem;
      padding: 0.65rem 1rem;
      border-radius: 10px;
      background: var(--accent);
      color: #06261a;
      font-weight: 600;
      text-decoration: none;
    }
    main { max-width: 1100px; margin: auto; padding: 2rem; }
    section { margin-bottom: 3rem; }
    h2 { font-size: 1.6rem; margin-bottom: 1rem; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.25rem;
    }
    .card {
      background: linear-gradient(180deg, #121821, #0f141c);
      border: 1px solid #1b2431;
      border-radius: 16px;
      padding: 1.25rem;
    }
    .card h3 { margin-bottom: 0.4rem; }
    .card p { color: var(--muted); }
    ul { list-style: none; }
    li::before { content: '▹'; margin-right: 0.4rem; color: var(--accent); }
    footer {
      text-align: center;
      padding: 2rem;
      color: var(--muted);
      border-top: 1px solid #1b2431;
    }
  </style>
</head>
<body>

<header>
  <h1>M. Blackwell</h1>
  <p>From DOS-era systems to modern development, I’ve grown with the IT landscape through network administration, system support, cybersecurity fundamentals, and continuous learning.</p>
  <div class="cta">
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    https://github.com/yourusername
  </div>
</header>

<main>

<section id="about">
  <h2>About Me</h2>
  <p class="card">Technology professional with hands-on experience in IT support and networking, a strong interest in cybersecurity, and an expanding focus on software development. Driven by curiosity, problem-solving, and building secure, efficient systems.</p>
</section>

<section id="skills">
  <h2>Core Skills</h2>
  <div class="grid">
    <div class="card">
      <h3>IT & Infrastructure</h3>
      <ul>
        <li>System Administration</li>
        <li>Network Support</li>
        <li>Troubleshooting</li>
        <li>Windows & Linux</li>
      </ul>
    </div>
    <div class="card">
      <h3>Cybersecurity</h3>
      <ul>
        <li>Security Fundamentals</li>
        <li>Access Control</li>
        <li>Threat Awareness</li>
        <li>Best Practices</li>
      </ul>
    </div>
    <div class="card">
      <h3>Development</h3>
      <ul>
        <li>HTML & CSS</li>
        <li>JavaScript (Learning)</li>
        <li>Git & GitHub</li>
        <li>Automation Mindset</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <h3>Portfolio Website</h3>
      <p>A GitHub Pages–hosted portfolio built with clean HTML and CSS to showcase skills, projects, and growth.</p>
    </div>
    <div class="card">
      <h3>Future Cyber Lab</h3>
      <p>Planned hands-on labs focused on networking, security fundamentals, and defensive techniques.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p class="card">Connect with me on GitHub or LinkedIn. A professional email can be provided upon request.</p>
</section>

</main>

<footer>
  © 2026 M. Blackwell • Built with GitHub Pages
</footer>

</body>
</html>
