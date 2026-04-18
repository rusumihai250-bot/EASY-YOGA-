<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy Yoga | Beatrice</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #fdfcf9; color: #4a4a4a; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        .hero-fade {
            background: linear-gradient(to bottom, rgba(253,252,249,0) 0%, rgba(253,252,249,0.8) 80%, rgba(253,252,249,1) 100%);
        }
    </style>
</head>
<body>

    <nav class="p-6 flex justify-between items-center bg-white/80 backdrop-blur-md sticky top-0 z-50">
        <div class="text-xl tracking-widest uppercase font-light text-[#8c6d46]">Easy Yoga</div>
        <div class="hidden md:flex gap-8 text-[11px] uppercase tracking-widest font-medium">
            <a href="#acasa">Acasă</a>
            <a href="#despre">Despre Mine</a>
            <a href="#servicii">Ce oferim</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header id="acasa" class="relative w-full h-[80vh] flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0">
            <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=1200" class="w-full h-full object-cover" alt="Beatrice Yoga">
            <div class="absolute inset-0 hero-fade"></div>
        </div>
        <div class="relative z-10 text-center px-4">
            <h1 class="text-4xl md:text-6xl tracking-widest uppercase mb-4 text-white drop-shadow-lg">Bine ai venit la Easy Yoga</h1>
            <p class="text-xl md:text-2xl text-white italic font-light drop-shadow-md">Relaxare. Echilibru. Comunitate.</p>
        </div>
    </header>

    <section id="despre" class="py-20 px-6 max-w-4xl mx-auto text-center">
        <div class="w-48 h-48 rounded-full overflow-hidden border-[10px] border-white shadow-lg mx-auto mb-10">
            <img src="https://images.unsplash.com/photo-1599447421416-3414500d18a5?auto=format&fit=crop&w=400" class="w-full h-full object-cover" alt="Beatrice">
        </div>
        <h2 class="text-3xl uppercase tracking-widest mb-8 text-[#8c6d46]">Despre Mine</h2>
        <p class="text-lg leading-relaxed font-light text-stone-600 mb-6">
            Mă numesc Beatrice și am adus în Moldova experiența mea din Italia și New York. Din 2020, am descoperit cum respirația și mișcarea yoga pot transforma starea de bine.
        </p>
    </section>

    <section id="servicii" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6 text-center">
            <h2 class="text-5xl font-serif text-[#8c6d46] mb-20 uppercase tracking-widest">Ce oferim</h2>
            
            <div class="grid md:grid-cols-4 gap-12">
                <div class="space-y-6">
                    <div class="w-44 h-44 mx-auto rounded-full overflow-hidden border-4 border-[#f4eee5] shadow-md">
                        <img src="https://images.unsplash.com/photo-1544367567-0f2fcb009e0b?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Incepatori">
                    </div>
                    <h3 class="text-lg font-serif uppercase tracking-widest">Clasă pentru începători</h3>
                    <p class="text-sm text-stone-500">Exerciții blânde și ghidate pentru toate vârstele.</p>
                </div>

                <div class="space-y-6">
                    <div class="w-44 h-44 mx-auto rounded-full overflow-hidden border-4 border-[#f4eee5] shadow-md">
                        <img src="https://images.unsplash.com/photo-1599447421416-3414500d18a5?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Flow Yoga">
                    </div>
                    <h3 class="text-lg font-serif uppercase tracking-widest">Flow Yoga</h3>
                    <p class="text-sm text-stone-500">Secvențe ușoare pentru flexibilitate și respirație profundă.</p>
                </div>

                <div class="space-y-6">
                    <div class="w-44 h-44 mx-auto rounded-full overflow-hidden border-4 border-[#f4eee5] shadow-md">
                        <img src="https://images.unsplash.com/photo-1506126613408-eca07ce68773?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Posture">
                    </div>
                    <h3 class="text-lg font-serif uppercase tracking-widest">Posture de Yoga</h3>
                    <p class="text-sm text-stone-500">Echilibru pentru corp și minte, corectat la fiecare pas.</p>
                </div>

                <div class="space-y-6">
                    <div class="w-44 h-44 mx-auto rounded-full overflow-hidden border-4 border-[#f4eee5] shadow-md">
                        <img src="https://images.unsplash.com/photo-1510894347713-fc3ed6fdf539?auto=format&fit=crop&w=300" class="w-full h-full object-cover" alt="Miscare Libera">
                    </div>
                    <h3 class="text-lg font-serif uppercase tracking-widest">Mișcare Liberă</h3>
                    <p class="text-sm text-stone-500">Mișcări ghidate de instinct în sintonie cu corpul tău.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-20 px-6">
        <div class="max-w-4xl mx-auto bg-[#c5d1bc] rounded-[40px] p-12 text-center text-white">
            <h2 class="text-3xl uppercase tracking-widest mb-6">Contact & Înregistrare</h2>
            <p class="italic mb-10">Alătură-te Comunității Noastre!</p>
            <div class="space-y-2 mb-10 text-sm tracking-widest">
                <p>EMAIL: beatricenicolau96@gmail.com</p>
                <p>TELEFON: +373 60 404 887</p>
            </div>
            <div class="flex justify-center gap-10 text-2xl">
                <a href="https://instagram.com/easy_yoga33" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://wa.me/37360404887"><i class="fab fa-whatsapp"></i></a>
            </div>
        </div>
    </section>

</body>
</html>
