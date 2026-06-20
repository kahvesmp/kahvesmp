<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KahveSMP</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0d0d0d;
color:white;
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.8)),
url('https://images.unsplash.com/photo-1511512578047-dfb367046420?q=80&w=1920');
background-size:cover;
background-position:center;
}

.logo{
font-size:90px;
font-weight:bold;
text-shadow:0 0 20px #8B4513;
}

.subtitle{
font-size:22px;
color:#ddd;
margin-top:10px;
}

.ipbox{
margin-top:30px;
background:#1a1a1a;
padding:15px 25px;
border-radius:12px;
border:1px solid #8B4513;
}

.ip{
font-size:24px;
font-weight:bold;
}

.copy{
margin-top:10px;
padding:10px 20px;
border:none;
background:#8B4513;
color:white;
border-radius:8px;
cursor:pointer;
}

.discord{
display:inline-block;
margin-top:20px;
padding:12px 24px;
background:#5865F2;
color:white;
text-decoration:none;
border-radius:10px;
}

.store{
padding:80px 20px;
text-align:center;
}

.store h2{
font-size:50px;
margin-bottom:40px;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
}

.card{
width:320px;
background:#171717;
padding:25px;
border-radius:15px;
border:1px solid #333;
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.price{
font-size:40px;
color:#8B4513;
margin:15px 0;
}

.buy{
display:inline-block;
margin-top:15px;
padding:12px 25px;
background:#8B4513;
color:white;
text-decoration:none;
border-radius:8px;
}

footer{
padding:30px;
text-align:center;
color:#888;
}
</style>
</head>
<body>

<section class="hero">
<div class="logo">☕ KAHVESMP</div>
<div class="subtitle">Türkiye'nin Kahve Kokulu SMP Sunucusu</div>

<div class="ipbox">
<div class="ip">kahvesmp.net</div>
<button class="copy" onclick="copyIP()">IP Kopyala</button>
</div>

<a class="discord" href="https://discord.gg/WQ6vUaSV9" target="_blank">
Discord'a Katıl
</a>
</section>

<section class="store">
<h2>STORE</h2>

<div class="cards">

<div class="card">
<h3>☕ Kahve+</h3>
<div class="price">79 TL</div>
<p>Özel sohbet etiketi<br>3 SetHome<br>Discord Rolü</p>
<a href="#" class="buy">Satın Al</a>
</div>

<div class="card">
<h3>☕☕ Kahve++</h3>
<div class="price">149 TL</div>
<p>5 SetHome<br>/ec<br>VIP Kit</p>
<a href="#" class="buy">Satın Al</a>
</div>

<div class="card">
<h3>☕☕☕ Kahve+++</h3>
<div class="price">299 TL</div>
<p>10 SetHome<br>/feed<br>En Üst VIP Kit</p>
<a href="#" class="buy">Satın Al</a>
</div>

</div>
</section>

<footer>
© 2026 KahveSMP - Tüm Hakları Saklıdır
</footer>

<script>
function copyIP(){
navigator.clipboard.writeText("kahvesmp.net");
alert("IP kopyalandı: kahvesmp.net");
}
</script>

</body>
</html>
