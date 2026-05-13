=-=-= About =-=-=

<p> hey, i'm sofia — media student & digital designer based in inland. </p>

<p> 🇫🇮 Media student & digital designer based in Finland </p>
<p> 🎨 Creating UI/UX, visual content, and web experiences </p>
<p>✨ Love making beautiful things that feel simple and alive</p>
<ul>
<li> 🌐 <a href="https://www.linkedin.com/in/sofia-maksimova-digital-gastri/">LinkedIn</a></li>
<li> 📧 <a href="maksimova_sofia02@mail.ru ">Email</li>
</ul>
<style>
  body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(#bfe9ff, #e8f7ff);
    font-family: sans-serif;
  }

  .dog {
    position: relative;
    width: 140px;
    height: 100px;
    animation: bounce 1.2s infinite ease-in-out;
  }

  /* тело */
  .body {
    position: absolute;
    bottom: 0;
    width: 100px;
    height: 60px;
    background: #8b5a2b;
    border-radius: 40px;
  }

  /* голова */
  .head {
    position: absolute;
    top: -20px;
    left: 60px;
    width: 50px;
    height: 50px;
    background: #8b5a2b;
    border-radius: 50%;
  }

  /* уши */
  .ear {
    position: absolute;
    width: 15px;
    height: 25px;
    background: #5a3a1e;
    border-radius: 50%;
    top: -10px;
  }

  .ear.left { left: 65px; transform: rotate(-20deg); }
  .ear.right { left: 90px; transform: rotate(20deg); }

  /* глаз */
  .eye {
    position: absolute;
    width: 6px;
    height: 6px;
    background: black;
    border-radius: 50%;
    top: 10px;
    left: 80px;
  }

  /* хвост */
  .tail {
    position: absolute;
    width: 10px;
    height: 40px;
    background: #5a3a1e;
    right: -5px;
    bottom: 20px;
    border-radius: 10px;
    transform-origin: top;
    animation: wag 0.4s infinite alternate;
  }

  @keyframes wag {
    from { transform: rotate(20deg); }
    to { transform: rotate(-30deg); }
  }

  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }

</style>
</head>
<body>

<div class="dog">
  <div class="body"></div>
  <div class="head"></div>
  <div class="ear left"></div>
  <div class="ear right"></div>
  <div class="eye"></div>
  <div class="tail"></div>
</div>
<!--
**SofiPomidorka/SofiPomidorka** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
