<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Simple Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
      background-color: #f0f0f0;
    }
    .banner {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      font-size: 30px;
      font-weight: bold;
    }
    button {
      margin-top: 50px;
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
      background-color: #008CBA;
      color: white;
      border: none;
      border-radius: 5px;
    }
    #message {
      margin-top: 30px;
      font-size: 24px;
      color: #333;
    }
  </style>
</head>
<body>
  <div class="banner">You are Pro</div>

  <button onclick="showMessage()">Click to Continue</button>

  <div id="message"></div>

  <script>
    function showMessage() {
      document.getElementById("message").textContent = "You made your website!";
    }
  </script>
</body>
</html>

