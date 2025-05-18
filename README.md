<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NSTFOOD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fffaf0;
        }
        header {
            background-color: #e67e22;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #f39c12;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 20px;
        }
        h2 {
            color: #d35400;
        }
        .menu-section {
            margin-bottom: 30px;
        }
        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        .menu-item img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            margin-right: 15px;
            border-radius: 10px;
        }
        footer {
            background-color: #e67e22;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .wa-link {
            display: inline-block;
            margin-top: 20px;
            background-color: #25D366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .order-form {
            background-color: #ffe8d6;
            padding: 20px;
            border-radius: 10px;
            margin-top: 30px;
        }
        .order-form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        .order-form input, .order-form select, .order-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .order-form button {
            background-color: #e67e22;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Selamat Datang di NSTFOOD</h1>
        <p>Warteg dengan cita rasa Nusantara</p>
    </header>
    <nav>
        <a href="#makanan">Makanan</a>
        <a href="#minuman">Minuman</a>
        <a href="#pesan">Pesan Sekarang</a>
        <a href="https://wa.me/6281297718114" target="_blank">Hubungi Kami</a>
    </nav>
    <main>
        <section id="makanan" class="menu-section">
            <h2>Jenis Makanan</h2>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/nasi-uduk-indonesian-food_74190-1232.jpg" alt="Nasi Uduk">
                <span>Nasi Uduk</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/nasi-rames-traditional-food_74190-3125.jpg" alt="Nasi Rames">
                <span>Nasi Rames</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/fried-chicken-with-rice_1339-1317.jpg" alt="Ayam Goreng">
                <span>Ayam Goreng</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/fried-tempeh_1339-1320.jpg" alt="Tempe Orek">
                <span>Tempe Orek</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/indonesian-kangkung-vegetable-dish_1150-11898.jpg" alt="Tumis Kangkung">
                <span>Tumis Kangkung</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/telur-balado_1150-11900.jpg" alt="Telur Balado">
                <span>Telur Balado</span>
            </div>
        </section>
        <section id="minuman" class="menu-section">
            <h2>Aneka Minuman</h2>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/sweet-iced-tea_144627-5113.jpg" alt="Es Teh Manis">
                <span>Es Teh Manis</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/iced-orange-juice_1339-1438.jpg" alt="Es Jeruk">
                <span>Es Jeruk</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/tea-cup-steam_1339-1421.jpg" alt="Teh Hangat">
                <span>Teh Hangat</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/black-coffee-cup_1339-1471.jpg" alt="Kopi Hitam">
                <span>Kopi Hitam</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/ginger-milk_1150-11991.jpg" alt="Susu Jahe">
                <span>Susu Jahe</span>
            </div>
            <div class="menu-item">
                <img src="https://img.freepik.com/free-photo/wedang-uwuh-herbal-drink_1150-11994.jpg" alt="Wedang Uwuh">
                <span>Wedang Uwuh</span>
            </div>
        </section>
        <section id="pesan" class="order-form">
            <h2>Formulir Pemesanan</h2>
            <form action="https://wa.me/6281297718114" target="_blank" onsubmit="return confirm('Lanjutkan pemesanan via WhatsApp?');">
                <label for="nama">Nama:</label>
                <input type="text" id="nama" name="nama" required>

                <label for="menu">Pilih Menu:</label>
                <select id="menu" name="menu" required>
                    <option value="Nasi Uduk">Nasi Uduk</option>
                    <option value="Nasi Rames">Nasi Rames</option>
                    <option value="Ayam Goreng">Ayam Goreng</option>
                    <option value="Tempe Orek">Tempe Orek</option>
                    <option value="Tumis Kangkung">Tumis Kangkung</option>
                    <option value="Telur Balado">Telur Balado</option>
                    <option value="Es Teh Manis">Es Teh Manis</option>
                    <option value="Es Jeruk">Es Jeruk</option>
                    <option value="Teh Hangat">Teh Hangat</option>
                    <option value="Kopi Hitam">Kopi Hitam</option>
                    <option value="Susu Jahe">Susu Jahe</option>
                    <option value="Wedang Uwuh">Wedang Uwuh</option>
                </select>

                <label for="catatan">Catatan Tambahan:</label>
                <textarea id="catatan" name="catatan" rows="4"></textarea>

                <button type="submit">Pesan Sekarang</button>
            </form>
        </section>
        <a class="wa-link" href="https://wa.me/6281297718114" target="_blank">Chat via WhatsApp</a>
    </main>
    <footer>
        <p>&copy; 2025 NSTFOOD. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
