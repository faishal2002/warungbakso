<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="Warung Bakso Pak Joni menyajikan bakso lezat dengan resep turun temurun sejak 1995" />
    <title>Warung Bakso Pak Joni - Bakso Lezat dengan Rasa Autentik</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            background-color: #f9f5f0;
            padding: 10px;
        }
        
        header {
            background-color: #c62828;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        
        .logo {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-style: italic;
        }
        
        nav {
            background-color: #e53935;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        
        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        
        nav li {
            margin: 0 15px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        
        .container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .main-content {
            flex: 3;
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .sidebar {
            flex: 1;
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .menu-item {
            margin-bottom: 30px;
            border-bottom: 1px dashed #ddd;
            padding-bottom: 20px;
        }
        
        .menu-item h3 {
            color: #c62828;
            margin-bottom: 5px;
        }
        
        .price {
            font-weight: bold;
            color: #e53935;
        }
        
        .promo-banner {
            background-color: #ffeb3b;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
            margin-bottom: 20px;
            font-weight: bold;
        }
        
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            border-radius: 5px;
        }
        
        .testimonial {
            background-color: #f5f5f5;
            padding: 15px;
            border-left: 4px solid #c62828;
            margin-bottom: 15px;
        }
        
        .testimonial-author {
            font-weight: bold;
            text-align: right;
            font-style: italic;
        }
        
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Warung Bakso Pak Joni</div>
        <div class="tagline">Bakso Lezat dengan Rasa Autentik Sejak 1995</div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#tentang">Tentang Kami</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#lokasi">Lokasi</a></li>
            <li><a href="#kontak">Kontak</a></li>
        </ul>
    </nav>
    
    <div class="promo-banner">
        PROMO SPESIAL! Setiap Pembelian 5 Porsi Bakso Gratis 1 Es Teh
    </div>
    
    <div class="container">
        <main class="main-content">
            <section id="tentang">
                <h2>Tentang Warung Bakso Pak Joni</h2>
                <p>Warung Bakso Pak Joni telah melayani pelanggan dengan bakso lezat sejak tahun 1995. Kami menggunakan bahan-bahan pilihan dan resep turun temurun yang menjadikan bakso kami istimewa. Daging sapi segar, bumbu rempah pilihan, dan kuah kaldu yang gurih adalah rahasia kenikmatan bakso kami.</p>
                
                <div class="testimonial">
                    <p>"Bakso terenak yang pernah saya coba! Tekstur kenyalnya pas, kuahnya gurih, dan penyajiannya cepat. Sudah langganan sejak 5 tahun lalu!"</p>
                    <div class="testimonial-author">- Budi, Pelanggan Setia</div>
                </div>
            </section>
            
            <section id="menu">
                <h2>Menu Andalan Kami</h2>
                
                <div class="menu-item">
                    <h3>Bakso Spesial</h3>
                    <p>Bakso daging sapi pilihan dengan tambahan mie, tahu, pangsit, dan sayuran segar.</p>
                    <p class="price">Rp 25.000</p>
                </div>
                
                <div class="menu-item">
                    <h3>Bakso Urat</h3>
                    <p>Bakso dengan campuran daging dan urat sapi yang memberikan tekstur unik dan kenikmatan ekstra.</p>
                    <p class="price">Rp 30.000</p>
                </div>
                
                <div class="menu-item">
                    <h3>Bakso Mercon</h3>
                    <p>Untuk pecinta pedas! Bakso dengan isian cabai rawit yang akan membuat lidah Anda terbakar.</p>
                    <p class="price">Rp 28.000</p>
                </div>
                
                <div class="menu-item">
                    <h3>Es Teh Manis</h3>
                    <p>Penyegar dahaga yang cocok menemani bakso panas Anda.</p>
                    <p class="price">Rp 5.000</p>
                </div>
            </section>
            
            <section id="lokasi">
                <h2>Lokasi dan Jam Buka</h2>
                <p>Warung Bakso Pak Joni berlokasi di:</p>
                <p><strong>Jl. Raya Bakso No. 123, Kelurahan Bakso Asri, Kecamatan Bakso Enak, Kota Bakso</strong></p>
                <p>Jam Buka:</p>
                <ul>
                    <li>Senin-Jumat: 08.00 - 21.00 WIB</li>
                    <li>Sabtu-Minggu: 08.00 - 22.00 WIB</li>
                </ul>
            </section>
        </main>
        
        <aside class="sidebar">
            <h3>Promo Hari Ini</h3>
            <p>Setiap pembelian 3 porsi bakso dapatkan diskon 10%!</p>
            
            <h3>Layanan Kami</h3>
            <ul>
                <li>Makan di tempat</li>
                <li>Take away</li>
                <li>Pesan antar (minimal order Rp 50.000)</li>
            </ul>
            
            <h3>Kontak Kami</h3>
            <p><strong>Telepon:</strong> 0812-3456-7890</p>
            <p><strong>WhatsApp:</strong> 0812-3456-7890</p>
            <p><strong>Instagram:</strong> @warungbakso_pakjoni</p>
            
            <h3>Foto-foto</h3>
            <p>GALERI FOTO BAKSO DAN WARUNG</p>
        </aside>
    </div>
    
    <footer>
        <p>Copyright © 2023 Warung Bakso Pak Joni. Hak Cipta Dilindungi.</p>
        <p>Dibuat dengan cinta untuk pecinta bakso sejati</p>
    </footer>
</body>
</html>
