<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga | Beatrice</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Montserrat:wght@300;400;500&display=swap');
        
        body { font-family: 'Montserrat', sans-serif; background-color: #f4f4eb; color: #4a4a4a; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        
        .glass-nav { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(10px); }
        .hero-text { text-shadow: 0 2px 4px rgba(0,0,0,0.1); }
        .clasa-card { 
            background: rgba(255, 255, 255, 0.5); 
            border: 1px solid rgba(140, 109, 70, 0.1); 
            border-radius: 15px; 
            transition: all 0.3s ease;
        }
        .clasa-card:hover { background: #fff; transform: translateY(-5px); }
    </style>
</head>
<body>

    <nav class="p-5 flex justify-between items-center glass-nav sticky top-0 z-50">
        <div class="flex items-center gap-2">
            <div class="text-[#8c9c82] text-2xl"><i class="fas fa-seedling"></i></div>
            <div class="text-xl tracking-[0.2em] font-light">EASY YOGA</div>
        </div>
        <div class="hidden md:flex gap-8 text-[11px] uppercase tracking-widest font-medium">
            <a href="#" class="border-b border-black pb-1">Acasă</a>
            <a href="#despre">Despre Mine</a>
            <a href="#clase">Clase</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header class="relative h-[85vh] flex flex-col items-center justify-center text-center p-6">
        <div class="absolute inset-0 z-0">
            <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=1200" class="w-full h-full object-cover" alt="Yoga Beatrice">
            <div class="absolute inset-0 bg-gradient-to-b from-white/10 via-white/40 to-[#f4f4eb]"></div>
        </div>
        
        <div class="relative z-10 space-y-4">
            <h1 class="text-4xl md:text-6xl text-white hero-text tracking-wide uppercase">Bine ai venit la Easy Yoga</h1>
            <p class="text-xl md:text-2xl text-white italic font-light drop-shadow-md">Relaxare. Echilibru. Comunitate.</p>
        </div>
    </header>

    <section id="despre" class="py-16 px-6 max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
        <div class="relative flex justify-center">
            <div class="w-64 h-64 md:w-80 md:h-80 rounded-full overflow-hidden border-[15px] border-white shadow-xl">
                 <img src="https://images.unsplash.com/photo-1599447421416-3414500d18a5?auto=format&fit=crop&w=500" class="w-full h-full object-cover" alt="Beatrice">
            </div>
        </div>
        <div class="space-y-6">
            <h2 class="text-3xl text-[#5c5c5c] uppercase tracking-widest border-b-2 border-[#8c9c82] inline-block pb-2">Despre Mine</h2>
            <p class="leading-relaxed text-lg font-light">
                Mă numesc Beatrice și pasiunea mea pentru yoga a început în New York, trecând prin experiențe în Italia și Moldova. Astăzi, îmi doresc să aduc aceste tehnici de relaxare și mișcare liberă în comunitatea noastră.
            </p>
            <p class="italic text-[#8c9c82]">"Yoga este despre regăsirea liniștii interioare prin mișcări blânde și conștiente."</p>
        </div>
    </section>

    <section id="clase" class="py-16 bg-white/30">
        <div class="max-w-5xl mx-auto px-6 text-center">
            <h2 class="text-3xl mb-12 uppercase tracking-[0.3em]">Clase</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 gap-6">
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-spa text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Hatha Yoga</span>
                </div>
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-om text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Meditație</span>
                </div>
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-tree text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Yoga în Parc</span>
                </div>
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-wind text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Respirație</span>
                </div>
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-heart text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Privat</span>
                </div>
                <div class="clasa-card p-6 flex flex-col items-center gap-3">
                    <i class="fas fa-leaf text-2xl text-[#8c9c82]"></i>
                    <span class="text-xs uppercase tracking-widest">Flow</span>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 px-6">
        <div class="max-w-3xl mx-auto bg-[#b4c4ab] rounded-[40px] p-8 md:p-12 text-center text-white shadow-2xl">
            <div class="w-20 h-20 mx-auto rounded-full overflow-hidden border-4 border-white mb-6">
                 <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=200" class="w-full h-full object-cover" alt="Profile">
            </div>
            <h2 class="text-3xl font-serif mb-4 uppercase tracking-widest">Contact & Înregistrare</h2>
            <p class="mb-8 font-light italic">Alătură-te Comunității Noastre! Trimite-mi un mesaj pentru o clasă de probă gratuită.</p>
            
            <div class="space-y-4 mb-8 text-sm">
                <p class="tracking-widest">EMAIL: beatricenicolau96@gmail.com</p>
                <p class="tracking-widest font-bold">TELEFON: +373 60 404 887</p>
            </div>

            <div class="flex justify-center gap-6 text-2xl">
                <a href="https://www.instagram.com/easy_yoga33" target="_blank" class="hover:scale-110 transition"><i class="fab fa-instagram"></i></a>
                <a href="https://wa.me/37360404887" class="hover:scale-110 transition"><i class="fab fa-whatsapp"></i></a>
                <a href="https://www.tiktok.com/@easy_yoga33" target="_blank" class="hover:scale-110 transition"><i class="fab fa-tiktok"></i></a>
            </div>
        </div>
    </section>

    <footer class="py-10 text-center text-stone-400 text-[10px] uppercase tracking-[0.4em]">
        © 2026 Easy Yoga • Beatrice • Moldova
    </footer>

</body>
</html>
