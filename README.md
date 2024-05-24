# my-web-project
public
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wisata Indonesia</title>
    <link rel="stylesheet" href="style3.css">
</head>
<body>
    <header>
        <div class="overlay">
            <h1>Ayo Jelajahi Keindahan Indonesia!</h1>
        </div>
    </header>

    <section class="intro">
        <h2>Selamat Datang di Pariwisata Indonesia</h2>
        <p>Indonesia adalah negara yang kaya akan keindahan alam, budaya yang beragam, dan warisan sejarah yang mengagumkan. Dari pantai yang memukau di Bali hingga hutan tropis di Kalimantan, ada banyak destinasi menakjubkan yang menunggu untuk dijelajahi. Indonesia merupakan salah satu negara kepulauan terbesar di dunia. Terdiri lebih dari 17.000 pulau yang membentang dari Sabang sampai Merauke menyipan aset kekayaan tak ternilai harganya. Ribuan pulau tersebut berderet-deret membentuk garis pantai yang memanjang dengan hamparan pasir putih besih yang sangat memikat. Deburan ombak bergulung-gulung mulai dari yang ombak kecil sampai ombak besar yang cocok buat pecinta olahraga surfing semuanya tersedia di Indonesia.</p>
    </section>

    <section class="destinasi">
        <h2>Destinasi Wisata Populer</h2>
        <div class="card">
            <img src="Bromo.jpg" alt="Destinasi 1">
            <h3>Gunung Bromo</h3>
            <p>Gunung Bromo atau dalam bahasa Tengger dieja "Brama", juga disebut Kaldera Tengger, adalah sebuah gunung berapi aktif di Jawa Timur, Indonesia. Gunung ini memiliki ketinggian 2.329 meter di atas permukaan laut </p>
            <a href="#">Lihat Detail</a>
        </div>
        <div class="card">
            <img src="Labuan bajo.webp" alt="Destinasi 2">
            <h3>Nama Destinasi 2</h3>
            <p>Deskripsi singkat destinasi 2</p>
            <a href="#">Lihat Detail</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 - Website Pariwisata Indonesia</p>
    </footer>
</body>
</html>
body {
    background-color: #f0f0f0; /* Warna latar belakang */
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-image: url('header-background.jpg'); /* Gambar latar belakang */
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 60px 20px; /* Menambah padding atas dan bawah */
    position: relative;
}

header .overlay {
    background-color: rgba(0, 0, 0, 0.5); /* Overlay transparan */
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

header h1 {
    margin: 0;
    font-size: 3em; /* Ukuran font lebih besar */
    z-index: 1; /* Menempatkan di atas overlay */
}

.intro {
    padding: 20px;
    text-align: center;
}

.intro h2 {
    margin-top: 0;
    font-size: 2em;
    color: #333;
}

.intro p {
    color: #666;
    font-size: 1.2em;
}

.destinasi {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    width: 300px; /* Lebar kartu */
    margin: 10px;
    padding: 20px;
    border: 1px solid #ccc;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    text-align: center;
    background-color: white; /* Warna latar belakang kartu */
    transition: transform 0.2s; /* Animasi transformasi */
}

.card:hover {
    transform: scale(1.05); /* Efek zoom saat hover */
}

.card img {
    width: 100%;
    height: 200px; /* Tinggi gambar */
    object-fit: cover;
}

.card h3 {
    margin-top: 10px;
    color: #333;
}

.card p {
    margin-bottom: 10px;
    color: #666;
}

.card a {
    display: block;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    text-decoration: none;
    border-radius: 5px; /* Sudut tombol lebih halus */
}

.card a:hover {
    background-color: #45a049; /* Warna latar belakang saat hover */
}

footer {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 10px;
    position: absolute;
    bottom: 0;
    width: 100%;
}
