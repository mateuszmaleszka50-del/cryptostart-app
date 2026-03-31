# cryptostart-app
https://M1.github.io/cryptostart.pl
<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>CryptoStart</title>
<style>
body {
font-family: Arial;
background: #0b0f1a;
color: white;
text-align: center;
}
button {
padding: 10px 20px;
background: #00ffcc;
border: none;
cursor: pointer;
}
.card {
background: #111827;
padding: 20px;
margin: 10px;
}
</style>
</head>

<body>

<h1>🚀 CryptoStart</h1>

<div id="auth">
<h2>Logowanie / Rejestracja</h2>
<input id="email" placeholder="Email"><br><br>
<input id="password" type="password" placeholder="Hasło"><br><br>
<button onclick="register()">Zarejestruj</button>
<button onclick="login()">Zaloguj</button>
</div>

<hr>

<h2>Kup Kryptowaluty</h2>

<div class="card">
<h3>Bitcoin (BTC)</h3>
<button onclick="buyCrypto('btc')">Kup</button>
</div>

<div class="card">
<h3>Ethereum (ETH)</h3>
<button onclick="buyCrypto('eth')">Kup</button>
</div>

<script>
function register() {
alert("Rejestracja działa (demo)");
}

function login() {
alert("Logowanie działa (demo)");
}

function buyCrypto(type) {
if(type === 'btc'){
window.location.href = "https://www.binance.com/pl/register?ref=TWÓJ_LINK";
}
if(type === 'eth'){
window.location.href = "https://www.coinbase.com/join/TWÓJ_LINK";
}
}
</script>

</body>
</html>
