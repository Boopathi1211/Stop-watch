<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Stopwatch Web Application</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #121212;
      color: #fff;
      text-align: center;
      padding: 50px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .stopwatch {
      font-size: 3rem;
      margin: 20px 0;
    }

    .buttons button {
      padding: 10px 20px;
      margin: 10px;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }

    .start { background: #28a745; color: white; }
    .pause { background: #ffc107; color: black; }
    .reset { background: #dc3545; color: white; }
    .lap { background: #007bff; color: white; }

    .laps {
      margin-top: 30px;
      text-align: left;
      max-width: 300px;
      margin-left: auto;
      margin-right: auto;
    }

    .laps li {
      background: #1e1e1e;
      padding: 5px 10px;
      margin: 5px 0;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <h1>Stopwatch Web App</h1>
  <div class="stopwatch" id="display">00:00:00</div>

  <div class="buttons">
    <button class="start" onclick="start()">Start</button>
    <button class="pause" onclick="pause()">Pause</button>
    <button class="reset" onclick="reset()">Reset</button>
    <button class="lap" onclick="lap()">Lap</button>
  </div>

  <ul class="laps" id="laps"></ul>

  <script>
    let [hours, minutes, seconds] = [0, 0, 0];
    let display = document.getElementById("display");
    let laps = document.getElementById("laps");
    let timer = null;

    function updateDisplay() {
      let h = String(hours).padStart(2, '0');
      let m = String(minutes).padStart(2, '0');
      let s = String(seconds).padStart(2, '0');
      display.innerText = `${h}:${m}:${s}`;
    }

    function stopwatch() {
      seconds++;
      if (seconds == 60) {
        seconds = 0;
        minutes++;
        if (minutes == 60) {
          minutes = 0;
          hours++;
        }
      }
      updateDisplay();
    }

    function start() {
      if (timer !== null) return;
      timer = setInterval(stopwatch, 1000);
    }

    function pause() {
      clearInterval(timer);
      timer = null;
    }

    function reset() {
      clearInterval(timer);
      [hours, minutes, seconds] = [0, 0, 0];
      updateDisplay();
      laps.innerHTML = "";
      timer = null;
    }

    function lap() {
      let time = display.innerText;
      let li = document.createElement("li");
      li.textContent = `Lap: ${time}`;
      laps.appendChild(li);
    }
  </script>

</body>
</html>
