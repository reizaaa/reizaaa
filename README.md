## Hi there 👋

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>SmartHome AI Speaker – Perkenalan Produk</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <section class="hero">
    <div class="overlay"></div>
    <div class="hero-content">
      <h1>SmartHome AI Speaker</h1>
      <p>Speaker pintar dengan AI canggih, kendali rumah hanya dengan suara. Suara jernih, desain modern, dan fitur smart home terintegrasi!</p>
      <a href="#features" class="cta-btn">Jelajahi Fitur</a>
    </div>
  </section>

  <section class="features" id="features">
    <h2>Fitur Unggulan</h2>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">🎤</div>
        <h3>Voice Assistant</h3>
        <p>Perintah suara cerdas, terintegrasi Google & Alexa.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📶</div>
        <h3>WiFi & Bluetooth</h3>
        <p>Koneksi mudah ke semua perangkat Anda.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">🔊</div>
        <h3>Hi-Fi Sound</h3>
        <p>Audio jernih, bass kuat, cocok untuk hiburan.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">💡</div>
        <h3>Smart Home Control</h3>
        <p>Kendalikan lampu, AC & perangkat rumah pintar.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📱</div>
        <h3>Aplikasi Mobile</h3>
        <p>Pantau & atur speaker dari aplikasi smartphone.</p>
      </div>
    </div>
  </section>

  <section class="carousel-section">
    <h2>Galeri Produk</h2>
    <div class="carousel-container">
      <button class="carousel-btn left" onclick="prevImage()">&#10094;</button>
      <img id="carousel-img" src="data:image/jpeg;base64,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"alt="Produk 1">
      <button class="carousel-btn right" onclick="nextImage()">&#10095;</button>
    </div>
    <div class="carousel-indicator" id="carousel-indicator"></div>
  </section>

  <section class="review-section">
    <h2>Testimoni Pengguna</h2>
    <div id="reviews-list">
      <!-- Reviews tampil di sini -->
    </div>
    <div class="review-form">
      <h3>Tambah Review Anda</h3>
      <input type="text" id="reviewer-name" placeholder="Nama Anda" required>
      <textarea id="review-text" rows="2" placeholder="Tulis review..." required></textarea>
      <div class="rating-select">
        Rating:
        <span id="rating-stars">
          <span data-star="1">&#9733;</span>
          <span data-star="2">&#9733;</span>
          <span data-star="3">&#9733;</span>
          <span data-star="4">&#9733;</span>
          <span data-star="5">&#9733;</span>
        </span>
      </div>
      <button onclick="submitReview()">Kirim</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 SmartHome AI Speaker | Desain oleh reizaaa</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
