<!DOCTYPE html>
<html lang="tr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gider Temizlik - İstanbul Çatalca Profesyonel Temizlik Hizmetleri</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0284c7',
                            600: '#0369a1',
                            700: '#075985',
                        }
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 dark:bg-slate-900 dark:text-slate-100 transition-colors duration-300 min-h-screen">

    <!-- Header / Navbar -->
    <header class="fixed top-0 left-0 w-full bg-white/90 dark:bg-slate-900/90 backdrop-blur-md z-50 border-b border-slate-200 dark:border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <a href="#" class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-xl bg-cyan-600 text-white flex items-center justify-center font-black text-xl shadow-lg shadow-cyan-500/30">
                        <i class="fas fa-sparkles"></i>
                    </div>
                    <div>
                        <span class="text-xl font-extrabold tracking-tight text-slate-900 dark:text-white block leading-none">GİDER</span>
                        <span class="text-xs font-semibold text-cyan-600 dark:text-cyan-400 tracking-widest uppercase">TEMİZLİK</span>
                    </div>
                </a>

                <nav class="hidden md:flex items-center space-x-8 text-sm font-semibold">
                    <a href="#hizmetler" class="hover:text-cyan-600 dark:hover:text-cyan-400 transition-colors">Hizmetlerimiz</a>
                    <a href="#hesaplama" class="hover:text-cyan-600 dark:hover:text-cyan-400 transition-colors">Fiyat Hesapla</a>
                    <a href="#hakkimizda" class="hover:text-cyan-600 dark:hover:text-cyan-400 transition-colors">Hakkımızda</a>
                    <a href="#iletisim" class="hover:text-cyan-600 dark:hover:text-cyan-400 transition-colors">İletişim</a>
                </nav>

                <div class="hidden lg:flex items-center space-x-4">
                    <a href="tel:05417891708" class="flex items-center space-x-2 text-sm font-bold text-slate-700 dark:text-slate-200 hover:text-cyan-600 dark:hover:text-cyan-400">
                        <i class="fas fa-phone-alt text-cyan-600 dark:text-cyan-400"></i>
                        <span>0541 739 17 08</span>
                    </a>
                    <a href="https://api.whatsapp.com/send?phone=905372891274&text=Merhaba,%20temizlik%20hizmeti%20almak%20istiyorum." target="_blank" class="px-4 py-2.5 bg-emerald-600 hover:bg-emerald-700 text-white font-semibold rounded-xl text-sm shadow-md transition-all flex items-center space-x-2">
                        <i class="fab fa-whatsapp text-lg"></i>
                        <span>WhatsApp Teklif</span>
                    </a>
                    <button id="theme-toggle" class="p-2.5 rounded-xl bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300">
                        <i id="theme-toggle-dark-icon" class="fas fa-moon hidden"></i>
                        <i id="theme-toggle-light-icon" class="fas fa-sun hidden"></i>
                    </button>
                </div>

                <div class="flex lg:hidden items-center space-x-3">
                    <button id="theme-toggle-mobile" class="p-2 rounded-lg bg-slate-100 dark:bg-slate-800 text-slate-600 dark:text-slate-300">
                        <i id="theme-toggle-dark-icon-mobile" class="fas fa-moon hidden"></i>
                        <i id="theme-toggle-light-icon-mobile" class="fas fa-sun hidden"></i>
                    </button>
                    <button id="mobile-menu-btn" class="p-2 text-slate-600 dark:text-slate-300">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <div id="mobile-menu" class="hidden lg:hidden bg-white dark:bg-slate-900 border-b border-slate-200 dark:border-slate-800 px-4 py-4 space-y-3">
            <a href="#hizmetler" class="mobile-link block font-medium">Hizmetlerimiz</a>
            <a href="#hesaplama" class="mobile-link block font-medium">Fiyat Hesapla</a>
            <a href="#hakkimizda" class="mobile-link block font-medium">Hakkımızda</a>
            <a href="#iletisim" class="mobile-link block font-medium">İletişim</a>
            <div class="pt-3 border-t border-slate-200 dark:border-slate-800 flex flex-col space-y-2">
                <a href="tel:05417391708" class="flex items-center justify-center space-x-2 py-2 bg-slate-100 dark:bg-slate-800 rounded-lg font-bold">
                    <i class="fas fa-phone-alt text-cyan-600"></i>
                    <span>0541 739 17 08</span>
                </a>
                <a href="https://api.whatsapp.com/send?phone=905372891274&text=Merhaba,%20temizlik%20hizmeti%20almak%20istiyorum." target="_blank" class="flex items-center justify-center space-x-2 py-2 bg-emerald-600 text-white rounded-lg font-bold">
                    <i class="fab fa-whatsapp text-lg"></i>
                    <span>WhatsApp İle Ulaşın</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <span class="inline-flex items-center space-x-2 px-3 py-1 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-700 dark:text-cyan-300 rounded-full text-xs font-extrabold uppercase tracking-wider">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>İstanbul / Çatalca & Çevre Bölgeler</span>
                </span>
                <h1 class="text-4xl sm:text-5xl font-extrabold tracking-tight leading-tight text-slate-900 dark:text-white">
                    Yaşam Alanlarınızda <span class="text-cyan-600 dark:text-cyan-400">Pırıl Pırıl</span> Temizlik Hijyeni
                </h1>
                <p class="text-lg text-slate-600 dark:text-slate-300 leading-relaxed">
                    Gider Temizlik olarak Çatalca ve tüm İstanbul'da profesyonel ekip, doğa dostu hijyen ürünleri ve %100 memnuniyet garantisiyle hizmetinizdeyiz.
                </p>
                <div class="flex flex-wrap gap-4 pt-2">
                    <a href="#hesaplama" class="px-6 py-3.5 bg-cyan-600 hover:bg-cyan-700 text-white font-bold rounded-xl shadow-lg shadow-cyan-600/30 transition-all flex items-center space-x-2">
                        <i class="fas fa-calculator"></i>
                        <span>Anında Fiyat Hesapla</span>
                    </a>
                    <a href="tel:05417891708" class="px-6 py-3.5 bg-slate-200 dark:bg-slate-800 hover:bg-slate-300 dark:hover:bg-slate-700 font-bold rounded-xl transition-all flex items-center space-x-2">
                        <i class="fas fa-phone-alt"></i>
                        <span>0541 739 17 08</span>
                    </a>
                </div>
            </div>
            <div class="relative">
                <div class="aspect-video rounded-3xl overflow-hidden shadow-2xl border-4 border-white dark:border-slate-800">
                    <img src="https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&q=80&w=800" alt="Gider Temizlik" class="w-full h-full object-cover">
                </div>
                <div class="absolute -bottom-6 -left-6 bg-white dark:bg-slate-800 p-4 rounded-2xl shadow-xl border border-slate-100 dark:border-slate-700 hidden sm:flex items-center space-x-4">
                    <div class="w-12 h-12 bg-emerald-100 text-emerald-600 rounded-xl flex items-center justify-center text-xl font-bold">
                        <i class="fas fa-shield-check"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm">Sigortalı & Güvenilir</h4>
                        <p class="text-xs text-slate-500">Uzman Temizlik Personeli</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Interactive Calculator Section -->
    <section id="hesaplama" class="py-20 bg-slate-100 dark:bg-slate-800/60 transition-colors">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-extrabold tracking-tight mb-3">Şeffaf Fiyat Hesaplama Modülü</h2>
                <p class="text-slate-600 dark:text-slate-300 max-w-2xl mx-auto">
                    İhtiyacınıza uygun kriterleri seçin, tahmini temizlik tutarını anında öğrenin ve doğrudan WhatsApp'tan teklifinizi iletin.
                </p>
            </div>

            <div class="bg-white dark:bg-slate-900 rounded-3xl p-6 sm:p-10 shadow-xl border border-slate-200/80 dark:border-slate-800">
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                    <!-- Options Selection -->
                    <div class="lg:col-span-2 space-y-6">
                        <!-- Service Type -->
                        <div>
                            <label class="block text-sm font-bold mb-3">1. Temizlik Türünü Seçin</label>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3" id="service-options">
                                <button type="button" class="service-btn active p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-cyan-600 bg-cyan-50 dark:bg-cyan-950/40 text-cyan-900 dark:text-cyan-200" data-rate="130" data-type="per_sqm" data-name="Ev Temizliği">
                                    <span>Ev Temizliği</span>
                                    <span class="text-xs font-bold bg-cyan-200 dark:bg-cyan-800 px-2 py-1 rounded">130 ₺/m²</span>
                                </button>
                                <button type="button" class="service-btn p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-slate-200 dark:border-slate-800" data-rate="125" data-type="per_sqm" data-name="Ofis Temizliği">
                                    <span>Ofis Temizliği</span>
                                    <span class="text-xs font-bold bg-slate-100 dark:bg-slate-800 px-2 py-1 rounded">125 ₺/m²</span>
                                </button>
                                <button type="button" class="service-btn p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-slate-200 dark:border-slate-800" data-rate="140" data-type="per_sqm" data-name="İnşaat Sonrası Temizlik">
                                    <span>İnşaat Sonrası</span>
                                    <span class="text-xs font-bold bg-slate-100 dark:bg-slate-800 px-2 py-1 rounded">140 ₺/m²</span>
                                </button>
                                <button type="button" class="service-btn p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-slate-200 dark:border-slate-800" data-rate="135" data-type="per_sqm" data-name="Dış Cephe & Cam">
                                    <span>Dış Cephe & Cam</span>
                                    <span class="text-xs font-bold bg-slate-100 dark:bg-slate-800 px-2 py-1 rounded">135 ₺/m²</span>
                                </button>
                                <button type="button" class="service-btn p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-slate-200 dark:border-slate-800" data-rate="2500" data-type="flat" data-name="Koltuk & Halı Yıkama">
                                    <span>Koltuk & Halı Yıkama</span>
                                    <span class="text-xs font-bold bg-slate-100 dark:bg-slate-800 px-2 py-1 rounded">Sabit 2.500 ₺</span>
                                </button>
                                <button type="button" class="service-btn p-4 rounded-xl border-2 text-left font-semibold text-sm transition-all flex justify-between items-center border-slate-200 dark:border-slate-800" data-rate="60" data-type="per_sqm" data-name="Dezenfeksiyon & İlaçlama">
                                    <span>Dezenfeksiyon</span>
                                    <span class="text-xs font-bold bg-slate-100 dark:bg-slate-800 px-2 py-1 rounded">60 ₺/m²</span>
                                </button>
                            </div>
                        </div>

                        <!-- Area Slider -->
                        <div id="sqm-container">
                            <div class="flex justify-between items-center mb-2">
                                <label class="text-sm font-bold">2. Alan Büyüklüğü (Metrekare)</label>
                                <span class="text-cyan-600 dark:text-cyan-400 font-extrabold text-lg"><span id="sqm-display">100</span> m²</span>
                            </div>
                            <input type="range" id="sqm-range" min="30" max="500" value="100" step="10" class="w-full h-2 bg-slate-200 dark:bg-slate-700 rounded-lg appearance-none cursor-pointer accent-cyan-600">
                            <div class="flex justify-between text-xs text-slate-400 mt-1">
                                <span>30 m²</span>
                                <span>250 m²</span>
                                <span>500 m²</span>
                            </div>
                        </div>

                        <!-- Addon Services -->
                        <div>
                            <label class="block text-sm font-bold mb-3">3. Ekstra Hizmetler (İsteğe Bağlı)</label>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <label class="flex items-center justify-between p-3 rounded-xl border border-slate-200 dark:border-slate-800 cursor-pointer hover:bg-slate-50 dark:hover:bg-slate-800/50">
                                    <div class="flex items-center space-x-3">
                                        <input type="checkbox" class="addon-checkbox w-4 h-4 text-cyan-600 rounded" value="400" data-name="Cam/Pencere Detaylı Temizliği">
                                        <span class="text-sm font-medium">Cam/Pencere Detayı</span>
                                    </div>
                                    <span class="text-xs font-bold text-slate-500">+400 ₺</span>
                                </label>
                                <label class="flex items-center justify-between p-3 rounded-xl border border-slate-200 dark:border-slate-800 cursor-pointer hover:bg-slate-50 dark:hover:bg-slate-800/50">
                                    <div class="flex items-center space-x-3">
                                        <input type="checkbox" class="addon-checkbox w-4 h-4 text-cyan-600 rounded" value="350" data-name="Balkon / Teras Temizliği">
                                        <span class="text-sm font-medium">Balkon / Teras</span>
                                    </div>
                                    <span class="text-xs font-bold text-slate-500">+350 ₺</span>
                                </label>
                                <label class="flex items-center justify-between p-3 rounded-xl border border-slate-200 dark:border-slate-800 cursor-pointer hover:bg-slate-50 dark:hover:bg-slate-800/50">
                                    <div class="flex items-center space-x-3">
                                        <input type="checkbox" class="addon-checkbox w-4 h-4 text-cyan-600 rounded" value="500" data-name="Mutfak İçi (Fırın/Buzdolabı)">
                                        <span class="text-sm font-medium">Mutfak İçi Detay</span>
                                    </div>
                                    <span class="text-xs font-bold text-slate-500">+500 ₺</span>
                                </label>
                                <label class="flex items-center justify-between p-3 rounded-xl border border-slate-200 dark:border-slate-800 cursor-pointer hover:bg-slate-50 dark:hover:bg-slate-800/50">
                                    <div class="flex items-center space-x-3">
                                        <input type="checkbox" class="addon-checkbox w-4 h-4 text-cyan-600 rounded" value="800" data-name="Koltuk Yıkama Ekstresi">
                                        <span class="text-sm font-medium">Koltuk Yıkama Ekstresi</span>
                                    </div>
                                    <span class="text-xs font-bold text-slate-500">+800 ₺</span>
                                </label>
                            </div>
                        </div>

                        <!-- Frequency Discount -->
                        <div>
                            <label class="block text-sm font-bold mb-3">4. Temizlik Sıklığı</label>
                            <div class="grid grid-cols-2 sm:grid-cols-4 gap-2">
                                <button type="button" class="freq-btn active py-2.5 px-3 rounded-xl border text-xs font-semibold text-center border-cyan-600 bg-cyan-50 dark:bg-cyan-950/40 text-cyan-900 dark:text-cyan-200" data-discount="0" data-name="Tek Seferlik">Tek Seferlik</button>
                                <button type="button" class="freq-btn py-2.5 px-3 rounded-xl border text-xs font-semibold text-center border-slate-200 dark:border-slate-800" data-discount="0.05" data-name="Haftalık (%5 İndirim)">Haftalık (%5 Ind.)</button>
                                <button type="button" class="freq-btn py-2.5 px-3 rounded-xl border text-xs font-semibold text-center border-slate-200 dark:border-slate-800" data-discount="0" data-name="İki Haftada Bir">2 Haftada Bir</button>
                                <button type="button" class="freq-btn py-2.5 px-3 rounded-xl border text-xs font-semibold text-center border-slate-200 dark:border-slate-800" data-discount="0" data-name="Aylık">Aylık</button>
                            </div>
                        </div>
                    </div>

                    <!-- Summary Box -->
                    <div class="bg-slate-50 dark:bg-slate-800/80 rounded-2xl p-6 border border-slate-200 dark:border-slate-700 flex flex-col justify-between">
                        <div>
                            <h3 class="text-lg font-bold border-b border-slate-200 dark:border-slate-700 pb-3 mb-4">Teklif Özeti</h3>
                            <div class="space-y-3 text-sm">
                                <div class="flex justify-between">
                                    <span class="text-slate-500">Seçilen Hizmet:</span>
                                    <span id="summary-service" class="font-bold">Ev Temizliği</span>
                                </div>
                                <div class="flex justify-between" id="summary-sqm-row">
                                    <span class="text-slate-500">Alan:</span>
                                    <span id="summary-sqm" class="font-bold">100 m²</span>
                                </div>
                                <div class="flex justify-between">
                                    <span class="text-slate-500">Sıklık:</span>
                                    <span id="summary-freq" class="font-bold">Tek Seferlik</span>
                                </div>
                                <div class="border-t border-dashed border-slate-300 dark:border-slate-700 pt-3">
                                    <span class="text-slate-500 block mb-1">Ekstra Hizmetler:</span>
                                    <ul id="summary-addons" class="text-xs font-medium text-slate-600 dark:text-slate-300 space-y-1 pl-2">
                                        <li class="italic text-slate-400">Seçilmedi</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <div class="pt-6 border-t border-slate-200 dark:border-slate-700 mt-6">
                            <span class="text-xs uppercase tracking-wider font-extrabold text-slate-400 block mb-1">Tahmini Toplam Tutar</span>
                            <div class="text-3xl font-black text-cyan-600 dark:text-cyan-400 mb-4" id="total-price">13.000 ₺</div>
                            
                            <a id="whatsapp-order-btn" href="#" target="_blank" class="w-full py-3.5 px-4 bg-emerald-600 hover:bg-emerald-700 text-white font-bold rounded-xl text-center shadow-lg shadow-emerald-600/20 transition-all flex items-center justify-center space-x-2">
                                <i class="fab fa-whatsapp text-lg"></i>
                                <span>WhatsApp İle Teklif Al</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Cards Section -->
    <section id="hizmetler" class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
            <h2 class="text-3xl font-extrabold tracking-tight mb-3">Hizmetlerimiz</h2>
            <div class="w-16 h-1 bg-cyan-600 mx-auto rounded-full mb-4"></div>
            <p class="text-slate-600 dark:text-slate-300 max-w-2xl mx-auto">
                Ev, ofis ve özel alanlarınız için ihtiyaç duyduğunuz profesyonel temizlik çözümleri.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Card 1 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-home"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Ev Temizliği</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Detaylı oda, mutfak, banyo ve hijyenik alan temizlik paketleri.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">130 ₺ / m²</span>
            </div>

            <!-- Card 2 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-building"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Ofis Temizliği</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Çalışma ortamlarınız için periyodik veya tek seferlik hijyen çözümleri.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">125 ₺ / m²</span>
            </div>

            <!-- Card 3 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-paint-roller"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">İnşaat Sonrası Temizlik</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Boya, moloz ve harç kalıntılarının profesyonel araçlarla derinlemesine temizliği.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">140 ₺ / m²</span>
            </div>

            <!-- Card 4 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-window-maximize"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Dış Cephe & Cam Temizliği</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Plaza, bina dış cepheleri ve geniş cam yüzeylerin lekesiz yıkanması.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">135 ₺ / m²</span>
            </div>

            <!-- Card 5 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-couch"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Koltuk & Halı Yıkama</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Yerinde buharlı koltuk yıkama ve anti-alerjik halı temizliği.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">Sabit 2.500 ₺</span>
            </div>

            <!-- Card 6 -->
            <div class="bg-white dark:bg-slate-900 rounded-2xl p-6 shadow-sm border border-slate-200 dark:border-slate-800 hover:shadow-xl transition-all">
                <div class="w-12 h-12 bg-cyan-100 dark:bg-cyan-900/40 text-cyan-600 dark:text-cyan-400 rounded-xl flex items-center justify-center text-xl font-bold mb-4">
                    <i class="fas fa-pump-medical"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Dezenfeksiyon & İlaçlama</h3>
                <p class="text-slate-500 dark:text-slate-400 text-sm mb-4">Ortamları virüs ve bakterilerden arındıran onaylı dezenfeksiyon.</p>
                <span class="text-xs font-extrabold text-cyan-600 dark:text-cyan-400">60 ₺ / m²</span>
            </div>
        </div>
    </section>

    <!-- Contact & Footer Section -->
    <section id="iletisim" class="py-20 bg-slate-100 dark:bg-slate-800/60 transition-colors">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <div class="space-y-6">
                    <h2 class="text-3xl font-extrabold tracking-tight">İletişim & Lokasyon</h2>
                    <p class="text-slate-600 dark:text-slate-300">
                        Sorularınız ve doğrudan rezervasyon talepleriniz için bize telefon, e-posta veya WhatsApp üzerinden 7/24 ulaşabilirsiniz.
                    </p>
                    
                    <div class="space-y-4 pt-2">
                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 bg-cyan-100 text-cyan-600 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm">Adres</h4>
                                <p class="text-slate-500 text-sm">İstanbul / Çatalca</p>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 bg-cyan-100 text-cyan-600 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm">Telefon</h4>
                                <a href="tel:05417891708" class="text-slate-500 hover:text-cyan-600 text-sm">0541 789 17 08</a>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 bg-emerald-100 text-emerald-600 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fab fa-whatsapp"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm">WhatsApp Line</h4>
                                <a href="https://api.whatsapp.com/send?phone=905372891274" target="_blank" class="text-slate-500 hover:text-emerald-600 text-sm">0537 289 12 74</a>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 bg-cyan-100 text-cyan-600 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm">E-Posta</h4>
                                <a href="mailto:senolyeni12@gmail.com" class="text-slate-500 hover:text-cyan-600 text-sm">senolyeni12@gmail.com</a>
                            </div>
                        </div>

                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 bg-cyan-100 text-cyan-600 rounded-xl flex items-center justify-center shrink-0">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm">Çalışma Saatleri</h4>
                                <p class="text-slate-500 text-sm">Hafta içi 08:30 - 19:00</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Fast Contact Form -->
                <div class="bg-white dark:bg-slate-900 rounded-3xl p-8 shadow-xl border border-slate-200 dark:border-slate-800">
                    <h3 class="text-xl font-bold mb-6">Hızlı Mesaj Gönderin</h3>
                    <form id="fast-contact-form" class="space-y-4">
                        <div>
                            <label class="block text-xs font-bold uppercase text-slate-500 mb-1">Adınız Soyadınız</label>
                            <input type="text" required class="w-full px-4 py-3 rounded-xl border border-slate-200 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-cyan-500">
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase text-slate-500 mb-1">Telefon Numarası</label>
                            <input type="tel" required class="w-full px-4 py-3 rounded-xl border border-slate-200 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-cyan-500">
                        </div>
                        <div>
                            <label class="block text-xs font-bold uppercase text-slate-500 mb-1">Mesajınız / İhtiyacınız</label>
                            <textarea rows="3" required class="w-full px-4 py-3 rounded-xl border border-slate-200 dark:border-slate-700 bg-slate-50 dark:bg-slate-800 focus:outline-none focus:ring-2 focus:ring-cyan-500"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3.5 bg-cyan-600 hover:bg-cyan-700 text-white font-bold rounded-xl transition-all">
                            Mesajı İlet
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-white dark:bg-slate-900 border-t border-slate-200 dark:border-slate-800 text-center text-xs text-slate-500">
        <p>© 2026 Gider Temizlik - İstanbul Çatalca. Tüm Hakları Saklıdır.</p>
    </footer>

    <script>
        // State variables for calculation
        let selectedRate = 130;
        let selectedType = 'per_sqm';
        let selectedServiceName = 'Ev Temizliği';
        let currentSqm = 100;
        let selectedDiscount = 0;
        let selectedFreqName = 'Tek Seferlik';

        const serviceBtns = document.querySelectorAll('.service-btn');
        const freqBtns = document.querySelectorAll('.freq-btn');
        const addonCheckboxes = document.querySelectorAll('.addon-checkbox');
        const sqmRange = document.getElementById('sqm-range');
        const sqmDisplay = document.getElementById('sqm-display');
        const sqmContainer = document.getElementById('sqm-container');

        const summaryService = document.getElementById('summary-service');
        const summarySqm = document.getElementById('summary-sqm');
        const summarySqmRow = document.getElementById('summary-sqm-row');
        const summaryFreq = document.getElementById('summary-freq');
        const summaryAddons = document.getElementById('summary-addons');
        const totalPriceEl = document.getElementById('total-price');
        const whatsappBtn = document.getElementById('whatsapp-order-btn');

        function calculateTotal() {
            let basePrice = 0;
            if (selectedType === 'per_sqm') {
                basePrice = selectedRate * currentSqm;
                sqmContainer.style.display = 'block';
                summarySqmRow.style.display = 'flex';
            } else {
                basePrice = selectedRate;
                sqmContainer.style.display = 'none';
                summarySqmRow.style.display = 'none';
            }

            let addonsPrice = 0;
            let selectedAddonNames = [];
            addonCheckboxes.forEach(cb => {
                if (cb.checked) {
                    addonsPrice += parseFloat(cb.value);
                    selectedAddonNames.push(cb.getAttribute('data-name'));
                }
            });

            let subtotal = basePrice + addonsPrice;
            let finalPrice = subtotal * (1 - selectedDiscount);

            // Format Turkish Lira
            let formattedPrice = Math.round(finalPrice).toLocaleString('tr-TR') + ' ₺';
            totalPriceEl.textContent = formattedPrice;

            // Summary update
            summaryService.textContent = selectedServiceName;
            summarySqm.textContent = currentSqm + ' m²';
            summaryFreq.textContent = selectedFreqName;

            if (selectedAddonNames.length > 0) {
                summaryAddons.innerHTML = selectedAddonNames.map(name => `<li>• ${name}</li>`).join('');
            } else {
                summaryAddons.innerHTML = '<li class="italic text-slate-400">Seçilmedi</li>';
            }

            // WhatsApp Message Generator
            let waMsg = `Merhaba Gider Temizlik,%0A%0AWeb sitenizden teklif almak istiyorum:%0A- *Hizmet:* ${selectedServiceName}%0A`;
            if (selectedType === 'per_sqm') {
                waMsg += `- *Alan:* ${currentSqm} m²%0A`;
            }
            waMsg += `- *Sıklık:* ${selectedFreqName}%0A`;
            if (selectedAddonNames.length > 0) {
                waMsg += `- *Ek Hizmetler:* ${selectedAddonNames.join(', ')}%0A`;
            }
            waMsg += `- *Tahmini Tutar:* ${formattedPrice}%0A%0ARezervasyon için dönüş yapabilir misiniz?`;

            whatsappBtn.href = `https://api.whatsapp.com/send?phone=905372891274&text=${waMsg}`;
        }

        // Event Listeners for Service buttons
        serviceBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                serviceBtns.forEach(b => {
                    b.classList.remove('border-cyan-600', 'bg-cyan-50', 'dark:bg-cyan-950/40', 'text-cyan-900', 'dark:text-cyan-200');
                    b.classList.add('border-slate-200', 'dark:border-slate-800');
                });
                btn.classList.add('border-cyan-600', 'bg-cyan-50', 'dark:bg-cyan-950/40', 'text-cyan-900', 'dark:text-cyan-200');
                btn.classList.remove('border-slate-200', 'dark:border-slate-800');

                selectedRate = parseFloat(btn.getAttribute('data-rate'));
                selectedType = btn.getAttribute('data-type');
                selectedServiceName = btn.getAttribute('data-name');
                calculateTotal();
            });
        });

        // Event Listeners for SQM slider
        sqmRange.addEventListener('input', (e) => {
            currentSqm = e.target.value;
            sqmDisplay.textContent = currentSqm;
            calculateTotal();
        });

        // Event Listeners for Addons
        addonCheckboxes.forEach(cb => {
            cb.addEventListener('change', calculateTotal);
        });

        // Event Listeners for Frequency
        freqBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                freqBtns.forEach(b => {
                    b.classList.remove('border-cyan-600', 'bg-cyan-50', 'dark:bg-cyan-950/40', 'text-cyan-900', 'dark:text-cyan-200');
                    b.classList.add('border-slate-200', 'dark:border-slate-800');
                });
                btn.classList.add('border-cyan-600', 'bg-cyan-50', 'dark:bg-cyan-950/40', 'text-cyan-900', 'dark:text-cyan-200');
                btn.classList.remove('border-slate-200', 'dark:border-slate-800');

                selectedDiscount = parseFloat(btn.getAttribute('data-discount'));
                selectedFreqName = btn.getAttribute('data-name');
                calculateTotal();
            });
        });

        // Initialize Calculation on page load
        calculateTotal();

        // Theme Toggle
        const themeToggleBtn = document.getElementById('theme-toggle');
        const themeToggleBtnMobile = document.getElementById('theme-toggle-mobile');
        const darkIcon = document.getElementById('theme-toggle-dark-icon');
        const lightIcon = document.getElementById('theme-toggle-light-icon');
        const darkIconMobile = document.getElementById('theme-toggle-dark-icon-mobile');
        const lightIconMobile = document.getElementById('theme-toggle-light-icon-mobile');

        function updateIcons(isDark) {
            if (isDark) {
                darkIcon.classList.add('hidden');
                lightIcon.classList.remove('hidden');
                darkIconMobile.classList.add('hidden');
                lightIconMobile.classList.remove('hidden');
            } else {
                darkIcon.classList.remove('hidden');
                lightIcon.classList.add('hidden');
                darkIconMobile.classList.remove('hidden');
                lightIconMobile.classList.add('hidden');
            }
        }

        if (localStorage.getItem('color-theme') === 'dark' || (!('color-theme' in localStorage) && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
            document.documentElement.classList.add('dark');
            updateIcons(true);
        } else {
            document.documentElement.classList.remove('dark');
            updateIcons(false);
        }

        function toggleTheme() {
            if (document.documentElement.classList.contains('dark')) {
                document.documentElement.classList.remove('dark');
                localStorage.setItem('color-theme', 'light');
                updateIcons(false);
            } else {
                document.documentElement.classList.add('dark');
                localStorage.setItem('color-theme', 'dark');
                updateIcons(true);
            }
        }

        themeToggleBtn.addEventListener('click', toggleTheme);
        themeToggleBtnMobile.addEventListener('click', toggleTheme);

        // Mobile Menu
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Form submission
        document.getElementById('fast-contact-form').addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Mesajınız Gider Temizlik ekibine iletildi! En kısa sürede dönüş yapacağız.');
            e.target.reset();
        });
    </script>
</body>
</html>