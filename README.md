<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Battle of Archiez - Sewa FT Terpercaya</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
        .map-option {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
        }
        .rank-option {
            background: linear-gradient(135deg, #ffd452 0%, #ff6b6b 100%);
            color: white;
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="gradient-bg shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <i class="fas fa-trophy text-3xl text-white mr-3"></i>
                    <span class="text-2xl font-bold text-white">Battle of Archiez</span>
                </div>
                <div class="flex items-center space-x-6">
                    <a href="#paket" class="text-white hover:text-yellow-300 transition">Paket</a>
                    <a href="#pembayaran" class="text-white hover:text-yellow-300 transition">Pembayaran</a>
                    <a href="#discord" class="text-white hover:text-yellow-300 transition">Discord</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-20 pb-20 gradient-bg text-white">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h1 class="text-5xl md:text-6xl font-bold mb-6 animate-pulse">
                Battle of Archiez
            </h1>
            <p class="text-xl md:text-2xl mb-8 opacity-90">Sewa FT Terpercaya Mulai 1K - Rank Bebas</p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center mb-12">
                <a href="#paket" class="bg-yellow-400 text-gray-900 px-8 py-4 rounded-full font-semibold text-lg hover:bg-yellow-300 transition transform hover:scale-105">
                    <i class="fas fa-play mr-2"></i>Pilih Paket
                </a>
                <a href="https://discord.gg/syJ3pnWXV" target="_blank" class="border-2 border-white text-white px-8 py-4 rounded-full font-semibold text-lg hover:bg-white hover:text-gray-900 transition transform hover:scale-105">
                    <i class="fab fa-discord mr-2"></i>Join Discord
                </a>
            </div>
        </div>
    </section>

    <!-- Paket Section -->
    <section id="paket" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Pilih Paket FT Anda</h2>
                <p class="text-xl text-gray-600">Semua rank bebas - Solo BR/CS - Semua turnamen support</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Paket Noob -->
                <div class="bg-white rounded-3xl shadow-2xl p-8 card-hover transition-all duration-300 border-4 border-transparent hover:border-yellow-400">
                    <div class="text-center">
                        <div class="w-20 h-20 bg-yellow-400 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <i class="fas fa-seedling text-2xl text-white"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Paket Noob</h3>
                        <div class="text-4xl font-bold text-yellow-500 mb-6">Rp 1.000</div>
                        <ul class="text-left mb-8 space-y-3 text-gray-700">
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Rank Bebas Solo BR/CS</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Waktu 1 Jam</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Match Bebas</li>
                        </ul>
                        <button onclick="selectPackage('noob', 1000)" class="w-full bg-gradient-to-r from-yellow-400 to-yellow-500 text-gray-900 py-4 rounded-2xl font-bold text-lg hover:from-yellow-500 hover:to-yellow-600 transform hover:scale-105 transition-all duration-300">
                            Pilih Paket Noob
                        </button>
                    </div>
                </div>

                <!-- Paket Basic -->
                <div class="bg-white rounded-3xl shadow-2xl p-8 card-hover transition-all duration-300 border-4 border-transparent hover:border-blue-400 relative">
                    <div class="absolute -top-3 left-1/2 transform -translate-x-1/2 bg-blue-500 text-white px-6 py-2 rounded-full text-sm font-bold">POPULAR</div>
                    <div class="text-center">
                        <div class="w-20 h-20 bg-blue-500 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <i class="fas fa-star text-2xl text-white"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Paket Basic</h3>
                        <div class="text-4xl font-bold text-blue-500 mb-6">Rp 2.000</div>
                        <ul class="text-left mb-8 space-y-3 text-gray-700">
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Rank Bebas Duo BR/CS</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Match Bebas / Rush Hour</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Waktu Fleksibel</li>
                        </ul>
                        <button onclick="selectPackage('basic', 2000)" class="w-full bg-gradient-to-r from-blue-500 to-blue-600 text-white py-4 rounded-2xl font-bold text-lg hover:from-blue-600 hover:to-blue-700 transform hover:scale-105 transition-all duration-300">
                            Pilih Paket Basic
                        </button>
                    </div>
                </div>

                <!-- Paket Master -->
                <div class="bg-white rounded-3xl shadow-2xl p-8 card-hover transition-all duration-300 border-4 border-transparent hover:border-purple-400">
                    <div class="text-center">
                        <div class="w-20 h-20 bg-purple-500 rounded-full mx-auto mb-6 flex items-center justify-center">
                            <i class="fas fa-crown text-2xl text-white"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800 mb-2">Paket Master</h3>
                        <div class="text-4xl font-bold text-purple-500 mb-6">Rp 5.000</div>
                        <ul class="text-left mb-8 space-y-3 text-gray-700">
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Rank Bebas Duo BR 3 Jam</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Solo/Duo Bebas + Rush Hour</li>
                            <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Custom Glow + Logo</li>
                        </ul>
                        <button onclick="selectPackage('master', 5000)" class="w-full bg-gradient-to-r from-purple-500 to-purple-600 text-white py-4 rounded-2xl font-bold text-lg hover:from-purple-600 hover:to-purple-700 transform hover:scale-105 transition-all duration-300">
                            Pilih Paket Master
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Form Pemesanan -->
    <section id="form-section" class="py-20 bg-gray-50 hidden">
        <div class="max-w-4xl mx-auto px-4">
            <div class="bg-white rounded-3xl shadow-2xl p-12">
                <div class="text-center mb-12">
                    <h2 class="text-4xl font-bold text-gray-800 mb-4">Lengkapi Data Pemesanan</h2>
                    <p class="text-xl text-gray-600">Pilih map & rank untuk FT turnamen</p>
                </div>

                <form id="orderForm">
                    <!-- Info Paket Terpilih -->
                    <div class="grid md:grid-cols-2 gap-6 mb-8 p-6 bg-blue-50 rounded-2xl">
                        <div>
                            <label class="block text-lg font-semibold text-gray-700 mb-2">Paket Terpilih</label>
                            <div id="selectedPackage" class="text-2xl font-bold text-blue-600"></div>
                            <div id="selectedPrice" class="text-xl text-gray-600"></div>
                        </div>
                        <div>
                            <label class="block text-lg font-semibold text-gray-700 mb-2">Fitur Tambahan</label>
                            <label class="flex items-center">
                                <input type="checkbox" id="customGlow" class="mr-2 w-5 h-5">
                                <span class="text-lg">Custom Glow + Logo</span>
                            </label>
                        </div>
                    </div>

                    <!-- Pilihan Map - 5 PILIHAN -->
                    <div class="mb-8 p-6 bg-gradient-to-r from-purple-500 to-pink-500 rounded-3xl text-white shadow-2xl">
                        <label class="block text-2xl font-bold mb-6 flex items-center justify-center">
                            <i class="fas fa-map-marked-alt text-yellow-300 mr-3 text-3xl"></i>
                            Pilih Map (5 Pilihan)
                        </label>
                        <div class="grid md:grid-cols-3 gap-4 max-w-2xl mx-auto">
                            <label class="map-option p-6 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white/50">
                                <input type="radio" name="mapSelect" value="Nexterra" class="mr-3 w-6 h-6">
                                <i class="fas fa-mountain text-2xl mb-2 block"></i>
                                Nexterra
                            </label>
                            <label class="map-option p-6 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white/50">
                                <input type="radio" name="mapSelect" value="Bermuda" class="mr-3 w-6 h-6">
                                <i class="fas fa-island-tropical text-2xl mb-2 block"></i>
                                Bermuda
                            </label>
                            <label class="map-option p-6 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white/50">
                                <input type="radio" name="mapSelect" value="Kalahari" class="mr-3 w-6 h-6">
                                <i class="fas fa-dune text-2xl mb-2 block"></i>
                                Kalahari
                            </label>
                            <label class="map-option p-6 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white/50">
                                <input type="radio" name="mapSelect" value="Solara" class="mr-3 w-6 h-6">
                                <i class="fas fa-solar-panel text-2xl mb-2 block"></i>
                                Solara
                            </label>
                            <label class="bg-gradient-to-r from-green-500 to-blue-500 p-6 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white">
                                <input type="radio" name="mapSelect" value="Random" class="mr-3 w-6 h-6">
                                <i class="fas fa-random text-2xl mb-2 block text-white"></i>
                                🎲 Random
                            </label>
                        </div>
                    </div>

                    <!-- Pilihan Rank - 8 PILIHAN BARU -->
                    <div class="mb-8 p-6 bg-gradient-to-r from-orange-500 to-red-500 rounded-3xl text-white shadow-2xl">
                        <label class="block text-2xl font-bold mb-6 flex items-center justify-center">
                            <i class="fas fa-medal text-yellow-300 mr-3 text-3xl"></i>
                            Pilih Rank (8 Pilihan)
                        </label>
                        <div class="grid md:grid-cols-4 gap-4 max-w-4xl mx-auto">
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Bronze" class="mr-2 w-5 h-5">
                                <i class="fas fa-medal text-xl mb-1 block text-yellow-200"></i>
                                <div>Bronze</div>
                            </label>
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Silver" class="mr-2 w-5 h-5">
                                <i class="fas fa-medal text-xl mb-1 block text-gray-200"></i>
                                <div>Silver</div>
                            </label>
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Gold" class="mr-2 w-5 h-5">
                                <i class="fas fa-medal text-xl mb-1 block text-yellow-300"></i>
                                <div>Gold</div>
                            </label>
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Platinum" class="mr-2 w-5 h-5">
                                <i class="fas fa-medal text-xl mb-1 block text-blue-200"></i>
                                <div>Platinum</div>
                            </label>
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Heroic" class="mr-2 w-5 h-5">
                                <i class="fas fa-crown text-xl mb-1 block text-purple-300"></i>
                                <div>Heroic</div>
                            </label>
                            <label class="rank-option p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-2 border-white/50">
                                <input type="radio" name="rankSelect" value="Master" class="mr-2 w-5 h-5">
                                <i class="fas fa-crown text-xl mb-1 block text-indigo-200"></i>
                                <div>Master</div>
                            </label>
                            <label class="bg-gradient-to-r from-purple-600 to-pink-500 p-5 rounded-2xl cursor-pointer hover:scale-105 transition-all duration-300 shadow-xl hover:shadow-2xl text-center font-bold border-4 border-white">
                                <input type="radio" name="rankSelect" value="Grandmaster" class="mr-2 w-5 h-5">
                                <i class="fas fa-crown text-xl mb-1 block text-yellow-300"></i>
                                <div>Grandmaster</div>
                            </label>
                        </div>
                    </div>

                    <!-- Nomor Rekening (Semua Metode) -->
                    <div class="mb-8 p-6 bg-yellow-50 border-4 border-yellow-200 rounded-3xl shadow-lg">
                        <label class="block text-xl font-bold text-yellow-800 mb-4 flex items-center">
                            <i class="fas fa-mobile-alt text-yellow-500 mr-3 text-2xl"></i>
                            Nomor Rekening / Nomor Tujuan Pembayaran
                        </label>
                        <input type="tel" id="rekeningNumber" placeholder="💳 E-Wallet: No. HP | 🏦 Bank: No. Rekening" 
                               class="w-full p-6 border-2 border-yellow-300 rounded-2xl text-xl bg-yellow-50 focus:border-yellow-500 focus:outline-none focus:ring-4 focus:ring-yellow-200 font-semibold shadow-inner" required>
                        <p class="text-sm text-yellow-700 mt-3 font-medium">📱 ShopeePay/DANA/GoPay → Input No. HP | 💳 BNI/BSI/Permata → Input No. Rekening</p>
                    </div>

                    <!-- Metode Pembayaran -->
                    <div id="pembayaran">
                        <label class="block text-2xl font-bold text-gray-800 mb-8">Metode Pembayaran</label>
                        
                        <!-- E-Wallet -->
                        <div class="mb-8">
                            <h4 class="text-xl font-semibold mb-6 flex items-center">
                                <i class="fas fa-wallet text-yellow-500 mr-3 text-xl"></i>E-Wallet
                            </h4>
                            <div class="grid md:grid-cols-3 gap-4">
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-yellow-400 cursor-pointer transition bg-gradient-to-br from-yellow-50 to-orange-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="shopeepay" class="mr-4 w-6 h-6 text-yellow-500">
                                    <div>
                                        <i class="fab fa-shopify text-orange-500 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">ShopeePay</div>
                                    </div>
                                </label>
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-green-400 cursor-pointer transition bg-gradient-to-br from-green-50 to-emerald-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="dana" class="mr-4 w-6 h-6 text-green-500">
                                    <div>
                                        <i class="fas fa-coins text-green-500 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">DANA</div>
                                    </div>
                                </label>
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-orange-400 cursor-pointer transition bg-gradient-to-br from-orange-50 to-red-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="gopay" class="mr-4 w-6 h-6 text-orange-500">
                                    <div>
                                        <i class="fas fa-money-bill-wave text-orange-500 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">GoPay</div>
                                    </div>
                                </label>
                            </div>
                        </div>

                        <!-- Kartu Kredit & Bank -->
                        <div class="mb-12">
                            <h4 class="text-xl font-semibold mb-6 flex items-center">
                                <i class="fas fa-credit-card text-blue-500 mr-3 text-xl"></i>Kartu Kredit / Transfer Bank
                            </h4>
                            <div class="grid md:grid-cols-3 gap-4">
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-blue-400 cursor-pointer transition bg-gradient-to-br from-blue-50 to-indigo-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="bni" class="mr-4 w-6 h-6 text-blue-500">
                                    <div>
                                        <i class="fas fa-university text-blue-600 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">BNI</div>
                                    </div>
                                </label>
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-green-400 cursor-pointer transition bg-gradient-to-br from-green-50 to-teal-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="bsi" class="mr-4 w-6 h-6 text-green-500">
                                    <div>
                                        <i class="fas fa-mosque text-green-600 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">BSI</div>
                                    </div>
                                </label>
                                <label class="flex items-center p-6 border-2 border-gray-200 rounded-2xl hover:border-purple-400 cursor-pointer transition bg-gradient-to-br from-purple-50 to-violet-50 shadow-md hover:shadow-xl">
                                    <input type="radio" name="payment" value="permata" class="mr-4 w-6 h-6 text-purple-500">
                                    <div>
                                        <i class="fas fa-piggy-bank text-purple-500 text-3xl"></i>
                                        <div class="font-bold text-lg mt-1">Permata</div>
                                    </div>
                                </label>
                            </div>
                        </div>
                    </div>

                    <!-- Tombol Order -->
                    <div class="flex gap-4 mt-16 pt-8 border-t-4 border-green-200">
                        <button type="button" onclick="submitOrder()" class="flex-1 bg-gradient-to-r from-green-500 to-emerald-600 text-white py-6 rounded-3xl font-bold text-xl hover:from-green-600 hover:to-emerald-700 transform hover:scale-105 transition-all duration-300 shadow-2xl hover:shadow-3xl border-4 border-green-300">
                            <i class="fas fa-rocket mr-3 text-lg"></i>🚀 Order Sekarang
                        </button>
                        <button type="button" onclick="cancelOrder()" class="px-12 py-6 bg-gradient-to-r from-gray-300 to-gray-400 text-gray-800 rounded-3xl font-bold text-lg hover:from-gray-400 hover:to-gray-500 transition-all duration-300 shadow-xl hover:shadow-2xl">
                            <i class="fas fa-times mr-2"></i>❌ Batal
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Success Modal -->
    <div id="successModal" class="fixed inset-0 bg-black bg-opacity-50 hidden flex items-center justify-center z-50">
        <div class="bg-white rounded-3xl p-12 max-w-lg w-full mx-4 text-center animate-bounce">
            <div class="w-28 h-28 bg-gradient-to-r from-green-500 to-emerald-600 rounded-full mx-auto mb-8 flex items-center justify-center shadow-2xl border-8 border-white">
                <i class="fas fa-check-double text-4xl text-white"></i>
            </div>
            <h3 class="text-4xl font-bold text-gray-800 mb-4">Order Berhasil! 🎉</h3>
            <p class="text-xl text-gray-600 mb-8">Pesan Anda telah terkirim ke admin WhatsApp</p>
            <div class="space-y-4 mb-10 p-6 bg-green-50 border-4 border-green-200 rounded-3xl">
                <p><strong>📋 ID Order:</strong> <span id="orderId" class="font-mono bg-white px-4 py-2 rounded-xl font-bold text-green-600 text-lg block"></span></p>
                <p><strong>⏱️ Estimasi:</strong> <span class="font-bold text-2xl text-green-600">5-10 menit</span></p>
                <p class="text-sm text-green-700">WhatsApp admin akan balas segera!</p>
            </div>
            <div class="flex gap-4">
                <a href="#paket" onclick="closeModal()" class="flex-1 bg-gradient-to-r from-green-500 to-emerald-600 text-white py-4 px-6 rounded-2xl font-bold hover:from-green-600 hover:to-emerald-700 transition shadow-2xl hover:shadow-3xl">
                    <i class="fas fa-plus-circle mr-2"></i>Order Lagi
                </a>
                <a href="https://discord.gg/syJ3pnWXV" target="_blank" class="px-8 py-4 bg-indigo-600 text-white rounded-2xl font-bold hover:bg-indigo-700 transition shadow-xl hover:shadow-2xl">
                    <i class="fab fa-discord mr-2"></i>Discord
                </a>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 mt-20" id="discord">
        <div class="max-w-7xl mx-auto px-4 grid md:grid-cols-3 gap-8">
            <div>
                <div class="flex items-center mb-4">
                    <i class="fas fa-trophy text-3xl text-yellow-400 mr-3"></i>
                    <span class="text-2xl font-bold">Battle of Archiez</span>
                </div>
                <p class="text-gray-400">Sewa FT terpercaya untuk semua turnamen. Rank bebas, map bebas, support semua event!</p>
            </div>
            <div>
                <h4 class="text-xl font-bold mb-6">Admin</h4>
                <div class="space-y-3">
                    <p class="flex items-center mb-2">
                        <i class="fab fa-whatsapp text-green-400 mr-3 text-xl"></i>
                        Chat Admin Otomatis (3 Admin)
                    </p>
                    <p class="flex items-center">
                        <i class="fab fa-tiktok text-pink-400 mr-3 text-xl"></i>
                        <a href="https://tiktok.com/@7starnabil" target="_blank" class="hover:text-yellow-300">@7starnabil</a>
                    </p>
                    <p class="flex items-center">
                        <i class="fab fa-tiktok text-pink-400 mr-3 text-xl"></i>
                        <a href="https://tiktok.com/@fathan6379" target="_blank" class="hover:text-yellow-300">@fathan6379</a>
                    </p>
                </div>
            </div>
            <div>
                <h4 class="text-xl font-bold mb-6">Discord</h4>
                <a href="https://discord.gg/syJ3pnWXV" target="_blank" class="inline-flex items-center bg-indigo-600 text-white px-8 py-4 rounded-2xl font-bold hover:bg-indigo-700 transition shadow-2xl hover:shadow-3xl text-lg">
                    <i class="fab fa-discord mr-3 text-2xl"></i>
                    Join Server Discord
                </a>
            </div>
        </div>
        <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
            <p>&copy; 2024 Battle of Archiez. All rights reserved. | No.1 FT Provider Indonesia</p>
        </div>
    </footer>

    <script>
        let selectedPackage = '';
        let selectedPrice = 0;

        // Pilih Paket
        function selectPackage(pkg, price) {
            selectedPackage = pkg;
            selectedPrice = price;
            document.getElementById('form-section').classList.remove('hidden');
            document.getElementById('form-section').scrollIntoView({ behavior: 'smooth' });
            
            const packageNames = {
                'noob': 'Paket Noob - Rp 1.000',
                'basic': 'Paket Basic - Rp 2.000', 
                'master': 'Paket Master - Rp 5.000'
            };
            
            document.getElementById('selectedPackage').textContent = packageNames[pkg];
            document.getElementById('selectedPrice').textContent = `Harga: Rp ${price.toLocaleString()}`;
        }

        // Submit Order
        function submitOrder() {
            // Ambil map dari radio button
            const selectedMapRadio = document.querySelector('input[name="mapSelect"]:checked');
            const map = selectedMapRadio ? selectedMapRadio.value : '';
            
            // Ambil rank dari radio button BARU
            const selectedRankRadio = document.querySelector('input[name="rankSelect"]:checked');
            const rank = selectedRankRadio ? selectedRankRadio.value : '';
            
            const rekening = document.getElementById('rekeningNumber').value;
            const payment = document.querySelector('input[name="payment"]:checked')?.value;
            const customGlow = document.getElementById('customGlow').checked;

            // Validasi lengkap
            if (!selectedPackage || !map || !rank || !rekening || !payment) {
                alert('❌ Mohon lengkapi SEMUA field yang diperlukan!\n\n• ✅ Paket\n• 🗺️ Map (5 pilihan)\n• 🏆 Rank (8 pilihan)\n• 📱 Nomor Rekening/HP\n• 💳 Metode Pembayaran');
                return false;
            }

            const orderId = 'BOA-' + Date.now().toString().slice(-6);
            document.getElementById('orderId').textContent = orderId;

            // Pilih admin random dari 3 admin
            const admins = [
                'https://wa.me/628815346307',      // Admin 1
                'https://wa.me/6287836820275',     // Admin 2  
                'https://wa.me/6287898435754'      // Admin 3 (BARU)
            ];
            const randomAdmin = admins[Math.floor(Math.random() * admins.length)];

            // Nama paket dan pembayaran
            const packageNames = {
                'noob': 'Noob (1K)',
                'basic': 'Basic (2K)',
                'master': 'Master (5K)'
            };

            const paymentNames = {
                'shopeepay': 'ShopeePay',
                'dana': 'DANA',
                'gopay': 'GoPay',
                'bni': 'Kartu Kredit BNI',
                'bsi': 'Kartu Kredit BSI',
                'permata': 'Rekening Bank Permata'
            };

            // Pesan WhatsApp LENGKAP dengan RANK BARU
            let message = `Halo admin battle of archiez ft saya ingin mendaftar FENALTI TURMAMEN untuk main dengan paket ${packageNames[selectedPackage]}

Bolehkah saya ingin membayar dengan metode pembayaran ${paymentNames[payment]} dan ini nomor rekening saya ${rekening}

🏆 DETAIL ORDER:
- Map: ${map}
- Rank: ${rank}
- Fitur Tambahan: ${customGlow ? '✅ Custom Glow + Logo' : '❌ Tidak ada'}
- ID Order: ${orderId}
- Harga: Rp ${selectedPrice.toLocaleString()}

Terima kasih admin! 🙏`;

            // Buka WhatsApp
            const whatsappUrl = `${randomAdmin}?text=${encodeURIComponent(message)}`;
            window.open(whatsappUrl, '_blank');
            
            // Copy pesan ke clipboard
            navigator.clipboard.writeText(message).then(() => {
                console.log('✅ Pesan dicopy ke clipboard');
            });

            // Tampilkan modal sukses
            document.getElementById('successModal').classList.remove('hidden');
        }

        // Cancel Order
        function cancelOrder() {
            document.getElementById('form-section').classList.add('hidden');
            document.getElementById('orderForm').reset();
            document.querySelectorAll('input[name="mapSelect"]').forEach(r => r.checked = false);
            document.querySelectorAll('input[name="rankSelect"]').forEach(r => r.checked = false);
            selectedPackage = '';
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Close Modal
        function closeModal() {
            document.getElementById('successModal').classList.add('hidden');
            cancelOrder();
        }

        // Enter key untuk submit
        document.addEventListener('keypress', function(e) {
            if (e.key === 'Enter' && !document.getElementById('form-section').classList.contains('hidden')) {
                submitOrder();
            }
        });

        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
