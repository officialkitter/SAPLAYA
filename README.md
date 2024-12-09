# SAPLAYA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saplayatz - Food and Drinks Revolution</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <h1>Saplaya</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#market">Market</a>
            <a href="#about">About</a>
            <a href="#team">Team</a>
            <a href="#login">Login</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Revolutionizing Food and Drink Services</h2>
        <p>Connecting producers, suppliers, and customers seamlessly.</p>
    </section>

    <!-- Public Market Section -->
    <section id="market" class="market">
        <h3>Our Categories</h3>
        <div class="categories">
            <div>
                <h4>Students</h4>
                <p>Affordable and nutritious options for students.</p>
            </div>
            <div>
                <h4>Office</h4>
                <p>Quick meals and snacks for office workers.</p>
            </div>
            <div>
                <h4>Home</h4>
                <p>Essentials and ready-made meals for families.</p>
            </div>
        </div>
    </section>

    <!-- Producers Section -->
    <section id="team" class="team">
        <h3>For Producers, Farmers, and Suppliers</h3>
        <p>A dedicated zone to facilitate operations from production to supply.</p>
    </section>

    <!-- Login/Private Section -->
    <section id="login" class="login">
        <h3>Login to Access More Features</h3>
        <form action="/login" method="POST">
            <input type="email" name="email" placeholder="Enter your email" required>
            <input type="password" name="password" placeholder="Enter your password" required>
            <button type="submit">Login</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Saplayatz. All Rights Reserved.</p>
    </footer>
</body>
</html>
