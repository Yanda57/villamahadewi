
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Maha Dewi Villa — Tropical Natural Night</title>
<meta name="description" content="Villa minimalis alami di Ubud, Bali. Dapur lengkap, kamar elegan, kolam renang pribadi.">
<style>
  :root{
    --wood:#b08968;   /* coklat kayu hangat */
    --leaf:#a3b18a;   /* hijau lembut */
    --bone:#f9f7f3;   /* putih hangat */
    --dark:#1f1f1f;   /* latar belakang gelap nyaman */
    --ink:#f0f0f0;    /* teks terang */
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html,body{
    font-family:'Poppins',sans-serif;
    background:var(--dark);
    color:var(--ink);
    scroll-behavior:smooth;
  }

  /* NAV */
  header{
    position:fixed;
    top:0;left:0;width:100%;z-index:1000;
    background:rgba(25,25,25,0.8);
    backdrop-filter:blur(8px);
  }
  .nav{
    max-width:1200px;margin:auto;
    padding:14px 20px;
    display:flex;justify-content:space-between;align-items:center;
  }
  .brand{
    color:#fff;font-weight:700;letter-spacing:0.5px;
    font-size:1.2rem;
  }
  .menu a{
    color:#f9f9f9;text-decoration:none;margin-left:18px;
    font-weight:500;transition:0.3s;
  }
  .menu a:hover{color:var(--leaf)}

  /* HERO VIDEO */
  .hero{position:relative;height:100vh;overflow:hidden}
  .hero video{
    position:absolute;inset:0;width:100%;height:100%;
    object-fit:cover;filter:brightness(.65);
  }
  .hero::after{
    content:"";position:absolute;inset:0;
    background:linear-gradient(180deg,rgba(0,0,0,.5),rgba(0,0,0,.45));
    animation:fade 1.2s ease both;
  }
  @keyframes fade{from{opacity:0}to{opacity:1}}
  .heroContent{
    position:relative;z-index:2;height:100%;
    display:grid;place-items:center;text-align:center;padding:0 6vw;
  }
  .heroContent h1{
    color:#fff;font-size:clamp(28px,5vw,54px);
  }
  .heroContent p{
    color:#ddd;margin-top:12px;
  }
  .ctaWrap{margin-top:22px;display:flex;gap:12px;justify-content:center;flex-wrap:wrap}
  .btn{
    border:none;padding:12px 18px;border-radius:999px;
    cursor:pointer;font-weight:600;transition:.3s;
  }
  .btn-primary{
    background:rgba(255,255,255,0.85);
    color:#111;
    border:2px solid #ddd;
    box-shadow:0 4px 12px rgba(0,0,0,0.2);
  }
  .btn-primary:hover{
    background:#fff;
    border-color:#ccc;
  }
  .btn-outline{
    background:transparent;color:#fff;border:2px solid #ffffff80;
  }
  .btn-outline:hover{
    background:rgba(255,255,255,0.15);
  }

  section{max-width:1200px;margin:auto;padding:84px 20px}
  h2.sec{color:var(--bone);font-size:clamp(22px,3vw,32px);margin-bottom:20px;text-align:center;}

  /* ABOUT */
  #about{
    text-align:center;
    background:#2a2a2a;
    border-radius:12px;
    box-shadow:0 6px 20px -10px rgba(0,0,0,.6);
    padding:60px 30px;
  }
  #about p{
    font-size:1.1rem;line-height:1.8;
    color:#e0e0e0;max-width:850px;margin:auto;
  }

  /* GALLERY */
  #gallery{text-align:center;}
  .grid{
    display:grid;gap:14px;
    grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
    margin-top:28px;
  }
  .card{
    position:relative;overflow:hidden;border-radius:14px;
    background:#333;
    box-shadow:0 10px 18px -12px rgba(255,255,255,0.05);
    cursor:pointer;
  }
  .card img{
    width:100%;height:100%;object-fit:cover;display:block;
    transform:scale(1.02);
    transition:.4s ease;
    filter:brightness(0.9);
  }
  .card:hover img{transform:scale(1.07);filter:brightness(1.05)}
  .tag{
    position:absolute;left:10px;top:10px;background:rgba(163,177,138,.95);
    color:#0d160f;font-weight:700;padding:6px 10px;border-radius:999px;font-size:12px;
  }

  /* MODAL ZOOM */
  .modal{
    display:none;position:fixed;z-index:2000;left:0;top:0;width:100%;height:100%;
    background:rgba(0,0,0,0.9);align-items:center;justify-content:center;
  }
  .modal img{max-width:90%;max-height:80vh;border-radius:10px;}
  .close{
    position:absolute;top:30px;right:40px;color:#fff;font-size:36px;cursor:pointer;font-weight:bold;
  }
  .modal:target{display:flex;}

  /* CONTACT */
  .contact{
    background:#2b2b2b;border-radius:16px;
    box-shadow:0 12px 24px -18px rgba(0,0,0,.5);
    padding:60px;
    color:#ddd;
  }
  .contact .row{
    display:grid;gap:18px;grid-template-columns:1.1fr 1fr;
  }
  .contact a{color:var(--leaf);text-decoration:none;}
  .contact a:hover{text-decoration:underline;}

  footer{
    padding:28px 20px;text-align:center;
    color:#ccc;
    background:#151515;
  }

  @media(max-width:900px){
    .contact .row{grid-template-columns:1fr;}
  }
