<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Núcleo Sonoro Estudio IA</title>
    <!-- Tailwind CSS para diseño moderno -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: system-ui, -apple-system, sans-serif;
            color: #f3f4f6;
            background-color: #0d1117;
        }
        /* Contenedor del fondo Vanta.js */
        #vanta-background {
            position: fixed;
            width: 100vw;
            height: 100vh;
            top: 0;
            left: 0;
            z-index: -1;
        }
        .glass-card {
            background: rgba(13, 17, 23, 0.75);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body class="overflow-x-hidden">

    <!-- Fondo Interactivo Vanta Birds -->
    <div id="vanta-background"></div>

    <!-- Navegación -->
    <header class="fixed top-0 left-0 w-full z-50 glass-card">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <!-- Espacio para tu logo -->
                <img src="logo.png" alt="Logo Núcleo Sonoro" class="h-10 w-auto object-contain" onerror="this.style.display='none'">
                <span class="font-bold text-lg tracking-wider text-white">NÚCLEO SONORO <span class="text-emerald-400">ESTUDIO IA</span></span>
            </div>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#inicio" class="hover:text-emerald-400 transition">Inicio</a>
                <a href="#estudio" class="hover:text-emerald-400 transition">Estudio</a>
                <a href="#metodologia" class="hover:text-emerald-400 transition">Metodología</a>
                <a href="#galeria" class="hover:text-emerald-400 transition">Galería</a>
                <a href="#contacto" class="hover:text-emerald-400 transition">Contacto</a>
            </nav>
        </div>
    </header>

    <!-- Sección Principal / Hero -->
    <section id="inicio" class="min-h-screen flex items-center justify-center text-center px-6 pt-20">
        <div class="max-w-3xl glass-card p-10 rounded-2xl shadow-2xl">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 tracking-tight">
                El Futuro del Sonido y la Inteligencia Artificial
            </h1>
            <p class="text-lg md:text-xl text-gray-300 mb-8">
                Consultoría y desarrollo de proyectos de vanguardia basados en Bogotá, Colombia. Atención exclusiva con cita previa.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="https://wa.me/573144052859" target="_blank" class="bg-emerald-600 hover:bg-emerald-500 text-white font-semibold px-8 py-3 rounded-xl transition shadow-lg">
                    Agendar por WhatsApp
                </a>
                <a href="#contacto" class="glass-card hover:bg-white/10 text-white font-semibold px-8 py-3 rounded-xl transition">
                    Contacto Directo
                </a>
            </div>
        </div>
    </section>

    <!-- Sección Metodología -->
    <section id="metodologia" class="py-24 px-6 max-w-7xl mx-auto">
        <div class="glass-card p-8 md:p-12 rounded-2xl">
            <h2 class="text-3xl font-bold mb-6 text-emerald-400">Metodología de Trabajo</h2>
            <p class="text-gray-300 leading-relaxed text-lg">
                Fusionamos la ingeniería de software de alto nivel con estrategias creativas de ejecución rápida (Vibe Coding). Cada solución está diseñada a la medida para garantizar un impacto profundo y sostenible.
            </p>
        </div>
    </section>

    <!-- Sección Galería (Espacio para tus 16 imágenes) -->
    <section id="galeria" class="py-24 px-6 max-w-7xl mx-auto">
        <h2 class="text-3xl font-bold mb-10 text-center">Nuestra Experiencia Visual</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6">
            <!-- Ejemplo de carga de imágenes (reemplaza 'foto-01.jpg' con los nombres reales de tus archivos subidos a GitHub) -->
            <div class="glass-card rounded-xl overflow-hidden h-48 flex items-center justify-center border border-white/10">
                <img src="foto-01.jpg" alt="Proyecto 1" class="w-full h-full object-cover" onerror="this.parentElement.innerHTML='<span class=\'text-xs text-gray-500\'>Imagen 01</span>'">
            </div>
            <div class="glass-card rounded-xl overflow-hidden h-48 flex items-center justify-center border border-white/10">
                <img src="foto-02.jpg" alt="Proyecto 2" class="w-full h-full object-cover" onerror="this.parentElement.innerHTML='<span class=\'text-xs text-gray-500\'>Imagen 02</span>'">
            </div>
            <div class="glass-card rounded-xl overflow-hidden h-48 flex items-center justify-center border border-white/10">
                <img src="foto-03.jpg" alt="Proyecto 3" class="w-full h-full object-cover" onerror="this.parentElement.innerHTML='<span class=\'text-xs text-gray-500\'>Imagen 03</span>'">
            </div>
            <div class="glass-card rounded-xl overflow-hidden h-48 flex items-center justify-center border border-white/10">
                <img src="foto-04.jpg" alt="Proyecto 4" class="w-full h-full object-cover" onerror="this.parentElement.innerHTML='<span class=\'text-xs text-gray-500\'>Imagen 04</span>'">
            </div>
        </div>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto" class="py-24 px-6 max-w-4xl mx-auto text-center">
        <div class="glass-card p-10 rounded-2xl">
            <h2 class="text-3xl font-bold mb-6">Iniciemos tu Proyecto</h2>
            <p class="text-gray-300 mb-6">Bogotá, Colombia | Atención exclusiva con cita previa</p>
            <p class="text-emerald-400 font-mono text-lg mb-2">WhatsApp: +57 314 405 2859</p>
            <p class="text-gray-400 font-mono">Email: nucleosonoro@gmail.com</p>
        </div>
    </section>

    <!-- Scripts de Three.js y Vanta.js (Birds) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.birds.min.js"></script>
    <script>
        VANTA.BIRDS({
          el: "#vanta-background",
          mouseControls: true,
          touchControls: true,
          gyroControls: false,
          minHeight: 200.00,
          minWidth: 200.00,
          scale: 1.00,
          scaleMobile: 1.00,
          color1: 0x382e27,
          color2: 0x314f46,
          cohesion: 5.00
        })
    </script>
</body>
</html>
