<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KahveSMP</title>

<style>
body{
    background:#111;
    color:white;
    font-family:Arial,sans-serif;
    text-align:center;
    margin:0;
}

.logo{
    margin-top:80px;
    font-size:60px;
}

.ip-box{
    margin:30px auto;
    background:#222;
    width:300px;
    padding:15px;
    border-radius:10px;
}

button{
    background:#8B4513;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
}

.store{
    margin-top:50px;
}

.rank{
    background:#222;
    width:300px;
    margin:20px auto;
    padding:20px;
    border-radius:10px;
}
</style>
</head>
<body>

<div class="logo">☕ KahveSMP</div>

<div class="ip-box">
    <h3>Sunucu IP</h3>
    <p id="ip">YAKINDA</p>
    <button onclick="copyIP()">Kopyala</button>
</div>

<div class="store">
    <h1>STORE</h1>

    <div class="rank">
        <h2>Kahve+</h2>
        <p>Yakında</p>
    </div>

    <div class="rank">
        <h2>Kahve++</h2>
        <p>Yakında</p>
    </div>

    <div class="rank">
        <h2>Kahve+++</h2>
        <p>Yakında</p>
    </div>
</div>

<br>

<a href="https://discord.gg/WQ6vUaSV9">
<button>Discord</button>
</a>

<script>
function copyIP(){
navigator.clipboard.writeText(
document.getElementById("ip").innerText
);
alert("IP kopyalandı!");
}
</script>

</body>
</html>
