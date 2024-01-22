<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promosi Web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Selamat Datang di Web Promosi Kami</h1>
    </header>

    <section class="promo-content">
        <a href="https://imgur.com/beQYhMW"><img src="https://i.imgur.com/beQYhMWh.png" title="source: imgur.com" /></a>
        <p>Temukan penawaran istimewa kami! Diskon besar-besaran untuk produk berkualitas tinggi.</p>
        <button onclick="redirectToShop()">Jelajahi Sekarang</button>
    </section>

    <footer>
        <p>&copy; 2024 Web Promosi. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<style>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
}

.promo-content {
    text-align: center;
    padding: 2em;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #4CAF50;
    color: #fff;
    border: none;
}

button:hover {
    background-color: #45a049;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
</style><script>function redirectToShop() {
    // Ganti URL dengan URL toko online Anda
    window.location.href = "https://shopee.co.id/cloud.design4u";
}
</script>
