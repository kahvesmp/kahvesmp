kahvesmp/
│
├─ index.html
├─ style.css
└─ README.md
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KahveSMP</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="hero">
    <h1>☕ KAHVESMP</h1>
    <p>Türkiye'nin Kahve Kokulu SMP Sunucusu</p>

    <div class="ip-box">
        <span id="ip">kahvesmp.net</span>
        <button onclick="copyIP()">Kopyala</button>
    </div>

    <a class="discord" href="https://discord.gg/WQ6vUaSV9" target="_blank">
        Discord'a Katıl
    </a>
</div>

<section class="store">
    <h2>STORE</h2>

    <div class="card">
        <h3>☕ Kahve+</h3>
        <p>79 TL</p>
    </div>

    <div class="card">
        <h3>☕☕ Kahve++</h3>
        <p>149 TL</p>
    </div>

    <div class="card">
        <h3>☕☕☕ Kahve+++</h3>
        <p>299 TL</p>
    </div>
</section>

<script>
function copyIP() {
    navigator.clipboard.writeText("kahvesmp.net");
    alert("IP kopyalandı!");
}
</script>

</body>
</html>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#111;
    color:white;
}

.hero{
    text-align:center;
    padding:100px 20px;
    background:linear-gradient(180deg,#2d1b0f,#111);
}

.hero h1{
    font-size:70px;
}

.ip-box{
    margin:20px auto;
}

button{
    padding:10px 20px;
    border:none;
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
    border-radius:8px;
}

.store{
    text-align:center;
    padding:50px 20px;
}

.card{
    background:#1f1f1f;
    max-width:300px;
    margin:20px auto;
    padding:20px;
    border-radius:12px;
}# KahveSMP

Resmi KahveSMP web sitesi.

IP: kahvesmp.net
Discord: https://discord.gg/WQ6vUaSV9
