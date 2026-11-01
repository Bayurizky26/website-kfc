<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KFC Indonesia - Official Clone</title>
    <style>
        * { box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            margin: 0; 
            padding: 0; 
            display: flex; 
            flex-direction: column; 
            min-height: 100vh; 
            background-color: #f4f4f4;
            color: #333;
            overflow-x: hidden;
        }
        
        /* Header */
        header { 
            background-color: #e4002b; 
            color: white; 
            padding: 12px 15px; 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .logo { 
            font-size: 20px; 
            font-weight: 900; 
            letter-spacing: 1px; 
            color: white; 
            background: #b50022;
            padding: 4px 10px;
            border-radius: 4px;
            cursor: pointer;
        }
        .nav-links { display: flex; gap: 8px; }
        .nav-links a { 
            color: white; 
            text-decoration: none; 
            font-size: 12px; 
            font-weight: bold; 
            cursor: pointer;
            transition: color 0.3s; 
        }
        .nav-links a:hover { color: #ffcc00; }

        /* Halaman / Konten Utama */
        .page-section {
            display: none;
            flex: 1;
            padding: 20px 15px;
            max-width: 600px;
            margin: 0 auto;
            width: 100%;
            animation: fadeIn 0.3s ease-in-out;
        }
        .page-section.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(4px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Hero Section */
        .hero { 
            background: linear-gradient(135deg, #e4002b 0%, #99001c 100%); 
            color: white;
            text-align: center; 
            padding: 35px 15px; 
            border-radius: 12px;
            margin-bottom: 15px;
        }
        .hero h1 { font-size: 22px; margin-bottom: 5px; }
        .hero p { font-size: 12px; opacity: 0.9; margin: 0; }

        /* Banner Diskon */
        .banner-diskon {
            background: linear-gradient(135deg, #ffcc00 0%, #ff9900 100%);
            color: #222;
            padding: 12px;
            border-radius: 10px;
            text-align: center;
            font-weight: bold;
            margin-bottom: 15px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .banner-diskon h3 { margin: 0 0 3px 0; color: #d40000; font-size: 15px; }
        .banner-diskon p { margin: 0; font-size: 11px; }

        /* Grid Menu */
        .section-title {
            text-align: center;
            margin: 25px 0 10px;
            font-size: 17px;
            color: #e4002b;
            font-weight: bold;
        }
        .menu-grid { 
            display: grid; 
            grid-template-columns: repeat(2, 1fr); 
            gap: 12px; 
            margin-bottom: 15px;
        }
        .menu-item { 
            background: #fff;
            border-radius: 10px; 
            box-shadow: 0 2px 8px rgba(0,0,0,0.08); 
            text-align: center; 
            overflow: hidden; 
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            position: relative;
        }
        .badge-diskon {
            position: absolute;
            top: 8px;
            left: 8px;
            background: #ffcc00;
            color: #000;
            font-size: 10px;
            font-weight: bold;
            padding: 3px 6px;
            border-radius: 4px;
            z-index: 10;
        }
        .menu-item img { 
            width: 100%; 
            height: 110px; 
            object-fit: cover; 
        }
        .menu-item h3 { 
            margin: 8px 5px 4px; 
            font-size: 13px; 
            font-weight: bold;
        }
        .price-box { margin-bottom: 6px; }
        .price { color: #e4002b; font-weight: bold; font-size: 12px; display: inline; }
        .menu-item button { 
            background-color: #e4002b; 
            color: white; 
            border: none; 
            padding: 7px 10px; 
            border-radius: 15px; 
            cursor: pointer; 
            font-weight: bold;
            font-size: 11px;
            margin-bottom: 10px; 
            width: 85%;
            margin-left: auto;
            margin-right: auto;
            transition: background 0.2s; 
        }
        .menu-item button:hover { background-color: #b50022; }

        /* Card Informasi */
        .info-card {
            background: #fff;
            padding: 14px;
            border-radius: 10px;
            margin-bottom: 12px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.06);
            border-left: 4px solid #e4002b;
        }
        .info-card h3 { color: #e4002b; margin: 0 0 5px 0; font-size: 14px; }
        .info-card p { font-size: 12px; color: #555; line-height: 1.4; margin: 0; }
        .news-date { font-size: 10px; color: #888; margin-bottom: 3px; display: block; }

        /* Form Checkout Styling */
        .form-group { margin-bottom: 12px; }
        .form-group label { display: block; font-size: 12px; font-weight: bold; margin-bottom: 4px; color: #333; }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%; padding: 8px 10px; border: 1px solid #ccc; border-radius: 6px; font-size: 12px;
        }
        .order-summary { background: #f9f9f9; padding: 10px; border-radius: 6px; margin-bottom: 12px; font-size: 12px; }
        .order-summary div { display: flex; justify-content: space-between; margin-bottom: 4px; }
        .order-total { font-weight: bold; color: #e4002b; font-size: 14px; border-top: 1px dashed #ddd; padding-top: 6px; margin-top: 6px; }
        .btn-konfirmasi { background-color: #28a745; color: white; border: none; padding: 10px; border-radius: 8px; width: 100%; font-weight: bold; font-size: 13px; cursor: pointer; }
        .btn-konfirmasi:hover { background-color: #218838; }

        /* Footer */
        footer { 
            background-color: #222; 
            color: white; 
            text-align: center; 
            padding: 18px 15px; 
            margin-top: auto; 
            font-size: 12px; 
        }
        .footer-links { margin-bottom: 8px; }
        .footer-links a { color: #aaa; text-decoration: none; margin: 0 5px; cursor: pointer; }
        .footer-links a:hover { color: white; }

        @media (max-width: 380px) {
            header { flex-direction: column; gap: 8px; text-align: center; }
            .nav-links { justify-content: center; flex-wrap: wrap; gap: 6px; }
            .menu-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo" onclick="gantiHalaman('beranda')">KFC</div>
        <nav class="nav-links">
            <a onclick="gantiHalaman('beranda')">Beranda</a>
            <a onclick="gantiHalaman('menu')">Menu</a>
            <a onclick="gantiHalaman('promo')">Promo</a>
            <a onclick="gantiHalaman('kontak')">Kontak</a>
        </nav>
    </header>

    <!-- 1. HALAMAN BERANDA -->
    <section id="beranda" class="page-section active">
        <div class="hero">
            <h1>Jagonya Ayam!</h1>
            <p>Nikmati kelezatan ayam goreng renyah dan berbagai menu andalan KFC Indonesia langsung di genggaman Anda.</p>
        </div>

        <div class="banner-diskon">
            <h3>🔥 PROMO J,T,W (Jawara, Taktis, Wajib) 🔥</h3>
            <p>Nikmati paket hemat spesial eksklusif pemesanan aplikasi hari ini!</p>
        </div>

        <h2 class="section-title">Menu Pilihan Terfavorit</h2>
        <div class="menu-grid">
            <div class="menu-item">
                <span class="badge-diskon">Favorit</span>
                <img src="https://images.unsplash.com/photo-1626645738196-c2a7c87a8f58?w=500&auto=format&fit=crop&q=60" alt="Ayam">
                <div>
                    <h3>Chicken Attack</h3>
                    <div class="price-box"><div class="price">Rp 22.727</div></div>
                </div>
                <button onclick="prosesCheckout('Chicken Attack', 22727)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Paket</span>
                <img src="https://images.unsplash.com/photo-1562967914-608f82629710?w=500&auto=format&fit=crop&q=60" alt="Bucket">
                <div>
                    <h3>Super Besar 1</h3>
                    <div class="price-box"><div class="price">Rp 39.091</div></div>
                </div>
                <button onclick="prosesCheckout('Super Besar 1', 39091)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Burger</span>
                <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500&auto=format&fit=crop&q=60" alt="Zinger">
                <div>
                    <h3>Zinger Burger</h3>
                    <div class="price-box"><div class="price">Rp 45.455</div></div>
                </div>
                <button onclick="prosesCheckout('Zinger Burger', 45455)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Keluarga</span>
                <img src="https://images.unsplash.com/photo-1562967914-608f82629710?w=500&auto=format&fit=crop&q=60" alt="Bucket">
                <div>
                    <h3>The Bucket (9 Ayam)</h3>
                    <div class="price-box"><div class="price">Rp 165.000</div></div>
                </div>
                <button onclick="prosesCheckout('The Bucket', 165000)">Pesan</button>
            </div>
        </div>

        <h2 class="section-title">Kenapa Memesan di KFC?</h2>
        <div class="info-card">
            <h3>🌟 Ayam Segar & Berkualitas Tinggi</h3>
            <p>Dipilih dari peternakan lokal terbaik dengan proses pemotongan bersertifikat Halal MUI serta standar kebersihan tinggi.</p>
        </div>
        <div class="info-card">
            <h3>🚀 Pengantaran Cepat & Hangat</h3>
            <p>Jaringan gerai yang luas memastikan pesanan Anda tiba tepat waktu dalam kondisi hangat dan renyah.</p>
        </div>
        <div class="info-card">
            <h3>💳 Metode Pembayaran Fleksibel</h3>
            <p>Mendukung berbagai sistem pembayaran digital modern mulai dari QRIS, GoPay, OVO, transfer bank, hingga Bayar di Tempat (COD).</p>
        </div>

        <h2 class="section-title">Berita & Informasi Terbaru</h2>
        <div class="info-card">
            <span class="news-date">November 2026</span>
            <h3>Perluasan Layanan Drive-Thru 24 Jam</h3>
            <p>KFC Indonesia terus meningkatkan kenyamanan pelanggan dengan membuka jalur layanan kendaraan bermotor tanpa henti di kota-kota besar.</p>
        </div>
        <div class="info-card">
            <span class="news-date">Oktober 2026</span>
            <h3>Komitmen Kepedulian Lingkungan Gerai Hijau</h3>
            <p>Seluruh cabang kini mulai mengimplementasikan pengurangan plastik sekali pakai demi mendukung pelestarian lingkungan hidup.</p>
        </div>

        <h2 class="section-title">Apa Kata Pelanggan Setia?</h2>
        <div class="info-card">
            <h3>⭐ Rina S. (Jakarta)</h3>
            <p>"Super Besar 1 andalan banget kalau lagi lapar siang-siap. Ayamnya selalu panas, kulitnya crispy, dan pengirimannya super cepat!"</p>
        </div>
        <div class="info-card">
            <h3>⭐ Budi H. (Surabaya)</h3>
            <p>"Fitur pesanan di web clone ini praktis banget, mirip aslinya dan langsung bisa pilih menu favorit keluarga tanpa ribet."</p>
        </div>
    </section>

    <!-- 2. HALAMAN MENU LENGKAP -->
    <section id="menu" class="page-section">
        <h2 class="section-title" style="margin-top:0;">Katalog Menu Resmi KFC</h2>
        <div class="menu-grid">
            <div class="menu-item">
                <span class="badge-diskon">Andalan</span>
                <img src="https://images.unsplash.com/photo-1626645738196-c2a7c87a8f58?w=500&auto=format&fit=crop&q=60" alt="Super Besar 1">
                <div>
                    <h3>Super Besar 1</h3>
                    <div class="price-box"><div class="price">Rp 39.091</div></div>
                </div>
                <button onclick="prosesCheckout('Super Besar 1', 39091)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Porsi Besar</span>
                <img src="https://images.unsplash.com/photo-1562967914-608f82629710?w=500&auto=format&fit=crop&q=60" alt="Super Besar 2">
                <div>
                    <h3>Super Besar 2</h3>
                    <div class="price-box"><div class="price">Rp 53.636</div></div>
                </div>
                <button onclick="prosesCheckout('Super Besar 2', 53636)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Ekonomis</span>
                <img src="https://images.unsplash.com/photo-1626645738196-c2a7c87a8f58?w=500&auto=format&fit=crop&q=60" alt="Chicken Attack">
                <div>
                    <h3>Chicken Attack</h3>
                    <div class="price-box"><div class="price">Rp 22.727</div></div>
                </div>
                <button onclick="prosesCheckout('Chicken Attack', 22727)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Keluarga</span>
                <img src="https://images.unsplash.com/photo-1562967914-608f82629710?w=500&auto=format&fit=crop&q=60" alt="The Bucket">
                <div>
                    <h3>The Bucket (9 Ayam)</h3>
                    <div class="price-box"><div class="price">Rp 165.000</div></div>
                </div>
                <button onclick="prosesCheckout('The Bucket', 165000)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Burger</span>
                <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500&auto=format&fit=crop&q=60" alt="Zinger">
                <div>
                    <h3>Zinger Burger</h3>
                    <div class="price-box"><div class="price">Rp 45.455</div></div>
                </div>
                <button onclick="prosesCheckout('Zinger Burger', 45455)">Pesan</button>
            </div>
            <div class="menu-item">
                <span class="badge-diskon">Burger</span>
                <img src="https://images.unsplash.com/photo-1568901346375-23c9450c58cd?w=500&auto=format&fit=crop&q=60" alt="OR Burger">
                <div>
                    <h3>O.R. Burger</h3>
                    <div class="price-box"><div class="price">Rp 34.545</div></div>
                </div>
                <button onclick="prosesCheckout('O.R. Burger', 34545)">Pesan</button>
            </div>
        </div>
    </section>

    <!-- 3. HALAMAN PROMO -->
    <section id="promo" class="page-section">
        <h2 class="section-title" style="margin-top:0;">Pusat Promo & Penawaran Resmi</h2>
        <div class="info-card">
            <h3>🔥 Promo Takeaway / Dine-In Special</h3>
            <p>Nikmati berbagai penawaran paket hemat harian yang tersedia secara langsung di gerai KFC terdekat maupun pemesanan via aplikasi.</p>
        </div>
        <div class="info-card">
            <h3>🎉 Paket Dukungan Acara / Catering</h3>
            <p>Solusi praktis dan lezat untuk ulang tahun, rapat kantor, atau acara keluarga besar dengan pilihan menu porsi melimpah.</p>
        </div>
    </section>

    <!-- 4. HALAMAN KONTAK -->
    <section id="kontak" class="page-section">
        <h2 class="section-title" style="margin-top:0;">Tentang Kami & Layanan</h2>
        <div class="info-card">
            <h3>PT Fast Food Indonesia Tbk</h3>
            <p>Pemegang hak waralaba tunggal merek KFC di Indonesia yang berdiri sejak tahun 1978 dan membuka gerai pertamanya di Jakarta pada tahun 1979.</p>
        </div>
        <div class="info-card">
            <h3>Layanan Pelanggan Resmi</h3>
            <p>📞 Layanan Pelanggan Nasional: 14022<br>📧 Situs Resmi: kfcindonesia.com</p>
        </div>
    </section>

    <!-- 5. HALAMAN CHECKOUT -->
    <section id="checkout" class="page-section">
        <h2 class="section-title" style="margin-top:0;">Formulir Checkout Pesanan</h2>
        <div class="info-card">
            <h3>Ringkasan Pesanan Anda</h3>
            <div class="order-summary">
                <div>
                    <span id="summary-nama-menu">Menu Pilihan</span>
                    <span id="summary-harga-satuan">Rp 0</span>
                </div>
                <div>
                    <span>Biaya Layanan & Pengiriman</span>
                    <span>Rp 15.000</span>
                </div>
                <div class="order-total">
                    <span>Total Pembayaran</span>
                    <span id="summary-total">Rp 0</span>
                </div>
            </div>

            <h3>Informasi Pengiriman</h3>
            <div class="form-group">
                <label>Nama Lengkap Penerima</label>
                <input type="text" id="nama-pembeli" placeholder="Masukkan nama Anda">
            </div>
            <div class="form-group">
                <label>Nomor Telepon / WhatsApp</label>
                <input type="text" id="telp-pembeli" placeholder="Contoh: 08123456789">
            </div>
            <div class="form-group">
                <label>Alamat Lengkap Pengiriman</label>
                <textarea id="alamat-pembeli" rows="3" placeholder="Jalan, Nomor Rumah, Patokan..."></textarea>
            </div>
            <div class="form-group">
                <label>Metode Pembayaran</label>
                <select id="metode-pembayaran">
                    <option value="QRIS">QRIS (GoPay, OVO, Dana, BCA Mobile)</option>
                    <option value="Transfer Bank">Transfer Bank (BCA / Mandiri / BNI)</option>
                    <option value="COD">Bayar di Tempat (COD)</option>
                </select>
            </div>

            <button class="btn-konfirmasi" onclick="selesaikanPesanan()">Konfirmasi & Bayar Pesanan</button>
        </div>
    </section>

    <footer>
        <div class="footer-links">
            <a onclick="gantiHalaman('kontak')">Tentang Kami</a> | 
            <a onclick="gantiHalaman('kontak')">Kebijakan Privasi</a> | 
            <a onclick="gantiHalaman('kontak')">Syarat & Ketentuan</a>
        </div>
        <p>&copy; 2026 KFC Clone Indonesia. Hak Cipta Dilindungi.</p>
    </footer>

    <script>
        let menuTerpilih = "";

        /**
         * @param {string} idHalaman
         */
        function gantiHalaman(idHalaman) {
            const sections = document.querySelectorAll('.page-section');
            sections.forEach(sec => sec.classList.remove('active'));

            const target = document.getElementById(idHalaman);
            if (target) {
                target.classList.add('active');
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        /**
         * @param {string} nama
         * @param {number} harga
         */
        function prosesCheckout(nama, harga) {
            menuTerpilih = nama;
            let ongkir = 15000;
            let total = harga + ongkir;

            document.getElementById('summary-nama-menu').innerText = nama;
            document.getElementById('summary-harga-satuan').innerText = "Rp " + harga.toLocaleString('id-ID');
            document.getElementById('summary-total').innerText = "Rp " + total.toLocaleString('id-ID');

            gantiHalaman('checkout');
        }

        function selesaikanPesanan() {
            let nama = document.getElementById('nama-pembeli').value;
            let telp = document.getElementById('telp-pembeli').value;
            let alamat = document.getElementById('alamat-pembeli').value;
            let pembayaran = document.getElementById('metode-pembayaran').value;

            if(nama === "" || telp === "" || alamat === "") {
                alert("Mohon lengkapi nama, nomor telepon, dan alamat pengiriman Anda!");
                return;
            }

            alert("Terima kasih, " + nama + "! Pesanan " + menuTerpilih + " Anda berhasil dibuat.\nMetode: " + pembayaran + "\nKurir akan segera mengirimkan pesanan ke alamat Anda.");
            gantiHalaman('beranda');
        }
    </script>

</body>
</html>
