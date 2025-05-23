<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DhalRhythm - Musik Barat</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }
    .hero {
      background-image: url('logo.png');
      background-size: cover;
      background-position: center;
      height: 500px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-shadow: 2px 2px 5px #000;
    }
    .hero h1 {
      font-size: 2em;
      padding-top: 300px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .articles {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
    }
    .card h3 {
      margin: 15px;
    }
    .card p {
      margin: 0 15px 15px;
      color: #666;
    }
    .section {
      background-color: white;
      padding: 20px;
      margin-top: 40px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      margin-bottom: 15px;
      padding: 10px;
      font-size: 16px;
    }
    button {
      padding: 10px;
      background-color: #111;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>DhalRhythm</h1>
    <nav>
      <a href="#beranda">Beranda</a>
      <a href="#berita">Berita</a>
      <a href="#opini">Opini</a>
      <a href="#wawancara">Wawancara</a>
      <a href="#playlist">Playlist</a>
      <a href="#newsletter">Newsletter</a>
      <a href="#kontak">Kontak</a>
      <a href="#komentar">Komentar</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Berita & Ulasan Musik Barat Terbaru</h1>
  </div>

  <div class="container">

    <section id="beranda" class="section">
      <h2>Beranda</h2>
      <p>Selamat datang di DhalRhythm - sumber utama berita, opini, dan wawancara seputar musik barat.</p>
    </section>

    <section id="berita" class="section">
      <h2>Berita</h2>
      <div class="articles">
        <div class="card">
          <img src="Taylor Swift.png" alt="concert">
          <h3>Konser Taylor Swift Hentak Dunia</h3>
          <p>Taylor Swift memecahkan rekor penonton global dalam tur "Eras"-nya.</p>
        </div>
        <div class="card">
          <img src="Dawn FM.jpg" alt="music">
          <h3>Review Album Terbaru The Weeknd</h3>
          <p>Album "Dawn FM" menyajikan warna baru yang mengejutkan.</p>
        </div>
      </div>
    </section>

    <section id="opini" class="section">
      <h2>Opini</h2>
      <p>Apakah dominasi pop masih relevan di era musik streaming? Kami bahas dari berbagai sudut pandang.</p>
      <p>1. YA, Dominasi Pop Masih Relevan – Tapi dengan Nuansa Baru</p>
      <p>* Algoritma platform streaming mendukung pop: Genre pop, dengan struktur lagu yang catchy dan durasi yang singkat, cenderung cocok dengan algoritma Spotify, Apple Music, dan TikTok, yang mendorong engagement cepat dan repeat plays.</p>
      <p>* Hybrid genre semakin umum: Pop kini sering dikombinasikan dengan elemen hip-hop, R&B, Latin, EDM, dan bahkan country, menghasilkan subgenre seperti "bedroom pop", "alt-pop", atau "trap-pop". Artis seperti Olivia Rodrigo, Billie Eilish, dan Doja Cat adalah contoh representasi pop modern yang tidak lagi "bersih" secara genre.</p>
      <p>* Dominasi playlist editorial dan viralitas: Lagu-lagu pop cenderung lebih mudah masuk ke playlist populer seperti "Today's Top Hits" atau viral di TikTok, yang memperluas jangkauan dan memperkuat relevansinya.</p>
      <p>2. Namun, Definisi 'Dominasi' Sudah Berubah</p>
      <p># Fragmentasi selera musik: Era streaming memungkinkan pengguna untuk menjelajah genre yang lebih niche. Dengan kemudahan akses, pendengar bisa memilih folk Nordik, hyperpop, atau punk revival—sesuatu yang tidak umum di era radio.</p>
      <p># Genre non-pop juga punya panggung besar: Hip-hop tetap kuat secara global, musik Latin (seperti reggaeton) melesat lewat artis seperti Bad Bunny, dan K-pop membentuk fenomena global dengan basis penggemar yang militan.</p>
      <p># Chart tidak lagi mencerminkan satu dominasi mutlak: Di banyak negara, chart musik menampilkan genre campuran, dan lagu-lagu pop klasik harus bersaing dengan viral hits dari genre tak terduga.</p>
    </section>

    <section id="wawancara" class="section">
      <h2>Wawancara</h2>
      <p>Simak wawancara eksklusif kami dengan musisi-musisi inspiratif seputar proses kreatif dan perjalanan karier mereka, seperti Taylor Swift dan Dawn FM.</p>
      <p>Dalam edisi kali ini, Taylor Swift berbagi cerita tentang evolusi lirik personalnya dan bagaimana proses kreatif di balik album Midnights mencerminkan perjalanannya sebagai penulis lagu. Sementara itu, The Weeknd mengungkap filosofi artistik di balik konsep futuristik dan nuansa 80-an dalam album Dawn FM, yang menurutnya merupakan “sebuah siaran radio dari akhirat.”</p>
    </section>

    <section id="playlist" class="section">
      <h2>Playlist Mingguan</h2>
      <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1DXcBWIGoYBM5M" width="100%" height="152" frameborder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </section>

    <section id="newsletter" class="section">
      <h2>Berlangganan Newsletter</h2>
      <form>
        <input type="email" placeholder="Masukkan email kamu" required>
        <button type="submit">Daftar</button>
      </form>
    </section>

    <section id="kontak" class="section">
      <h2>Hubungi Kami</h2>
      <form>
        <input type="text" placeholder="Nama" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Pesan" rows="5" required></textarea>
        <button type="submit">Kirim</button>
      </form>
    </section>

    <section id="komentar" class="section">
      <h2>Kolom Komentar</h2>
      <form>
        <input type="text" placeholder="Nama Anda" required>
        <textarea placeholder="Tulis komentar Anda..." rows="4" required></textarea>
        <button type="submit">Kirim Komentar</button>
      </form>
    </section>

    <section id="profil" class="section">
      <h2>Profil Artis: Billie Eilish</h2>
      <p>Billie Eilish adalah penyanyi dan penulis lagu asal AS yang meroket dengan gaya unik dan suara khas. Lagu-lagunya sering mengangkat tema psikologis dan sosial.</p>
    </section>

  </div>

  <footer>
    <p>&copy; 2025 DhalRhythm. All rights reserved.</p>
  </footer>

  <!-- SPA Script -->
  <script>
    document.addEventListener("DOMContentLoaded", function () {
      const navLinks = document.querySelectorAll("nav a");
      const sections = document.querySelectorAll(".section");

      navLinks.forEach(link => {
        link.addEventListener("click", function (e) {
          e.preventDefault();
          const targetId = this.getAttribute("href").substring(1);

          sections.forEach(section => {
            section.style.display = (section.id === targetId) ? "block" : "none";
          });

          window.scrollTo({ top: 0, behavior: "smooth" });
        });
      });

      // Tampilkan hanya 'beranda' saat pertama kali dibuka
      sections.forEach(section => {
        section.style.display = section.id === "beranda" ? "block" : "none";
      });
    });
  </script>
</body>
</html>
