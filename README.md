<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>For My Pookie Amira</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;600&display=swap" rel="stylesheet" />
  <style>
    /* Background gradient */
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #fbd3e9 0%, #bb377d 100%);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-family: 'Poppins', sans-serif;
      color: #4a153c;
      overflow: hidden;
      text-align: center;
      animation: fadeIn 2s ease forwards;
    }

    /* Heading with glow and cursive font */
    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 4rem;
      margin: 0 0 0.2em;
      color: #fff;
      text-shadow:
        0 0 10px #ff70a6,
        0 0 20px #ff70a6,
        0 0 30px #ff70a6,
        0 0 40px #ff70a6;
      animation: fadeIn 2s ease forwards 0.5s;
      opacity: 0;
    }

    /* Subheading */
    h2 {
      font-weight: 600;
      font-size: 2.5rem;
      margin: 0 0 1.5em;
      color: #ffe3ec;
      letter-spacing: 2px;
      animation: fadeIn 2s ease forwards 1s;
      opacity: 0;
    }

    /* Cake image with floating animation */
    img {
      width: 280px;
      height: auto;
      border-radius: 20px;
      box-shadow:
        0 10px 30px rgba(255, 182, 193, 0.6),
        0 0 40px #ff70a6;
      animation: float 4s ease-in-out infinite, fadeIn 2s ease forwards 1.5s;
      opacity: 0;
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    img:hover {
      transform: scale(1.05) rotate(3deg);
      box-shadow:
        0 15px 50px rgba(255, 105, 180, 0.8),
        0 0 60px #ff4d94;
    }

    /* Animations */
    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-15px);
      }
    }
  </style>
</head>
<body>
  <h1>For My Pookie Amira</h1>
  <h2>Happy Birthday!</h2>
  <img
    src="https://cdn.pixabay.com/photo/2022/10/30/14/33/cake-7558567_960_720.jpg"
    alt="Birthday Cake with Candle"
  />
</body>
</html>
