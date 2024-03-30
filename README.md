# Intern
#HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <div class="hero-content">
            <h2>Welcome to My Website</h2>
            <p>Discover the possibilities</p>
            <a href="#" class="btn">Explore Now</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>



#CSS CODE
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    margin: 0;
    font-size: 32px;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #ff7f50;
}

.hero {
    background-image: url('background.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.hero-content {
    max-width: 600px;
    margin: 0 auto;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 24px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background-color: #ff7f50;
    color: #fff;
    padding: 15px 30px;
    border-radius: 30px;
    text-decoration: none;
    transition: background-color 0.3s ease;
    font-weight: bold;
}

.btn:hover {
    background-color: #fff;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}
