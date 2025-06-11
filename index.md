---
title: Welcome to my blog!
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Assassin's Creed - OffSec Blog</title>
  <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
  <style>
     *{
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Ubuntu', sans-serif;
      background-color: #0d0d0d;
      color: #f0f0f0;
    }

    .hero {
      background-image: url('https://wallpaperaccess.com/full/153274.jpg');
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 40px;
      position: relative;
    }

    .hero::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(to top, rgba(0, 0, 0, 0.9), transparent);
      z-index: 1;
    }

    .content {
      position: relative;
      z-index: 2;
    }

    .title {
      font-size: 3rem;
      font-weight: 700;
      text-shadow: 2px 2px 5px #000;
    }

    .subtitle {
      font-size: 1.25rem;
      margin-top: 10px;
      color: #ccc;
    }

    .episode-list {
      background-color: #111;
      padding: 30px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }

    .episode {
      background-color: #1b1b1b;
      padding: 20px;
      border-left: 4px solid crimson;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
      transition: transform 0.3s;
    }

    .episode:hover {
      transform: translateY(-5px);
    }

    .episode h3 {
      font-size: 1.2rem;
      color: crimson;
    }

    .episode p {
      font-size: 0.95rem;
      margin-top: 5px;
      color: #aaa;
    }

    .meta {
      margin-top: 15px;
      font-size: 0.85rem;
      color: #666;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #0b0b0b;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>
  <div class="hero">
    <div class="content">
      <h1 class="title">ASSASSIN'S CREED</h1>
      <p class="subtitle">The path to mastery is forged in the shadows – Welcome to the OffSec Blog</p>
    </div>
  </div>

  <div class="episode-list">
    <div class="episode">
      <h3>01 - Enter the Animus</h3>
      <p>Diving deep into memory manipulation and binary exploitation foundations.</p>
      <p class="meta">Posted on: June 1, 2025</p>
    </div>
    <div class="episode">
      <h3>02 - Creed of Recon</h3>
      <p>Advanced recon and OSINT for real-world red team scenarios.</p>
      <p class="meta">Posted on: June 3, 2025</p>
    </div>
    <div class="episode">
      <h3>03 - Hidden Blade: Buffer Overflows</h3>
      <p>Sharpen your exploits with stack smashing and shellcode crafting.</p>
      <p class="meta">Posted on: June 5, 2025</p>
    </div>
    <div class="episode">
      <h3>04 - Brotherhood of Shells</h3>
      <p>Reverse shells, bind shells, and evasion techniques for stealthy operations.</p>
      <p class="meta">Posted on: June 7, 2025</p>
    </div>
    <div class="episode">
      <h3>05 - The Templars' Firewall</h3>
      <p>Bypassing modern defenses and abusing misconfigurations.</p>
      <p class="meta">Posted on: June 9, 2025</p>
    </div>
  </div>

  <footer>
    Crafted with discipline in the digital shadows. &copy; 2025 AssassinSec
  </footer>
</body>
</html>
