## Hi there 👋
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kampung Al-Hamdi | Resto & Coffee Shop</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
    </style>
</head>
<body class="bg-[#FAF6F0] text-gray-800">

    <!-- NAVBAR -->
    <nav class="fixed w-full z-50 bg-[#1E1B18]/90 backdrop-blur-md text-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <!-- Gunakan logo Kampung Al-Hamdi -->
                <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center overflow-hidden">
                    <span class="font-bold text-red-600 text-xs text-center leading-none">AL<br>HAMDI</span>
                </div>
                <span class="font-extrabold text-lg tracking-wider text-yellow-500">KAMPUNG AL-HAMDI</span>
            </div>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#home" class="hover:text-yellow-500 transition">Beranda</a>
                <a href="#about" class="hover:text-yellow-500 transition">Tentang Kami</a>
                <a href="#menu" class="hover:text-yellow-500 transition">Menu Andalan</a>
                <a href="#kontak" class="hover:text-yellow-500 transition">Kontak</a>
            </div>
            <a href="https://wa.me/6287750760235" target="_blank" class="bg-emerald-600 hover:bg-emerald-700 text-white px-4 py-2 rounded-full font-semibold flex items-center gap-2 transition text-sm">
                <i class="fab fa-whatsapp text-lg"></i> Tanya Admin
            </a>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section id="home" class="relative min-h-screen flex items-center justify-center bg-cover bg-center pt-16" style="background-image: linear-gradient(to bottom, rgba(0,0,0,0.5), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&q=80&w=1200');">
        <div class="text-center text-white px-4 max-w-3xl">
            <span class="text-yellow-500 font-bold uppercase tracking-widest text-sm bg-yellow-500/10 px-4 py-2 rounded-full">Resto & Coffee Shop</span>
            <h1 class="text-4xl md:text-6xl font-extrabold mt-6 mb-4 tracking-tight leading-tight">Makan Nikmat, Ngopi Syahdu dengan <span class="text-red-500">View Gunung Indah</span></h1>
            <p class="text-gray-300 text-base md:text-lg mb-8">Nikmati kelezatan Nasi Kebuli otentik, Ayam Bakar lezat, pizza, dan segarnya racikan kopi premium kami langsung di atas awan dengan pemandangan pegunungan yang memanjakan mata.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#menu" class="bg-red-600 hover:bg-red-700 text-white font-bold px-8 py-3 rounded-full transition shadow-lg">Lihat Menu</a>
                <a href="https://maps.app.goo.gl/tKtS23jLEMjaqtHJ9?g_st=ac" target="_blank" class="bg-transparent border-2 border-white hover:bg-white hover:text-black font-bold px-8 py-3 rounded-full transition flex items-center gap-2">
                    <i class="fas fa-map-marker-alt text-red-500"></i> Petunjuk Arah (Maps)
                </a>
            </div>
        </div>
    </section>

    <!-- TENTANG KAMI -->
    <section id="about" class="py-20 px-4 max-w-6xl mx-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="relative">
                <!-- Menggunakan mockup suasana outdoor dengan view gunung -->
                <div class="rounded-2xl overflow-hidden shadow-2xl border-4 border-white transform hover:scale-105 transition duration-500">
                    <img src="https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&q=80&w=800" alt="Suasana Kampung Al-Hamdi" class="w-full h-[400px] object-cover">
                </div>
                <div class="absolute -bottom-6 -right-6 bg-red-600 text-white p-6 rounded-xl hidden md:block shadow-lg">
                    <p class="text-2xl font-bold">100% Halal</p>
                    <p class="text-sm text-gray-200">Bahan Alami & Higienis</p>
                </div>
            </div>
            <div>
                <span class="text-red-600 font-bold uppercase tracking-wider text-sm">Tentang Kampung Al-Hamdi</span>
                <h2 class="text-3xl md:text-4xl font-extrabold text-[#1E1B18] mt-2 mb-6">Tempat Terbaik untuk Berkumpul Bersama Keluarga & Teman</h2>
                <p class="text-gray-600 mb-6 leading-relaxed">
                    Kampung Al-Hamdi memadukan konsep restoran keluarga dengan tempat nongkrong anak muda yang estetik. Berlokasi di area dengan pemandangan pegunungan hijau yang asri, kami menyajikan hidangan bercita rasa tinggi mulai dari makanan berat khas timur tengah & nusantara, hingga racikan kopi kekinian.
                </p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="flex items-center gap-3">
                        <i class="fas fa-coffee text-amber-700 text-2xl"></i>
                        <span class="font-semibold text-gray-700">Kopi Premium</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <i class="fas fa-mountain text-green-600 text-2xl"></i>
                        <span class="font-semibold text-gray-700">View Gunung Estetik</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <i class="fas fa-wifi text-blue-500 text-2xl"></i>
                        <span class="font-semibold text-gray-700">Free WiFi</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <i class="fas fa-parking text-yellow-600 text-2xl"></i>
                        <span class="font-semibold text-gray-700">Parkir Luas</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- MENU ANDALAN -->
    <section id="menu" class="py-20 bg-[#1E1B18] text-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-yellow-500 font-bold uppercase tracking-wider text-sm">Menu Spesial Kami</span>
                <h2 class="text-3xl md:text-4xl font-extrabold mt-2 mb-4">Paling Favorit di Kampung Al-Hamdi</h2>
                <p class="text-gray-400">Dari racikan kopi segar hingga hidangan kaya rempah yang siap memanjakan lidah Anda.</p>
            </div>

            <!-- Grid Menu -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Menu 1 -->
                <div class="bg-zinc-900 rounded-2xl overflow-hidden shadow-xl hover:-translate-y-2 transition duration-300">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1541518763669-27fef04b14ea?auto=format&fit=crop&q=80&w=600');"></div>
                    <div class="p-6">
                        <span class="text-xs bg-red-600 text-white px-3 py-1 rounded-full font-bold">Makanan Utama</span>
                        <h3 class="text-xl font-bold mt-3 mb-2">Nasi Kebuli Kambing / Ayam</h3>
                        <p class="text-gray-400 text-sm mb-4">Nasi rempah khas timur tengah yang gurih disajikan dengan daging empuk, kismis, almond, dan sambal spesial.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-yellow-500 font-extrabold text-lg">Menu Spesial</span>
                            <a href="https://wa.me/6287750760235?text=Halo%20Kampung%20Al-Hamdi,%20saya%20mau%20pesan%20Nasi%20Kebuli" class="text-sm bg-yellow-500 hover:bg-yellow-600 text-black px-4 py-2 rounded-lg font-bold transition">Pesan Sekarang</a>
                        </div>
                    </div>
                </div>

                <!-- Menu 2 -->
                <div class="bg-zinc-900 rounded-2xl overflow-hidden shadow-xl hover:-translate-y-2 transition duration-300">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1513530534585-c7b1394c6d51?auto=format&fit=crop&q=80&w=600');"></div>
                    <div class="p-6">
                        <span class="text-xs bg-amber-600 text-white px-3 py-1 rounded-full font-bold">Kopi & Minuman</span>
                        <h3 class="text-xl font-bold mt-3 mb-2">Ice Coffee Milk Al-Hamdi</h3>
                        <p class="text-gray-400 text-sm mb-4">Racikan kopi susu premium khas Al-Hamdi dengan gula aren murni. Segar, creamy, dan bikin melek seharian.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-yellow-500 font-extrabold text-lg">Best Seller</span>
                            <a href="https://wa.me/6287750760235?text=Halo%20Kampung%20Al-Hamdi,%20saya%20mau%20pesan%20Es%20Kopi%20Susu" class="text-sm bg-yellow-500 hover:bg-yellow-600 text-black px-4 py-2 rounded-lg font-bold transition">Pesan Sekarang</a>
                        </div>
                    </div>
                </div>

                <!-- Menu 3 -->
                <div class="bg-zinc-900 rounded-2xl overflow-hidden shadow-xl hover:-translate-y-2 transition duration-300">
                    <div class="h-64 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&q=80&w=600');"></div>
                    <div class="p-6">
                        <span class="text-xs bg-orange-600 text-white px-3 py-1 rounded-full font-bold">Cemilan</span>
                        <h3 class="text-xl font-bold mt-3 mb-2">Pizza & Crispy Snacks</h3>
                        <p class="text-gray-400 text-sm mb-4">Pizza panggang hangat dengan keju meleleh, pisang cokelat keju crispy, cocok menemani waktu santai Anda.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-yellow-500 font-extrabold text-lg">Favorit</span>
                            <a href="https://wa.me/6287750760235?text=Halo%20Kampung%20Al-Hamdi,%20saya%20mau%20pesan%20Pizza/Snack" class="text-sm bg-yellow-500 hover:bg-yellow-600 text-black px-4 py-2 rounded-lg font-bold transition">Pesan Sekarang</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- KONTAK & LOKASI -->
    <section id="kontak" class="py-20 px-4 bg-white text-gray-800">
        <div class="max-w-6xl mx-auto">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-red-600 font-bold uppercase tracking-wider text-sm">Hubungi Kami</span>
                <h2 class="text-3xl md:text-4xl font-extrabold mt-2 mb-4">Kunjungi Kampung Al-Hamdi</h2>
                <p class="text-gray-600">Silakan reservasi tempat atau pesan antar melalui nomor WhatsApp kami, atau langsung kunjungi lokasi kami.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <!-- Info Detail -->
                <div class="space-y-8">
                    <div class="bg-[#FAF6F0] p-6 rounded-2xl border border-gray-100 flex items-start gap-4">
                        <div class="bg-red-100 text-red-600 p-3 rounded-full">
                            <i class="fas fa-map-marked-alt text-2xl"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-lg mb-1">Alamat</h4>
                            <p class="text-gray-600 mb-3">Sila klik tombol di bawah untuk melihat rute langsung via Google Maps:</p>
                            <a href="https://maps.app.goo.gl/tKtS23jLEMjaqtHJ9?g_st=ac" target="_blank" class="inline-flex items-center gap-2 bg-red-600 text-white font-semibold px-4 py-2 rounded-lg text-sm hover:bg-red-700 transition">
                                <i class="fas fa-location-arrow"></i> Buka Google Maps
                            </a>
                        </div>
                    </div>

                    <div class="bg-[#FAF6F0] p-6 rounded-2xl border border-gray-100 flex items-start gap-4">
                        <div class="bg-emerald-100 text-emerald-600 p-3 rounded-full">
                            <i class="fab fa-whatsapp text-2xl"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-lg mb-1">WhatsApp Admin</h4>
                            <p class="text-gray-600 mb-3">Butuh booking tempat acara atau tanya ketersediaan menu?</p>
                            <a href="https://wa.me/6287750760235" target="_blank" class="inline-flex items-center gap-2 bg-emerald-600 text-white font-semibold px-4 py-2 rounded-lg text-sm hover:bg-emerald-700 transition">
                                <i class="fab fa-whatsapp"></i> Hubungi 0877-5076-0235
                            </a>
                        </div>
                    </div>

                    <div class="bg-[#FAF6F0] p-6 rounded-2xl border border-gray-100 flex items-start gap-4">
                        <div class="bg-amber-100 text-amber-600 p-3 rounded-full">
                            <i class="far fa-clock text-2xl"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-lg mb-1">Jam Operasional</h4>
                            <p class="text-gray-600 font-medium">Setiap Hari: 10:00 - 22:00 WITA</p>
                        </div>
                    </div>
                </div>

                <!-- Google Maps Embed Visual Mockup (Alternatif Praktis) -->
                <div class="bg-gray-100 rounded-2xl overflow-hidden shadow-inner h-96 relative flex flex-col justify-center items-center p-6 text-center border-2 border-dashed border-gray-300">
                    <i class="fas fa-map-marker-alt text-red-600 text-5xl mb-4 animate-bounce"></i>
                    <h4 class="font-extrabold text-xl mb-2">Lokasi Kampung Al-Hamdi</h4>
                    <p class="text-gray-600 text-sm max-w-sm mb-6">Klik tombol di bawah ini untuk melihat navigasi jalan secara langsung dan akurat di Google Maps Anda.</p>
                    <a href="https://maps.app.goo.gl/tKtS23jLEMjaqtHJ9?g_st=ac" target="_blank" class="bg-red-600 hover:bg-red-700 text-white font-bold px-8 py-3 rounded-full transition shadow-lg">
                        Mulai Navigasi Sekarang
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-[#1E1B18] text-white py-12 border-t border-zinc-800">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <h3 class="font-extrabold text-2xl text-yellow-500 tracking-wider mb-4">KAMPUNG AL-HAMDI</h3>
            <p class="text-gray-400 text-sm max-w-md mx-auto mb-8">Tempat ternyaman untuk melepas penat bersama keluarga ditemani sajian nikmat & kopi berkualitas dengan view pegunungan.</p>
            <div class="flex justify-center space-x-6 mb-8 text-xl text-gray-400">
                <a href="https://wa.me/6287750760235" class="hover:text-emerald-500 transition"><i class="fab fa-whatsapp"></i></a>
                <a href="#" class="hover:text-red-500 transition"><i class="fab fa-instagram"></i></a>
                <a href="https://maps.app.goo.gl/tKtS23jLEMjaqtHJ9?g_st=ac" class="hover:text-yellow-500 transition"><i class="fas fa-map-marker-alt"></i></a>
            </div>
            <p class="text-xs text-gray-500">&copy; 2026 Kampung Al-Hamdi Resto & Coffee Shop. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>

<!--
**KAMPUNG-AL-HAMDI/Kampung-Al-Hamdi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
