<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Knails ⚡ — Katerina Nails</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<style>
:root{
  --bg:#fdf8f6;
  --primary:#d9b6b0;
  --secondary:#fff4f2;
  --text:#2b2b2b;
  --muted:#8f8a88;
  --accent:#e28c8c;
  --shadow:0 10px 25px rgba(0,0,0,0.1);
  --radius:14px;
}

*{box-sizing:border-box;margin:0;padding:0;}
html,body{height:100%;scroll-behavior:smooth;font-family:'Roboto',sans-serif;background:var(--bg);color:var(--text);}
a{text-decoration:none;color:inherit;}
img{display:block;width:100%;height:auto;border-radius:var(--radius);}

.lightning-bg{position:fixed;top:0;left:0;width:100%;height:100%;pointer-events:none;z-index:0;}
.lightning{position:absolute;font-size:18px;opacity:0.12;animation:lightningFloat 8s ease-in-out infinite;}
.star{position:absolute;font-size:14px;opacity:0.04;animation:twinkle 15s ease-in-out infinite;}

@keyframes lightningFloat{0%,100%{transform:translateY(0) scale(1); opacity:0.08;}50%{transform:translateY(-15px) scale(1.1); opacity:0.18;}}
@keyframes twinkle{0%,100%{opacity:0.04;transform:scale(1)}50%{opacity:0.09;transform:scale(1.06)}}

.logo-title{text-align:center;font-family:'Playfair Display',serif;font-size:80px;font-weight:700;color:var(--primary);margin:40px 0 20px;letter-spacing:4px;z-index:2;position:relative;}

.search-container{display:flex;justify-content:center;margin-bottom:30px;position:relative;z-index:2;}
.search-bar{display:flex;align-items:center;background:white;border-radius:50px;padding:10px 25px;box-shadow:var(--shadow);border:1px solid rgba(217,182,176,0.6);transition:all 0.3s;}
.search-bar:focus-within{box-shadow:0 8px 25px rgba(217,182,176,0.25);border-color:var(--primary);}
.search-bar input{border:none;outline:none;background:transparent;flex:1;font-size:16px;color:var(--text);}
.search-results{position:absolute;top:105%;left:50%;transform:translateX(-50%);width:320px;background:white;border-radius:var(--radius);box-shadow:0 10px 25px rgba(0,0,0,0.15);margin-top:5px;display:none;max-height:300px;overflow-y:auto;z-index:10;}
.search-result-item{padding:14px 18px;border-bottom:1px solid rgba(200,190,185,0.3);cursor:pointer;transition:background 0.2s;}
.search-result-item:hover{background:rgba(217,182,176,0.1);}
.search-result-title{font-weight:600;margin-bottom:4px;}
.search-result-price{color:var(--primary);font-weight:700;font-size:14px;}
.search-result-type{font-size:12px;color:var(--muted);background:rgba(217,182,176,0.1);padding:2px 6px;border-radius:10px;display:inline-block;margin-top:4px;}

.container{max-width:1200px;margin:0 auto;padding:20px;position:relative;z-index:2;}
.main-grid{display:grid;grid-template-columns:1fr 350px;gap:20px;}
.paper{background:var(--secondary);border-radius:var(--radius);padding:20px;box-shadow:var(--shadow);border:1px solid rgba(200,190,185,0.5);position:relative;overflow:hidden;transition:transform 0.3s;}
.paper:hover{transform:translateY(-5px) scale(1.01);}
.pin{position:absolute;top:12px;right:12px;background:var(--primary);color:white;padding:6px 10px;border-radius:10px;font-size:14px;}

.services-columns{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-top:18px;}
.note{background:linear-gradient(180deg,rgba(255,255,255,0.85),rgba(250,244,242,0.9));padding:22px;display:flex;flex-direction:column;justify-content:center;position:relative;cursor:pointer;border-radius:var(--radius);border:1px solid rgba(200,190,185,0.3);box-shadow:0 5px 15px rgba(0,0,0,0.05);transition:all 0.3s;}
.note:hover{transform:translateY(-8px) rotate(-0.3deg) scale(1.02);box-shadow:0 12px 25px rgba(0,0,0,0.08);}
.note-title{font-family:'Playfair Display',serif;font-size:20px;font-weight:600;margin-bottom:6px;}
.note-sub{color:var(--muted);font-style:italic;margin-bottom:8px;}
.note-price{color:var(--primary);font-weight:700;font-size:20px;margin-right:auto;}
.pin-small{position:absolute;top:12px;right:12px;background:rgba(255,255,255,0.85);border-radius:50%;width:32px;height:32px;display:flex;align-items:center;justify-content:center;box-shadow:0 4px 8px rgba(0,0,0,0.08);}
.note-row{display:flex;width:100%;align-items:center;gap:10px;justify-content:space-between;}

