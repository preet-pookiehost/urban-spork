<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Click the Button - HTML Game</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 100px;
      background: #edf5ff;
    }
    #gameBtn, #startBtn, #restartBtn, #backBtn {
      padding: 20px 40px;
      font-size: 24px;
      background: #4CAF50;
      color: #fff;
      border: none;
      border-radius: 12px;
      box-shadow: 0 5px #888;
      transition: all 0.3s ease-in-out;
      cursor: pointer;
      margin-bottom: 20px;
    }
    #gameBtn.active {
      transform: translateY(5px);
      box-shadow: 0 0 #888;
      background: #45a049;
    }
    #score, #timer {
      font-size: 32px;
      margin-bottom: 20px;
    }
    .page {
      display: none;
    }
    .active-page {
      display: block;
    }
  </style>
</head>
<body>

  <h1>Click the Button</h1>

  <!-- Start Menu -->
  <div id="startPage" class="page active-page">
    <h2>Test your clicking speed in 10 seconds</h2>
    <button id="startBtn">Play</button>
  </div>

  <!-- Game Section -->
  <div id="gamePage" class="page">
    <h2>Click as much as you can in 10 seconds</h2>

    <button id="gameBtn" disabled>Click Me</button>

    <h2>Time Left: <span id="timer">10</span></h2>
    <h2>Score: <span id="score">0</span></h2>

    <button id="restartBtn" disabled>Restart</button>
    <button id="backBtn">Back to Menu</button>
  </div>

<script>
  let score = 0;
  let timeLeft = 10;
  let gameActive = false;
  let interval = null;

  // UI elements
  const startPage = document.getElementById("startPage");
  const gamePage = document.getElementById("gamePage");

  const startBtn = document.getElementById("startBtn");

  const gameBtn = document.getElementById("gameBtn");

  const restartBtn = document.getElementById("restartBtn");

  const backBtn = document.getElementById("backBtn");

  const scoreDisplay = document.getElementById("score");

  const timerDisplay = document.getElementById("timer");

  //Event handlers
  startBtn.addEventListener("click", startMenu);
  gameBtn.addEventListener("click", clickBtn);
  restartBtn.addEventListener("click", restart);
  backBtn.addEventListener("click", backToMenu);

  function startMenu(){
    startPage.classList.remove("active-page");

    gamePage.classList.add("active-page");

    startGame();
  }

  function startGame(){
    score = 0;
    timeLeft = 10;
    gameActive = true;

    scoreDisplay.textContent = score;
    timerDisplay.textContent = timeLeft;

    gameBtn.disabled = false;
    restartBtn.disabled = true;

    interval = setInterval(function(){
      timeLeft--;
      timerDisplay.textContent = timeLeft;

      if (timeLeft <= 0){
        clearInterval(interval);
        gameActive = false;

        gameBtn.disabled = true;
        restartBtn.disabled = false;

        alert("Time's up! Your score was: " + score);
      }
    }, 1000);
  }

  function clickBtn(){
    if (gameActive) {
      score++;
      scoreDisplay.textContent = score;

      gameBtn.classList.toggle("active");

      setTimeout(() => {
        gameBtn.classList.toggle("active");

      }, 100);
    }
  }

  function restart(){
    clearInterval(interval);
    score = 0;
    timeLeft = 10;
    gameActive = false;

    scoreDisplay.textContent = score;
    timerDisplay.textContent = timeLeft;

    gameBtn.disabled = true;
    restartBtn.disabled = true;

    startGame();
  }

  function backToMenu(){
    clearInterval(interval);
    gameActive = false;

    gameBtn.disabled = true;

    gamePage.classList.remove("active-page");

    startPage.classList.add("active-page");

    restartBtn.disabled = true;

    score = 0;
    timeLeft = 10;

    scoreDisplay.textContent = score;
    timerDisplay.textContent = timeLeft;
  }
</script>

</body>
</html>
