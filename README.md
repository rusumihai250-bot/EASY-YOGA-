<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga | Beatrice</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=Inter:wght@300;400&display=swap');
        
        body { font-family: 'Inter', sans-serif; background-color: #f8f7f2; color: #4a4a4a; }
        h1, h2, h3, .nav-link { font-family: 'Playfair Display', serif; }
        
        .hero-gradient {
            background: linear-gradient(to bottom, rgba(248,247,242,0) 0%, rgba(248,247,242,0.8) 80%, rgba(248,247,242,1) 100%);
        }
        
        .class-card {
            background: #ffffff;
            border: 1px solid #e0ddd5;
            border-radius: 12px;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 8px;
            transition: all 0.3s ease;
        }

        .contact-box {
            background-color: #c5d1bc;
            border-radius: 25px;
        }
    </style>
</head>
<body>

    <nav class="p-6 flex justify-between items-center bg-[#f8f7f2]/90 sticky top-0 z-50">
        <div class="flex items-center gap-2">
            <img src="https://cdn-icons-png.flaticon.com/512/1047/1047461.png" class="w-6 h-6 opacity-40" alt="logo">
            <span class="text-xl tracking-widest uppercase font-light">Easy Yoga</span>
        </div>
        <div class="hidden md:flex gap-8 text-xs uppercase tracking-widest font-medium">
            <a href="#" class="border-b border-stone-800 pb-1">Acasă</a>
            <a href="#despre">Despre Mine</a>
            <a href="#clase">Clase</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header class="relative w-full h-[85vh] flex items-end justify-center overflow-hidden">
        <div class="absolute inset-0">
            <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=1200" class="w-full h-full object-cover object-center" alt="Beatrice Yoga">
            <div class="absolute inset-0 hero-gradient"></div>
        </div>
        
        <div class="relative z-10 text-center mb-16 px-4">
            <h1 class="text-3xl md:text-5xl tracking-widest uppercase mb-2">Bine ai venit la Easy Yoga</h1>
            <p class="text-lg md:text-xl font-light italic">Relaxare. Echilibru. Comunitate.</p>
        </div>
    </header>

    <section id="despre" class="py-20 px-6 max-w-4xl mx-auto text-center">
        <div class="w-40 h-40 md:w-48 md:h-48 rounded-full overflow-hidden border-8 border-white shadow-sm mx-auto mb-10">
            <img src="https://images.unsplash.com/photo-1599447421416-3414500d18a5?auto=format&fit=crop&w=400" class="w-full h-full object-cover" alt="Beatrice profile">
        </div>
        
        <div class="space-y-6">
            <h2 class="text-2xl uppercase tracking-[0.3em] mb-4">Despre Mine</h2>
            <p class="text-lg leading-relaxed font-light text-stone-600">
                Mă numesc Beatrice și călătoria mea a început din dorința de a aduce armonie corpului și minții. După ani petrecuți în Italia și SUA, m-am întors în Moldova pentru a împărtăși tehnici de yoga care îmbină mișcarea blândă cu respirația conștientă.
            </p>
            <p class="italic text-stone-500">"Yoga nu este despre perfecțiune, ci despre progres și liniște interioară."</p>
        </div>
    </section>

    <section id="clase" class="py-16 px-6 max-w-5xl mx-auto text-center">
        <h2 class="text-2xl uppercase tracking-[0.3em] mb-12">Clase</h2>
        <div class="grid grid-cols-2 md:grid-cols-3 gap-4 md:gap-6">
            <div class="class-card">
                <i class="fas fa-spa text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Hatha Yoga</span>
            </div>
            <div class="class-card">
                <i class="fas fa-moon text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Meditație</span>
            </div>
            <div class="class-card">
                <i class="fas fa-leaf text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Yoga în Parc</span>
            </div>
            <div class="class-card">
                <i class="fas fa-sun text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Flow Yoga</span>
            </div>
            <div class="class-card">
                <i class="fas fa-heart text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Meditație Ghidată</span>
            </div>
            <div class="class-card">
                <i class="fas fa-accessibility text-[#8c9c82]"></i>
                <span class="text-[10px] uppercase tracking-widest">Yoga Privat</span>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 px-6">
        <div class="max-w-3xl mx-auto contact-box p-10 flex flex-col md:flex-row items-center gap-10">
            <div class="w-32 h-32 rounded-full overflow-hidden border-4 border-white shrink-0">
                <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=200" class="w-full h-full object-cover" alt="Profile circle">
            </div>
            <div class="text-white text-center md:text-left">
                <h2 class="text-2xl uppercase tracking-widest mb-3">Contact & Înregistrare</h2>
                <p class="text-sm italic font-light mb-6">Alătură-te Comunității Noastre! Trimite-mi un mesaj sau programează-te pentru o clasă de probă gratuită.</p>
                <div class="text-[11px] tracking-widest space-y-1">
                    <p>EMAIL: beatricenicolau96@gmail.com</p>
                    <p>TELEFON: +373 60 404 887</p>
                </div>
                <div class="flex justify-center md:justify-start gap-4 mt-6 text-xl">
                    <a href="https://instagram.com/easy_yoga33" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://wa.me/37360404887"><i class="fab fa-whatsapp"></i></a>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-10 text-center text-[9px] uppercase tracking-[0.5em] text-stone-400">
        © 2026 Easy Yoga • Beatrice • Moldova
    </footer>

</body>
</html>
