<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Affiliate-Seite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #111;
            color: #fff;
            padding: 20px 0;
            border-bottom: 1px solid #333;
        }

        h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        main {
            padding: 40px 20px;
        }

        .affiliate-links {
            list-style-type: none;
            padding: 0;
        }

        .affiliate-links li {
            margin: 20px 0;
        }

        a {
            color: #fff;
            text-decoration: none;
            display: inline-block;
            padding: 10px 20px;
            border: 2px solid #fff;
            transition: background-color 0.3s, color 0.3s;
        }

        a:hover {
            background-color: #fff;
            color: #000;
        }

        /* Bild-Link Stil */
        .affiliate-image {
            max-width: 300px;
            border: 2px solid #fff;
            transition: transform 0.3s;
        }

        .affiliate-image:hover {
            transform: scale(1.05);
        }

    </style>
</head>
<body>
    <header>
        <h1>Willkommen auf meiner Affiliate-Seite</h1>
    </header>

    <main>
        <ul class="affiliate-links">
            <!-- Erstes Produkt -->
            <li>
                <a href="https://amzn.to/3NwTeqg" target="_blank">
                    <img src="/mnt/data/CC76A4C5-1EED-45E6-B87F-D9D901B8BE28.jpeg" alt="Produkt 1" class="affiliate-image">
                </a>
            </li>

            <!-- Zweites Produkt -->
            <li>
                <a href="https://example.com/produkt2" target="_blank">
                    <img src="https://via.placeholder.com/300x200.png?text=Produkt+2" alt="Produkt 2" class="affiliate-image">
                </a>
            </li>

            <!-- Drittes Produkt -->
            <li>
                <a href="https://example.com/produkt3" target="_blank">
                    <img src="https://via.placeholder.com/300x200.png?text=Produkt+3" alt="Produkt 3" class="affiliate-image">
                </a>
            </li>
        </ul>
    </main>
</body>
</html>