.contact-card{text-align:center;padding:20px;display:flex;flex-direction:column;gap:15px;}
.contact-btn{display:flex;flex-direction:column;align-items:center;gap:6px;text-decoration:none;padding:14px;background:linear-gradient(180deg,#fff,#fbf7f5);border-radius:var(--radius);box-shadow:var(--shadow);border:1px solid rgba(200,190,185,0.5);transition:transform 0.25s ease;color:var(--text);}
.contact-btn:hover{transform:translateY(-6px);}
.contact-btn i{font-size:28px;color:var(--primary);}
.contact-btn span{font-weight:600;font-size:14px;}

.portfolio-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:15px;}
.portfolio-item img{transition:transform 0.6s ease;}
.portfolio-item:hover img{transform:scale(1.08);}

/* Стили для красивого оформления раздела о мастере */
.master-section {
  background: linear-gradient(135deg, #fff8f6 0%, #fff0ed 100%);
  border-radius: 20px;
  padding: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid rgba(217,182,176,0.3);
  box-shadow: 0 15px 35px rgba(0,0,0,0.1);
}

.master-section::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  width: 200px;
  height: 200px;
  background: radial-gradient(circle, rgba(217,182,176,0.1) 0%, transparent 70%);
  border-radius: 50%;
}

.master-header {
  text-align: center;
  margin-bottom: 30px;
  position: relative;
}

.master-title {
  font-family: 'Playfair Display', serif;
  font-size: 32px;
  font-weight: 700;
  color: var(--primary);
  margin-bottom: 10px;
  position: relative;
  display: inline-block;
}

.master-title::after {
  content: "";
  position: absolute;
  bottom: -8px;
  left: 50%;
  transform: translateX(-50%);
  width: 80px;
  height: 3px;
  background: linear-gradient(90deg, transparent, var(--primary), transparent);
  border-radius: 2px;
}

.master-subtitle {
  font-size: 18px;
  color: var(--muted);
  font-style: italic;
}

.master-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 30px;
  align-items: start;
}

.master-stats {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin-bottom: 25px;
}

.stat-card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 5px 15px rgba(0,0,0,0.08);
  border: 1px solid rgba(217,182,176,0.2);
  transition: transform 0.3s ease;
}

.stat-card:hover {
  transform: translateY(-5px);
}

.stat-number {
  font-family: 'Playfair Display', serif;
  font-size: 28px;
  font-weight: 700;
  color: var(--primary);
  display: block;
  margin-bottom: 5px;
}

.stat-label {
  font-size: 14px;
  color: var(--muted);
  font-weight: 500;
}

.master-highlights-grid {
  display: grid;
  gap: 12px;
}

.highlight-card {
  background: rgba(255,255,255,0.8);
  padding: 16px;
  border-radius: 12px;
  border-left: 4px solid var(--primary);
  box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  transition: all 0.3s ease;
}

.highlight-card:hover {
  transform: translateX(5px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.1);
}

.highlight-icon {
  font-size: 20px;
  margin-right: 10px;
  color: var(--primary);
}

.inspiration-box {
  background: linear-gradient(135deg, rgba(217,182,176,0.1) 0%, rgba(226,140,140,0.05) 100%);
  padding: 25px;
  border-radius: 15px;
  border: 1px solid rgba(217,182,176,0.2);
  position: relative;
  margin: 25px 0;
  box-shadow: 0 5px 15px rgba(0,0,0,0.03);
}

