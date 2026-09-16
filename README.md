<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan Nuraida Turnip & Johan yusuf nasution</title>
    <!-- Google Fonts & Tailwind CSS untuk desain cepat -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Poppins', sans-serif; }
        .font-script { font-family: 'Great Vibes', cursive; }
    </style>
</head>
<body class="bg-stone-50 text-stone-800">

    <!-- COVER / HALAMAN DEPAN -->
    <div id="cover" class="fixed inset-0 z-50 bg-stone-900 text-white flex flex-col items-center justify-center text-center p-6 transition-all duration-700">
        <h2 class="text-xl tracking-widest uppercase mb-2 text-amber-200">The Wedding Of</h2>
        <h1 class="font-script text-6xl md:text-7xl mb-6 text-amber-100">Nuraida Turnip & Johan yusuf Nasution</h1>
        <p class="text-sm text-stone-300 mb-8">Kepada Yth. Bapak/Ibu/Saudara/i</p>
        <div id="nama-tamu" class="bg-white/10 px-6 py-2 rounded-full text-amber-200 font-semibold mb-8 border border-amber-200/30">
            Tamu Undangan
        </div>
        <button onclick="bukaUndangan()" class="bg-amber-600 hover:bg-amber-700 text-white px-8 py-3 rounded-full font-medium shadow-lg transition transform hover:scale-105">
            ✉️ Buka Undangan
        </button>
    </div>

    <!-- KONTEN UTAMA WEBSITE -->
    <div class="max-w-md mx-auto bg-white shadow-2xl min-h-screen relative">
        
        <!-- HEADER / HERO -->
        <div class="relative h-[500px] bg-cover bg-center flex items-end justify-center pb-12 text-center" style="background-image: url('https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80')">
            <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-black/20 to-transparent"></div>
            <div class="relative z-10 text-white px-4">
                <p class="text-sm uppercase tracking-widest text-amber-200 mb-1">Pernikahan Kami</p>
                <h1 class="font-script text-5xl mb-2">Dika & Siti</h1>
                <p class="text-sm text-stone-200">18 Desember 2026</p>
            </div>
        </div>

        <!-- MEMPELAI -->
        <div class="py-16 px-6 text-center">
            <h2 class="font-script text-4xl text-amber-800 mb-4">Assalamu’alaikum Wr. Wb.</h2>
            <p class="text-sm text-stone-600 mb-10 leading-relaxed">
                Tanpa mengurangi rasa hormat, kami bermaksud mengundang Bapak/Ibu/Saudara/i sekalian untuk menghadiri acara pernikahan kami.
            </p>

            <div class="mb-8">
                <h3 class="font-script text-3xl text-amber-900 mb-1">Nurayda Turnip, S.Kom</h3>
                <p class="text-xs text-stone-500">Putri dari Bpk. Rahman Turnip & Ibu Nurleli Nasution</p>
            </div>

            <div class="text-3xl font-script text-amber-700 my-4">&</div>

            <div class="mb-6">
                <h3 class="font-script text-3xl text-amber-900 mb-1">Johan yusuf Nasution,</h3>
                <p class="text-xs text-stone-500">Putra dari Bpk. Abd. Azis Nasution & Ibu Nuraini</p>
            </div>
        </div>

        <!-- HITUNG MUNDUR (COUNTDOWN) -->
        <div class="bg-amber-50 py-12 px-6 text-center">
            <h3 class="text-lg font-semibold text-amber-900 mb-6">Menuju Hari Bahagia</h3>
            <div class="flex justify-center gap-4 text-amber-900">
                <div class="bg-white p-3 rounded-lg shadow w-16"><span id="days" class="block text-xl font-bold">00</span><span class="text-xs">Hari</span></div>
                <div class="bg-white p-3 rounded-lg shadow w-16"><span id="hours" class="block text-xl font-bold">00</span><span class="text-xs">Jam</span></div>
                <div class="bg-white p-3 rounded-lg shadow w-16"><span id="minutes" class="block text-xl font-bold">00</span><span class="text-xs">Menit</span></div>
                <div class="bg-white p-3 rounded-lg shadow w-16"><span id="seconds" class="block text-xl font-bold">00</span><span class="text-xs">Detik</span></div>
            </div>
        </div>

        <!-- ACARA & LOKASI -->
        <div class="py-16 px-6 text-center border-t border-stone-100">
            <h2 class="font-script text-4xl text-amber-800 mb-8">Waktu & Tempat</h2>
            
            <div class="bg-stone-50 p-6 rounded-2xl shadow-sm mb-6 border border-stone-200">
                <h4 class="font-semibold text-lg text-amber-900 mb-2">Akad Nikah</h4>
                <p class="text-sm text-stone-600 mb-1">Sabtu, 18 Desember 2026</p>
                <p class="text-sm text-stone-600 mb-4">Pukul 08.00 WIB</p>
                <p class="text-xs text-stone-500 mb-4">Gedung Graha Sabha Lantai 2<br>Jl. Melati No. 12, Kota Anda</p>
                <a href="https://maps.google.com" target="_blank" class="inline-block bg-amber-700 text-white text-xs px-4 py-2 rounded-full font-medium hover:bg-amber-800">📍 Buka Google Maps</a>
            </div>

            <div class="bg-stone-50 p-6 rounded-2xl shadow-sm border border-stone-200">
                <h4 class="font-semibold text-lg text-amber-900 mb-2">Resepsi</h4>
                <p class="text-sm text-stone-600 mb-1">Sabtu, 18 Desember 2026</p>
                <p class="text-sm text-stone-600 mb-4">Pukul 11.00 - 13.00 WIB</p>
                <p class="text-xs text-stone-500 mb-4">Gedung Graha Sabha Lantai 2<br>Jl. Melati No. 12, Kota Anda</p>
                <a href="https://maps.google.com" target="_blank" class="inline-block bg-amber-700 text-white text-xs px-4 py-2 rounded-full font-medium hover:bg-amber-800">📍 Buka Google Maps</a>
            </div>
        </div>

        <!-- FOOTER -->
        <footer class="bg-stone-900 text-stone-400 py-8 text-center text-xs">
            <p class="mb-2 font-script text-2xl text-amber-200">Terima Kasih</p>
            <p>Merupakan suatu kehormatan dan kebahagiaan bagi kami...</p>
            <p class="mt-6 text-stone-600">© 2026 Dika & Siti Digital Invitation</p>
        </footer>

    </div>

    <!-- AUDIO LATAR (BACKGROUND MUSIC) -->
    <audio id="bg-music" loop>
        <source src="https://www.bensound.com/bensound-music/bensound-tenderness.mp3" type="audio/mpeg">
    </audio>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Ambil nama tamu dari URL (contoh: ?to=Budi)
        const urlParams = new URLSearchParams(window.location.search);
        const namaTamu = urlParams.get('to');
        if (namaTamu) {
            document.getElementById('nama-tamu').innerText = decodeURIComponent(namaTamu);
        }

        // Fungsi Buka Undangan
        function bukaUndangan() {
            const cover = document.getElementById('cover');
            cover.style.transform = 'translateY(-100%)';
            const music = document.getElementById('bg-music');
            music.play();
        }

        // Hitung Mundur (Countdown Timer)
        const countDownDate = new Date("Dec 18, 2026 08:00:00").getTime();
        setInterval(function() {
            const now = new Date().getTime();
            const distance = countDownDate - now;

            document.getElementById("days").innerText = Math.floor(distance / (1000 * 60 * 60 * 24));
            document.getElementById("hours").innerText = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            document.getElementById("minutes").innerText = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            document.getElementById("seconds").innerText = Math.floor((distance % (1000 * 60)) / 1000);
        }, 1000);
    </script>
</body>
</html>
# undangan-digital