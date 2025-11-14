
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yashim Spa</title>

<style>
    body {
        margin: 0;
        padding: 0;
        background: #d1ccbb;
        font-family: Arial, sans-serif;
        text-align: center;
    }

    .logo {
        width: 200px;
        margin: 30px auto 20px;
        display: block;
        filter: brightness(0) saturate(100%) invert(27%) sepia(21%) saturate(900%) hue-rotate(18deg) brightness(95%) contrast(90%);
    }

    /* صندوق أيقونة منفصل */
    .icon-item {
        width: 220px;
        margin: 0 auto 15px;
        padding: 15px 0;
        background: rgba(0, 0, 0, 0); /* شفاف */
        border-radius: 12px;
        border: 2px solid rgba(0,0,0,0.12); /* إطار شفاف خفيف */
    }

    .icon-item img {
        width: 50px;
        height: 50px;
        filter: brightness(0) saturate(100%) invert(27%) sepia(21%) saturate(900%) hue-rotate(18deg) brightness(95%) contrast(90%);
    }

    .map {
        width: 100%;
        height: 360px;
        border: 0;
        margin-top: 25px;
    }

    /* زر فتح الخرائط */
    .map-btn {
        display: block;
        width: 80%;
        margin: 15px auto;
        background: #494424;
        color: #fff;
        padding: 14px;
        border-radius: 10px;
        text-decoration: none;
        font-size: 18px;
    }

    footer {
        margin-top: 20px;
        padding: 15px;
        color: #494424;
        font-weight: bold;
    }
</style>
</head>

<body>

<!-- اللوجو -->
<img class="logo" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABJIAAARmCAYAAABk7p8QAAABamlDQ1BJQ0MgUHJvZmlsZQAAeJx1kL1Lw1AUxU+rUtA6iA4dHDKJ..." />

<!-- أيقونات — كل أيقونة في مستطيل منفصل -->

<div class="icon-item">
    <a href="https://www.instagram.com/yashim.spa?igsh=MWFsYndlZjBsaW42aw%3D%3D&utm_source=qr" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg">
    </a>
</div>

<div class="icon-item">
    <a href="https://snapchat.com/t/R6g5tyFL" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/snapchat.svg">
    </a>
</div>

<div class="icon-item">
    <a href="https://www.tiktok.com/@yashim.spa?_r=1&_t=ZS-91OZSq4k9TM" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/tiktok.svg">
    </a>
</div>

<div class="icon-item">
    <a href="https://wa.me/966558666115" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/whatsapp.svg">
    </a>
</div>

<div class="icon-item">
    <a href="tel:00966558666115">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/phone.svg">
    </a>
</div>

<!-- Google Map -->
<iframe 
    class="map"
    src="https://www.google.com/maps?q=21.5434386,39.1736164&hl=ar&z=16&output=embed"
    allowfullscreen
    loading="lazy">
</iframe>

<!-- زر خرائط Google -->
<a class="map-btn" 
   href="https://maps.app.goo.gl/VTQBmuooM6eKQBTx5?g_st=ic"
   target="_blank">
    فتح الموقع في خرائط Google
</a>

<footer>
جميع الحقوق محفوظة يشم سبا | Yashim Spa
</footer>

</body>
</html>
