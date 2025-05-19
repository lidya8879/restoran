# restoran
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Resto Nusantara</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Resto Nusantara</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#order">Pesan</a>
      <a href="#contact">Kontak</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Makanan Tradisional dengan Rasa Autentik</h2>
    <p>Datang dan nikmati hidangan khas Indonesia dari Sabang sampai Merauke.</p>
  </section>

  <section id="menu">
    <h2>🍽 Menu Kami</h2>
    <div class="menu-items">
      <div class="item">
        <img src="https://via.placeholder.com/150" alt="Nasi Goreng">
        <h3>Nasi Goreng</h3>
        <p>Rp 25.000</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/150" alt="Sate Ayam">
        <h3>Sate Ayam</h3>
        <p>Rp 30.000</p>
      </div>
    </div>
  </section>

  <section id="order">
    <h2>📝 Pesan Sekarang</h2>
    <form>
      <input type="text" placeholder="Nama Anda" required>
      <input type="number" placeholder="Jumlah Pesanan" required>
      <select required>
        <option disabled selected>Pilih Menu</option>
        <option>Nasi Goreng</option>
        <option>Sate Ayam</option>
      </select>
      <button type="submit">Kirim</button>
    </form>
  </section>

  <footer id="contact">
    <p>📍 Jl. Sudirman No. 123, Jakarta | 📞 0812-3456-7890</p>
  </footer>
</body>
</html>
