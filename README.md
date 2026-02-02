<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kiran Jadhav | SDET</title>
  <style>
    :root {
      --bg: #0b0f1a;
      --card: rgba(16, 24, 39, 0.7);
      --glass: rgba(255, 255, 255, 0.06);
      --neon: #7cf6ff;
      --accent: #8b5cf6;
      --accent2: #22d3ee;
      --text: #e5e7eb;
      --muted: #9ca3af;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      color: var(--text);
      background: radial-gradient(1200px 600px at 10% 10%, #111827 0%, #0b0f1a 50%, #05070d 100%);
      overflow-x: hidden;
    }
    .grid {
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
      background-size: 40px 40px;
      pointer-events: none;
      z-index: 0;
    }
    .glow {
      position: fixed;
      width: 600px;
      height: 600px;
      background: radial-gradient(circle, rgba(124,246,255,0.15) 0%, rgba(124,246,255,0) 70%);
      top: -200px;
      right: -200px;
      z-index: 0;
    }
    .container {
      position: relative;
      z-index: 1;
      max-width: 1000px;
      margin: 0 auto;
      padding: 48px 20px 80px;
    }
    .hero {
      background: var(--card);
      border: 1px solid rgba(124,246,255,0.2);
      box-shadow: 0 0 30px rgba(124,246,255,0.12);
      border-radius: 20px;
      padding: 28px;
      backdrop-filter: blur(8px);
    }
    h1 {
      margin: 0 0 6px 0;
      font-size: 36px;
      letter-spacing: 1px;
      color: var(--neon);
      text-shadow: 0 0 8px rgba(124,246,255,0.5);
    }
    .subtitle {
      font-size: 16px;
      color: var(--muted);
      margin-bottom: 16px;
    }
    .tag {
      display: inline-block;
      padding: 6px 12px;
      margin-right: 8px;
      margin-bottom: 8px;
      border-radius: 999px;
      background: var(--glass);
      border: 1px solid rgba(255,255,255,0.08);
      color: #dbeafe;
      font-size: 12px;
      letter-spacing: 0.5px;
    }
    .section {
      margin-top: 28px;
      padding: 22px;
      background: var(--card);
      border: 1px solid rgba(139,92,246,0.15);
      border-radius: 16px;
      backdrop-filter: blur(8px);
    }
    h2 {
      margin: 0 0 12px 0;
      font-size: 20px;
      color: var(--accent2);
      text-shadow: 0 0 6px rgba(34,211,238,0.35);
    }
    ul { margin: 0; padding-left: 18px; }
    li { margin: 6px 0; color: var(--text); }
    .stack {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 10px;
      color: var(--muted);
    }
    .links a {
      color: var(--neon);
      text-decoration: none;
      margin-right: 14px;
    }
    .links a:hover { text-decoration: underline; }
    .badges img { margin: 4px 6px 0 0; }
  </style>
</head>
<body>
  <div class="grid"></div>
  <div class="glow"></div>

  <div class="container">
    <div class="hero">
      <h1>Kiran Jadhav</h1>
      <div class="subtitle">SDET | UI & API Automation | CI/CD</div>
      <div class="tag">UI Automation</div>
      <div class="tag">API Automation</div>
      <div class="tag">Jenkins CI/CD</div>
      <div class="tag">Selenium</div>
      <p>
        I’m an SDET focused on building scalable automation frameworks and reliable CI/CD pipelines for fast, high-quality releases.
      </p>
      <div class="links">
        <a href="https://www.linkedin.com/in/kiran-jadhav-981650120/" target="_blank">LinkedIn</a>
        <a href="https://leetcode.com/u/ikiran001/" target="_blank">LeetCode</a>
        <a href="https://www.hackerrank.com/profile/kiran_jadhav1993" target="_blank">HackerRank</a>
        <a href="https://ikiran001.github.io/kiranPortfolio/" target="_blank">Portfolio</a>
        <a href="https://github.com/ikiran001" target="_blank">GitHub</a>
      </div>
    </div>

    <div class="section">
      <h2>✅ What I Do</h2>
      <ul>
        <li>UI Automation (Selenium)</li>
        <li>API Automation (Postman)</li>
        <li>CI/CD (Jenkins)</li>
        <li>Test Design & Functional Validation</li>
        <li>Data Structures & OOPs Foundation</li>
      </ul>
    </div>

    <div class="section">
      <h2>🧰 Tech Stack</h2>
      <div class="stack">
        <div><strong>Languages:</strong> Java, Python (basic), C# (basic)</div>
        <div><strong>Automation:</strong> Selenium, Cucumber</div>
        <div><strong>API Tools:</strong> Postman</div>
        <div><strong>CI/CD:</strong> Jenkins</div>
        <div><strong>OS/Tools:</strong> Linux, Git</div>
        <div><strong>Core CS:</strong> DSA, OOPs</div>
      </div>
    </div>

    <div class="section">
      <h2>📌 Impact</h2>
      <ul>
        <li><em>[Example]</em> Reduced regression time by <strong>XX%</strong> by introducing parallel UI automation</li>
        <li><em>[Example]</em> Improved defect detection by <strong>YY%</strong> with API automation suite</li>
        <li><em>[Example]</em> Cut release cycle from <strong>X days to Y days</strong> using Jenkins pipelines</li>
      </ul>
    </div>

    <div class="section">
      <h2>🏷️ Badges</h2>
      <div class="badges">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white" />
        <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white" />
        <img src="https://img.shields.io/badge/Cucumber-23D96C?style=flat&logo=cucumber&logoColor=white" />
        <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" />
        <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white" />
        <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
      </div>
    </div>

    <div class="section">
      <h2>📊 GitHub Stats</h2>
      <p>
        <img src="https://github-readme-stats.vercel.app/api?username=ikiran001&show_icons=true&theme=tokyonight" />
      </p>
      <p>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ikiran001&layout=compact&theme=tokyonight" />
      </p>
    </div>
  </div>
</body>
</html>
