<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga | Beatrice</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Inter:wght@300;400;600&display=swap');
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        h1, h2, h3, .font-serif { font-family: 'Playfair Display', serif; }
        .bg-cream { background-color: #fdfcf9; }
        .text-gold { color: #8c6d46; }
        .bg-gold { background-color: #8c6d46; }
        .card-shadow { box-shadow: 0 10px 30px rgba(140, 109, 70, 0.05); }
    </style>
</head>
<body class="bg-cream text-stone-800">

    <nav class="p-6 flex justify-between items-center bg-white/90 backdrop-blur-md sticky top-0 z-50 shadow-sm">
        <div class="text-2xl font-serif font-bold tracking-tight text-gold">EASY YOGA</div>
        <div class="hidden md:flex space-x-8 text-sm uppercase tracking-[0.2em]">
            <a href="#poveste" class="hover:text-gold transition">Povestea Mea</a>
            <a href="#servicii" class="hover:text-gold transition">Ce oferim</a>
            <a href="#studio" class="hover:text-gold transition">Studio</a>
        </div>
        <div class="flex space-x-4">
            <a href="https://www.instagram.com/easy_yoga33" target="_blank" class="text-stone-600 hover:text-pink-600"><i class="fab fa-instagram text-xl"></i></a>
            <a href="https://www.tiktok.com/@easy_yoga33" target="_blank" class="text-stone-600 hover:text-black"><i class="fab fa-tiktok text-xl"></i></a>
        </div>
    </nav>

    <header class="relative h-[60vh] flex items-center justify-center text-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="http://googleusercontent.com/generated_image_content/0" class="w-full h-full object-cover" alt="Beatrice Yoga">
            <div class="absolute inset-0 bg-black/20"></div>
        </div>
        <div class="relative z-10 text-white px-4">
            <h1 class="text-6xl md:text-7xl font-serif mb-4 drop-shadow-lg">Bună, sunt Beatrice</h1>
            <p class="text-xl font-light italic tracking-[0.2em] uppercase">Yoga • Mișcare • Echilibru</p>
        </div>
    </header>

    <section class="py-20 px-6 max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-12">
        <div class="md:w-1/2 space-y-8">
            <p class="text-2xl font-serif text-stone-600 leading-relaxed italic">
                "Adevărata stare de bine vine dintr-o sănătate fizică și mentală. Ai grijă de ambele cu o rutină de yoga care îți dezvoltă forța, flexibilitatea și echilibrul."
            </p>
            <a href="https://wa.me/37360404887" class="inline-block bg-[#6b5235] text-white px-10 py-4 rounded-md font-semibold tracking-widest hover:bg-stone-800 transition">
                Înscrie-te la o clasă
            </a>
        </div>
        <div class="md:w-1/2 flex gap-4">
            <img src="https://images.unsplash.com/photo-1552196564-972b2013f901?auto=format&fit=crop&w=400" class="w-1/2 rounded-sm shadow-xl" alt="Yoga 1">
            <img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773?auto=format&fit=crop&w=400" class="w-1/2 rounded-sm shadow-xl translate-y-8" alt="Yoga 2">
        </div>
    </section>

    <section id="servicii" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-5xl font-serif text-gold text-center mb-20">Ce oferim</h2>
            
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center space-y-6">
                    <div class="w-48 h-48 mx-auto rounded-full overflow-hidden border-8 border-[#f4eee5] shadow-inner">
                        <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Începători">
                    </div>
                    <h3 class="text-xl font-serif uppercase tracking-widest text-gold">Clasă pentru începători</h3>
                    <p class="text-sm text-stone-500 leading-relaxed">Perfectă pentru toate vârstele. Vei practica exerciții blânde și ghidate pentru o înțelegere rapidă și profundă.</p>
                    <a href="#" class="text-xs font-bold tracking-widest border-b border-gold pb-1 hover:text-gold">MAI MULT</a>
                </div>

                <div class="text-center space-y-6">
                    <div class="w-48 h-48 mx-auto rounded-full overflow-hidden border-8 border-[#f4eee5] shadow-inner">
                        <img src="https://images.unsplash.com/photo-1599447421416-3414500d18a5?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Flow Yoga">
                    </div>
                    <h3 class="text-xl font-serif uppercase tracking-widest text-gold">Flow Yoga</h3>
                    <p class="text-sm text-stone-500 leading-relaxed">Secvență ușoară ghidată pas cu pas pentru flexibilitate, respirație și relaxare în același timp.</p>
                    <a href="#" class="text-xs font-bold tracking-widest border-b border-gold pb-1 hover:text-gold">MAI MULT</a>
                </div>

                <div class="text-center space-y-6">
                    <div class="w-48 h-48 mx-auto rounded-full overflow-hidden border-8 border-[#f4eee5] shadow-inner">
                        <img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Posture">
                    </div>
                    <h3 class="text-xl font-serif uppercase tracking-widest text-gold">Posture de Yoga</h3>
                    <p class="text-sm text-stone-500 leading-relaxed">Poziții perfecte pentru echilibrul corpului și minții. Vei fi îndrumat și corectat la fiecare pas.</p>
                    <a href="#" class="text-xs font-bold tracking-widest border-b border-gold pb-1 hover:text-gold">MAI MULT</a>
                </div>

                <div class="text-center space-y-6">
                    <div class="w-48 h-48 mx-auto rounded-full overflow-hidden border-8 border-[#f4eee5] shadow-inner">
                        <img src="https://images.unsplash.com/photo-1510894347713-fc3ed6fdf539?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Mișcare Liberă">
                    </div>
                    <h3 class="text-xl font-serif uppercase tracking-widest text-gold">Mișcare Liberă</h3>
                    <p class="text-sm text-stone-500 leading-relaxed">Lăsăm corpul să facă mișcări ghidate de instinct, fără poziții stricte, în sintonie cu ritmul propriu.</p>
                    <a href="#" class="text-xs font-bold tracking-widest border-b border-gold pb-1 hover:text-gold">MAI MULT</a>
                </div>
            </div>
        </div>
    </section>

    <section id="studio" class="py-24 px-6 bg-[#f4eee5]">
        <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-16">
            <div class="space-y-6">
                <h2 class="text-3xl font-serif text-gold uppercase tracking-widest">Studio Principal</h2>
                <p class="text-xl font-light italic text-stone-500 underline decoration-gold/30">Adresa va fi comunicată în curând.</p>
                <div class="pt-4 space-y-3 font-light text-stone-600 text-lg">
                    <p><i class="fas fa-envelope text-gold mr-3"></i> beatricenicolau96@gmail.com</p>
                    <p><i class="fas fa-phone text-gold mr-3"></i> +373 60 404 887</p>
                </div>
            </div>
            <div class="bg-white p-10 rounded-2xl shadow-sm">
                <h3 class="text-2xl font-serif mb-6 text-gold uppercase tracking-widest border-b pb-4">Orele Studioului</h3>
                <div class="flex justify-between text-lg text-stone-600">
                    <span>Luni - Duminică</span>
                    <span class="font-bold">8:00 - 20:00</span>
                </div>
                <p class="mt-8 text-xs text-stone-400 uppercase tracking-widest italic leading-relaxed">
                    Clasele speciale sunt valabile pe comandă
                </p>
            </div>
        </div>
    </section>

    <footer class="py-16 text-center border-t border-stone-100 bg-white">
        <div class="flex justify-center gap-8 mb-8 text-2xl text-stone-400">
            <a href="https://www.tiktok.com/@easy_yoga33" target="_blank" class="hover:text-black transition"><i class="fab fa-tiktok"></i></a>
            <a href="https://www.instagram.com/easy_yoga33" target="_blank" class="hover:text-pink-700 transition"><i class="fab fa-instagram"></i></a>
            <a href="https://wa.me/37360404887" class="hover:text-green-600 transition"><i class="fab fa-whatsapp"></i></a>
        </div>
        <p class="text-stone-300 text-[10px] uppercase tracking-[0.5em]">© 2026 Easy Yoga • Beatrice • Moldova</p>
    </footer>

</body>
</html>
