# Black-w
في طور تعلم 
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>BlakFlix</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<header class="topbar">
    <h1>BlakFlix</h1>
    <nav>
        <a href="#">الرئيسية</a>
        <a href="#movies">أفلام</a>
        <a href="#gallery">صور</a>
    </nav>
</header>

<section id="hero">
    <h2>منصة مشاهدة ذكية</h2>
    <p>أفلام – صور – تجربة نظيفة</p>
</section>

<section id="movies" class="section">
    <h2>🎥 الأفلام</h2>

    <div class="movie-card" onclick="playMovie('movies/movie.mp4')">
        <img src="images/poster.jpg">
        <span>Action Movie</span>
    </div>

</section>

<section id="player" class="hidden">
    <video id="video" controls></video>
</section>

<section id="gallery" class="section">
    <h2>🖼️ الصور</h2>
    <div class="gallery">
        <img src="images/1.jpg">
        <img src="images/2.jpg">
        <img src="images/3.jpg">
    </div>
</section>

<footer>
    <p>© 2025 BlakFlix</p>
</footer>

<script src="js/app.js"></script>
</body>
</html>
