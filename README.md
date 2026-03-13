# albanyhandyman.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>West Albany Handyman</title>
  <style>
    :root {
      --bg: #0f172a;
      --panel: #111827;
      --text: #e5e7eb;
      --muted: #94a3b8;
      --accent: #38bdf8;
      --accent-2: #22c55e;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: var(--text);
      line-height: 1.6;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 24px;
    }

    header {
      text-align: center;
      padding: 72px 24px 48px;
    }

    h1 {
      font-size: clamp(2.2rem, 5vw, 4rem);
      margin: 0 0 12px;
    }

    .subtitle {
      color: var(--muted);
      font-size: 1.1rem;
      max-width: 700px;
      margin: 0 auto 24px;
    }

    .buttons {
      display: flex;
      gap: 12px;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 24px;
    }

    .btn {
      text-decoration: none;
      padding: 12px 18px;
      border-radius: 10px;
      font-weight: bold;
      transition: transform 0.15s ease, opacity 0.15s ease;
    }

    .btn:hover {
      transform: translateY(-2px);
      opacity: 0.95;
    }

    .btn-primary {
      background: var(--accent);
      color: #082f49;
    }

    .btn-secondary {
      background: #1f2937;
      color: var(--text);
      border: 1px solid #334155;
    }

    section {
      margin: 36px 0;
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }

    .card {
      background: rgba(17, 24, 39, 0.88);
      border: 1px solid rgba(148, 163, 184, 0.15);
      border-radius: 16px;
      padding: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    }

    .card h3 {
      margin-top: 0;
      margin-bottom: 10px;
      color: white;
    }

    .card p {
      margin: 0;
      color: var(--muted);
    }

    .highlight {
      color: var(--accent-2);
      font-weight: bold;
    }

    footer {
      text-align: center;
      color: var(--muted);
      padding: 30px 20px 50px;
      font-size: 0.95rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>West Albany Handyman</h1>
      <p class="subtitle">
        Reliable help for repairs, installs, light renovation work, and everyday home projects in West Albany and nearby areas.
      </p>
      <div class="buttons">
        <a class="btn btn-primary" href="#services">View Services</a>
        <a class="btn btn-secondary" href="mailto:westalbanyhandman@gmail.com">Email for a Quote</a>
      </div>
    </div>
  </header>

  <main class="container">
    <section>
      <div class="card">
        <h2>About Us</h2>
        <p>
          West Albany Handyman helps homeowners and property managers with practical, honest, and dependable home repair work. Whether you need small fixes knocked out fast or help with a longer to-do list, we focus on solid workmanship and clear communication.
        </p>
      </div>
    </section>

    <section id="services">
      <h2>Services</h2>
      <div class="card-grid">
        <div class="card">
          <h3>General Repairs</h3>
          <p>Drywall patching, trim repair, door adjustments, hardware replacement, and other common household fixes.</p>
        </div>
        <div class="card">
          <h3>Installation Work</h3>
          <p>Fixtures, shelves, blinds, curtain rods, bathroom accessories, TVs, and other small to medium installs.</p>
        </div>
        <div class="card">
          <h3>Maintenance & Punch Lists</h3>
          <p>Rental turnovers, property touch-ups, seasonal maintenance, and knocking out multiple small jobs in one visit.</p>
        </div>
      </div>
    </section>

    <section>
      <div class="card">
        <h2>Why Choose Us</h2>
        <p>We keep things simple: show up, communicate clearly, and get the job done right. We are a good fit for homeowners who want dependable help without the hassle.</p>
      </div>
    </section>

    <section>
      <div class="card">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:westalbanyhandman@gmail.com" style="color: var(--accent);">westalbanyhandman@gmail.com</a></p>
        <p>Serving West Albany and nearby communities</p>
      </div>
    </section>
  </main>

  <footer>
    West Albany Handyman • Simple, dependable home repair help.
  </footer>
</body>
</html>
