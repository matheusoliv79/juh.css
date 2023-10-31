<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Saudades Juh</title>
</head>
<body>
  <div class="container">
    <div class="heart">
      <p class="text">Saudades Juh</p>
    </div>
  </div>
</body>
  <style>@import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');
    @keyframes heartbeat {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }
    
    body {
      font-family: 'Raleway', sans-serif;
      background-color: #222;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    
    .container {
      position: relative;
    }
    
    .heart {
      position: relative;
      width: 150px;
      height: 150px;
      background: red;
      border-radius: 50%;
      animation: heartbeat 1s linear infinite;
    }
    
    .text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 1.5rem;
      color: white;
      text-align: center;
    }
    </style>
</html>

