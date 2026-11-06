
<!DOCTYPE html>
<html lang="si">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#2c1711">
<meta name="description" content="නවරස Products — රසවත් අතුරුපස, පුඩිං සහ අයිස් පැකට්. WhatsApp හරහා ඇණවුම් කරන්න.">
<title>නවරස Products | රසයෙන් පිරුණු මොහොතක්</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700;800&family=Noto+Sans+Sinhala:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
:root{
  --ink:#2c1711;
  --brown:#49271c;
  --caramel:#bd7136;
  --gold:#f1bd68;
  --cream:#fff8ed;
  --paper:#fffdf8;
  --muted:#806e60;
  --line:#eadbc8;
  --green:#168b58;
  --shadow:0 18px 50px rgba(66,37,21,.11);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;
  background:var(--cream);
  color:var(--ink);
  font-family:'Noto Sans Sinhala','DM Sans',sans-serif;
}
button,input,textarea,select{font:inherit}
button,a{-webkit-tap-highlight-color:transparent}
a{color:inherit;text-decoration:none}
button{cursor:pointer}
.container{
  width:100%;
  max-width:none;
  margin:0;
  padding-left:clamp(16px,3vw,48px);
  padding-right:clamp(16px,3vw,48px);
}

.announcement{
  background:var(--ink);
  color:#f8dfb5;
  text-align:center;
  padding:9px 14px;
  font-size:12px;
}
.announcement span{color:var(--gold);font-weight:800}

