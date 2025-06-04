<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warung Bakso Pak Slamet</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Warung Bakso Pak Slamet</h1>
        <nav>
            <ul>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#tentang">Tentang</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="hero">
            <h2>Bakso Lezat, Harga Bersahabat!</h2>
            <p>Nikmati bakso kenyal dengan kuah gurih khas Warung Bakso Pak Slamet.</p>
        </section>
        <section id="menu">
            <h2>Menu Kami</h2>
            <div class="menu-list">
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80" alt="Bakso Biasa">
                    <h3>Bakso Biasa</h3>
                    <p>Bakso sapi dengan kuah segar dan mie.</p>
                    <span class="harga">Rp15.000</span>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1502741338009-cac2772e18bc?auto=format&fit=crop&w=400&q=80" alt="Bakso Urat">
                    <h3>Bakso Urat</h3>
                    <p>Bakso urat spesial, kenyal dan gurih.</p>
                    <span class="harga">Rp18.000</span>
                </div>
                <div class="menu-item">
                    <img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c?auto=format&fit=crop&w=400&q=80" alt="Bakso Telur">
                    <h3>Bakso Telur</h3>
                    <p>Bakso isi telur ayam, cocok untuk anak-anak.</p>
                    <span class="harga">Rp20.000</span>
                </div>
            </div>
        </section>
        <section id="tentang">
            <h2>Tentang Warung Kami</h2>
            <p>Warung Bakso Pak Slamet berdiri sejak 1998, selalu menggunakan bahan-bahan segar dan resep turun-temurun keluarga. Kami berkomitmen memberikan rasa terbaik untuk setiap pelanggan.</p>
        </section>
        <section id="kontak">
            <h2>Kontak</h2>
            <p>Alamat: Jl. Kenangan No. 12, Yogyakarta</p>
            <p>Telepon: 0812-3456-7890</p>
            <form id="formKontak">
                <input type="text" name="nama" placeholder="Nama Anda" required>
                <input type="email" name="email" placeholder="Email Anda" required>
                <textarea name="pesan" placeholder="Pesan" required></textarea>
                <button type="submit">Kirim</button>
            </form>
            <div id="pesanSukses" style="display:none;">Pesan Anda telah terkirim!</div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Warung Bakso Pak Slamet</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
