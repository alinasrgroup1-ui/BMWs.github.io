<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>BW — Black & White Portfolio</title>
  <meta name="description" content="Black & White portfolio template — minimal, responsive, accessible." />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a class="brand" href="#home">BW</a>
      <nav class="nav" aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
      <button id="themeToggle" aria-label="Toggle black and white theme">Toggle</button>
    </div>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-inner">
        <h1 class="title">Black & White</h1>
        <p class="subtitle">Minimal design, maximum contrast. A clean portfolio to showcase work in monochrome.</p>
        <a href="#projects" class="btn">See Projects</a>
      </div>
    </section>

    <section id="about" class="section container">
      <h2>About</h2>
      <p>BW is a minimal single-page template focused on typography, layout, and content. Designed for photographers, designers, and developers who prefer monochrome aesthetics.</p>
      <dl class="meta">
        <div>
          <dt>Focus</dt>
          <dd>Portfolio &amp; case studies</dd>
        </div>
        <div>
          <dt>Style</dt>
          <dd>Responsive, accessible, B&amp;W</dd>
        </div>
      </dl>
    </section>

    <section id="projects" class="section container">
      <h2>Projects</h2>
      <div id="gallery" class="gallery" aria-live="polite">
        <!-- Project cards inserted or edited directly in HTML -->
        <article class="card">
          <img src="https://via.placeholder.com/800x500?text=Project+1" alt="Project 1 preview" />
          <div class="card-body">
            <h3>Project One</h3>
            <p>Editorial photography layout and website concept rendered in B&amp;W.</p>
            <div class="card-actions">
              <a class="link" href="#" aria-label="Open Project One">View</a>
            </div>
          </div>
        </article>

        <article class="card">
          <img src="https://via.placeholder.com/800x500?text=Project+2" alt="Project 2 preview" />
          <div class="card-body">
            <h3>Project Two</h3>
            <p>Type-driven branding system with high-contrast elements.</p>
            <div class="card-actions">
              <a class="link" href="#" aria-label="Open Project Two">View</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <section id="contact" class="section container">
      <h2>Contact</h2>
      <p>Interested in working together? Send a short message below.</p>
      <form id="contactForm" class="form" action="#" method="post" novalidate>
        <label>
          <span>Name</span>
          <input name="name" type="text" required />
        </label>
        <label>
          <span>Email</span>
          <input name="email" type="email" required />
        </label>
        <label>
          <span>Message</span>
          <textarea name="message" rows="4" required></textarea>
        </label>
        <button type="submit" class="btn">Send</button>
        <p id="formStatus" class="form-status" aria-live="polite"></p>
      </form>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>© <span id="year"></span> BW · Built with minimalism</small>
      <div class="social">
        <a href="#" aria-label="GitHub">GitHub</a>
        <a href="#" aria-label="Twitter">Twitter</a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
