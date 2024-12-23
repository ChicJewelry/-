<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to bjioux lasotita!">
    <title>Welcome to bjioux lasotita</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Welcome to bjioux lasotita</h1>
            <p>Your one-stop shop for unique and beautiful jewelry.</p>
        </section>

        <section class="products">
            <h2>Featured Products</h2>
            <!-- Add product listings here -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 bjioux lasotita</p>
    </footer>

    <script src="script.js"></script>
</body>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.hero {
    background-color: #5a5a5a;
    color: #fff;
    padding: 50px 20px;
    text-align: center;
}

.products {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
</html>
document.addEventListener("DOMContentLoaded", function() {
    // You can add JavaScript to handle things like user interaction, loading content, etc.
    console.log("Website Loaded");
});
