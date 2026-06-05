# Digital-teach
A logo design website where users can create and download custom logos online.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Teach - Logo Maker</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Digital Teach Logo Maker</h1>
    <p>Create your custom logo in seconds</p>
  </header>

  <main>
    <div class="box">
      <input type="text" id="text" placeholder="Enter your logo text">
      <button onclick="generateLogo()">Generate Logo</button>

      <div id="logo">Your Logo</div>

      <button onclick="downloadLogo()">Download</button>
    </div>
  </main>

  <footer>
    <p>© 2026 Digital Teach</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
