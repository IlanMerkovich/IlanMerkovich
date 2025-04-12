<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ilan Markovich | GitHub Profile</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0f0f0f, #1a1a1a);
      color: #00ffe7;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 5rem 2rem;
      background: linear-gradient(135deg, #0ff, #0088ff);
      color: black;
      animation: slideDown 1.5s ease-out;
    }
    @keyframes slideDown {
      from { transform: translateY(-100%); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    h1 {
      font-size: 3rem;
      margin: 0;
      text-shadow: 0 0 15px #00fff2;
    }
    h2 {
      font-size: 1.5rem;
      margin-top: 0.5rem;
    }
    .section {
      padding: 3rem 2rem;
      max-width: 900px;
      margin: auto;
      background: rgba(0, 255, 234, 0.05);
      border: 1px solid #00ffe7;
      border-radius: 20px;
      margin-top: 2rem;
      backdrop-filter: blur(5px);
      box-shadow: 0 0 20px #00fff2;
      animation: fadeIn 1.5s ease-in;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
    .contact-btn {
      background: #00ffe7;
      color: #000;
      padding: 1rem 2rem;
      font-size: 1.2rem;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .contact-btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 25px #00fff2;
    }
    .memes {
      display: flex;
      flex-direction: column;
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .memes img {
      max-width: 100%;
      border-radius: 15px;
      box-shadow: 0 0 15px #00fff2;
    }
    .neon-glow {
      text-align: center;
      font-size: 1.5rem;
      margin-top: 4rem;
      color: #00ffe7;
      text-shadow: 0 0 10px #00fff2;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { text-shadow: 0 0 10px #00fff2; }
      50% { text-shadow: 0 0 30px #00fff2; }
      100% { text-shadow: 0 0 10px #00fff2; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Ilan Markovich</h1>
    <h2>Futuristic GitHub Portfolio</h2>
  </header>

  <section class="section">
    <h2>🚀 Welcome to my digital universe</h2>
    <p>Exploring code, building dreams, and sipping coffee near the sea 🌊☕</p>
    <button class="contact-btn" onclick="location.href='mailto:merkovichilan@gmail.com'">GET IN TOUCH</button>
  </section>

  <section class="section memes">
    <h2>💻 Coding Memes</h2>
    <img src="https://i.imgur.com/U3vTGjX.jpeg" alt="Debugging meme" />
    <img src="https://i.imgur.com/6HjKXwz.jpeg" alt="Git meme" />
    <img src="https://i.imgur.com/tCFe3F7.jpeg" alt="JavaScript meme" />
  </section>

  <div class="neon-glow">Thanks for visiting my profile! ✨</div>
</body>
</html>
