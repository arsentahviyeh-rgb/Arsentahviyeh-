# Arsentahviyeh-
فروش و خدمات پس از فروش کولر گازی 
html>
<html lang="fa">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>خدمات کولر گازی — [نام برند شما]</title>
  <meta name="description" content="فروش، نصب و تعمیر کولر گازی در [نام شهر]. نصب تخصصی، سرویس دوره‌ای و تعمیرات فوری." />
  <style>
    /* ساده + ریسپانسیو */
    :root{--accent:#0b84ff;--muted:#666}
    body{font-family: Vazir, Tahoma, Arial, sans-serif; margin:0; background:#f7f9fc; color:#111; line-height:1.6}
    .container{max-width:1000px;margin:0 auto;padding:18px}
    header{display:flex;align-items:center;justify-content:space-between;padding:10px 0}
    .brand{font-weight:700;font-size:20px}
    .hero{background:white;border-radius:10px;padding:20px;margin:12px 0;display:flex;gap:18px;align-items:center;flex-wrap:wrap}
    .hero .left{flex:1}
    .hero h1{margin:0 0 8px 0}
    .btn{display:inline-block;background:var(--accent);color:white;padding:10px 16px;border-radius:8px;text-decoration:none}
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px;margin-top:12px}
    .card{background:white;padding:12px;border-radius:8px;box-shadow:0 4px 14px rgba(15,15,15,0.05)}
    .gallery{display:flex;gap:8px;flex-wrap:wrap}
    .gallery img{width:calc(33% - 8px);border-radius:6px}
    footer{margin-top:18px;padding:12px 0;color:var(--muted);text-align:center}
    @media(max-width:600px){ .gallery img{width:100%} header{flex-direction:column;gap:8px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">[اسم برند شما] — خدمات کولر گازی</div>
      <div>
        <a class="btn" href="https://wa.me/98XXXXXXXXXX" target="_blank">چت واتساپ</a>
      </div>
    </header>

    <section class="hero">
      <div class="left">
        <h1>فروش، نصب و تعمیر کولر گازی در [شهر شما]</h1>
        <p>نصب تخصصی، سرویس دوره‌ای و تعمیرات فوری با تکنسین مجرب و قطعات اصل. گارانتی خدمات و پاسخگویی سریع.</p>
        <p><strong>تماس:</strong> [شماره شما] — <strong>ساعات کار:</strong> ۸:۰۰ الی ۲۰:۰۰</p>
        <a class="btn" href="#services">خدمات و قیمت‌ها</a>
      </div>
      <div style="min-width:240px">
        <img src="https://via.placeholder.com/320x200?text=AC+Install" alt="نصب کولر" style="width:100%;border-radius:8px" />
      </div>
    </section>

    <section id="services">
      <h2>خدمات ما</h2>
      <div class="services">
        <div class="card">
          <h3>فروش کولر گازی</h3>
          <p>اسپلیت، ایستاده و پنجره‌ای — برندهای معتبر — قیمت رقابتی</p>
        </div>
        <div class="card">
          <h3>نصب تخصصی</h3>
          <p>نصب استاندارد، تضمین عملکرد و تنظیمات اولیه.</p>
        </div>
        <div class="card">
          <h3>تعمیرات فوری</h3>
          <p>شارژ گاز، تعمیر برد، صدای غیرعادی، تعویض کمپرسور.</p>
        </div>
        <div class="card">
          <h3>سرویس دوره‌ای</h3>
          <p>شست‌وشوی کامل، بررسی مسیر گاز و کاهش مصرف برق.</p>
        </div>
      </div>
    </section>

    <section id="products" style="margin-top:16px">
      <h2>محصولات (نمونه)</h2>
      <div class="card">
        <h3>[مدل مثال] — اسپلیت دیواری</h3>
        <p>ظرفیت: 12000 BTU — مناسب برای اتاق تا 20 متر — گارانتی: ۱۸ ماه</p>
      </div>
    </section>

    <section id="portfolio" style="margin-top:16px">
      <h2>نمونه کارها</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/300x200?text=Before" alt="قبل">
        <img src="https://via.placeholder.com/300x200?text=During" alt="در حین">
        <img src="https://via.placeholder.com/300x200?text=After" alt="بعد">
      </div>
    </section>

    <section id="blog" style="margin-top:16px">
      <h2>مقالات و نکات</h2>
      <div class="card">
        <h4>چند نکته برای کاهش مصرف کولر گازی</h4>
        <p>تنظیم دمای مناسب، سرویس دوره‌ای و بستن منافذ محیط ...</p>
      </div>
    </section>

    <section id="contact" style="margin-top:16px">
      <h2>تماس با ما</h2>
      <div class="card">
        <p><strong>آدرس:</strong> [آدرس]</p>
        <p><strong>تلفن:</strong> [شماره]</p>
        <p><strong>واتساپ:</strong> <a href="https://wa.me/98XXXXXXXXXX" target="_blank">شروع چت</a></p>
        <p><a class="btn" href="mailto:you@example.com">ارسال ایمیل</a></p>
      </div>
    </section>

    <footer>
      © <span id="year"></span> [نام برند شما] — کلیه حقوق محفوظ است.
    </footer>
  </div>

<script>document.getElementById('year').textContent=new Date().getFullYear()</script>
</body>
</html>
