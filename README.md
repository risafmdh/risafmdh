<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>the intro</title>
  <style>
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
  body{
    font-family: 'Bebas Neue', Courier, monospace;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    background-color: rgb(13, 2, 53);
  }
  .mai-titleconta{
    margin-top: 10px;
    height: 200px;
    width: 650px;
    border-radius: 20px;
    border: none;
    display: flex;
    justify-content: center;
    align-items: center;
  height: 160px;
  background: rgba(255, 255, 255, 0.4);
  backdrop-filter: blur(41px);
  -webkit-backdrop-filter: blur(41px);
  border-radius: 20px;
  border: 1px solid rgba(255, 255, 255, 0.3);
  box-shadow: 
    0 8px 32px rgba(0, 0, 0, 0.1),
    inset 0 1px 0 rgba(255, 255, 255, 0.5),
    inset 0 -1px 0 rgba(255, 255, 255, 0.1),
    inset 0 0 0px 0px rgba(255, 255, 255, 0);
  position: relative;
  overflow: hidden;
}

.mai-titleconta::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 1px;
  background: linear-gradient(
    90deg,
    transparent,
    rgba(255, 255, 255, 0.9),
    transparent
  );
}

.mai-titleconta::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 1px;
  height: 100%;
  background: linear-gradient(
    180deg,
    rgba(255, 255, 255, 0.8),
    transparent,
    rgba(255, 255, 255, 0.3)
  );
  }

  .main-title {
  animation: flicker 2s linear infinite;
  font-size: 100px;
  font-weight: bold;

  /* Attractive neon gradient colors */
  color: #ffffff;
  text-shadow:
    0 0 5px #ff00ff,
    0 0 10px #ff00ff,
    0 0 20px #00ffff,
    0 0 40px #00ffff,
    0 0 80px #7b2cff;
}

@keyframes flicker {
  75% {
    color: #ffffff;
    text-shadow:
      0 0 5px #ff00ff,
      0 0 10px #ff00ff,
      0 0 20px #00ffff,
      0 0 40px #00ffff,
      0 0 80px #7b2cff;
  }

  76% {
    color: #222;
    text-shadow: none;
  }

  77% {
    color: #00ffff;
    text-shadow:
      0 0 5px #00ffff,
      0 0 15px #00ffff,
      0 0 30px #00ffff;
  }

  78% {
    color: #ff4dff;
    text-shadow:
      0 0 5px #ff4dff,
      0 0 15px #ff4dff,
      0 0 30px #ff4dff;
  }

  79% {
    color: #111;
    text-shadow: none;
  }

  80% {
    color: #ffffff;
    text-shadow:
      0 0 5px #7b2cff,
      0 0 15px #7b2cff,
      0 0 30px #00ffff;
  }

  90% {
    color: #222;
    text-shadow: none;
  }

  90.5% {
    color: #ffffff;
    text-shadow:
      0 0 5px #ff00ff,
      0 0 15px #00ffff,
      0 0 30px #7b2cff;
  }
}
.stand-line{
  background-color: white;
  height: 300px;
  width: 10px;
  
}

.stand-under{
  height: 100px;
  width: 70%;
  display: flex;
  justify-content: center;
  margin-top: -60px;
}

.rock-image{
  height: 100px;
  width: 100%;
}

.the-handle{
  height: 15px;
  width: 70px;
  background-color: white;
  border-radius: 0 0 12px 12px;
}

.deatal-text{
  z-index: -2;
  margin-top: -270px;
  width: 70%;
  color: yellow;
  word-spacing: 4px;
  font-size: 20px;
  text-align: center;
}
</style>
</head>
<body>
  <div class="mai-titleconta">
    <h1 class="main-title">SOFTWARE ENGINEER</h1>
</div>
<div class="the-handle"></div>
<div class="stand-line"></div>
<div class="stand-under">
  <img src="155635.svg" alt="" class="rock-image">
</div>
<div class="deatal-text">
  <p>Hi, I'm a Software Engineer focused on creating reliable and user-friendly applications. I enjoy working with modern technologies, backend systems, cloud services, and open-source projects. Passionate about continuous learning, teamwork, and writing maintainable code.
</p>
</div>
</body>
</html>
