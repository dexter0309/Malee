# Malee
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For My Mama ❤️</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: url('https://source.unsplash.com/1600x900/?roses,flowers') no-repeat center center fixed;
      background-size: cover;
      color: white;
      text-align: center;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      flex-direction: column;
    }
    .container {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 20px;
      border-radius: 10px;
    }
    h1 {
      font-size: 2.5em;
    }
    input {
      padding: 10px;
      font-size: 1.2em;
      margin: 10px 0;
      width: 80%;
      border-radius: 5px;
      border: none;
      outline: none;
    }
    button {
      padding: 15px 25px;
      font-size: 1.2em;
      background-color: #e63946;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #f1faee;
    }
    .message {
      display: none;
      font-size: 1.2em;
      margin-top: 20px;
      padding: 20px;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      text-align: left;
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome My Love ❤️🌍<br>From Dama</h1>
    <input type="text" id="username" placeholder="Username">
    <input type="password" id="password" placeholder="Password">
    <button onclick="login()">Log In</button>
    <div class="message" id="message">
      <p>My Dearest Mama, ❤️🌹</p>
      <p>Happy Valentine’s Day to the most beautiful, loving, and incredible woman in my life! 💕🥰 Today is all about love, and no one deserves to be celebrated more than you! 💖💐</p>
      <p>From the moment I opened my eyes to this world, you have been my constant—my first home 🏡, my greatest comfort 🤗, and my safest place 🛡️. No matter where life takes me, your love is my anchor ⚓, holding me steady when I feel lost and lifting me up when I feel weak. 💪😭</p>
      <p>You have given me more than I could ever put into words. ✨ Your sacrifices, your strength, and your endless care have shaped me into who I am today. 💕 Every lesson you’ve taught me 🎓, every hug you’ve given me 🤗, and every time you put me before yourself—I see it 👀, I feel it 💖, and I cherish it more than you know. 😭❤️</p>
      <p>No matter how old I get, I will always be your child 👶, always needing your love 🥰, always looking up to you. 🌟 And I promise, for as long as I live, I will love you ❤️, respect you 🙏, and do my best to make you proud. 😘</p>
      <p>Today, I just want to remind you that you are deeply loved—not just as my mother, but as my heart ❤️, my home 🏡, and my greatest blessing. 💝 You are my forever Valentine, Mama! 💌💖🌹</p>
      <p>With all my love,<br>Your son, Adam 💕🥰😘</p>
    </div>
  </div>
  <audio id="bgMusic" autoplay loop>
    <source src="سلطان العماني   احلى ملاك.mp3" type="audio/mpeg">
  </audio>
  <script>
    function login() {
      const username = document.getElementById("username").value;
      const password = document.getElementById("password").value;
      
      if (username.toLowerCase() === "amal" && password.toLowerCase() === "iloveyou") {
        document.querySelector("h1").style.display = "none";
        document.querySelector("input").style.display = "none";
        document.querySelector("button").style.display = "none";
        document.getElementById("message").style.display = "block";
      } else {
        alert("Oops! Try again Mama 🌸❤️ The password is: 'iloveyou' 💖🥰");
      }
    }
  </script>
</body>
</html>
