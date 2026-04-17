# EASY-YOGA-
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga - Design Finalizat Exact</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --teal-accent: #1e8e8e; /* Teal-ul vibrant din design */
            --teal-dark: #006666;   /* Teal-ul închis din footer */
            --text-dark: #333;
            --text-gray: #666;
            --bg-light: #fefefe;   /* Un alb foarte curat */
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', 'Helvetica Neue', Arial, sans-serif;
            color: var(--text-dark);
            line-height: 1.6;
            background-color: var(--bg-light);
        }

        /* HEADER & NAV */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 10%;
            background: white;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .logo {
            font-weight: 700;
            font-size: 26px;
            color: var(--teal-dark);
            display: flex;
            align-items: center;
            gap: 8px;
            text-decoration: none;
        }

        nav {
            display: flex;
            gap: 25px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            font-size: 15px;
            transition: 0.2s;
            padding-bottom: 3px;
        }

        nav a:hover, nav a.active {
            color: var(--teal-accent);
            border-bottom: 2px solid var(--teal-accent);
        }

        /* HERO SECTION */
        .hero {
            height: 75vh;
            /* Folosim imaginea femeii ca fundal principal */
            background: linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)), 
                        url('poza1.jpg') center/cover no-repeat;
            display: flex;
            align-items: center;
            padding: 0 10%;
            color: white;
        }

        .hero-content {
            max-width: 580px;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: 800;
            margin: 0 0 10px 0;
            letter-spacing: -1px;
        }

        .hero .subtitle {
            font-size: 1.5rem;
            font-weight: 600;
            margin: 0 0 20px 0;
        }

        .hero p {
            font-size: 1.1rem;
            margin-bottom: 35px;
            opacity: 0.9;
        }

        .btn-group {
            display: flex;
            gap: 15px;
        }

        .btn {
            padding: 12px 30px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 700;
            font-size: 15px;
            transition: all 0.2s ease-in-out;
            border: 2px solid transparent;
        }

        .btn-primary { 
            background: var(--teal-accent); 
            color: white; 
        }
        .btn-outline { 
            background: transparent; 
            color: white; 
            border: 2px solid white; 
        }
        
        .btn:hover { 
            transform: translateY(-2px); 
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        /* SECTION COMMON */
        .section-padding { padding: 80px 10%; text-align: center; }
        .section-tag { color: var(--teal-accent); text-transform: uppercase; font-size: 13px; font-weight: 700; letter-spacing: 2px; margin-bottom: 5px; }
        .section-title { font-size: 32px; font-weight: 800; margin-bottom: 50px; color: var(--teal-dark); }

        /* BENEFITS SECTION */
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            margin-bottom: 70px;
        }

        .benefit-item {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .benefit-icon-container {
            width: 70px;
            height: 70px;
            background-color: #e6f7f7; /* Fundal discret sub iconițe */
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
        }

        .benefit-item i { font-size: 30px; color: var(--teal-accent); }
        .benefit-item h3 { font-size: 17px; font-weight: 700; margin: 0 0 8px 0; }
        .benefit-item p { font-size: 14px; color: var(--text-gray); margin: 0; }

        /* PHOTO GRID & CARDS */
        .photo-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .photo-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 6px 18px rgba(0,0,0,0.06);
            text-align: left;
            transition: transform 0.2s;
        }

        .photo-card:hover {
            transform: translateY(-5px);
        }

        .photo-card img { 
            width: 100%; 
            height: 270px; 
            object-fit: cover; 
            display: block;
        }
        
        .photo-card-info { padding: 22px; }
        .photo-card-info h3 { font-size: 19px; font-weight: 700; margin: 0 0 8px 0; color: var(--teal-dark); }
        .photo-card-info p { font-size: 15px; color: var(--text-gray); margin: 0; }

        /* SOCIAL MEDIA SECTION */
        .social-section {
            background-color: #f6fbfb;
            padding: 60px 10%;
        }

        .social-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            justify-items: center;
            margin-top: 40px;
        }

        .social-card {
            display: flex;
            align-items: center;
            gap: 15px;
            padding: 12px 28px;
            border-radius: 10px;
            color: white;
            text-decoration: none;
            width: 100%;
            max-width: 250px;
            transition: all 0.2s;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .ws-card { background: #25D366; }
        .tk-card { background: #010101; }
        .ig-card { background: linear-gradient(135deg, #fdf497 0%, #fdf497 5%, #fd5949 45%, #d6249f 60%, #285AEB 90%); }

        .social-card span { font-size: 14px; flex-grow: 1; }
        .social-card strong { font-size: 15px; display: block; }
        
        .social-card:hover {
            opacity: 0.9;
            transform: scale(1.03);
        }

        /* FOOTER */
        footer {
            background: var(--teal-dark);
            color: rgba(255,255,255,0.7);
            text-align: center;
            padding: 25px;
            font-size: 14px;
        }

        /* RESPONSIVITATE PENTRU MOBIL */
        @media (max-width: 900px) {
            .hero h1 { font-size: 3rem; }
            .hero .subtitle { font-size: 1.2rem; }
            .benefits-grid, .photo-grid, .social-container { grid-template-columns: 1fr; }
            .section-title { font-size: 26px; }
            header { flex-direction: column; gap: 15px; padding: 15px; }
            nav { gap: 15px; }
            .section-padding { padding: 50px 5%; }
        }
    </style>
</head>
<body>

<header>
    <a href="#" class="logo">🌿 EASY YOGA</a>
    <nav>
        <a href="#" class="active">Acasă</a>
        <a href="#">Despre Yoga</a>
        <a href="#">Beneficii</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Yoga & Echilibru</h1>
        <p class="subtitle">Liniște. Natură. Energie interioară.</p>
        <p>Yoga te ajută să te conectezi cu tine, să reduci stresul și să trăiești prezentul.</p>
        <div class="btn-group">
            <a href="#" class="btn btn-primary">Descoperă Yoga</a>
            <a href="https://wa.me/37369404887" target="_blank" class="btn btn-outline">Contactează-mă</a>
        </div>
    </div>
</section>

<section class="section-padding">
    <p class="section-tag">Practica Yoga</p>
    <h2 class="section-title">Beneficii pentru corp și minte</h2>
    
    <div class="benefits-grid">
        <div class="benefit-item">
            <div class="benefit-icon-container"><i class="fas fa-leaf"></i></div>
            <h3>Reduce stresul</h3>
            <p>Calmează mintea și aduce relaxare profundă.</p>
        </div>
        <div class="benefit-item">
            <div class="benefit-icon-container"><i class="fas fa-child-reaching"></i></div>
            <h3>Crește flexibilitatea</h3>
            <p>Îmbunătățește postura și mobilitatea corpului.</p>
        </div>
        <div class="benefit-item">
            <div class="benefit-icon-container"><i class="fas fa-spa"></i></div>
            <h3>Energie și vitalitate</h3>
            <p>Respirația conștientă îți dă mai multă energie.</p>
        </div>
        <div class="benefit-item">
            <div class="benefit-icon-container"><i class="fas fa-heart"></i></div>
            <h3>Echilibru interior</h3>
            <p>Te ajută să fii prezent și conectat cu tine.</p>
        </div>
    </div>

    <div class="photo-grid">
        <div class="photo-card">
            <img src="poza1.jpg" alt="Femeie meditând">
            <div class="photo-card-info">
                <h3>Meditație</h3>
                <p>Conectare profundă cu liniștea interioară.</p>
            </div>
        </div>
        <div class="photo-card">
            <img src="poza2.jpg" alt="Bărbat meditând">
            <div class="photo-card-info">
                <h3>Respirație & Echilibru</h3>
                <p>Respiră conștient și simte momentul prezent.</p>
            </div>
        </div>
        <div class="photo-card">
            <img src="poza3.jpg" alt="Bărbat meditând într-o altă perspectivă">
            <div class="photo-card-info">
                <h3>Armonie și Bucurie</h3>
                <p>Zâmbește, trăiește și bucură-te de viață.</p>
            </div>
        </div>
    </div>
</section>

<section class="social-section section-padding">
    <h2 class="section-title">Contact & Social Media</h2>
    <p>Hai să ne conectăm! Urmărește-mă și scrie-mi pentru programări sau întrebări.</p>
    
    <div class="social-container">
        <a href="https://wa.me/37369404887" target="_blank" class="social-card ws-card">
            <i class="fab fa-whatsapp fa-2x"></i>
            <span>WhatsApp<br><strong>+373 694 048 87</strong></span>
        </a>
        <a href="https://www.tiktok.com/@easy_yoga33" target="_blank" class="social-card tk-card">
            <i class="fab fa-tiktok fa-2x"></i>
            <span>TikTok<br><strong>@easy_yoga33</strong></span>
        </a>
        <a href="https://www.instagram.com/easy_yoga33" target="_blank" class="social-card ig-card">
            <i class="fab fa-instagram fa-2x"></i>
            <span>Instagram<br><strong>@easy_yoga33</strong></span>
        </a>
    </div>
</section>

<footer>
    <p>© 2026 Easy Yoga. Toate drepturile rezervate.</p>
</footer>

</body>
</html>
