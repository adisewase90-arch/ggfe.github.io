<!DOCTYPE html>
<html>
<head>
  <title>Earn Coins App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>💰 Earn Coins</h1>

<div id="auth">
  <input type="text" id="username" placeholder="Enter username">
  <button onclick="login()">Login</button>
</div>

<div id="app" style="display:none;">
  <h2>Welcome <span id="user"></span></h2>
  <h3>Coins: <span id="coins">0</span></h3>

  <button onclick="doTask()">Do Task (+10 coins)</button>
  <button onclick="logout()">Logout</button>
</div>

<script src="script.js"></script>
</body>
</html># ggfe.github.io
