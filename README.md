<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="google-site-verification" content="WvntH1Z31BROUijSwq0ax3S65m7pqpYlfyXn0ulmDWc" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="TechMa - Your Source for Tech News and Insights">
    <meta name="author" content="TechMa Team">
    <title>TechMa - Innovating Technology</title>
    <link rel="stylesheet" href="./webpag.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>TechMaa.org</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#help">help</a></li>

            </ul>
        </nav>
    </header>

    <!-- Main Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to TechMaa</h2>
            <p>Your Source for the Latest Tech Trends and News</p>
            <button onclick="showMoreInfo()">Learn More</button>
        </div>
    </section>

    <!-- News Section -->
    <section id="news">
        <h2>Latest News</h2>
        <div class="news-articles">
            <div class="article">
                <h3>Tech Innovations of 2024</h3>
                <p>Discover the latest tech innovations shaping the future.</p>
            </div>
            <div class="article">
                <h3>AI and Its Impact</h3>
                <p>How Artificial Intelligence is changing industries worldwide.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    /* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #c6c6d7;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo h1 {
    margin: 0;
}

header nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin-right: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

header nav ul li a:hover {
    text-decoration: underline;
}

.hero {
    background: url('tech-banner.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 0;
}

.hero h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.hero button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
}

.hero button:hover {
    background-color: #0056b3;
}

#news, #about, #contact {
    padding: 50px 20px;
    text-align: center;
}

.news-articles {
    display: flex;
    justify-content: center;
    gap: 30px;
}

.article {
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 250px;
}

article h3 {
    color: #333;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    padding: 10px 20px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 5px;
}

form button:hover {
    background-color: #218838;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
    
