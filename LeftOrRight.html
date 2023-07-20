<!DOCTYPE html>
<html>
<head>
  <title>Background Color Changer</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: Arial, sans-serif;
      font-size: 24px;
      color: white;
    }

    #centerText {
      display: none;
      font-weight: bold;
      font-size: 48px;
    }
  </style>
</head>
<body>
  <audio id="beep" preload="auto">
    <!-- Add your beep sound file here (e.g., beep.mp3) -->
    <source src="path_to_your_audio_file.mp3" type="audio/mpeg" />
    <!-- If you want to support other audio formats, add them here -->
  </audio>
  <div id="centerText">START</div>
  <script>
    function sleep(ms) {
      return new Promise(resolve => setTimeout(resolve, ms));
    }

    async function createBeep(duration, frequency) {
      const audioContext = new (window.AudioContext || window.webkitAudioContext)();
      const oscillator = audioContext.createOscillator();
      oscillator.type = "sine";
      oscillator.frequency.setValueAtTime(frequency, audioContext.currentTime);
      oscillator.connect(audioContext.destination);
      oscillator.start();
      await sleep(duration);
      oscillator.stop();
    }

    async function changeBackgroundColor(color, duration) {
      
      document.body.style.backgroundColor = color;
      document.getElementById("centerText").innerText = color === "blue" ? "LEFT" : color === "red" ? "RIGHT" : "START";
      if (color === "blue" || color === "red") {
        document.getElementById("centerText").style.display = "block";
        document.getElementById("beep").play();
      }
      if (color === "blue" || color === "red" || color === "green") {
      await createBeep(100, 440); // Duration: 100ms, Frequency: 440Hz
      }
      await sleep(duration);
      document.getElementById("centerText").style.display = "none";
      document.body.style.backgroundColor = "black";
    }

    async function startSequence() {
      // await changeBackgroundColor("green", 3000);
      document.body.style.backgroundColor = "green";

      document.getElementById("centerText").innerText = "START";
      document.getElementById("centerText").style.display = "block";
      await sleep(3000);
      document.getElementById("centerText").style.display = "none";

      const randomTimes = Math.floor(Math.random() * 5) + 1;
      for (let i = 0; i < randomTimes; i++) {
        await changeBackgroundColor("green", 500);
        await changeBackgroundColor("black", 500);
      }

      const randomColor = Math.random() < 0.5 ? "red" : "blue";
      await changeBackgroundColor(randomColor, 1000);
      await changeBackgroundColor("black", 500);

      startSequence(); // Infinite loop
    }

    startSequence(); // Start the sequence when the page loads
  </script>
</body>
</html>
