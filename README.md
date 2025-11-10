<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pooja Bhati — Portfolio</title>
  <meta name="description" content="Portfolio of Pooja Bhati — Presentation Specialist & Graphic Designer" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg: #0b0d0f;
      --panel:#111418;
      --muted:#9aa4b2;
      --text:#f3f5f7;
      --accent:#8b5cf6; /* violet */
      --ring: rgba(139,92,246,.35);
      --card:#0f1216;
    }
    *{box-sizing:border-box}
    html,body{margin:0;height:100%;background:var(--bg);color:var(--text);font-family:Inter,system-ui,Segoe UI,Roboto,Arial,sans-serif;}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{max-width:1100px;margin:0 auto;padding:28px}
    .btn{display:inline-flex;gap:8px;align-items:center;padding:12px 16px;border-radius:14px;background:linear-gradient(180deg,var(--accent),#6d28d9);color:#fff;font-weight:600;border:none;cursor:pointer;box-shadow:0 6px 18px var(--ring);transition:transform .15s ease,box-shadow .15s ease}
    .btn:hover{transform:translateY(-2px);box-shadow:0 10px 24px var(--ring)}
    .btn.ghost{background:transparent;border:1px solid #273242;color:var(--text);box-shadow:none}
    .badge{padding:8px 12px;border:1px solid #273242;border-radius:999px;background:#0e1217;font-size:12px;color:var(--muted)}
    header{position:sticky;top:0;backdrop-filter:saturate(180%) blur(10px);background:rgba(11,13,15,.6);border-bottom:1px solid #141a22;z-index:20}
    nav{display:flex;align-items:center;justify-content:space-between}
    nav .links{display:flex;gap:18px}
    nav a{padding:12px 10px;color:var(--muted)}
    nav a:hover{color:#fff}
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:32px;align-items:center;padding:48px 0}
    .hero .title{font-size:48px;line-height:1.1;margin:0 0 12px}
    .hero .subtitle{color:var(--muted);font-size:18px}
    .card{background:var(--card);border:1px solid #141a22;border-radius:18px;padding:20px}
    .grid{display:grid;gap:16px}
    .work-grid{grid-template-columns:repeat(3,minmax(0,1fr))}
    .skills{grid-template-columns:repeat(6,minmax(0,1fr))}
    .section{padding:24px 0 8px}
    .section h2{margin:0 0 6px;font-size:28px}
    .muted{color:var(--muted)}
    .work-card{display:flex;flex-direction:column;gap:10px}
    .work-thumb{aspect-ratio:16/10;border-radius:14px;overflow:hidden;border:1px solid #1a2330;background:linear-gradient(135deg,#1a2330,#141a22)}
    .work-meta{display:flex;justify-content:space-between;align-items:center;gap:10px}
    .footer{padding:36px 0;color:var(--muted);font-size:14px;border-top:1px solid #141a22;margin-top:40px}
    .socials{display:flex;gap:12px}
    .pill{padding:10px 12px;border-radius:999px;border:1px solid #273242}
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      .work-grid{grid-template-columns:1fr 1fr}
      .skills{grid-template-columns:repeat(3,minmax(0,1fr))}
    }
    @media (max-width: 620px){
      .hero .title{font-size:36px}
      .work-grid{grid-template-columns:1fr}
      .skills{grid-template-columns:repeat(2,minmax(0,1fr))}
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <a href="#" class="logo" aria-label="home" style="font-weight:800;letter-spacing:.3px">PB.</a>
        <div class="links">
          <a href="#work">Work</a>
          <a href="#about">About</a>
          <a href="#skills">Skills</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- HERO -->
    <section class="hero">
      <div>
        <span class="badge">Presentation Specialist · Graphic Designer</span>
        <h1 class="title">Hi, I'm <span style="color:var(--accent)">Pooja Bhati</span>.<br/>I turn complex ideas into crisp, compelling decks.</h1>
        <p class="subtitle">5+ years crafting high-impact sales presentations at Genpact. Trusted by stakeholders for fast, accurate delivery and sleek visual narratives.</p>
        <div style="display:flex;gap:12px;margin-top:18px">
          <a class="btn" href="#work">See my work</a>
          <a class="btn ghost" href="#contact">Hire me</a>
        </div>
        <div style="display:flex;gap:8px;margin-top:18px" class="socials">
          <a class="pill" href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a>
          <a class="pill" href="mailto:hello@example.com">Email</a>
          <a class="pill" href="#" download>Download Resume</a>
        </div>
      </div>
      <div class="card" style="align-self:stretch">
        <h3 style="margin:0 0 8px">Recent highlights</h3>
        <ul style="margin:0;padding-left:18px;color:var(--muted)">
          <li>Built 120+ sales decks in FY25 with 98% on‑time delivery</li>
          <li>Created Diwali event creatives as part of HR catalyst team</li>
          <li>Specialized in data storytelling, iconography, and brand systems</li>
        </ul>
        <div style="display:flex;gap:10px;margin-top:16px;flex-wrap:wrap">
          <span class="badge">PowerPoint</span>
          <span class="badge">Figma</span>
          <span class="badge">Illustrator</span>
          <span class="badge">Canva</span>
        </div>
      </div>
    </section>

    <!-- WORK -->
    <section id="work" class="section">
      <h2>Selected work</h2>
      <p class="muted">A few projects I can share publicly. More available on request.</p>
      <div class="grid work-grid">
        <article class="work-card card">
          <div class="work-thumb">
            <img alt="Project thumbnail" src="https://picsum.photos/seed/deck1/800/500" />
          </div>
          <div class="work-meta">
            <div>
              <strong>Sales Pitch Redesign</strong>
              <div class="muted" style="font-size:14px">Narrative revamp · 24 slides</div>
            </div>
            <a class="btn ghost" href="#">View</a>
          </div>
        </article>
        <article class="work-card card">
          <div class="work-thumb">
            <img alt="Project thumbnail" src="https://picsum.photos/seed/deck2/800/500" />
          </div>
          <div class="work-meta">
            <div>
              <strong>Product One‑pager</strong>
              <div class="muted" style="font-size:14px">Visual system · 1 page</div>
            </div>
            <a class="btn ghost" href="#">View</a>
          </div>
        </article>
        <article class="work-card card">
          <div class="work-thumb">
            <img alt="Project thumbnail" src="https://picsum.photos/seed/deck3/800/500" />
          </div>
          <div class="work-meta">
            <div>
              <strong>Event Branding</strong>
              <div class="muted" style="font-size:14px">Diwali creatives</div>
            </div>
            <a class="btn ghost" href="#">View</a>
          </div>
        </article>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
      <h2>About</h2>
      <div class="card" style="display:grid;gap:16px;grid-template-columns:1fr 2fr;align-items:start">
        <img src="https://picsum.photos/seed/pooja/420/420" alt="Portrait" style="border-radius:14px;border:1px solid #1a2330" />
        <div>
          <p>I'm a presentation specialist based in India, known for crisp visual storytelling and reliable delivery in fast‑paced sales environments. I partner closely with stakeholders, translating complex requirements into clear, high‑impact slides.</p>
          <p class="muted">Interests: minimalist layouts, information hierarchy, and efficient workflows.</p>
          <div style="display:flex;gap:8px;flex-wrap:wrap">
            <span class="badge">Available for freelance</span>
            <span class="badge">Open to full‑time roles</span>
          </div>
        </div>
      </div>
    </section>

    <!-- SKILLS -->
    <section id="skills" class="section">
      <h2>Skills</h2>
      <div class="grid skills">
        <div class="card">Slide storytelling</div>
        <div class="card">Layout & grids</div>
        <div class="card">Iconography</div>
        <div class="card">Charts & data</div>
        <div class="card">Templates & masters</div>
        <div class="card">Brand systems</div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section">
      <h2>Contact</h2>
      <div class="card">
        <form name="contact" onsubmit="sendMessage(event)">
          <div style="display:grid;gap:12px;grid-template-columns:1fr 1fr">
            <label> Name<br/><input required name="name" class="input" /></label>
            <label> Email<br/><input required type="email" name="email" class="input" /></label>
          </div>
          <label> Message<br/><textarea required name="message" class="input" rows="5"></textarea></label>
          <div style="display:flex;gap:12px;align-items:center;margin-top:12px">
            <button class="btn" type="submit">Send</button>
            <span id="status" class="muted"></span>
          </div>
        </form>
      </div>
    </section>

    <footer class="footer">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap">
        <div>© <span id="year"></span> Pooja Bhati</div>
        <div class="socials">
          <a href="#" class="pill">Behance</a>
          <a href="#" class="pill">Dribbble</a>
          <a href="#" class="pill">Instagram</a>
        </div>
      </div>
    </footer>
  </main>

  <style>
    .input{width:100%;padding:12px 14px;border-radius:12px;background:#0b0f14;border:1px solid #1b2635;color:var(--text);outline:none}
    .input:focus{border-color:var(--accent);box-shadow:0 0 0 6px var(--ring)}
  </style>

  <script>
    const y = document.getElementById('year'); if (y) y.textContent = new Date().getFullYear();
    async function sendMessage(e){
      e.preventDefault();
      const form = e.target;
      const data = Object.fromEntries(new FormData(form));
      // This demo just shows a success message. Replace with your endpoint (Formspree, Getform, Netlify Forms, etc.).
      await new Promise(r=>setTimeout(r,600));
      document.getElementById('status').textContent = 'Thanks! I will get back to you soon.';
      form.reset();
    }
  </script>
</body>
</html>
