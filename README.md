# beauricegroen.github.io
<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Beauricegroenwerk — Heggen snoeien & Tuinonderhoud</title>
  <meta name="description" content="Beauricegroenwerk — professioneel heggen snoeien, tuinen zomerklaar en winterklaar maken in jouw regio.">
  <style>
    :root{--groen:#2e7d32;--donkergroen:#1b5e20;--accent:#7cb342;--bg:#f7f7f7;--card:#ffffff}
    *{box-sizing:border-box}
    body{font-family:'Segoe UI',Arial,Helvetica,sans-serif;margin:0;background:var(--bg);color:#222;line-height:1.6}
    header{background:linear-gradient(180deg,var(--groen),var(--donkergroen));color:#fff;padding:40px 16px;text-align:center}
    header h1{margin:0;font-size:34px;font-weight:800}
    header p{margin:12px 0 0;font-size:18px}
    nav{display:flex;gap:20px;justify-content:center;padding:14px;background:var(--donkergroen)}
    nav a{color:#fff;text-decoration:none;font-weight:600;transition:0.2s}
    nav a:hover{color:var(--accent)}
    .container{max-width:1100px;margin:40px auto;padding:0 20px}

    .hero{display:grid;grid-template-columns:1fr;gap:28px;align-items:center}
    @media(min-width:900px){.hero{grid-template-columns:1fr 460px}}
    .intro{background:var(--card);padding:26px;border-radius:14px;box-shadow:0 6px 18px rgba(0,0,0,0.08)}
    .intro h2{margin-top:0;font-size:26px;color:var(--groen)}
    .cta{margin-top:16px}
    .btn{display:inline-block;padding:12px 20px;border-radius:10px;background:var(--accent);color:#fff;text-decoration:none;font-weight:700;box-shadow:0 3px 8px rgba(0,0,0,0.2)}
    .btn:hover{background:var(--groen)}

    .diensten{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px;margin-top:20px}
    .kaart{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 4px 12px rgba(0,0,0,0.06)}
    .kaart h3{margin-top:0;color:var(--donkergroen)}

    .portfolio{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:20px}
    .portfolio img{width:100%;height:200px;object-fit:cover;border-radius:10px;box-shadow:0 3px 10px rgba(0,0,0,0.06)}

    .over{margin-top:30px}
    .contact{background:var(--card);padding:20px;border-radius:12px;margin-top:20px;box-shadow:0 4px 12px rgba(0,0,0,0.06)}
    footer{margin-top:40px;padding:18px;text-align:center;color:#fff;background:var(--donkergroen)}
    footer small{color:#ddd}
  </style>
</head>
<body>
  <header>
    <h1>Beauricegroenwerk</h1>
    <p>Uw tuin in goede handen — heggen snoeien, tuinonderhoud, zomerklaar & winterklaar maken</p>
  </header>

  <nav>
    <a href="#diensten">Diensten</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#over">Over mij</a>
    <a href="#contact">Contact</a>
  </nav>

  <main class="container">
    <section class="hero">
      <div class="intro">
        <h2>Welkom bij Beauricegroenwerk</h2>
        <p>Ik ben <strong>Beaurice Dekker</strong>, ervaren hovenier gespecialiseerd in het netjes houden van heggen en het seizoensklaar maken van tuinen. Ik werk snel, netjes en met oog voor detail, zodat uw tuin er altijd verzorgd uitziet.</p>
        <p class="cta"><a class="btn" href="#contact">Vraag een offerte aan</a></p>

        <div class="diensten" id="diensten">
          <div class="kaart">
            <h3>Heggen snoeien</h3>
            <p>Strak en veilig gesnoeid — voor een nette uitstraling en gezonde hagen.</p>
          </div>
          <div class="kaart">
            <h3>Tuinen winterklaar maken</h3>
            <p>Bescherm planten, ruim blad op en maak uw tuin klaar voor de koude maanden.</p>
          </div>
          <div class="kaart">
            <h3>Tuinen zomerklaar maken</h3>
            <p>Snoeien, opfrissen en klaarzetten zodat u optimaal van uw tuin kunt genieten.</p>
          </div>
          <div class="kaart">
            <h3>Onderhoudscontracten</h3>
            <p>Periodiek onderhoud zodat uw tuin het hele jaar door netjes blijft.</p>
          </div>
        </div>
      </div>

      <aside>
        <img src="2476b567-d7ba-47bf-b8a7-8403c8adf8bb.jpg" alt="Beauricegroenwerk aan het werk" style="width:100%;border-radius:12px;box-shadow:0 4px 14px rgba(0,0,0,0.1)">
        <div class="contact" id="contact" style="margin-top:16px">
          <h3>Contact</h3>
          <p><strong>Naam:</strong> Beaurice Dekker</p>
          <p><strong>Telefoon:</strong> <a href="tel:0612345678">06-12345678</a></p>
          <p><strong>Email:</strong> <a href="mailto:beauricedekker2008@gmail.com">beauricedekker2008@gmail.com</a></p>
          <p><strong>Bedrijf:</strong> Beauricegroenwerk</p>
        </div>
      </aside>
    </section>

    <section id="portfolio">
      <h2>Portfolio — Voor & Na</h2>
      <p>Bekijk hieronder een impressie van mijn werk. Vervang of breid uit met eigen foto's.</p>
      <div class="portfolio">
        <img src="2476b567-d7ba-47bf-b8a7-8403c8adf8bb.jpg" alt="Beaurice aan het werk">
        <img src="https://via.placeholder.com/600x400.png?text=Voor" alt="Voor">
        <img src="https://via.placeholder.com/600x400.png?text=Na" alt="Na">
      </div>
    </section>

    <section class="over" id="over">
      <h2>Over mij</h2>
      <p>Ik, Beaurice Dekker, ben de oprichter van Beauricegroenwerk. Met passie voor tuinen en vakmanschap zorg ik dat heggen netjes gesnoeid zijn en dat tuinen klaar zijn voor ieder seizoen.</p>
      <ul>
        <li>Vakmanschap en zorgvuldigheid</li>
        <li>Duidelijke prijzen en heldere afspraken</li>
        <li>Snel en betrouwbaar</li>
      </ul>
    </section>

  </main>

  <footer>
    <p>&copy; 2025 Beauricegroenwerk — <small>Alle rechten voorbehouden</small></p>
  </footer>

  <!-- Instructies voor jou:
    - Upload "2476b567-d7ba-47bf-b8a7-8403c8adf8bb.jpg" naar je GitHub repository samen met index.html.
    - Je kunt meerdere foto's toevoegen door ze te uploaden en hun bestandsnaam in de <img> tags te gebruiken.
    - Daarna: Instellingen → Pagina's → Implementeren vanuit een branch → main → /(root) → Opslaan.
    - Binnen 1 minuut staat je site online!
  -->
</body>
</html>
