<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>j1nn3 - Nightmares Await</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }
    
    h1 {
      font-size: 3em;
      text-align: center;
      margin-bottom: 20px;
      text-shadow: 0 0 20px rgba(255, 0, 0, 0.7);
    }

    p {
      font-size: 1.2em;
      line-height: 1.5;
      text-align: center;
      margin-bottom: 30px;
    }

    .warning {
      color: red;
      font-size: 1.5em;
      font-weight: bold;
    }

    .scary-image {
      width: 100%;
      max-width: 800px;
      border: 5px solid red;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(255, 0, 0, 0.7);
      animation: pulse 2s infinite;
    }

    .container {
      text-align: center;
      position: relative;
    }

    .atmosphere {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      animation: backgroundAnimation 20s infinite alternate;
    }

    @keyframes backgroundAnimation {
      0% { background-color: #000; }
      50% { background-color: #222; }
      100% { background-color: #000; }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>j1nn3</h1>
    <div class="atmosphere"></div>
    <p class="warning">⚠ WARNING: This website contains dark and atmospheric graphics, jumpscares, blood, and loud noises. Play as a child with the fear of big, scary animatronics. ⚠</p>
  </div>
</body>
</html>
