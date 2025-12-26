# encryption 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>3‑Layer Encryption Demo</title>
</head>
<body>
  <h2>3‑Layer Encryption Demo</h2>

  <label>Plain text:</label><br>
  <textarea id="plain" rows="4" cols="60"></textarea><br><br>

  <label>Key 1:</label><input id="k1" type="password"><br>
  <label>Key 2:</label><input id="k2" type="password"><br>
  <label>Key 3:</label><input id="k3" type="password"><br><br>

  <button id="encryptBtn">Encrypt (3 layers)</button>
  <button id="decryptBtn">Decrypt</button>

  <h3>Encrypted (base64):</h3>
  <textarea id="encrypted" rows="4" cols="60" readonly></textarea>

  <script src="app.js"></script>
</body>
</html>