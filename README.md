<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Easy Yoga</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: Poppins;
    background: #f5f7f5;
    color: #2b2b2b;
}

/* NAV */
nav {
    position: fixed;
    width: 100%;
    background: rgba(30, 100, 50, 0.95);
    padding: 12px;
    text-align: center;
    z-index: 1000;
    backdrop-filter: blur(8px);
}

nav a {
    color: white;
    margin: 12px;
    text-decoration: none;
    font-weight: 500;
}

/* HERO */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)),
    url('https://images.unsplash.com/photo-1545389336-cf090694435e') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
    padding: 20px;
}

.hero h1 {
    font-size: 60px;
    margin: 0;
}

.hero p {
    font-size: 20px;
    margin-top: 10px;
}

.btn {
    margin-top: 20px;
    padding: 14px 28px;
    border: none;
    border-radius: 30px;
    background: #2e7d32;
    color: white;
    cursor: pointer;
    font-size: 16px;
    transition: 0.3s;
}

.btn:hover {
    transform: scale(1.05);
    background: #1b5e20;
}

/* SECTIONS */
section {
    padding: 80px 20px;
    text-align: center;
}

/* CARDS */
.cards {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background: white;
    width: 260px;
    padding: 25px;
    border-radius: 18px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 10px;
    max-width: 900px;
    margin: auto;
}

.gallery img {
    width: 100%;
    border-radius: 12px;
}

/* REVIEWS */
.review {
    max-width: 600px;
    margin: 15px auto;
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
}

/* CONTACT */
.contact {
    background: #e8f5e9;
}

/* FLOAT WHATSAPP */
.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    padding: 15px;
    border-radius: 50%;
    font-size: 20px;
    text-decoration: none;
}

/* FOOTER */
footer {
    background: #2e7d32;
    color: white;
    text-align: center;
    padding: 20px;
}

/* MOBILE */
@media(max-width:768px){
    .hero h1 {font-size: 38px;}
}
</style>
</head>

<body>

<nav>
<a href="#home">Acasă</a>
<a href="#about">Despre</a>
<a href="#services">Clase</a>
<a href="#gallery">Galerie</a>
<a href="#reviews">Recenzii</a>
<a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    <div>
        <h1>EASY YOGA</h1>
        <p>Echilibru • Energie • Liniște interioară</p>
        <button class="btn" onclick="window.location.href='https://wa.me/37369404887'">
            Rezervă o clasă
        </button>
    </div>
</div>

<section id="about">
    <h2>Despre noi</h2>
    <p>Easy Yoga este un spațiu dedicat relaxării, sănătății și echilibrului interior prin mișcare și respirație.</p>
</section>

<section id="services">
    <h2>Clasele noastre</h2>
    <div class="cards">
        <div class="card">
            <h3>Yoga</h3>
            <p>Clase pentru toate nivelurile</p>
        </div>

        <div class="card">
            <h3>Meditație</h3>
            <p>Calm mental și reducerea stresului</p>
        </div>

        <div class="card">
            <h3>Stretching</h3>
            <p>Flexibilitate și relaxare corporală</p>
        </div>
    </div>
</section>

<section id="gallery">
    <h2>Galerie</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1552196563-55cd4e45efb3">
        <img src="https://images.unsplash.com/photo-1518611012118-fddc5c9c6a3b">
        <img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773">
    </div>
</section>

<section id="reviews">
    <h2>Recenzii</h2>

    <div class="review">
        „Un loc perfect pentru relaxare și energie pozitivă.”
        <br><b>- Ana</b>
    </div>

    <div class="review">
        „Foarte profesionist și atmosferă calmă.”
        <br><b>- Mihai</b>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>📍 Chișinău</p>
    <p>📞 +37369404887</p>
    <p>Instagram: easy_yoga33</p>

    <button class="btn" onclick="window.location.href='https://wa.me/37369404887'">
        Scrie pe WhatsApp
    </button>
</section>

<footer>
    © EASY YOGA — Toate drepturile rezervate
</footer>

<a class="whatsapp" href="https://wa.me/37369404887">💬</a>

</body>
</html>
