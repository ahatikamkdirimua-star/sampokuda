<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Shampo Kuda Anti Hairfall</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- GOOGLE FONT -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

<style>
:root{
  --gold:#b8933d;
  --dark:#111;
  --gray:#666;
  --light:#f9f9f9;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:'Poppins',sans-serif;
  background:#fff;
  color:var(--dark);
  line-height:1.7;
}

/* CONTAINER */
.container{
  width:90%;
  max-width:1100px;
  margin:auto;
}

/* NAV */
nav{
  background:#000;
  padding:18px 0;
}

nav .container{
  display:flex;
  justify-content:space-between;
  align-items:center;
  color:#fff;
}

nav strong{
  color:var(--gold);
  font-size:20px;
}

/* HERO */
.hero{
  background:#111;
  color:#fff;
  padding:100px 0;
}

.hero .container{
  display:grid;
  grid-template-columns:1fr 1fr;
  align-items:center;
  gap:40px;
}

.hero h1{
  font-size:42px;
  margin-bottom:20px;
}

.hero p{
  color:#ccc;
  margin-bottom:30px;
}

.hero img{
  width:100%;
  max-width:380px;
  display:block;
  margin:auto;
}

.btn{
  display:inline-block;
  background:var(--gold);
  color:#000;
  padding:14px 30px;
  border-radius:40px;
  font-weight:600;
  text-decoration:none;
  transition:.3s;
}

.btn:hover{
  opacity:.85;
}

/* SECTION */
section{
  padding:80px 0;
}

section h2{
  font-size:32px;
  margin-bottom:20px;
  text-align:center;
}

/* BENEFITS */
.benefits{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:30px;
  margin-top:40px;
}

.card{
  background:var(--light);
  padding:30px;
  border-radius:15px;
  text-align:center;
  box-shadow:0 8px 20px rgba(0,0,0,.05);
}

.card h3{
  margin-bottom:10px;
  font-size:18px;
}

/* PRODUCT DETAIL */
.product-detail{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:50px;
  align-items:center;
  margin-top:40px;
}

.product-detail ul{
  margin-top:20px;
  padding-left:20px;
}

.product-detail li{
  margin-bottom:10px;
}

/* CTA SECTION */
.cta-section{
  background:#000;
  color:#fff;
  text-align:center;
  padding:80px 0;
}

.cta-section h2{
  margin-bottom:30px;
}

/* FLOAT WA */
.wa-float{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:#fff;
  padding:14px 20px;
  border-radius:50px;
  font-weight:600;
  text-decoration:none;
  box-shadow:0 8px 20px rgba(0,0,0,.3);
}

/* RESPONSIVE */
@media(max-width:900px){

  .hero .container,
  .product-detail{
    grid-template-columns:1fr;
    text-align:center;
  }

  .benefits{
    grid-template-columns:1fr;
  }

}
</style>
</head>

<body>

<!-- NAV -->
<nav>
  <div class="container">
    <strong>Shampo Kuda</strong>
    <div>Anti Hairfall Treatment</div>
  </div>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="container">
    <div>
      <h1>Rambut Lebih Kuat & Tidak Mudah Rontok</h1>
      <p>
        Shampo Kuda membantu memperkuat akar rambut dan menjaga
        kesehatan kulit kepala untuk tampilan rambut lebih tebal.
      </p>
      <a href="https://wa.me/6281234567890?text=Halo%20saya%20ingin%20pesan%20Shampo%20Kuda"
         class="btn">Pesan via WhatsApp</a>
    </div>
    <div>
      <img src="https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//catalog-image/96/MTA-114383193/no_brand_the_caviar_sampo_kuda_shampoo_original_bpom_caviar_full27_pcaj2wy4.jpg"
           alt="Shampo Kuda">
    </div>
  </div>
</div>

<!-- BENEFITS -->
<section>
  <div class="container">
    <h2>Manfaat Shampo Kuda</h2>
    <div class="benefits">
      <div class="card">
        <h3>Mengurangi Kerontokan</h3>
        <p>Membantu mengurangi rambut rontok akibat akar yang lemah.</p>
      </div>
      <div class="card">
        <h3>Memperkuat Akar</h3>
        <p>Menutrisi kulit kepala untuk rambut lebih kokoh.</p>
      </div>
      <div class="card">
        <h3>Rambut Lebih Tebal</h3>
        <p>Membuat rambut terasa lebih bervolume & sehat.</p>
      </div>
    </div>
  </div>
</section>

<!-- DETAIL -->
<section>
  <div class="container">
    <h2>Tentang Produk</h2>
    <div class="product-detail">
      <img src="https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//catalog-image/96/MTA-114383193/no_brand_the_caviar_sampo_kuda_shampoo_original_bpom_caviar_full27_pcaj2wy4.jpg">
      <div>
        <p>
          Diformulasikan untuk membantu menjaga keseimbangan kulit kepala
          dan memperkuat struktur rambut secara menyeluruh.
        </p>
        <ul>
          <li>Cocok untuk pria & wanita</li>
          <li>Aman untuk penggunaan rutin</li>
          <li>Mudah dibilas & tidak membuat kering</li>
          <li>Digunakan secara teratur untuk hasil optimal</li>
        </ul>
        <br>
        <a href="https://wa.me/6281234567890?text=Halo%20saya%20ingin%20pesan%20Shampo%20Kuda"
           class="btn">Order Sekarang</a>
      </div>
    </div>
  </div>
</section>

<!-- CTA -->
<div class="cta-section">
  <div class="container">
    <h2>Mulai Perawatan Rambutmu Hari Ini</h2>
    <a href="https://wa.me/6281234567890?text=Halo%20saya%20ingin%20pesan%20Shampo%20Kuda"
       class="btn">Chat WhatsApp Sekarang</a>
  </div>
</div>

<footer style="text-align:center;padding:30px;font-size:14px;color:#777;">
  © 2026 Shampo Kuda Anti Hairfall
</footer>

<a href="https://wa.me/6281234567890?text=Halo%20saya%20ingin%20pesan%20Shampo%20Kuda"
   class="wa-float">WhatsApp</a>

</body>
</html>
