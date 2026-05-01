

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Louisiana Earthship Biotecture — Nontechnical Summary</title>
<style>
  :root{
    --green:#123821; --green2:#1e5a34; --moss:#6d7d3c; --gold:#c6a35a;
    --sand:#f4efe4; --cream:#fffaf0; --ink:#172116; --muted:#586356;
    --blue:#1f6d91; --orange:#c77821; --purple:#765a86;
  }
  *{box-sizing:border-box} body{margin:0;background:var(--sand);color:var(--ink);font-family:Arial,Helvetica,sans-serif;line-height:1.55}
  .hero{min-height:62vh;background:linear-gradient(90deg,rgba(18,56,33,.94),rgba(18,56,33,.76)),radial-gradient(circle at 80% 20%,#e6c876 0,#4f6b37 28%,#123821 65%);color:white;padding:64px 7vw;display:grid;grid-template-columns:1.05fr .95fr;gap:42px;align-items:center}
  .eyebrow{letter-spacing:.18em;text-transform:uppercase;color:#e7d5a0;font-weight:700;font-size:.8rem}.hero h1{font-size:clamp(2.8rem,6vw,6.2rem);line-height:.92;margin:.3rem 0 1.2rem;font-weight:900;letter-spacing:-.05em}.hero p{font-size:clamp(1.05rem,1.6vw,1.45rem);max-width:680px;color:#f7efd7}.hero-card{background:rgba(255,250,240,.12);border:1px solid rgba(255,255,255,.28);border-radius:28px;padding:28px;box-shadow:0 20px 70px rgba(0,0,0,.25)}
  .mini-house{height:330px;border-radius:22px;background:linear-gradient(#cfe2d2,#e9dbb9 54%,#654525 55%,#2a1b10);position:relative;overflow:hidden}.roof{position:absolute;left:12%;top:24%;width:76%;height:18%;background:#2e4a24;clip-path:polygon(0 100%,46% 0,100% 100%)}.solar{position:absolute;left:34%;top:24%;width:26%;height:8%;background:repeating-linear-gradient(90deg,#1f4d76 0 18px,#bcd7e8 19px 21px);transform:skew(-19deg);border:2px solid #dceaf3}.home{position:absolute;left:22%;top:39%;width:56%;height:34%;background:#c7a77a;border:5px solid #6a4c2d;border-bottom:12px solid #5d3b20}.glass{position:absolute;left:10%;top:15%;width:44%;height:70%;background:linear-gradient(135deg,#9dc7d8,#ffe1a0);border:4px solid #5b3d21}.door{position:absolute;right:16%;top:24%;width:17%;height:61%;background:#80562c}.berm{position:absolute;left:-8%;right:-8%;bottom:0;height:35%;background:radial-gradient(circle,#2e4a24 0 2px,transparent 3px),#4b3a23;background-size:22px 18px;border-top-left-radius:50% 45%;border-top-right-radius:50% 45%}.water{position:absolute;left:0;right:0;bottom:0;height:10%;background:linear-gradient(90deg,#1f6d91,#5ea2ba)}
  .wrap{max-width:1180px;margin:0 auto;padding:54px 24px}.section{background:var(--cream);border:1px solid #dfd2b6;border-radius:26px;padding:34px;margin:28px 0;box-shadow:0 8px 28px rgba(38,30,10,.08)}h2{font-size:clamp(1.8rem,3vw,3rem);line-height:1.05;color:var(--green);margin:0 0 14px;font-weight:900;letter-spacing:-.03em}.lead{font-size:1.18rem;color:#344132;max-width:900px}.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:24px}.card{background:#fff;border:1px solid #e0d4ba;border-radius:20px;padding:22px;min-height:170px}.icon{font-size:2.2rem;margin-bottom:8px}.card h3{margin:0 0 8px;color:var(--green);font-size:1.18rem}.card p{margin:0;color:#465244}.compare{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:22px}.compare .box{border-radius:22px;padding:24px}.desert{background:#fbf1d8;border:1px solid #dcc37c}.louisiana{background:#e7f2e8;border:1px solid #b4d3b9}.box h3{margin-top:0;color:var(--green);font-size:1.35rem}.flow{display:flex;flex-wrap:wrap;gap:10px;margin:22px 0}.pill{padding:12px 16px;border-radius:999px;background:#fff;border:1px solid #d6c8ab;font-weight:700;color:#263224}.arrow{align-self:center;color:var(--gold);font-weight:900}.big-takeaway{background:linear-gradient(135deg,var(--green),#0d2918);color:white;border-radius:28px;padding:36px;margin:36px 0;display:grid;grid-template-columns:1fr 1fr;gap:24px;align-items:center}.big-takeaway h2{color:white}.big-takeaway p{color:#f3ead3;font-size:1.14rem}.highlight{color:#f2d98c;font-weight:900}.steps{counter-reset:item}.step{display:grid;grid-template-columns:64px 1fr;gap:16px;margin:20px 0}.num{width:54px;height:54px;border-radius:50%;display:grid;place-items:center;background:var(--green);color:white;font-weight:900;font-size:1.4rem}.step h3{margin:0;color:var(--green);font-size:1.25rem}.step p{margin:.25rem 0 0;color:#465244}.quote{font-size:clamp(1.6rem,3vw,2.6rem);font-weight:900;color:var(--green);line-height:1.1;text-align:center;margin:24px auto;max-width:850px}.footer{background:#0f2e1c;color:#eadfbd;text-align:center;padding:32px 20px;margin-top:40px}.tagline{letter-spacing:.14em;text-transform:uppercase;font-weight:800;color:#d2ba72}
  @media(max-width:850px){.hero,.big-takeaway,.compare{grid-template-columns:1fr}.grid{grid-template-columns:1fr}.hero{padding:42px 24px}.mini-house{height:240px}}
</style>
</head>
<body>
  <header class="hero">
    <div>
      <div class="eyebrow">Louisiana Earthship Biotecture</div>
      <h1>A house that works like a living system.</h1>
      <p>A plain-language overview of Earthships, why Louisiana changes the design, and what a hot-humid version needs to succeed.</p>
    </div>
    <div class="hero-card" aria-label="Illustration of a Louisiana Earthship">
      <div class="mini-house"><div class="roof"></div><div class="solar"></div><div class="home"><div class="glass"></div><div class="door"></div></div><div class="berm"></div><div class="water"></div></div>
    </div>
  </header>

  <main class="wrap">
    <section class="section">
      <h2>What is an Earthship?</h2>
      <p class="lead">An Earthship is a home designed to provide many of its own basic needs. Instead of treating power, water, waste, and comfort as separate utilities, the home connects them into one coordinated system.</p>
      <div class="grid">
        <div class="card"><div class="icon">☀️</div><h3>Collects energy</h3><p>Solar panels generate electricity that can be stored in batteries for later use.</p></div>
        <div class="card"><div class="icon">💧</div><h3>Harvests water</h3><p>Rain is captured from the roof, stored, filtered, and reused carefully.</p></div>
        <div class="card"><div class="icon">🌿</div><h3>Uses natural materials</h3><p>Earthships often use local, recycled, and low-impact materials wherever possible.</p></div>
        <div class="card"><div class="icon">🏠</div><h3>Buffers the climate</h3><p>Thick walls, insulation, and smart orientation help stabilize indoor conditions.</p></div>
        <div class="card"><div class="icon">♻️</div><h3>Reduces waste</h3><p>Water and waste streams are treated as resources instead of things to simply throw away.</p></div>
        <div class="card"><div class="icon">🛡️</div><h3>Builds resilience</h3><p>The goal is a home that can keep working during outages, storms, and disruptions.</p></div>
      </div>
    </section>

    <section class="section">
      <h2>Why Louisiana needs a different Earthship</h2>
      <p class="lead">Traditional Earthships were shaped by the high desert around Taos, New Mexico. Louisiana is almost the opposite: wet, hot, humid, storm-prone, and flood-aware.</p>
      <div class="compare">
        <div class="box desert"><h3>Traditional high-desert Earthship</h3><p>Works with dry air, big day-to-night temperature swings, heavy thermal mass, passive solar heating, and earth-sheltering.</p></div>
        <div class="box louisiana"><h3>Louisiana-adapted Earthship</h3><p>Must control humidity, prevent mold, avoid deep berming, elevate for flood risk, and use active HVAC and dehumidification.</p></div>
      </div>
    </section>

    <section class="big-takeaway">
      <div><h2>The big idea</h2><p>A Louisiana Earthship is not a desert Earthship copied into the swamp. It is a <span class="highlight">climate-adapted off-grid home</span> that keeps the Earthship spirit while redesigning the parts that would fail in hot, humid weather.</p></div>
      <div class="quote">“Same philosophy. Different climate. Smarter system.”</div>
    </section>

    <section class="section">
      <h2>The core systems</h2>
      <p class="lead">The home works by connecting several simple loops. Each loop reduces dependence on outside infrastructure.</p>
      <h3>Energy loop</h3>
      <div class="flow"><span class="pill">Sun</span><span class="arrow">→</span><span class="pill">Solar panels</span><span class="arrow">→</span><span class="pill">Inverter</span><span class="arrow">→</span><span class="pill">Batteries</span><span class="arrow">→</span><span class="pill">Home loads</span><span class="arrow">+</span><span class="pill">Emergency generator</span></div>
      <h3>Water loop</h3>
      <div class="flow"><span class="pill">Rain</span><span class="arrow">→</span><span class="pill">Roof</span><span class="arrow">→</span><span class="pill">First flush</span><span class="arrow">→</span><span class="pill">Cistern</span><span class="arrow">→</span><span class="pill">Pump</span><span class="arrow">→</span><span class="pill">Filters</span><span class="arrow">→</span><span class="pill">Home use</span><span class="arrow">+</span><span class="pill">Backup well</span></div>
      <h3>Comfort loop</h3>
      <div class="flow"><span class="pill">Tight envelope</span><span class="arrow">+</span><span class="pill">Insulation</span><span class="arrow">+</span><span class="pill">Heat pump</span><span class="arrow">+</span><span class="pill">Dehumidifier</span><span class="arrow">+</span><span class="pill">Fresh-air ventilation</span></div>
    </section>

    <section class="section">
      <h2>What must change for South Louisiana?</h2>
      <div class="steps">
        <div class="step"><div class="num">1</div><div><h3>Raise the building instead of burying it</h3><p>Deep berming can trap moisture and create flood risk. A Louisiana version should use a raised foundation and thoughtful drainage.</p></div></div>
        <div class="step"><div class="num">2</div><div><h3>Treat humidity as the main enemy</h3><p>Comfort is not just about temperature. Mold prevention and dehumidification become central to the design.</p></div></div>
        <div class="step"><div class="num">3</div><div><h3>Use a durable, breathable envelope</h3><p>The wall and roof should shed rain, block air leaks, insulate continuously, and still allow safe drying.</p></div></div>
        <div class="step"><div class="num">4</div><div><h3>Add active HVAC and dehumidification</h3><p>Passive cooling alone is not enough in Lafayette. A heat pump, whole-house dehumidifier, and ventilation system are needed.</p></div></div>
        <div class="step"><div class="num">5</div><div><h3>Use abundant rainfall wisely</h3><p>Louisiana receives enough rain to make harvesting very useful, but storage, filtration, overflow, and backup water are still important.</p></div></div>
        <div class="step"><div class="num">6</div><div><h3>Keep indoor planting controlled</h3><p>Indoor greywater gardens can add humidity. In Louisiana, more treatment should be outdoors or carefully isolated.</p></div></div>
      </div>
    </section>

    <section class="section">
      <h2>What this means in everyday language</h2>
      <p class="lead">The Louisiana Earthship is best understood as a resilient home that borrows from nature but does not ignore physics. It collects sunshine and rain, protects itself from moisture, keeps indoor air healthy, and uses backup systems only when needed.</p>
      <div class="grid">
        <div class="card"><div class="icon">🌧️</div><h3>Rain becomes a resource</h3><p>Roof water becomes household water after storage and treatment.</p></div>
        <div class="card"><div class="icon">🌬️</div><h3>Air is managed intentionally</h3><p>Fresh air is brought in, filtered, dried, and conditioned.</p></div>
        <div class="card"><div class="icon">🔋</div><h3>Power is stored for resilience</h3><p>Batteries keep the home operating when the sun is gone or the grid is down.</p></div>
      </div>
    </section>

    <section class="big-takeaway">
      <div><h2>Final takeaway</h2><p>A South Louisiana Earthship should not be sold as a passive desert house. It should be presented as a <span class="highlight">regional redesign</span>: off-grid, water-smart, humidity-aware, flood-conscious, and built to last.</p></div>
      <div class="quote">“The house becomes infrastructure.”</div>
    </section>
  </main>
  <footer class="footer"><div class="tagline">Louisiana Earthship · Designed for water, heat, storms, and resilience</div></footer>
</body>
</html>
