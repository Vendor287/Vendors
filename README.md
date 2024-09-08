# Vendors
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isolier Vendoren</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Willkommen bei Isolier-Vendoren</h1>
    <p>Finden Sie die besten Anbieter für Isolierlösungen.</p>
    <nav>
        <a href="vendors.html">Alle Anbieter</a> |
        <a href="about.html">Über uns</a> | 
        <a href="contact.html">Kontakt</a>
    </nav>
</header>

<main>
    <section>
        <h2>Empfohlene Anbieter</h2>
        <div class="vendor-list">
            <div class="vendor">
                <h3><a href="vendor1-details.html">Isolier Vendor 1</a></h3>
                <p>Experte für Gebäudedämmung und Industrieverkleidung.</p>
            </div>
            <div class="vendor">
                <h3><a href="vendor2-details.html">Isolier Vendor 2</a></h3>
                <p>Professionelle Lösungen für Schallschutz und Wärmedämmung.</p>
            </div>
        </div>
    </section>
</main>

<footer>
    <p>&copy; 2024 Isolier-Vendoren - Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alle Anbieter</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Alle Isolier-Anbieter</h1>
    <nav>
        <a href="index.html">Startseite</a> | 
        <a href="about.html">Über uns</a> | 
        <a href="contact.html">Kontakt</a>
    </nav>
</header>

<main>
    <section>
        <h2>Unsere Anbieter</h2>
        <ul>
            <li><a href="vendor1-details.html">Isolier Vendor 1</a></li>
            <li><a href="vendor2-details.html">Isolier Vendor 2</a></li>
            <!-- Weitere Anbieter -->
        </ul>
    </section>
</main>

<footer>
    <p>&copy; 2024 Isolier-Vendoren - Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isolier Vendor 1</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Isolier Vendor 1</h1>
    <nav>
        <a href="index.html">Startseite</a> | 
        <a href="vendors.html">Alle Anbieter</a> | 
        <a href="about.html">Über uns</a> | 
        <a href="contact.html">Kontakt</a>
    </nav>
</header>

<main>
    <section>
        <h2>Über Isolier Vendor 1</h2>
        <p>Isolier Vendor 1 ist spezialisiert auf Gebäudedämmung und Industrieverkleidungen.</p>
        <h3>Services:</h3>
        <ul>
            <li>Wärmedämmung</li>
            <li>Schallschutz</li>
            <li>Brandschutz</li>
        </ul>
        <h3>Kontaktdaten:</h3>
        <p>Email: info@isolier-vendor1.de</p>
        <p>Telefon: 123-456-7890</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Isolier-Vendoren - Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontakt</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Kontaktieren Sie uns</h1>
    <nav>
        <a href="index.html">Startseite</a> | 
        <a href="vendors.html">Alle Anbieter</a> | 
        <a href="about.html">Über uns</a>
    </nav>
</header>

<main>
    <section>
        <h2>Kontaktformular</h2>
        <form action="submit_contact.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-Mail:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Nachricht:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Absenden</button>
        </form>
    </section>
</main>

<footer>
    <p>&copy; 2024 Isolier-Vendoren - Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Über uns</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Über Isolier-Vendoren</h1>
    <nav>
        <a href="index.html">Startseite</a> | 
        <a href="vendors.html">Alle Anbieter</a> | 
        <a href="contact.html">Kontakt</a>
    </nav>
</header>

<main>
    <section>
        <h2>Unsere Mission</h2>
        <p>Isolier-Vendoren bietet Ihnen Zugang zu den besten Anbietern von Isolierlösungen in der Region.</p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Isolier-Vendoren - Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #4CAF50;
    padding: 20px;
    text-align: center;
    color: white;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

main {
    padding: 20px;
}

.vendor-list {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.vendor {
    background-color: white;
    border: 1px solid #ddd;
    padding: 15px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
