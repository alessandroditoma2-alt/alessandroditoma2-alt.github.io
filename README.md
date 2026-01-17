# alessandroditoma2-alt.github.io
Personal website
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Alessandro Di Toma</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <a href="index.html" class="nav-logo">Alessandro Di Toma</a>
            <ul class="nav-menu">
                <li><a href="index.html" class="nav-link">Home</a></li>
                <li><a href="cv.html" class="nav-link">CV</a></li>
                <li><a href="articles.html" class="nav-link">Articoli</a></li>
            </ul>
        </div>
    </nav>
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Articoli - Alessandro Di Toma</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <a href="index.html" class="nav-logo">Alessandro Di Toma</a>
            <ul class="nav-menu">
                <li><a href="index.html" class="nav-link">Home</a></li>
                <li><a href="cv.html" class="nav-link">CV</a></li>
                <li><a href="articles.html" class="nav-link">Articoli</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section class="articles-section">
            <h1>Articoli e Lavori</h1>
            
            <div class="articles-list">
                <article class="article-card">
                    <h2><a href="https://www.liberioltreleillusioni.it/articoli/articolo/censimento-istat-2024-declino-demografico-e-fratture-territoriali" target="_blank">Censimento ISTAT 2024: declino demografico e fratture territoriali</a></h2>
                    <p>Un'analisi approfondita dei dati del Censimento ISTAT 2024, focalizzata sulle tendenze demografiche italiane e le disparità territoriali.</p>
                    <a href="https://www.liberioltreleillusioni.it/articoli/articolo/censimento-istat-2024-declino-demografico-e-fratture-territoriali" target="_blank" class="read-more">Leggi l'articolo →</a>
                </article>

                <article class="article-card">
                    <h2><a href="https://www.liberioltreleillusioni.it/articoli/articolo/famiglie-imprese-e-finanza-pubblica-cosa-dice-la-banca-ditalia-sulla-manovra" target="_blank">Famiglie, imprese e finanza pubblica: cosa dice la Banca d'Italia sulla manovra</a></h2>
                    <p>Un'esame critico dei dati Banca d'Italia riguardanti l'impatto della manovra finanziaria su famiglie, imprese e conti pubblici.</p>
                    <a href="https://www.liberioltreleillusioni.it/articoli/articolo/famiglie-imprese-e-finanza-pubblica-cosa-dice-la-banca-ditalia-sulla-manovra" target="_blank" class="read-more">Leggi l'articolo →</a>
                </article>

                <article class="article-card">
                    <h2><a href="https://www.liberioltreleillusioni.it/articoli/articolo/come-cambiata-loccupazione-italiana-post-covid" target="_blank">Come è cambiata l'occupazione italiana post-COVID</a></h2>
                    <p>Un'analisi delle trasformazioni nel mercato del lavoro italiano seguito alla pandemia di COVID-19, con dati e trend attuali.</p>
                    <a href="https://www.liberioltreleillusioni.it/articoli/articolo/come-cambiata-loccupazione-italiana-post-covid" target="_blank" class="read-more">Leggi l'articolo →</a>
                </article>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2024 Alessandro Di Toma. Tutti i diritti riservati.</p>
        <p><a href="mailto:alessandroditoma2@gmail.com">alessandroditoma2@gmail.com</a></p>
    </footer>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #fff;
}

/* Navbar */
.navbar {
    background-color: #f8f8f8;
    border-bottom: 1px solid #e0e0e0;
    position: sticky;
    top: 0;
    z-index: 100;
}

.nav-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-logo {
    font-size: 1.2rem;
    font-weight: 600;
    color: #333;
    text-decoration: none;
}

.nav-menu {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-link {
    color: #666;
    text-decoration: none;
    transition: color 0.3s;
}

.nav-link:hover {
    color: #000;
}

/* Container */
.container {
    max-width: 900px;
    margin: 0 auto;
    padding: 3rem 2rem;
    min-height: calc(100vh - 200px);
}

/* Hero Section */
.hero {
    text-align: center;
    margin-bottom: 3rem;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #000;
}

.hero p {
    font-size: 1.1rem;
    color: #666;
    margin-bottom: 2rem;
    line-height: 1.8;
}

/* Contact Links */
.contact-links {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-bottom: 2rem;
    flex-wrap: wrap;
}

.btn {
    display: inline-block;
    padding: 0.75rem 1.5rem;
    background-color: #000;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s;
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn:hover {
    background-color: #333;
}

/* Quick Navigation Links */
.quick-nav {
    display: flex;
    gap: 2rem;
    justify-content: center;
    flex-wrap: wrap;
}

.link {
    color: #0066cc;
    text-decoration: none;
    font-size: 1.1rem;
    transition: text-decoration 0.3s;
</body>
</html>
