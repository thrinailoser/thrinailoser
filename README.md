<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Calm Your Mind</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      color: #333;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    h1 {
      color: #6fa3ef;
    }
    .section {
      padding: 20px;
      margin: 20px;
      background-color: #e0f7fa;
      border-radius: 8px;
    }
    button {
      background-color: #6fa3ef;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #4d82c2;
    }
  </style>
</head>
<body>
  <h1>Welcome to Your Calm Space</h1>
  <div class="section">
    <h2>Breathing Exercise</h2>
    <p>Follow this guide to relax your mind.</p>
    <button onclick="startBreathing()">Start Breathing Exercise</button>
  </div>

  <div class="section">
    <h2>Calming Music</h2>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
      Your browser does not support the audio element.
    </audio>
  </div>

  <div class="section">
    <h2>Inspirational Quote</h2>
    <p id="quote">"Breathe in, breathe out, and stay calm."</p>
  </div>

  <script>
    function startBreathing() {
      alert('Breathe in... Hold... Breathe out... Repeat!');
    }
  </script>
</body>
</html>