header{
  position:sticky;
  top:0;
  z-index:20;
  background:rgba(255,253,248,.94);
  backdrop-filter:blur(16px);
  border-bottom:1px solid rgba(234,219,200,.8);
}
.nav{
  height:78px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:22px;
}
.brand{
  display:flex;
  align-items:center;
  gap:12px;
  min-width:220px;
}
.brand-mark{
  width:45px;
  height:45px;
  border-radius:15px;
  background:linear-gradient(145deg,#f6d18d,#bb7036);
  display:grid;
  place-items:center;
  color:#3d2015;
  font-size:24px;
  box-shadow:0 7px 18px rgba(189,113,54,.24);
}
.brand-title{font-size:19px;font-weight:800;line-height:1.2}
.brand-title small{
  display:block;
  font:700 9px 'DM Sans',sans-serif;
  letter-spacing:2.3px;
  color:var(--caramel);
  margin-top:5px;
}
.nav-links{
  display:flex;
  align-items:center;
  gap:24px;
  color:#715b4c;
  font-size:13px;
  font-weight:700;
}
.nav-links a:hover{color:var(--caramel)}
.nav-actions{display:flex;align-items:center;gap:10px}
.icon-button{
  border:1px solid var(--line);
  background:#fffaf2;
  color:var(--ink);
  border-radius:13px;
  padding:11px 13px;
  font-size:13px;
  font-weight:700;
  display:flex;
  align-items:center;
  gap:8px;
}
.cart-count{
  background:var(--caramel);
  color:white;
  border-radius:50%;
  min-width:20px;
  height:20px;
  display:inline-grid;
  place-items:center;
  font:700 11px 'DM Sans',sans-serif;
}
.mobile-menu{display:none}

/* HERO */
.hero{
  position:relative;
  overflow:hidden;
  padding:74px 0 68px;
  background:
    radial-gradient(circle at 81% 43%,rgba(241,189,104,.25),transparent 28%),
    linear-gradient(115deg,#fff8ec 0%,#fff4df 50%,#f7e2c4 100%);
}
.hero:before{
  content:'✦';
  position:absolute;
  font-size:300px;
  line-height:1;
  color:rgba(189,113,54,.06);
  right:-18px;
  top:-85px;
  transform:rotate(18deg);
}
.hero-grid{
  position:relative;
  display:grid;
  grid-template-columns:1.04fr .96fr;
  align-items:center;
  gap:48px;
}
.eyebrow{
  display:inline-flex;
  align-items:center;
  gap:8px;
  border:1px solid #e7c99e;
  border-radius:999px;
  padding:8px 13px;
  color:#8b542d;
  background:rgba(255,255,255,.56);
  font-size:11px;
  font-weight:800;
}
.eyebrow i{
  width:7px;
  height:7px;
  border-radius:50%;
  background:#d88b43;
  box-shadow:0 0 0 4px rgba(216,139,67,.14);
}
h1{
  font-size:clamp(37px,5vw,63px);
  line-height:1.28;
  letter-spacing:-1.5px;
  margin:20px 0 15px;
  font-weight:800;
}
h1 em{font-style:normal;color:#b56832}
.hero-copy{
  max-width:550px;
  color:#786456;
  font-size:15px;
  line-height:2.05;
  margin:0 0 25px;
}
.hero-buttons{display:flex;flex-wrap:wrap;gap:11px}
.btn{
  border:0;
  border-radius:14px;
  padding:14px 21px;
  font-size:13px;
  font-weight:800;
  display:inline-flex;
  align-items:center;
  justify-content:center;
  gap:9px;
  transition:.2s;
}
.btn:hover{transform:translateY(-2px)}
.btn-primary{
  background:var(--ink);
  color:#fff5e7;
  box-shadow:0 10px 25px rgba(44,23,17,.19);
}
.btn-light{
  border:1px solid #e2c9a7;
  background:rgba(255,255,255,.65);
  color:var(--ink);
}
.hero-note{margin-top:20px;color:#907c69;font-size:11px}
.hero-art{
  position:relative;
  min-height:390px;
  display:grid;
  place-items:center;
}
.hero-photo{
  width:min(100%,475px);
  height:375px;
  object-fit:cover;
  border-radius:34px 34px 110px 34px;
  box-shadow:0 25px 55px rgba(73,39,28,.22);
  border:8px solid rgba(255,255,255,.65);
}
.floating-tag{
  position:absolute;
  background:#fffdf8;
  border:1px solid #f0dfc8;
  padding:14px 18px;
  border-radius:17px;
  box-shadow:var(--shadow);
  font-size:12px;
  font-weight:800;
}
.floating-tag small{
  display:block;
  color:var(--muted);
  font-weight:500;
  font-size:10px;
  margin-top:4px;
}
.tag-top{top:22px;left:-10px}
.tag-bottom{right:-5px;bottom:22px}

/* TRUST */
.trust-row{
  padding:21px 0;
  background:var(--paper);
  border-bottom:1px solid var(--line);
}
.trust-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:16px;
}
.trust-item{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:10px;
  color:#6b5849;
  font-size:12px;
  font-weight:700;
}
.trust-icon{
  width:35px;
  height:35px;
  border-radius:12px;
  background:#f8ead4;
  display:grid;
  place-items:center;
  font-size:16px;
}

/* PRODUCTS */
section.section{padding:72px 0}
.section-head{
  text-align:center;
  margin:0 auto 32px;
  max-width:650px;
}
.kicker{
  color:var(--caramel);
  font:800 10px 'DM Sans',sans-serif;
  letter-spacing:2.5px;
  text-transform:uppercase;
}
.section-head h2{
  font-size:clamp(27px,3.2vw,38px);
  margin:10px 0 8px;
  font-weight:800;
}
.section-head p{
  color:var(--muted);
  font-size:13px;
  line-height:1.9;
  margin:0;
}
.filters{
  display:flex;
  justify-content:center;
  flex-wrap:wrap;
  gap:9px;
  margin:0 0 28px;
}
.filter{
  border:1px solid var(--line);
  background:#fffdf8;
  color:#745c49;
  border-radius:999px;
  padding:9px 16px;
  font-size:11px;
  font-weight:700;
}
.filter.active,.filter:hover{
  background:var(--ink);
  border-color:var(--ink);
  color:#fff3e1;
}
.products{
  display:grid;
  grid-template-columns:repeat(4,minmax(0,1fr));
  gap:18px;
}
.product-card{
  background:var(--paper);
  border:1px solid var(--line);
  border-radius:21px;
  overflow:hidden;
  box-shadow:0 8px 25px rgba(66,37,21,.045);
  transition:.22s;
}
.product-card:hover{
  transform:translateY(-5px);
  box-shadow:var(--shadow);
}
.product-image-wrap{
  height:205px;
  position:relative;
  overflow:hidden;
  background:#f1dfc5;
}
.product-image{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block;
  transition:transform .5s;
}
.product-card:hover .product-image{transform:scale(1.05)}
.product-label{
  position:absolute;
  left:12px;
  top:12px;
  background:rgba(255,253,248,.92);
  backdrop-filter:blur(8px);
  padding:6px 10px;
  border-radius:999px;
  font-size:9px;
  font-weight:800;
  color:#8c542d;
}
.product-info{padding:17px}
.product-info h3{font-size:16px;margin:0 0 7px;font-weight:800}
.product-info p{
  font-size:11px;
  line-height:1.8;
  color:var(--muted);
  min-height:40px;
  margin:0 0 14px;
}
.product-bottom{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:8px;
}
.price{color:#9a5b30;font-size:11px;font-weight:800}
.add-btn{
  border:0;
  border-radius:11px;
  background:#f4e4cc;
  color:#6e3f21;
  padding:9px 12px;
  font-size:10px;
  font-weight:800;
}
.add-btn:hover{background:var(--gold)}
.custom-order{
  margin-top:30px;
  padding:24px 26px;
  border-radius:20px;
  background:linear-gradient(110deg,#382018,#68402b);
  color:#fff4e5;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:20px;
}
.custom-order h3{margin:0 0 5px;font-size:17px}
.custom-order p{
  margin:0;
  color:#e7c8a4;
  font-size:11px;
  line-height:1.7;
}

/* ABOUT */
.about{background:#f5ead8}
.about-grid{
  display:grid;
  grid-template-columns:.95fr 1.05fr;
  gap:55px;
  align-items:center;
}
.about-photo{
  width:100%;
  height:360px;
  object-fit:cover;
  border-radius:28px;
  box-shadow:var(--shadow);
}
.about-copy h2{font-size:34px;margin:12px 0;font-weight:800}
.about-copy p{
  font-size:13px;
  line-height:2.1;
  color:#786555;
}
.about-points{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:12px;
  margin-top:20px;
}
.point{
  background:rgba(255,253,248,.75);
  border:1px solid #eadbc8;
  border-radius:13px;
  padding:13px;
  font-size:11px;
  font-weight:700;
  color:#60432f;
}
.point span{
  display:block;
  color:var(--caramel);
  font-size:18px;
  margin-bottom:5px;
}

/* ORDERING */
.order-steps{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:16px;
}
.step{
  background:var(--paper);
  border:1px solid var(--line);
  padding:22px;
  border-radius:18px;
}
.step-number{
  width:34px;
  height:34px;
  border-radius:12px;
  background:#f4e3c9;
  color:#955a2d;
  display:grid;
  place-items:center;
  font:800 12px 'DM Sans',sans-serif;
}
.step h3{font-size:14px;margin:14px 0 7px}
.step p{
  font-size:11px;
  color:var(--muted);
  line-height:1.9;
  margin:0;
}

/* CONTACT */
.contact{
  background:var(--ink);
  color:#fff4e5;
  padding:58px 0;
}
.contact-grid{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:25px;
}
.contact h2{font-size:27px;margin:0 0 8px}
.contact p{
  color:#d9bda3;
  font-size:12px;
  line-height:1.8;
  margin:0;
}
.contact-actions{display:flex;flex-wrap:wrap;gap:10px}
.wa-btn{
  background:#168b58;
  color:white;
  border:0;
  border-radius:13px;
  padding:13px 17px;
  font-size:11px;
  font-weight:800;
  display:inline-flex;
  align-items:center;
  gap:8px;
}
.wa-btn.alt{background:#236b50}

/* FOOTER */
footer{
  background:#21120e;
  color:#d6bda5;
  padding:25px 0;
  font-size:10px;
}
.footer-inner{
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:15px;
}
.footer-inner b{color:#fff0dd}
.footer-contact{display:flex;gap:16px;flex-wrap:wrap}

/* CART */
.overlay{
  position:fixed;
  inset:0;
  background:rgba(22,12,8,.55);
  z-index:40;
  opacity:0;
  visibility:hidden;
  transition:.22s;
}
.overlay.open{opacity:1;visibility:visible}
.cart-drawer{
  position:fixed;
  z-index:41;
  right:0;
  top:0;
  height:100dvh;
  width:min(460px,100%);
  background:var(--paper);
  box-shadow:-20px 0 60px rgba(0,0,0,.18);
  transform:translateX(105%);
  transition:.25s;
  display:flex;
  flex-direction:column;
}
.cart-drawer.open{transform:translateX(0)}
.drawer-head{
  padding:22px 22px 15px;
  border-bottom:1px solid var(--line);
  display:flex;
  align-items:center;
  justify-content:space-between;
}
.drawer-head h2{font-size:18px;margin:0}
.close-btn{
  border:1px solid var(--line);
  background:#fff8ed;
  border-radius:10px;
  width:35px;
  height:35px;
  font-size:19px;
  color:var(--ink);
}
.cart-items{padding:16px 22px;overflow:auto;flex:1}
.empty-cart{
  text-align:center;
  padding:45px 10px;
  color:var(--muted);
  font-size:12px;
}
.cart-line{
  display:grid;
  grid-template-columns:1fr auto;
  gap:12px;
  padding:13px 0;
  border-bottom:1px solid var(--line);
}
.cart-line strong{font-size:12px}
.cart-line small{
  display:block;
  color:var(--muted);
  font-size:10px;
  margin-top:4px;
}
.qty{display:flex;align-items:center;gap:8px}
.qty button{
  width:27px;
  height:27px;
  border:1px solid var(--line);
  border-radius:8px;
  background:#fff8ed;
  color:var(--ink);
  font-weight:800;
}
.qty span{
  font:700 12px 'DM Sans',sans-serif;
  min-width:13px;
  text-align:center;
}
.cart-form{
  border-top:1px solid var(--line);
  padding:17px 22px 22px;
  max-height:58%;
  overflow:auto;
}
.cart-form label{
  display:block;
  font-size:10px;
  font-weight:700;
  color:#6e5949;
  margin:10px 0 5px;
}
.cart-form input,.cart-form textarea,.cart-form select{
  width:100%;
  border:1px solid var(--line);
  border-radius:10px;
  background:white;
  padding:11px 12px;
  font-size:11px;
  color:var(--ink);
  outline:none;
}
.cart-form textarea{min-height:65px;resize:vertical}
.checkout-btn{
  width:100%;
  margin-top:13px;
  background:#168b58;
  color:white;
  border:0;
  border-radius:12px;
  padding:14px;
  font-size:12px;
  font-weight:800;
}
.form-note{
  font-size:9px;
  line-height:1.6;
  color:var(--muted);
  margin:9px 0 0;
}
.floating-wa{
  position:fixed;
  right:20px;
  bottom:20px;
  z-index:18;
  background:#168b58;
  color:white;
  border-radius:999px;
  padding:13px 17px;
  box-shadow:0 12px 26px rgba(22,139,88,.25);
  font-size:11px;
  font-weight:800;
  display:flex;
  align-items:center;
  gap:8px;
}
.hidden{display:none!important}

/* RESPONSIVE */
@media(max-width:950px){
  .products{grid-template-columns:repeat(2,minmax(0,1fr))}
  .hero-grid{gap:25px}
  .nav-links{gap:17px}
  .product-image-wrap{height:230px}
}
@media(max-width:700px){
  .container{
  width:100%;
  max-width:none;
}
  .nav{height:68px}
  .brand{min-width:0}
  .brand-mark{width:39px;height:39px}
  .brand-title{font-size:16px}
  .nav-links{
    display:none;
    position:absolute;
    top:68px;
    left:0;
    right:0;
    padding:16px 22px;
    background:var(--paper);
    border-bottom:1px solid var(--line);
    flex-direction:column;
    align-items:flex-start;
    gap:15px;
  }
  .nav-links.open{display:flex}
  .mobile-menu{display:inline-flex}
  .nav-actions .contact-nav{display:none}
  .hero{padding:48px 0 37px}
  .hero-grid{grid-template-columns:1fr;gap:25px}
  .hero-art{min-height:275px}
  .hero-photo{
    height:265px;
    width:90%;
    border-radius:26px 26px 75px 26px;
  }
  .tag-top{left:0;top:5px}
  .tag-bottom{right:0;bottom:0}
  .floating-tag{padding:11px 13px;font-size:10px}
  .hero-copy{font-size:13px}
  .trust-grid{gap:7px}
  .trust-item{
    font-size:9px;
    flex-direction:column;
    text-align:center;
    gap:5px;
  }
  .trust-icon{width:31px;height:31px}
  section.section{padding:56px 0}
  .products{gap:11px}
  .product-image-wrap{height:150px}
  .product-info{padding:12px}
  .product-info h3{font-size:13px}
  .product-info p{font-size:10px;min-height:48px}
  .product-bottom{align-items:flex-start;flex-direction:column}
  .add-btn{width:100%}
  .custom-order{
    padding:20px;
    align-items:flex-start;
    flex-direction:column;
  }
  .about-grid{grid-template-columns:1fr;gap:25px}
  .about-photo{height:260px}
  .about-copy h2{font-size:27px}
  .about-points{gap:8px}
  .point{font-size:10px;padding:10px}
  .order-steps{grid-template-columns:1fr}
  .contact-grid{align-items:flex-start;flex-direction:column}
  .contact h2{font-size:23px}
  .contact-actions{width:100%}
  .contact-actions a{flex:1;justify-content:center}
  .footer-inner{align-items:flex-start;flex-direction:column}
  .floating-wa{right:13px;bottom:13px;padding:11px 14px}
  .cart-form{max-height:62%}
}
@media(max-width:380px){
  .products{grid-template-columns:1fr}
  .product-image-wrap{height:210px}
  .trust-item{font-size:8px}
}
  /* NAWARASA FULL WIDTH FIX */

html,
body {
  width: 100%;
  max-width: 100%;
  margin: 0;
  overflow-x: hidden;
}

.container {
  width: 100% !important;
  max-width: none !important;
  margin-left: 0 !important;
  margin-right: 0 !important;
  padding-left: clamp(16px, 3vw, 48px) !important;
  padding-right: clamp(16px, 3vw, 48px) !important;
}

.hero-grid {
  width: 100%;
}

.products {
  width: 100%;
}

@media (max-width: 700px) {
  .container {
    width: 100% !important;
    max-width: none !important;
    padding-left: 16px !important;
    padding-right: 16px !important;
  }
}
</style>
</head>

<body>
<div class="announcement">
  නැවුම් රසය, ආදරයෙන් සකස් කළ
  <span>නවරස Products</span> වෙතින් ✨
</div>

<header>
  <div class="container nav">
    <a class="brand" href="#home" aria-label="නවරස මුල් පිටුව">
      <div class="brand-mark">✦</div>
      <div class="brand-title">
        නවරස Products
        <small>MADE WITH LOVE · SHARED WITH JOY</small>
      </div>
    </a>

    <nav class="nav-links" id="navLinks" aria-label="ප්‍රධාන මෙනුව">
      <a href="#home">මුල් පිටුව</a>
      <a href="#products">අපේ නිෂ්පාදන</a>
      <a href="#about">අප ගැන</a>
      <a href="#order">ඇණවුම් කරන හැටි</a>
      <a href="#contact">අප අමතන්න</a>
    </nav>

    <div class="nav-actions">
      <a class="icon-button contact-nav"
         href="https://wa.me/94778077332"
         target="_blank" rel="noopener">WhatsApp</a>

      <button class="icon-button" id="openCart" type="button"
              aria-label="ඇණවුම් බෑගය">
        🛍️ <span class="cart-count" id="cartCount">0</span>
      </button>

      <button class="icon-button mobile-menu" id="mobileMenu"
              type="button" aria-label="මෙනුව" aria-expanded="false">☰</button>
    </div>
  </div>
</header>

<main>
  <section class="hero" id="home">
    <div class="container hero-grid">
      <div>
        <div class="eyebrow"><i></i> රසවත් මොහොතකට පුංචි තෑග්ගක්</div>

        <h1>හැම කටකම<br><em>නවරස රසයක්!</em></h1>

        <p class="hero-copy">
          ආදරයෙන් සකස් කරන රසවත් අතුරුපස, පුඩිං සහ අයිස් පැකට්.
          ඔබේ විශේෂ මොහොත තවත් රසවත් කරගන්න — අදම අපෙන් ඇණවුම් කරන්න.
        </p>

        <div class="hero-buttons">
          <a class="btn btn-primary" href="#products">
            අපේ නිෂ්පාදන බලන්න <span>→</span>
          </a>
          <button class="btn btn-light" id="heroOrder" type="button">
            WhatsApp ඇණවුමක්
          </button>
        </div>

        <div class="hero-note">
          ♡ පවුලේ සැමට රස විඳින්න · ඇණවුම් WhatsApp හරහා
        </div>
      </div>

      <div class="hero-art">
        <img class="hero-photo"
             src="https://images.unsplash.com/photo-1488477181946-6428a0291777?auto=format&fit=crop&w=1100&q=88"
             alt="රසවත් අතුරුපස සහ පුඩිං"
             onerror="this.style.display='none'">

        <div class="floating-tag tag-top">
          🍮 රසයෙන් පිරුණු තේරීම
          <small>ඔබේ ප්‍රියතම රස සොයාගන්න</small>
        </div>

        <div class="floating-tag tag-bottom">
          ♡ ආදරයෙන් සකස් කරයි
          <small>නවරස Products</small>
        </div>
      </div>
    </div>
  </section>

  <div class="trust-row">
    <div class="container trust-grid">
      <div class="trust-item"><span class="trust-icon">🍮</span> රසවත් අතුරුපස</div>
      <div class="trust-item"><span class="trust-icon">💛</span> ආදරයෙන් සකස් කරයි</div>
      <div class="trust-item"><span class="trust-icon">💬</span> පහසු WhatsApp ඇණවුම්</div>
    </div>
  </div>

  <section class="section" id="products">
    <div class="container">
      <div class="section-head">
        <div class="kicker">OUR SWEET COLLECTION</div>
        <h2>අපේ රසවත් නිෂ්පාදන</h2>
        <p>ඔබ කැමති රසය තෝරන්න. නිෂ්පාදන සහ මිල විස්තර WhatsApp හරහා විමසන්න.</p>
      </div>

      <div class="filters" id="filters">
        <button class="filter active" data-filter="all" type="button">සියල්ල</button>
        <button class="filter" data-filter="pudding" type="button">පුඩිං</button>
        <button class="filter" data-filter="traditional" type="button">සාම්ප්‍රදායික රස</button>
        <button class="filter" data-filter="ice" type="button">අයිස් පැකට්</button>
      </div>

      <div class="products" id="productGrid">
        <article class="product-card" data-category="traditional" data-id="watalappan">
          <div class="product-image-wrap">
            <img class="product-image"
                 src="https://images.unsplash.com/photo-1578985545062-69928b1d9587?auto=format&fit=crop&w=800&q=85"
                 alt="වටලප්පන්" loading="lazy">
            <span class="product-label">ප්‍රියතම තේරීම</span>
          </div>
          <div class="product-info">
            <h3>වටලප්පන්</h3>
            <p>පොල් කිරි සහ හකුරු රසයෙන් පිරුණු සාම්ප්‍රදායික අතුරුපසක්.</p>
            <div class="product-bottom">
              <span class="price">මිල විමසන්න</span>
              <button class="add-btn" data-add="watalappan" type="button">+ ඇණවුමට එක් කරන්න</button>
            </div>
          </div>
        </article>

        <article class="product-card" data-category="pudding" data-id="caramel">
          <div class="product-image-wrap">
            <img class="product-image"
                 src="https://images.unsplash.com/photo-1488477181946-6428a0291777?auto=format&fit=crop&w=800&q=85"
                 alt="කැරමල් පුඩිං" loading="lazy">
            <span class="product-label">Smooth & Creamy</span>
          </div>
          <div class="product-info">
            <h3>කැරමල් පුඩිං</h3>
            <p>මෘදු, ක්‍රීම් ගතියෙන් යුතු කැරමල් රසැති පුඩිං.</p>
            <div class="product-bottom">
              <span class="price">මිල විමසන්න</span>
              <button class="add-btn" data-add="caramel" type="button">+ ඇණවුමට එක් කරන්න</button>
            </div>
          </div>
        </article>

        <article class="product-card" data-category="pudding" data-id="jelly">
          <div class="product-image-wrap">
            <img class="product-image"
                 src="https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=800&q=85"
                 alt="ජෙලි පුඩිං" loading="lazy">
            <span class="product-label">Colourful Treat</span>
          </div>
          <div class="product-info">
            <h3>ජෙලි පුඩිං</h3>
            <p>වර්ණවත්, රසවත් ජෙලි සහ පුඩිං එකතුවක්.</p>
            <div class="product-bottom">
              <span class="price">මිල විමසන්න</span>
              <button class="add-btn" data-add="jelly" type="button">+ ඇණවුමට එක් කරන්න</button>
            </div>
          </div>
        </article>

        <article class="product-card" data-category="ice" data-id="ice">
          <div class="product-image-wrap">
            <img class="product-image"
                 src="https://images.unsplash.com/photo-1560008581-09826d1de69e?auto=format&fit=crop&w=800&q=85"
                 alt="අයිස් පැකට්" loading="lazy">
            <span class="product-label">Cool & Refreshing</span>
          </div>
          <div class="product-info">
            <h3>අයිස් පැකට්</h3>
            <p>උණුසුම් දවසකට සිසිල් රසවත් සංග්‍රහයක්.</p>
            <div class="product-bottom">
              <span class="price">මිල විමසන්න</span>
              <button class="add-btn" data-add="ice" type="button">+ ඇණවුමට එක් කරන්න</button>
            </div>
          </div>
        </article>
      </div>

      <div class="custom-order">
        <div>
          <h3>විශේෂ ඇණවුමක් අවශ්‍යද?</h3>
          <p>ප්‍රමාණ, මිල සහ ලබාගත හැකි දිනය ගැන අපෙන් කෙළින්ම විමසන්න.</p>
        </div>
        <a class="wa-btn" href="https://wa.me/94778077332"
           target="_blank" rel="noopener">WhatsApp හරහා විමසන්න ↗</a>
      </div>
    </div>
  </section>

  <section class="section about" id="about">
    <div class="container about-grid">
      <img class="about-photo"
           src="https://images.unsplash.com/photo-1551024506-0bccd828d307?auto=format&fit=crop&w=1100&q=85"
           alt="රසවත් අතුරුපස" loading="lazy">

      <div class="about-copy">
        <div class="kicker">A LITTLE ABOUT US</div>
        <h2>රසයත් එක්ක බැඳුණු ආදරය.</h2>
        <p>
          නවරස Products වෙතින් ඔබට සමීප කරන්නේ රසවත් අතුරුපස සහ
          සිසිල් සංග්‍රහයන්. ඔබේ පවුලේ සතුටු මොහොතකට, පුංචි සැමරුමකට
          හෝ විශේෂ අවස්ථාවකට අපේ නිෂ්පාදන තෝරගන්න.
        </p>
        <p>
          නිෂ්පාදන ලබාගත හැකි බව, ප්‍රමාණ සහ මිල ගණන් ඔබේ ඇණවුමට
          පෙර WhatsApp හරහා තහවුරු කරගන්න.
        </p>
        <div class="about-points">
          <div class="point"><span>♡</span>ආදරයෙන් සකස් කළ රස</div>
          <div class="point"><span>✦</span>ඔබේ කැමැත්තට ඇණවුම්</div>
        </div>
      </div>
    </div>
  </section>

  <section class="section" id="order">
    <div class="container">
      <div class="section-head">
        <div class="kicker">EASY ORDERING</div>
        <h2>ඇණවුම් කරන්න හරිම පහසුයි</h2>
        <p>ඔබේ කැමති නිෂ්පාදන තෝරාගෙන WhatsApp හරහා අපට එවන්න.</p>
      </div>

      <div class="order-steps">
        <div class="step">
          <div class="step-number">01</div>
          <h3>නිෂ්පාදනය තෝරන්න</h3>
          <p>අපේ නිෂ්පාදන අතරින් ඔබ කැමති දේ තෝරාගෙන ඇණවුම් බෑගයට එක් කරන්න.</p>
        </div>
        <div class="step">
          <div class="step-number">02</div>
          <h3>විස්තර ලබා දෙන්න</h3>
          <p>ඔබේ නම, දුරකථන අංකය, ප්‍රදේශය සහ අවශ්‍ය ප්‍රමාණය සඳහන් කරන්න.</p>
        </div>
        <div class="step">
          <div class="step-number">03</div>
          <h3>WhatsApp හරහා යවන්න</h3>
          <p>අංක දෙකෙන් කැමති එකක් තෝරා ඇණවුම යවන්න. මිල සහ ලබාගැනීම තහවුරු කරගන්න.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <div class="container contact-grid">
      <div>
        <div class="kicker" style="color:#f1bd68">LET'S TALK</div>
        <h2>ඔබේ ඇණවුම ගැන කතා කරමු!</h2>
        <p>ප්‍රශ්නයක් තිබුණත්, මිල විමසීමක් වුණත් අපට WhatsApp පණිවිඩයක් එවන්න.</p>
      </div>
      <div class="contact-actions">
        <a class="wa-btn" href="https://wa.me/94778077332" target="_blank" rel="noopener">
          WhatsApp 077 807 7332 ↗
        </a>
        <a class="wa-btn alt" href="https://wa.me/94761105232" target="_blank" rel="noopener">
          WhatsApp 076 110 5232 ↗
        </a>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container footer-inner">
    <div>© <span id="year"></span> <b>නවරස Products</b>. සියලුම හිමිකම් ඇවිරිණි.</div>
    <div class="footer-contact">
      <a href="https://wa.me/94778077332" target="_blank" rel="noopener">077 807 7332</a>
      <a href="https://wa.me/94761105232" target="_blank" rel="noopener">076 110 5232</a>
    </div>
  </div>
</footer>

<a class="floating-wa" href="https://wa.me/94778077332"
   target="_blank" rel="noopener">☏ WhatsApp</a>

<div class="overlay" id="overlay"></div>

<aside class="cart-drawer" id="cartDrawer" aria-label="ඇණවුම් බෑගය" aria-hidden="true">
  <div class="drawer-head">
    <h2>ඔබේ ඇණවුම</h2>
    <button class="close-btn" id="closeCart" type="button" aria-label="වසන්න">×</button>
  </div>

  <div class="cart-items" id="cartItems">
    <div class="empty-cart">ඔබ තවම නිෂ්පාදන තෝරාගෙන නැහැ.</div>
  </div>

  <form class="cart-form" id="orderForm">
    <label for="customerName">ඔබේ නම *</label>
    <input id="customerName" name="customerName" required maxlength="70" placeholder="නම ඇතුළත් කරන්න">

    <label for="customerPhone">දුරකථන අංකය</label>
    <input id="customerPhone" name="customerPhone" inputmode="tel" maxlength="20" placeholder="ඔබව සම්බන්ධ කරගත හැකි අංකය">

    <label for="customerArea">ප්‍රදේශය / නගරය *</label>
    <input id="customerArea" name="customerArea" required maxlength="100" placeholder="ඔබ සිටින ප්‍රදේශය">

    <label for="contactNumber">WhatsApp වෙත යවන්න</label>
    <select id="contactNumber" name="contactNumber">
      <option value="94778077332">077 807 7332</option>
      <option value="94761105232">076 110 5232</option>
    </select>

    <label for="orderNotes">අමතර විස්තර</label>
    <textarea id="orderNotes" name="orderNotes" maxlength="500" placeholder="ප්‍රමාණය, අවශ්‍ය දිනය හෝ වෙනත් විස්තර..."></textarea>

    <button class="checkout-btn" type="submit">WhatsApp හරහා ඇණවුම යවන්න ↗</button>
    <p class="form-note">
      මිල, ලබාගත හැකි බව සහ delivery / pickup විස්තර WhatsApp හරහා තහවුරු කරනු ලැබේ.
      මෙම වෙබ් අඩවිය තුළ online payment සිදු නොවේ.
    </p>
  </form>
</aside>

<script>
(() => {
  "use strict";

  const products = {
    watalappan: { name: "වටලප්පන්", category: "සාම්ප්‍රදායික රස" },
    caramel: { name: "කැරමල් පුඩිං", category: "පුඩිං" },
    jelly: { name: "ජෙලි පුඩිං", category: "පුඩිං" },
    ice: { name: "අයිස් පැකට්", category: "අයිස් පැකට්" }
  };

  const cart = new Map();
  const $ = id => document.getElementById(id);
  const drawer = $("cartDrawer");
  const overlay = $("overlay");

  function openCart() {
    drawer.classList.add("open");
    overlay.classList.add("open");
    drawer.setAttribute("aria-hidden", "false");
    document.body.style.overflow = "hidden";
  }

  function closeCart() {
    drawer.classList.remove("open");
    overlay.classList.remove("open");
    drawer.setAttribute("aria-hidden", "true");
    document.body.style.overflow = "";
  }

  function updateCart() {
    const count = [...cart.values()].reduce((sum, quantity) => sum + quantity, 0);
    $("cartCount").textContent = count;

    const area = $("cartItems");
    area.replaceChildren();

    if (cart.size === 0) {
      const empty = document.createElement("div");
      empty.className = "empty-cart";
      empty.textContent = "ඔබ තවම නිෂ්පාදන තෝරාගෙන නැහැ.";
      area.append(empty);
      return;
    }

    for (const [id, quantity] of cart) {
      const product = products[id];
      if (!product) continue;

      const row = document.createElement("div");
      row.className = "cart-line";

      const info = document.createElement("div");

      const title = document.createElement("strong");
      title.textContent = product.name;

      const category = document.createElement("small");
      category.textContent = product.category;

      info.append(title, category);

      const controls = document.createElement("div");
      controls.className = "qty";

      const minus = document.createElement("button");
      minus.type = "button";
      minus.textContent = "−";
      minus.setAttribute("aria-label", product.name + " අඩු කරන්න");
      minus.addEventListener("click", () => setQuantity(id, quantity - 1));

      const number = document.createElement("span");
      number.textContent = quantity;

      const plus = document.createElement("button");
      plus.type = "button";
      plus.textContent = "+";
      plus.setAttribute("aria-label", product.name + " වැඩි කරන්න");
      plus.addEventListener("click", () => setQuantity(id, quantity + 1));

      controls.append(minus, number, plus);
      row.append(info, controls);
      area.append(row);
    }
  }

  function setQuantity(id, quantity) {
    if (quantity <= 0) {
      cart.delete(id);
    } else {
      cart.set(id, Math.min(99, quantity));
    }
    updateCart();
  }

  document.querySelectorAll("[data-add]").forEach(button => {
    button.addEventListener("click", () => {
      const id = button.dataset.add;
      setQuantity(id, (cart.get(id) || 0) + 1);

      const original = "+ ඇණවුමට එක් කරන්න";
      button.textContent = "එක් කළා ✓";

      window.setTimeout(() => {
        button.textContent = original;
      }, 1200);
    });
  });

  $("openCart").addEventListener("click", openCart);
  $("closeCart").addEventListener("click", closeCart);
  overlay.addEventListener("click", closeCart);

  document.addEventListener("keydown", event => {
    if (event.key === "Escape") closeCart();
  });

  $("heroOrder").addEventListener("click", openCart);

  $("filters").addEventListener("click", event => {
    const button = event.target.closest("[data-filter]");
    if (!button) return;

    document.querySelectorAll(".filter").forEach(item => {
      item.classList.toggle("active", item === button);
    });

    const filter = button.dataset.filter;

    document.querySelectorAll(".product-card").forEach(card => {
      card.classList.toggle(
        "hidden",
        filter !== "all" && card.dataset.category !== filter
      );
    });
  });

  $("orderForm").addEventListener("submit", event => {
    event.preventDefault();

    if (cart.size === 0) {
      alert("කරුණාකර මුලින් නිෂ්පාදනයක් තෝරන්න.");
      return;
    }

    const name = $("customerName").value.trim();
    const phone = $("customerPhone").value.trim();
    const area = $("customerArea").value.trim();
    const notes = $("orderNotes").value.trim();
    const target = $("contactNumber").value;

    if (!name || !area) {
      alert("කරුණාකර ඔබේ නම සහ ප්‍රදේශය ඇතුළත් කරන්න.");
      return;
    }

    const lines = [
      "ආයුබෝවන් නවරස Products!",
      "මට පහත නිෂ්පාදන ඇණවුම් කිරීමට අවශ්‍යයි:",
      "",
      ...[...cart].map(([id, quantity]) =>
        `• ${products[id].name} — ${quantity}`
      ),
      "",
      `නම: ${name}`,
      `දුරකථන අංකය: ${phone || "සඳහන් කර නැත"}`,
      `ප්‍රදේශය: ${area}`,
      `අමතර විස්තර: ${notes || "නැත"}`,
      "",
      "කරුණාකර මිල සහ ලබාගැනීමේ විස්තර දන්වන්න. ස්තූතියි!"
    ];

    const whatsappUrl =
      `https://wa.me/${target}?text=${encodeURIComponent(lines.join("\n"))}`;

    window.open(whatsappUrl, "_blank", "noopener,noreferrer");
  });

  $("mobileMenu").addEventListener("click", () => {
    const nav = $("navLinks");
    const isOpen = nav.classList.toggle("open");
    $("mobileMenu").setAttribute("aria-expanded", String(isOpen));
  });

  $("navLinks").querySelectorAll("a").forEach(link => {
    link.addEventListener("click", () => {
      $("navLinks").classList.remove("open");
      $("mobileMenu").setAttribute("aria-expanded", "false");
    });
  });

  $("year").textContent = new Date().getFullYear();
  updateCart();
})();
</script>
</body>
</html>
