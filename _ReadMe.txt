<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Harish Kumar Patel | Digital IT Operations Specialist</title>
  <style>
    :root {
      --primary: #2563eb;
      --bg: #0f172a;
      --card: #111827;
      --text: #e5e7eb;
      --muted: #9ca3af;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #020617, var(--bg));
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 4rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      color: var(--muted);
      margin-top: 0.5rem;
    }

    nav {
      margin-top: 1.5rem;
    }

    nav a {
      color: var(--text);
      margin: 0 0.75rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover { color: var(--primary); }

    section {
      max-width: 1000px;
      margin: 0 auto;
      padding: 3rem 1rem;
    }

    h2 {
      margin-bottom: 1.5rem;
      font-size: 1.8rem;
      border-left: 4px solid var(--primary);
      padding-left: 0.75rem;
    }

    .card {
      background: var(--card);
      padding: 1.5rem;
      border-radius: 12px;
      margin-bottom: 1rem;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
    }

    .skill {
      background: rgba(37,99,235,0.15);
      color: #bfdbfe;
      padding: 0.4rem 0.75rem;
      border-radius: 999px;
      font-size: 0.9rem;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      color: var(--muted);
      font-size: 0.9rem;
    }

    a.button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.2rem;
      background: var(--primary);
      color: white;
      border-radius: 8px;
      text-decoration: none;
    }

    a.button:hover { opacity: 0.9; }
  </style>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

  <header>
    <h1>Harish Kumar Patel</h1>
    <p>Digital IT Operations Specialist L3 | IT Support & Infrastructure</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#experience">Experience</a>
      <a href="#certifications">Certifications</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
    <a class="button" href="Harish_Patel_Resume.pdf" download>Download Resume (PDF)</a>
    <br/><br/>
    <button class="button" onclick="toggleTheme()">Toggle Dark / Light</button>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>
        Hello! I'm <strong>Harish Kumar Patel</strong>, a Digital IT Operations Specialist (L3) with nearly 8+ years of professional experience in IT support engineering, networking, and infrastructure operations. I specialize in onsite and remote support, incident management, IT asset management, and ensuring stable, secure IT environments for large user bases.
      </p>
    </div>
  </section>

  <section id="skills">
    <h2><i class="fas fa-tools"></i> Skills</h2>
    <div class="card skills">
      <span class="skill">IT Support & Troubleshooting</span>
      <span class="skill">Network Administration (LAN/WAN)</span>
      <span class="skill">Windows / Linux / macOS</span>
      <span class="skill">Incident & SLA Management</span>
      <span class="skill">IT Asset Management</span>
      <span class="skill">Remote Support Tools</span>
      <span class="skill">Team Leadership</span>
      <span class="skill">Cloud Basics (AWS / Azure)</span>
    </div>
  </section>

  <section id="experience">
    <h2><i class="fas fa-briefcase"></i> Work Experience</h2>
    <div class="card">
      <h3>Onsite Support Analyst — Schlumberger Asia Services Ltd</h3>
      <p><em>2018 – Present</em></p>
      <ul>
        <li>Managing IT infrastructure for 500+ users</li>
        <li>Incident, SLA & asset management</li>
        <li>Leading onsite IT support teams</li>
        <li>Vendor & stakeholder coordination</li>
      </ul>
    </div>
    <div class="card">
      <h3>Senior Desktop Support Engineer — Wipro / InTarvo</h3>
      <p><em>2012 – 2018</em></p>
      <ul>
        <li>Enterprise desktop & network support</li>
        <li>NOC operations & troubleshooting</li>
        <li>Client: Cairn India Ltd</li>
      </ul>
    </div>
  </section>

  <section id="certifications">
    <h2><i class="fas fa-shield-alt"></i> Certifications & Awards</h2>
    <div class="card">
      <ul>
        <li>CCNA</li>
        <li>MCSE</li>
        <li>RHCE</li>
        <li>A+ & N+</li>
        <li>Awarded by Schlumberger for outstanding performance</li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>IT Infrastructure Operations – Schlumberger</h3>
        <p>Managing and maintaining IT infrastructure for 500+ users, including hardware, network devices, printers, and enterprise systems while ensuring SLA compliance and operational stability.</p>
        <a class="button" href="#">Enterprise Environment</a>
      </div>
      <div class="card">
        <h3>Onsite & Remote Support Operations</h3>
        <p>Provided onsite and remote IT support using tools like Bomgar, TeamViewer, RDP, and DameWare, resolving incidents via BMC Remedy while coordinating with vendors and stakeholders.</p>
        <a class="button" href="#">Support Operations</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Email: harish.patel87@gmail.com</p>
      <p>Location: Udaipur, India</p>
      <p>Experience: 8+ Years</p>
    </div>
  </section>

  <footer>
    © 2026 Harish Kumar Patel. All rights reserved.
  </footer>

  <script>
    function toggleTheme() {
      document.body.classList.toggle('light');
    }
  </script>
</body>
</html>