</style>
</head>
<body>

<header>
  <nav class="nav">
    <div class="brand">Maha Dewi Villa</div>
    <div class="menu">
      <a href="#home">Home</a>
      <a href="#about">Tentang</a>
      <a href="#gallery">Galeri</a>
      <a href="#contact">Kontak</a>
    </div>
  </nav>
</header>

<!-- HERO -->
<section id="home" class="hero">
  <video autoplay muted loop playsinline>
    <source src="WhatsApp Video 2025-11-02 at 20.16.36.mp4" type="video/mp4"/>
  </video>
  <div class="heroContent">
    <div>
      <h1>Rasakan Ketentraman Alam Bali</h1>
      <p>Villa minimalis bernuansa kayu & batu alam dengan kolam renang pribadi.</p>
      <div class="ctaWrap">
        <a class="btn btn-primary" href="https://wa.me/6281337560650" target="_blank">Reservasi via WhatsApp</a>
        <a class="btn btn-outline" href="#gallery">Lihat Galeri</a>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <h2 class="sec">Tentang Maha Dewi Villa</h2>
  <p>
    Maha Dewi Villa terletak di kawasan Ubud yang asri, memadukan desain minimalis modern dengan material kayu dan batu alam.
    Dikelilingi pemandangan tropis hijau, villa ini menghadirkan suasana damai dan nyaman. Fasilitas lengkap: dapur terbuka,
    kamar tidur elegan, kamar mandi alami, serta kolam renang pribadi yang dikelilingi taman tropis Bali.
  </p>
</section>

<!-- GALLERY -->
<section id="gallery">
  <h2 class="sec">Galeri — Dari Depan Hingga Belakang</h2>
  <p>Lihat setiap detail Maha Dewi Villa</p>

  <div class="grid">
    <a href="#img1" class="card"><span class="tag">1 · Gerbang</span><img src="depan.jpeg" alt=""></a>
    <a href="#img2" class="card"><span class="tag">2 · Fasad</span><img src="WhatsApp Image 2025-11-02 at 20.16.54.jpeg" alt=""></a>
    <a href="#img3" class="card"><span class="tag">3 · Ruang</span><img src="WhatsApp Image 2025-11-03 at 19.07.42(2).jpeg" alt=""></a>
    <a href="#img4" class="card"><span class="tag">4 · Dapur</span><img src="WhatsApp Image 2025-11-03 at 19.07.42(1).jpeg" alt=""></a>
    <a href="#img5" class="card"><span class="tag">5 · Dapur & Bar</span><img src="WhatsApp Image 2025-11-02 at 20.16.38(1).jpeg" alt=""></a>
    <a href="#img6" class="card"><span class="tag">6 · Kamar Mandi</span><img src="WhatsApp Image 2025-11-03 at 19.07.42.jpeg" alt=""></a>
    <a href="#img7" class="card"><span class="tag">7 · Vanity</span><img src="WhatsApp Image 2025-11-02 at 20.16.41(1).jpeg" alt=""></a>
    <a href="#img8" class="card"><span class="tag">8 · Kamar Tidur</span><img src="WhatsApp Image 2025-11-03 at 19.07.43.jpeg" alt=""></a>
    <a href="#img9" class="card"><span class="tag">9 · Kamar</span><img src="WhatsApp Image 2025-11-02 at 20.16.43.jpeg" alt=""></a>
    <a href="#img10" class="card"><span class="tag">10 · Kolam</span><img src="WhatsApp Image 2025-11-02 at 20.16.52.jpeg" alt=""></a>
  </div>

  <!-- Modal Zoom -->
  <div id="img1" class="modal"><a href="#gallery" class="close">&times;</a><img src="depan.jpeg"></div>
  <div id="img2" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-02 at 20.16.54.jpeg"></div>
  <div id="img3" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-03 at 19.07.42(2).jpeg"></div>
  <div id="img4" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-03 at 19.07.42(1).jpeg"></div>
  <div id="img5" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-02 at 20.16.38(1).jpeg"></div>
  <div id="img6" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-03 at 19.07.42.jpeg"></div>
  <div id="img7" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-02 at 20.16.41(1).jpeg"></div>
  <div id="img8" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-03 at 19.07.43.jpeg"></div>
  <div id="img9" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-02 at 20.16.43.jpeg"></div>
  <div id="img10" class="modal"><a href="#gallery" class="close">&times;</a><img src="WhatsApp Image 2025-11-02 at 20.16.52.jpeg"></div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
  <div class="row">
    <div>
      <h2 class="sec">Kontak & Lokasi</h2>
      <p>
        📍 Jl. Raya Petulu, Ubud, Gianyar, Bali<br>
        📞 <a href="https://wa.me/6281337560650" target="_blank">0813-3756-0650</a><br>
        ✉️ ardayanawayan@gmail.com
      </p>
    </div>
    <div>
      <iframe src="https://www.google.com/maps?q=Ubud+Bali&output=embed" width="100%" height="300" style="border:0;border-radius:12px" loading="lazy"></iframe>
    </div>
  </div>
</section>

<footer>
  © 2025 Maha Dewi Villa · Desain Gelap Nyaman · 
</footer>

</body>
</html>
