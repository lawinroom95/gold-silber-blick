gold-silber-blick/
│
├── index.html
├── blog.html
├── about.html
├── contact.html
├── products.html
├── /css
│    └── style.css
└── /images
     └── (deine Bilder)

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gold-Silber-Blick | Edelmetallblog</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Gold-Silber-Blick</h1>
    <nav>
      <a href="index.html" class="active">Startseite</a>
      <a href="blog.html">Blog</a>
      <a href="products.html">Empfehlungen</a>
      <a href="about.html">Über mich</a>
      <a href="contact.html">Kontakt</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Dein Blick auf den Edelmetallmarkt</h2>
    <p>Analysen, Trends und Empfehlungen rund um Gold und Silber.</p>
  </section>

  <section class="latest-posts">
    <h3>Neueste Artikel</h3>
    <div class="posts">
      <article>
        <img src="images/gold.jpg" alt="Goldbarren">
        <h4><a href="#">Warum Gold mehr als nur ein Investment ist</a></h4>
        <p>Gold bleibt ein Symbol für Sicherheit – besonders in unsicheren Zeiten. Erfahre, warum es sich lohnt, Gold langfristig zu halten...</p>
      </article>

      <article>
        <img src="images/silver.jpg" alt="Silbermünzen">
        <h4><a href="#">Silber – das unterschätzte Edelmetall</a></h4>
        <p>Silber hat enormes Potenzial. Wir zeigen dir, warum der Markt in Bewegung ist und worauf du achten solltest...</p>
      </article>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Gold-Silber-Blick | Partner von <a href="https://www.goldsilbershop.de" target="_blank">GoldSilberShop.de</a></p>
  </footer>
</body>
</html>

body {
  font-family: 'Helvetica Neue', sans-serif;
  margin: 0;
  background-color: #fff;
  color: #333;
}

header {
  background-color: #fff;
  border-bottom: 2px solid #d4af37;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  color: #d4af37;
  font-size: 1.8rem;
}

nav a {
  margin-left: 1rem;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

nav a.active, nav a:hover {
  color: #d4af37;
}

.hero {
  background: linear-gradient(white, #faf7f0);
  text-align: center;
  padding: 4rem 1rem;
}

.hero h2 {
  color: #d4af37;
  font-size: 2rem;
}

.latest-posts {
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.posts {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
}

.posts article {
  border: 1px solid #eee;
  border-radius: 6px;
  overflow: hidden;
  transition: transform 0.3s;
}

.posts article:hover {
  transform: translateY(-5px);
}

.posts img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

footer {
  background-color: #faf7f0;
  text-align: center;
  padding: 1.5rem;
  font-size: 0.9rem;
  color: #666;
}
footer a {
  color: #d4af37;
  text-decoration: none;
}

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Empfehlungen | Gold-Silber-Blick</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Gold-Silber-Blick</h1>
  <nav>
    <a href="index.html">Startseite</a>
    <a href="blog.html">Blog</a>
    <a href="products.html" class="active">Empfehlungen</a>
    <a href="about.html">Über mich</a>
    <a href="contact.html">Kontakt</a>
  </nav>
</header>

<main class="content">
  <h2>Unsere Produktempfehlungen</h2>
  <p>Hier findest du hochwertige Produkte rund um Edelmetalle. Die folgenden Links sind <strong>Affiliate-Links</strong> zu unserem Partner <a href="https://www.goldsilbershop.de" target="_blank">GoldSilberShop.de</a>.</p>

  <div class="product-list">
    <div class="product">
      <img src="images/goldbar.jpg" alt="Goldbarren">
      <h3>1 Unze Goldbarren</h3>
      <a href="https://www.goldsilbershop.de/gold/goldbarren.html?partnerid=DEINID" target="_blank" class="button">Zum Angebot</a>
    </div>

    <div class="product">
      <img src="images/silvercoin.jpg" alt="Silbermünze">
      <h3>Silbermünze Maple Leaf</h3>
      <a href="https://www.goldsilbershop.de/silber/silbermuenzen.html?partnerid=DEINID" target="_blank" class="button">Zum Angebot</a>
    </div>
  </div>
</main>

<footer>
  <p>&copy; 2025 Gold-Silber-Blick</p>
</footer>
</body>
</html>
