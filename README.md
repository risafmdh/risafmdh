<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Software Engineer Intro</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:'Bebas Neue', sans-serif;
      min-height:100vh;
      background:linear-gradient(135deg,#050816,#12002f,#1f004d);
      display:flex;
      flex-direction:column;
      align-items:center;
      justify-content:center;
      overflow:hidden;
    }

    .main-title-container{
      width:700px;
      max-width:90%;
      height:180px;

      display:flex;
      justify-content:center;
      align-items:center;

      background:rgba(255,255,255,0.08);

      backdrop-filter:blur(30px);
      -webkit-backdrop-filter:blur(30px);

      border:1px solid rgba(255,255,255,0.2);

      border-radius:25px;

      box-shadow:
        0 8px 32px rgba(0,0,0,0.4),
        inset 0 1px 0 rgba(255,255,255,0.2);

      position:relative;
    }

    .main-title-container::before{
      content:'';
      position:absolute;
      inset:0;
      border-radius:25px;
      padding:2px;

      background:linear-gradient(
        45deg,
        #ff00ff,
        #00ffff,
        #7b2cff,
        #00ffff
      );

      -webkit-mask:
        linear-gradient(#fff 0 0) content-box,
        linear-gradient(#fff 0 0);

      -webkit-mask-composite:xor;
      mask-composite:exclude;
    }

    .main-title{
      font-size:90px;
      color:white;
      letter-spacing:4px;

      text-shadow:
        0 0 5px #ff00ff,
        0 0 10px #ff00ff,
        0 0 20px #00ffff,
        0 0 40px #00ffff,
        0 0 80px #7b2cff;

      animation:flicker 2s infinite;
    }

    @keyframes flicker{
      0%,18%,22%,25%,53%,57%,100%{
        opacity:1;
      }

      20%,24%,55%{
        opacity:0.4;
      }
    }

    .handle{
      width:80px;
      height:18px;
      background:white;
      border-radius:0 0 15px 15px;

      box-shadow:
        0 0 10px white,
        0 0 20px #00ffff;

      margin-top:-2px;
    }

    .stand-line{
      width:10px;
      height:220px;

      background:linear-gradient(
        to bottom,
        #ffffff,
        #00ffff
      );

      box-shadow:
        0 0 15px #00ffff;

      border-radius:10px;
    }

    .stand-base{
      width:300px;
      height:40px;

      background:linear-gradient(
        90deg,
        #00ffff,
        #7b2cff,
        #ff00ff
      );

      border-radius:50px;

      box-shadow:
        0 0 20px #00ffff,
        0 0 40px #ff00ff;

      margin-top:-5px;
    }

    .detail-text{
      width:70%;
      max-width:900px;

      color:#ffe600;

      text-align:center;

      font-size:26px;
      letter-spacing:2px;
      line-height:1.4;

      margin-top:40px;

      text-shadow:
        0 0 10px rgba(255,230,0,0.7);
    }

    @media(max-width:768px){

      .main-title{
        font-size:50px;
        text-align:center;
      }

      .detail-text{
        font-size:18px;
        width:90%;
      }

      .stand-base{
        width:200px;
      }

    }

  </style>
</head>

<body>

  <div class="main-title-container">
    <h1 class="main-title">SOFTWARE ENGINEER</h1>
  </div>

  <div class="handle"></div>

  <div class="stand-line"></div>

  <div class="stand-base"></div>

  <div class="detail-text">
    <p>
      Hi, I'm a Software Engineer focused on creating reliable and user-friendly applications.
      I enjoy working with modern technologies, backend systems, cloud services, and open-source projects.
      Passionate about continuous learning, teamwork, and writing maintainable code.
    </p>
  </div>

</body>
</html>
