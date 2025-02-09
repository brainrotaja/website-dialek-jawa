# website-dialek-jawa
website untuk dialek jawa
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kamus Dialek Jawa</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Kamus Dialek Jawa Yogyakarta</h1>
    <nav>
      <a href="#kamus">Kamus</a>
      <a href="#belajar">Belajar</a>
      <a href="#tentang">Tentang</a>
    </nav>
  </header>
  <main>
    <section id="kamus">
      <h2>Kamus Dialek</h2>
      <input type="text" id="search" placeholder="Cari kata...">
      <div id="result">
        <!-- Hasil pencarian akan ditampilkan di sini -->
      </div>
    </section>
    <section id="belajar">
      <h2>Belajar Dialek</h2>
      <p>Pelajari dialek Jawa dengan mendengarkan audio dan mengikuti kuis interaktif!</p>
      <audio controls>
        <source src="audio/sugeng-enjing.mp3" type="audio/mpeg">
        Browser Anda tidak mendukung elemen audio.
      </audio>
    </section>
    <section id="tentang">
      <h2>Tentang Kami</h2>
      <p>Proyek ini bertujuan untuk melestarikan dialek Jawa Yogyakarta melalui teknologi digital.</p>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Kamus Dialek Jawa</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
<section id="belajar">
  <h2>Belajar Dialek</h2>
  <p>Pelajari dialek Jawa dengan mendengarkan audio dan mengikuti kuis interaktif!</p>
  
  <!-- Audio contoh -->
  <audio controls>
    <source src="audio/sugeng-enjing.mp3" type="audio/mpeg">
    Browser Anda tidak mendukung elemen audio.
  </audio>

  <!-- Tombol Menuju Kuis Quizizz -->
  <div class="quiz-container">
    <p>Uji pemahaman Anda dengan mengikuti kuis berikut:</p>
    <a href="https://quizizz.com/join" target="_blank" class="quiz-button">
      Mulai Kuis di Quizizz
    </a>
  </div>
</section>
