<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Golden Language App</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="manifest" href="manifest.json">
<style>
body{margin:0;background:#000;color:#fff;font-family:Arial}
header{background:gold;color:black;text-align:center;padding:15px}
.box{border:1px solid gold;margin:15px;padding:15px;border-radius:10px}
button{background:gold;border:none;padding:10px 15px;font-weight:bold}
.ad{background:#222;color:yellow;padding:10px;margin-top:10px}
</style>
</head>
<body>

<header>
<h2>Golden Language App ✨</h2>
<p>English • Spanish • Korean</p>
</header>

<div class="box">
<h3>🇺🇸 English</h3>
<p>I play – He plays</p>
<audio controls><source src="en.mp3"></audio>
<div class="ad">Ad – free users</div>
</div>

<div class="box">
<h3>🇪🇸 Spanish</h3>
<p>Hola – Gracias</p>
<audio controls><source src="es.mp3"></audio>
<div class="ad">Ad – free users</div>
</div>

<div class="box">
<h3>🇰🇷 Korean</h3>
<p>안녕하세요 – 감사합니다</p>
<audio controls><source src="kr.mp3"></audio>
<div class="ad">Ad – free users</div>
</div>

<div class="box">
<h3>💎 Premium</h3>
<p>Full courses + No Ads</p>
<button onclick="alert('Subscription $2 / $4 coming soon')">Subscribe</button>
</div>

</body>
</html>