.inspiration-box::before {
  content: """;
  position: absolute;
  top: 15px;
  left: 20px;
  font-size: 60px;
  font-family: 'Playfair Display', serif;
  color: rgba(217,182,176,0.3);
  line-height: 1;
}

.inspiration-text {
  font-style: italic;
  line-height: 1.7;
  color: var(--text);
  font-size: 16px;
  margin-left: 10px;
  position: relative;
  z-index: 2;
}

.cta-section {
  text-align: center;
  margin-top: 30px;
  padding-top: 25px;
  border-top: 1px solid rgba(217,182,176,0.2);
}

.cta-text {
  font-size: 14px;
  color: var(--muted);
  margin-bottom: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}

.cta-icon {
  font-size: 18px;
  color: var(--primary);
}

.instagram-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: linear-gradient(135deg, var(--primary) 0%, var(--accent) 100%);
  color: white;
  padding: 14px 28px;
  border-radius: 50px;
  font-weight: 700;
  text-decoration: none;
  box-shadow: 0 8px 25px rgba(217,182,176,0.4);
  transition: all 0.3s ease;
  border: none;
  cursor: pointer;
  font-size: 16px;
}

.instagram-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 30px rgba(217,182,176,0.6);
}

.master-photo {
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 15px 35px rgba(0,0,0,0.12);
  position: relative;
}

.master-photo::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 40%;
  background: linear-gradient(transparent, rgba(0,0,0,0.1));
  pointer-events: none;
}

footer{margin-top:40px;text-align:center;color:var(--muted);font-size:14px;padding:40px 0;}

.modal{display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.55);z-index:1000;justify-content:center;align-items:center;}
.modal-content{background:var(--secondary);padding:30px;border-radius:var(--radius);max-width:600px;width:90%;position:relative;animation:fadeIn 0.3s;box-shadow:0 20px 40px rgba(0,0,0,0.15);}
.close-modal{position:absolute;top:15px;right:15px;font-size:24px;cursor:pointer;background:var(--primary);color:white;width:36px;height:36px;border-radius:50%;display:flex;align-items:center;justify-content:center;border:none;box-shadow:0 4px 8px rgba(0,0,0,0.1);}
.contact-options{display:flex;flex-direction:row;gap:15px;margin:25px 0;justify-content:center;}
.contact-option{display:flex;align-items:center;padding:20px;background:#f8f4f0;border-radius:var(--radius);text-decoration:none;color:var(--text);transition:background 0.3s;flex:1;justify-content:center;box-shadow:0 4px 8px rgba(0,0,0,0.05);}
.contact-option:hover{background:#eee6de;}
.contact-option i{margin-right:15px;font-size:28px;color:var(--primary);}
.promo-section{margin-top:20px;padding-top:20px;border-top:1px solid rgba(200,190,185,0.6);}
.promo-codes{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;}
.promo-code{padding:8px 15px;background:#f0e9e3;border-radius:6px;font-size:14px;font-weight:500;position:relative;box-shadow:0 3px 6px rgba(0,0,0,0.05);}
.promo-discount{position:absolute;top:-8px;right:-8px;background:var(--primary);color:white;font-size:10px;padding:2px 6px;border-radius:10px;font-weight:600;}

@keyframes fadeIn{from{opacity:0;transform:translateY(-20px);}to{opacity:1;transform:translateY(0);}}

@media(max-width:900px){
  .main-grid{grid-template-columns:1fr;}
  .services-columns{grid-template-columns:1fr;}
  .logo-title{font-size:60px;}
  .master-content{grid-template-columns:1fr;}
  .master-stats{grid-template-columns:1fr;}
  .master-photo{width:100%;max-width:400px;margin:0 auto 30px;}
  .contact-options{flex-direction:column;}
}
@media(max-width:480px){
  .portfolio-grid{grid-template-columns:1fr;}
  .logo-title{font-size:40px;}
  .search-bar{width:250px;}
  .master-title{font-size:26px;}
}
</style>
</head>
<body>

<div class="lightning-bg" id="lightning-bg"></div>

<div class="logo-title">Knails ⚡</div>

<div class="search-container">
  <div class="search-bar">
    <input type="text" id="search-input" placeholder="Hello Kitty...">
    <i class="fas fa-search" style="color: var(--primary);"></i>
  </div>
  <div class="search-results" id="search-results"></div>
</div>

<main class="container">
  <div class="main-grid">
    <div>
      <!-- Услуги и цены -->
      <div class="paper">
        <div style="display:flex;align-items:center;justify-content:space-between;">
          <h2 style="font-family:'Playfair Display', serif;">Услуги и цены</h2>
          <div class="pin">📌</div>
        </div>
        <div class="services-columns">
          <div class="note" data-service="Наращивание/Коррекция">
            <div class="pin-small">📌</div>
            <div class="note-row">
              <div><div class="note-title">Наращивание/Коррекция</div><div class="note-sub">(макс. длина 4)</div></div>
              <div class="note-price">1.900₽</div>
            </div>
          </div>
          <div class="note" data-service="Гель-лак">
            <div class="pin-small">📌</div>
            <div class="note-row">
              <div class="note-title">Гель-лак</div>
              <div class="note-price">1.500₽</div>
            </div>
          </div>
          <div class="note" data-service="Маникюр без покрытия">
            <div class="pin-small">📌</div>
            <div class="note-row">
              <div class="note-title">Маникюр без покрытия</div>
              <div class="note-price">800₽</div>
            </div>
          </div>
          <div class="note" data-service="Снятие чужой работы">
            <div class="pin-small">📌</div>
            <div class="note-row">
              <div class="note-title">Снятие чужой работы</div>
              <div class="note-price">300₽</div>
            </div>
          </div>
          <div class="note" data-service="Ремонт одного ногтя">
            <div class="pin-small">📌</div>
            <div class="note-row">
              <div class="note-title">Ремонт одного ногтя</div>
              <div class="note-price">200₽</div>
            </div>
          </div>
        </div>
      </div>

      <!-- О мастере - красивое оформление -->
      <div class="master-section" style="margin-top:20px;">
        <div class="master-header">
          <h2 class="master-title">Привет! Меня зовут Катя)</h2>
          <div class="master-subtitle">Мастер маникюра с любовью к деталям</div>
        </div>
        
        <div class="master-content">
          <div>
            <div class="master-stats">
              <div class="stat-card">
                <span class="stat-number">3+</span>
                <span class="stat-label">года опыта</span>
              </div>
              <div class="stat-card">
                <span class="stat-number">2000+</span>
                <span class="stat-label">довольных клиенток</span>
              </div>
            </div>
            
            <div class="master-highlights-grid">
              <div class="highlight-card">
                <span class="highlight-icon">⚡</span>
                Работаю быстро, но без потери качества
              </div>
              <div class="highlight-card">
                <span class="highlight-icon">⏱️</span>
                Коррекция всего за 1 час
              </div>
              <div class="highlight-card">
                <span class="highlight-icon">✨</span>
                Исправляю «проблемные» ногти
              </div>
              <div class="highlight-card">
                <span class="highlight-icon">💎</span>
                Стойкий и эстетичный результат
              </div>
            </div>
          </div>
          
          <div class="master-photo">
            <img src="https://i.postimg.cc/hjBThm9n/IMG-0059.jpg" alt="Катя - мастер маникюра">
          </div>
        </div>
        
        <div class="inspiration-box">
          <div class="inspiration-text">
            Моя цель — создавать не просто маникюр, а настоящее произведение искусства, которое будет радовать вас каждый день. Красивые ухоженные ногти — важная часть уверенности и самовыражения.
          </div>
        </div>
        
        <div class="cta-section">
          <div class="cta-text">
            <span class="cta-icon">📍</span>
            Запись в ЛС
            <span class="cta-icon">📆</span>
            Места быстро разбирают — не откладывай красоту
          </div>
          <a href="https://www.instagram.com/kateina_nails" class="instagram-btn" target="_blank">
            <i class="fab fa-instagram"></i>
            Мой Instagram
          </a>
        </div>
      </div>

      <!-- Портфолио -->
      <div class="paper" style="margin-top:20px;">
        <h3 style="font-family:'Playfair Display', serif;">Портфолио</h3>
        <div class="portfolio-grid">
          <a class="portfolio-item" href="https://i.ibb.co/NcP7mdB/IMG-1.jpg" target="_blank"><img src="https://i.ibb.co/NcP7mdB/IMG-1.jpg" alt="Работа 1"></a>
          <a class="portfolio-item" href="https://i.ibb.co/k2KZ1ZFY/IMG-2.jpg" target="_blank"><img src="https://i.ibb.co/k2KZ1ZFY/IMG-2.jpg" alt="Работа 2"></a>
          <a class="portfolio-item" href="https://i.ibb.co/JR9g2K6w/IMG-3.jpg" target="_blank"><img src="https://i.ibb.co/JR9g2K6w/IMG-3.jpg" alt="Работа 3"></a>
          <a class="portfolio-item" href="https://i.ibb.co/9HXtBzt0/IMG-4.jpg" target="_blank"><img src="https://i.ibb.co/9HXtBzt0/IMG-4.jpg" alt="Работа 4"></a>
          <a class="portfolio-item" href="https://i.ibb.co/SXS5Mstr/IMG-5.jpg" target="_blank"><img src="https://i.ibb.co/SXS5Mstr/IMG-5.jpg" alt="Работа 5"></a>
          <a class="portfolio-item" href="https://i.postimg.cc/7CGq3kt3/IMG-0060.jpg" target="_blank"><img src="https://i.postimg.cc/7CGq3kt3/IMG-0060.jpg" alt="Работа 6"></a>
          <a class="portfolio-item" href="https://i.postimg.cc/2qbCQD94/IMG-0064.jpg" target="_blank"><img src="https://i.postimg.cc/2qbCQD94/IMG-0064.jpg" alt="Работа 7"></a>
          <a class="portfolio-item" href="https://i.postimg.cc/qNZk6Rwx/IMG-0066.jpg" target="_blank"><img src="https://i.postimg.cc/qNZk6Rwx/IMG-0066.jpg" alt="Работа 8"></a>
        </div>
      </div>
    </div>

    <!-- Sidebar -->
    <aside>
      <div class="paper">
        <div class="contact-card">
          <h3>Связаться со мной</h3>
          <div class="contacts">
            <a class="contact-btn" href="https://www.instagram.com/kateina_nails" target="_blank"><i class="fab fa-instagram"></i><span>Instagram</span></a>
            <a class="contact-btn" href="https://t.me/Lazaryan0" target="_blank"><i class="fab fa-telegram"></i><span>Telegram</span></a>
            <a class="contact-btn" href="https://wa.me/79881605058" target="_blank"><i class="fab fa-whatsapp"></i><span>WhatsApp</span></a>
          </div>

          <div style="margin-top:20px; font-size:14px; color:var(--muted); text-align:left;">
            <strong>Промокоды:</strong>
            <div style="margin-top:5px;">
              <strong style="color:var(--primary)">FIRSTVISIT</strong> - первое посещение -10%<br>
              <strong style="color:var(--primary)">GEL5</strong> - гель-лак -5%<br>
              <strong style="color:var(--primary)">NAILS8</strong> - наращивание -8%<br>
              <strong style="color:var(--primary)">LOVE3</strong> - любые услуги -3%
            </div>
          </div>

          <div style="margin-top:15px; display:flex; gap:10px; justify-content:center;">
            <button onclick="scrollToSection('portfolio')" style="padding:8px 12px; border-radius:12px; border:1px solid rgba(200,190,185,0.6); background:transparent; color:var(--text); font-weight:600; cursor:pointer; box-shadow:0 2px 4px rgba(0,0,0,0.05);">Портфолио</button>
            <button onclick="openBookingModal()" style="padding:8px 12px; border-radius:12px; background:var(--primary); color:white; font-weight:700; border:none; cursor:pointer; box-shadow:0 4px 8px rgba(217,182,176,0.3);">Записаться</button>
          </div>
        </div>
      </div>
    </aside>
  </div>
</main>

<!-- Модальное окно -->
<div class="modal" id="booking-modal">
  <div class="modal-content">
    <button class="close-modal">&times;</button>
    <h2 style="font-family:'Playfair Display', serif; margin-bottom:10px;">Записаться на услугу</h2>
    <p style="color:var(--muted);">Выберите удобный способ связи для записи:</p>
    <div class="contact-options">
      <a href="https://www.instagram.com/kateina_nails" class="contact-option" target="_blank">
        <i class="fab fa-instagram"></i>
        <div>
          <strong>Instagram</strong><br>@kateina_nails
        </div>
      </a>
      <a href="https://wa.me/79881605058" class="contact-option" target="_blank">
        <i class="fab fa-whatsapp"></i>
        <div>
          <strong>WhatsApp</strong><br>+7 988 160 50 58
        </div>
      </a>
    </div>
    <div class="promo-section">
      <h3 style="font-family:'Playfair Display', serif; margin-bottom:15px;">Промокоды для скидок</h3>
      <div class="promo-codes">
        <div class="promo-code">FIRSTVISIT<div class="promo-discount">-10%</div></div>
        <div class="promo-code">GEL5<div class="promo-discount">-5%</div></div>
        <div class="promo-code">NAILS8<div class="promo-discount">-8%</div></div>
        <div class="promo-code">LOVE3<div class="promo-discount">-3%</div></div>
      </div>
      <p style="margin-top:15px; font-size:14px; color:var(--muted);">
        <strong>FIRSTVISIT</strong> - скидка 10% на первое посещение<br>
        <strong>GEL5</strong> - скидка 5% на гель-лак<br>
        <strong>NAILS8</strong> - скидка 8% на наращивание<br>
        <strong>LOVE3</strong> - скидка 3% на любые услуги
      </p>
    </div>
  </div>
</div>

<footer class="container">
  <p>Katerina Nails © 2025 — Все права защищены</p>
</footer>

<script>
// Lightning and stars background
function createBackgroundElements(){
  const cont = document.getElementById('lightning-bg');
  
  // Create 25 lightning elements
  for(let i=0; i<25; i++){
    const el = document.createElement('div');
    el.className = 'lightning';
    el.style.left = Math.random()*100 + '%';
    el.style.top = Math.random()*100 + '%';
    el.style.animationDelay = (Math.random()*8) + 's';
    el.style.animationDuration = (6 + Math.random()*6) + 's';
    el.textContent = '⚡';
    cont.appendChild(el);
  }
  
  const starPos=[{l:'10%',t:'10%',d:'2s',dur:'18s'},{l:'90%',t:'15%',d:'5s',dur:'20s'},{l:'20%',t:'90%',d:'8s',dur:'16s'},{l:'80%',t:'85%',d:'12s',dur:'22s'}];
  const starChars=['★','☆','✦','✧'];
  starPos.forEach((pos,i)=>{
    const el=document.createElement('div');el.className='star';el.style.left=pos.l;el.style.top=pos.t;el.style.animationDelay=pos.d;el.style.animationDuration=pos.dur;el.textContent=starChars[i];cont.appendChild(el);
  });
}
createBackgroundElements();

// Search functionality
const searchData=[
  {title:"Наращивание/Коррекция",price:"1.900₽",type:"услуга",description:"макс. длина 4"},
  {title:"Гель-лак",price:"1.500₽",type:"услуга",description:""},
  {title:"Маникюр без покрытия",price:"800₽",type:"услуга",description:""},
  {title:"Снятие чужой работы",price:"300₽",type:"услуга",description:""},
  {title:"Ремонт одного ногтя",price:"200₽",type:"услуга",description:""},
  {title:"FIRSTVISIT",price:"скидка 10%",type:"промокод",description:"первое посещение"},
  {title:"GEL5",price:"скидка 5%",type:"промокод",description:"гель-лак"},
  {title:"NAILS8",price:"скидка 8%",type:"промокод",description:"наращивание"},
  {title:"LOVE3",price:"скидка 3%",type:"промокод",description:"любые услуги"}
];
const searchInput=document.getElementById('search-input');
const searchResults=document.getElementById('search-results');

searchInput.addEventListener('input',function(){
  const query=this.value.toLowerCase().trim();
  searchResults.innerHTML='';
  if(query.length<2){searchResults.style.display='none';return;}
  const filtered=searchData.filter(item=>item.title.toLowerCase().includes(query)||item.description.toLowerCase().includes(query)||item.price.toLowerCase().includes(query));
  if(filtered.length>0){
    filtered.forEach(item=>{
      const div=document.createElement('div');div.className='search-result-item';
      div.innerHTML=`<div class="search-result-title">${item.title}</div><div class="search-result-price">${item.price}</div><div class="search-result-type">${item.type}</div>${item.description?`<div style="font-size:12px;color:var(--muted);margin-top:3px;">${item.description}</div>`:''}`;
      div.addEventListener('click',function(){searchInput.value=item.title;searchResults.style.display='none';if(item.type==='услуга')openBookingModal(item.title);});
      searchResults.appendChild(div);
    });
    searchResults.style.display='block';
  } else searchResults.style.display='none';
});
document.addEventListener('click',function(e){if(!e.target.closest('.search-container'))searchResults.style.display='none';});

// Modal
const modal=document.getElementById('booking-modal');
const closeModal=document.querySelector('.close-modal');
const notes=document.querySelectorAll('.note');
function openBookingModal(service=''){if(service){modal.querySelector('h2').textContent=`Записаться на ${service}`;}modal.style.display='flex';}
notes.forEach(note=>note.addEventListener('click',()=>openBookingModal(note.dataset.service)));
closeModal.addEventListener('click',()=>modal.style.display='none');
window.addEventListener('click',e=>{if(e.target===modal)modal.style.display='none';});

// Scroll
function scrollToSection(id){const el=document.getElementById(id);if(el)el.scrollIntoView({behavior:'smooth'});}
document.querySelector('.portfolio-grid').parentElement.parentElement.id='portfolio';
</script>

</body>
</html>
