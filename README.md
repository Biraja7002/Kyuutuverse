
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f6">
<title>Kyuutuverse ♡ | Anuska's Birthday</title>

<style>
:root{
  --pink:#ff6fae;--pink2:#ffc4dc;--purple:#a78bfa;
  --cream:#fff8fb;--ink:#513047;--muted:#936d83;
  --glass:rgba(255,255,255,.82);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:82px}
body{
  margin:0;font-family:"Trebuchet MS",Arial,sans-serif;color:var(--ink);
  background:radial-gradient(circle at 10% 5%,#ffe0ee,transparent 28%),
  radial-gradient(circle at 95% 25%,#e9ddff,transparent 28%),
  linear-gradient(145deg,#fff8fb,#fff0f6 45%,#f6efff);
  overflow-x:hidden;transition:background .3s,color .3s;
}
button,input,textarea{font:inherit}
button{cursor:pointer}
a{color:inherit}
img,video{max-width:100%}
section{padding:66px 18px}
.wrap{width:min(100%,920px);margin:auto}
.center{text-align:center}
.eyebrow{text-transform:uppercase;letter-spacing:3px;color:#d45b98;font-size:.76rem;font-weight:bold}
h1,h2,h3{line-height:1.2}
h2{font-size:clamp(1.8rem,6vw,2.8rem);margin:10px 0 14px}
p{line-height:1.8}
.muted{color:var(--muted)}
.small{font-size:.87rem}
.card{
  background:var(--glass);border:1px solid rgba(255,255,255,.9);
  border-radius:24px;padding:22px;
  box-shadow:0 12px 38px rgba(184,92,139,.10);
  backdrop-filter:blur(12px);
}
.btn{
  border:0;border-radius:999px;padding:13px 21px;
  background:linear-gradient(120deg,#ff75b5,#c5a0ff);
  color:white;font-weight:bold;box-shadow:0 7px 20px #ec8cbb40;
  transition:.2s;margin:4px 2px;
}
.btn:hover{transform:translateY(-2px)}
.btn.secondary{color:#a4497a;background:white;border:1px solid #f4c5dc;box-shadow:none}
.btn:disabled{opacity:.55;cursor:not-allowed}
.pill{display:inline-block;padding:7px 12px;border-radius:30px;background:#ffe2ef;color:#a54c7b;font-size:.8rem}
.grid{display:grid;gap:17px}
.two{grid-template-columns:repeat(2,minmax(0,1fr))}
.three{grid-template-columns:repeat(3,minmax(0,1fr))}
nav{
  position:sticky;top:0;z-index:10;display:flex;gap:9px;align-items:center;
  padding:11px 13px;overflow-x:auto;white-space:nowrap;
  background:#fff8f2ef;border-bottom:1px solid #f7dce9;backdrop-filter:blur(16px)
}
nav .brand{font-weight:bold;color:#c64d8b;margin-right:8px}
nav a{text-decoration:none;font-size:.8rem;padding:8px 10px;border-radius:30px;background:#fff;border:1px solid #f6dce8}
nav a:hover{background:#ffe2ef}
.hero{
  min-height:88vh;display:flex;align-items:center;justify-content:center;
  padding:55px 18px 70px;position:relative;overflow:hidden
}
.hero-inner{width:min(100%,800px);text-align:center;position:relative;z-index:1}
.hero h1{
  font-size:clamp(3rem,13vw,6.4rem);letter-spacing:-3px;margin:18px 0 10px;
  background:linear-gradient(100deg,#f05b9f,#ad80f2,#f05b9f);
  color:transparent;background-clip:text
}
.hero p{max-width:620px;margin:12px auto 24px}
.hero-heart{font-size:3rem;animation:heartbeat 1.5s infinite;display:inline-block}
@keyframes heartbeat{50%{transform:scale(1.15)}}
.float{position:absolute;pointer-events:none;opacity:.6;animation:floatUp 8s linear infinite}
@keyframes floatUp{
  from{transform:translateY(15vh) rotate(0);opacity:0}
  15%{opacity:.65}
  to{transform:translateY(-110vh) rotate(260deg);opacity:0}
}
.countdown{display:flex;justify-content:center;gap:10px;flex-wrap:wrap;margin:24px 0}
.timebox{min-width:72px;padding:15px 11px;background:#ffffffb8;border:1px solid #f5c9df;border-radius:18px;box-shadow:0 7px 20px #e9a5c522}
.timebox strong{display:block;font-size:1.65rem;color:#c94d91}
.timebox span{font-size:.72rem;color:var(--muted)}
.section-head{text-align:center;margin:0 auto 28px;max-width:650px}
.section-head p{color:var(--muted)}
.photo{width:100%;height:290px;object-fit:cover;border-radius:18px;background:#f8dfea;display:block}
.photo-card{padding:12px;transform:rotate(-1deg)}
.photo-card:nth-child(even){transform:rotate(1deg)}
.photo-card p{margin:10px 4px 2px;text-align:center}
.memory-number{color:#cf5997;font-size:.78rem}
.media{display:block;width:100%;border-radius:17px;background:#f4d8e7;max-height:460px}
audio{width:100%;margin:12px 0}
.song-cover{
  font-size:4rem;width:115px;height:115px;margin:0 auto 16px;border-radius:50%;
  display:grid;place-items:center;background:linear-gradient(140deg,#ffd2e7,#d9c8ff);
  box-shadow:0 0 0 10px #fff7fb,0 0 0 12px #f6d6e7
}
.equalizer{display:flex;justify-content:center;gap:5px;height:30px;align-items:center}
.equalizer span{width:5px;height:9px;border-radius:8px;background:#dc75ac}
.equalizer.playing span{animation:bars .65s ease-in-out infinite alternate}
.equalizer span:nth-child(2){animation-delay:.1s}
.equalizer span:nth-child(3){animation-delay:.2s}
.equalizer span:nth-child(4){animation-delay:.3s}
.equalizer span:nth-child(5){animation-delay:.4s}
@keyframes bars{to{height:28px}}
.portal{display:block;padding:20px;border-radius:20px;text-decoration:none;background:#fff9fd;border:1px solid #f4d9e8;transition:.2s}
.portal:hover{transform:translateY(-4px);background:white}
.portal .emoji{font-size:2rem}
.portal strong{display:block;margin:9px 0}
.letter{font-family:Georgia,serif;line-height:2;white-space:pre-line;background:#fffaf4;border:1px solid #f6dfd0;padding:23px;border-radius:15px;transform:rotate(-.3deg)}
.game-output{min-height:35px;color:#b34581;font-weight:bold;margin-top:12px}
.gift{font-size:3.2rem;border:0;border-radius:20px;padding:25px 8px;background:#fff5fb;border:1px solid #f3d4e6;width:100%}
.gift:hover{transform:scale(1.03)}
.progress{height:8px;background:#f5d8e7;border-radius:20px;overflow:hidden}
.progress div{height:100%;width:0;background:linear-gradient(90deg,#ff6fae,#ac88f5);transition:.3s}
textarea,input:not([type=checkbox]){
  width:100%;border:1px solid #efcbdc;background:#fffafd;border-radius:14px;
  padding:13px;color:var(--ink);outline-color:#f18bbd;margin:7px 0 12px
}
footer{padding:38px 18px 65px;text-align:center;color:#9b6c87}
#toast{
  position:fixed;left:50%;bottom:25px;z-index:50;transform:translate(-50%,25px);
  opacity:0;pointer-events:none;padding:13px 20px;border-radius:30px;
  color:#fff;background:#a54c7b;transition:.25s;max-width:90%;text-align:center
}
#toast.show{opacity:1;transform:translate(-50%,0)}
#confetti{position:fixed;inset:0;pointer-events:none;z-index:30;overflow:hidden}
.confetti-piece{position:absolute;top:-15px;animation:fall 3.5s linear forwards}
@keyframes fall{to{transform:translateY(110vh) rotate(800deg);opacity:.2}}
#bucketlist label{display:flex;align-items:center;gap:10px;padding:12px 8px;border-bottom:1px solid #f5dce8;line-height:1.5}
#bucketlist input[type=checkbox]{width:20px;height:20px;flex-shrink:0;margin:0;accent-color:#e76aa8}
#quizAnswers{margin:15px 0}
#quizAnswers .btn{width:100%;border-radius:14px}
#openwhen p:not([hidden]){background:#fff2f8;border-radius:15px;padding:14px;line-height:1.8}
.timeline{border-left:3px solid #f4bdd8;margin-left:10px;padding-left:20px}
.timeline .card{margin-bottom:18px}
#flowerGarden{overflow-wrap:anywhere}
@media(max-width:620px){
  .two,.three{grid-template-columns:1fr}
  section{padding:50px 15px}
  .hero{min-height:84vh}
  .photo{height:320px}
  .card{padding:18px}
  .timebox{min-width:65px}
}
</style>
</head>

<body>
<div id="confetti"></div>

<nav>
  <span class="brand">♡ Kyuutuverse</span>
  <a href="#home">Home</a>
  <a href="#memories">Memories</a>
  <a href="#song">Song</a>
  <a href="#videos">Videos</a>
  <a href="#games">Games</a>
  <a href="#timeline">Timeline</a>
  <a href="#openwhen">Letters</a>
  <a href="#quiz">Quiz</a>
  <a href="#garden">Garden</a>
  <a href="#bucketlist">Bucket List</a>
  <a href="#letter">Main Letter</a>
  <a href="#wishes">Wishes</a>
  <a href="#surprise">Surprise</a>
</nav>

<header class="hero" id="home">
  <div class="hero-inner">
    <span class="pill">A tiny universe made for one special girl</span>
    <div class="hero-heart">💗</div>
    <p class="eyebrow">For my favourite person</p>
    <h1>Kyuutuverse</h1>
    <h2 style="font-size:clamp(1.25rem,5vw,2rem)">Happy Birthday, Anuska! 🎂</h2>
    <p>Welcome to your own little corner of the internet, Kyuutu. Filled with memories, music, silly games, warm wishes and all the little things that remind me of you. 🎀✨</p>

    <div class="countdown" id="countdown">
      <div class="timebox"><strong id="days">--</strong><span>DAYS</span></div>
      <div class="timebox"><strong id="hours">--</strong><span>HOURS</span></div>
      <div class="timebox"><strong id="minutes">--</strong><span>MINUTES</span></div>
      <div class="timebox"><strong id="seconds">--</strong><span>SECONDS</span></div>
    </div>
    <p id="countdownMessage" class="muted small">Counting down to your special day 💕</p>
    <a href="#universe"><button class="btn">Enter your universe ✨</button></a>
    <button class="btn secondary" onclick="showToast('You deserve happiness, Kyuutu 💗')">A little reminder 💌</button>
  </div>
</header>

<section id="universe">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Choose your adventure</p>
      <h2>Your Little Universe 🌷</h2>
      <p>Every corner holds a different little surprise.</p>
    </div>
    <div class="grid three">
      <a class="portal" href="#memories"><span class="emoji">📸</span><strong>Memory Lane</strong><span class="muted small">Little moments, forever saved.</span></a>
      <a class="portal" href="#song"><span class="emoji">🎧</span><strong>Our Song</strong><span class="muted small">Press play and stay a while.</span></a>
      <a class="portal" href="#videos"><span class="emoji">🎬</span><strong>Mini Cinema</strong><span class="muted small">Three little video moments.</span></a>
      <a class="portal" href="#games"><span class="emoji">🎮</span><strong>Kyuutu Games</strong><span class="muted small">Tiny challenges and rewards.</span></a>
      <a class="portal" href="#timeline"><span class="emoji">💞</span><strong>Our Chapters</strong><span class="muted small">A timeline of memories.</span></a>
      <a class="portal" href="#openwhen"><span class="emoji">💌</span><strong>Open When...</strong><span class="muted small">Letters for different days.</span></a>
      <a class="portal" href="#quiz"><span class="emoji">🧩</span><strong>Birthday Quiz</strong><span class="muted small">A tiny challenge.</span></a>
      <a class="portal" href="#garden"><span class="emoji">🌹</span><strong>Flower Garden</strong><span class="muted small">Plant a digital flower.</span></a>
      <a class="portal" href="#wishes"><span class="emoji">🌠</span><strong>Wish Galaxy</strong><span class="muted small">Make a wish for your new year.</span></a>
    </div>
  </div>
</section>

<section id="memories">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Little pieces of forever</p>
      <h2>Our Memory Lane 📸</h2>
      <p>Three pictures, three little reminders that ordinary moments can feel special.</p>
    </div>
    <div class="grid three">
      <div class="card photo-card">
        <img class="photo" src="IMG-20260829-WA0026.jpg" alt="Memory one" loading="lazy">
        <p><span class="memory-number">MEMORY 01</span><br>One for the memory book 💗</p>
      </div>
      <div class="card photo-card">
        <img class="photo" src="IMG-20260917-WA0025.jpg" alt="Memory two" loading="lazy">
        <p><span class="memory-number">MEMORY 02</span><br>A moment worth keeping 🌷</p>
      </div>
      <div class="card photo-card">
        <img class="photo" src="Snapchat-1339605840.jpg" alt="Memory three" loading="lazy">
        <p><span class="memory-number">MEMORY 03</span><br>Saved with a little love 🎀</p>
      </div>
    </div>
    <p class="center muted small">Tap a picture to view it larger.</p>
  </div>
</section>

<section id="song">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Press play, think of us</p>
      <h2>Our Little Soundtrack 🎧</h2>
      <p>Some feelings are easier to share through music than through words.</p>
    </div>
    <div class="card center" style="max-width:590px;margin:auto">
      <div class="song-cover">🎵</div>
      <h3>Tera Naam Doon</h3>
      <p class="muted small">A song for my Kyuutu 💗</p>
      <div class="equalizer" id="equalizer"><span></span><span></span><span></span><span></span><span></span></div>
      <audio id="ourSong" controls preload="metadata">
        <source src="tera naam doon.mp3" type="audio/mpeg">
        Your browser does not support audio playback.
      </audio>
      <p class="small muted">Press play to listen.</p>
      <button class="btn secondary" onclick="showToast('A little pink sky and your favourite song 💕')">Song dedication 💌</button>
    </div>
  </div>
</section>

<section id="videos">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Little moments in motion</p>
      <h2>Our Mini Cinema 🎬</h2>
      <p>Press play whenever you want to revisit these moments.</p>
    </div>
    <div class="grid">
      <div class="card"><span class="pill">VIDEO 01</span><h3>Memory in Motion 🌸</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO1.mp4" type="video/mp4">Video not supported.</video></div>
      <div class="card"><span class="pill">VIDEO 02</span><h3>A Little More of Us 🎀</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO2.mp4" type="video/mp4">Video not supported.</video></div>
      <div class="card"><span class="pill">VIDEO 03</span><h3>One to Remember 💗</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO3.mp4" type="video/mp4">Video not supported.</video></div>
    </div>
  </div>
</section>

<section id="games">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">Play a little</p><h2>Kyuutu's Fun Corner 🎮</h2><p>Little games made to bring a smile to your face.</p></div>
    <div class="grid two">
      <div class="card center">
        <h3>1. Catch the Hearts 💗</h3><p>Tap to collect five hearts.</p>
        <div class="progress"><div id="heartProgress"></div></div>
        <p id="heartCount">Hearts collected: 0 / 5</p>
        <button class="btn" id="heartButton" onclick="collectHeart()">Collect a heart 💗</button>
        <div class="game-output" id="heartOutput"></div>
      </div>
      <div class="card center">
        <h3>2. Guess the Nickname 🎀</h3><p>What nickname is used on this website?</p>
        <input id="nicknameInput" placeholder="Type your answer..." autocomplete="off">
        <button class="btn" onclick="checkNickname()">Check answer</button>
        <div class="game-output" id="nicknameOutput"></div>
      </div>
      <div class="card center">
        <h3>3. Pick a Mystery Gift 🎁</h3><p>Choose a box.</p>
        <div class="grid three">
          <button class="gift" onclick="openGift(0)" aria-label="Gift one">🎁</button>
          <button class="gift" onclick="openGift(1)" aria-label="Gift two">🎀</button>
          <button class="gift" onclick="openGift(2)" aria-label="Gift three">💝</button>
        </div>
        <div class="game-output" id="giftOutput"></div>
      </div>
      <div class="card center">
        <h3>4. Daily Compliment 🌷</h3><p>Tap for a little reminder.</p>
        <div style="font-size:2.6rem">🌸</div>
        <button class="btn" onclick="compliment()">Give me a compliment</button>
        <div class="game-output" id="complimentOutput"></div>
      </div>
    </div>
  </div>
</section>

<section id="timeline">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">Every little moment matters</p><h2>Our Story in Little Chapters 💞</h2><p>A timeline for moments and memories worth keeping.</p></div>
    <div class="timeline">
      <div class="card"><span class="pill">CHAPTER 01 🌷</span><h3>The Beginning</h3><p>Every story begins somewhere. This one has its own little place in my heart.</p></div>
      <div class="card"><span class="pill">CHAPTER 02 💬</span><h3>The Conversations</h3><p>Random talks, silly jokes and little moments can become beautiful memories.</p></div>
      <div class="card"><span class="pill">CHAPTER 03 💗</span><h3>Today and Beyond</h3><p>Here's to growing, learning, laughing and making more memories.</p></div>
    </div>
    <p class="center muted small">Personalize these chapters with your real dates and memories.</p>
  </div>
</section>

<section id="openwhen">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">Little letters for different days</p><h2>Open When… 💌</h2><p>Choose a letter to reveal a message for that moment.</p></div>
    <div class="grid two">
      <div class="card center"><div style="font-size:2.5rem">🥹</div><h3>When you need a smile</h3><button class="btn secondary" onclick="openLetter(0)">Open letter 💗</button><p id="openLetter0" hidden></p></div>
      <div class="card center"><div style="font-size:2.5rem">🌧️</div><h3>On a difficult day</h3><button class="btn secondary" onclick="openLetter(1)">Open letter 🌷</button><p id="openLetter1" hidden></p></div>
      <div class="card center"><div style="font-size:2.5rem">🌟</div><h3>When you doubt yourself</h3><button class="btn secondary" onclick="openLetter(2)">Open letter ✨</button><p id="openLetter2" hidden></p></div>
      <div class="card center"><div style="font-size:2.5rem">🎂</div><h3>On your next birthday</h3><button class="btn secondary" onclick="openLetter(3)">Open letter 🎀</button><p id="openLetter3" hidden></p></div>
    </div>
  </div>
</section>

<section id="quiz">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A tiny challenge</p><h2>The Kyuutu Quiz 🧩</h2><p>Answer some just-for-fun questions.</p></div>
    <div class="card" style="max-width:600px;margin:auto">
      <p id="quizProgress" class="pill">Question 1 of 4</p>
      <h3 id="quizQuestion">What nickname appears on this website?</h3>
      <div id="quizAnswers" class="grid"></div>
      <p id="quizFeedback" class="game-output" aria-live="polite"></p>
      <button id="quizNext" class="btn" onclick="nextQuiz()" disabled>Next question →</button>
      <p id="quizScore" class="center"></p>
    </div>
  </div>
</section>

<section id="garden">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">Flowers just for you</p><h2>Kyuutu's Flower Garden 🌹</h2><p>Tap to grow your own little digital garden.</p></div>
    <div class="card center">
      <div id="flowerGarden" style="font-size:2.5rem;line-height:1.8;min-height:110px">🌱</div>
      <p id="flowerCount">Your garden is waiting for its first flower.</p>
      <button class="btn" onclick="plantFlower()">Plant a flower 🌷</button>
      <button class="btn secondary" onclick="resetGarden()">Start a new garden</button>
    </div>
  </div>
</section>

<section id="messages">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A little message, anytime</p><h2>Message in a Petal 🌸</h2><p>Open a new message whenever you want a little encouragement.</p></div>
    <div class="card center" style="max-width:600px;margin:auto">
      <div style="font-size:3rem">💌</div>
      <p id="petalMessage" style="font-size:1.15rem">Your little message is waiting…</p>
      <button class="btn" onclick="newPetalMessage()">Give me a message ✨</button>
    </div>
  </div>
</section>

<section id="bucketlist">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">More memories to make</p><h2>The Little Bucket List 🎀</h2><p>Tick off the little adventures you'd like to do someday.</p></div>
    <div class="card" style="max-width:650px;margin:auto">
      <label><input class="bucket-item" type="checkbox"> Take a beautiful picture together 📸</label>
      <label><input class="bucket-item" type="checkbox"> Share favourite songs 🎧</label>
      <label><input class="bucket-item" type="checkbox"> Watch the sunset 🌅</label>
      <label><input class="bucket-item" type="checkbox"> Have a long conversation 💬</label>
      <label><input class="bucket-item" type="checkbox"> Try a new food together 🍰</label>
      <label><input class="bucket-item" type="checkbox"> Make a memory scrapbook 📖</label>
      <label><input class="bucket-item" type="checkbox"> Celebrate another birthday 🎂</label>
      <div class="progress" style="margin-top:20px"><div id="bucketProgress"></div></div>
      <p id="bucketCount" class="center">0 of 7 little adventures completed</p>
      <p class="small muted center">Ideas, not obligations. Choose what feels right.</p>
    </div>
  </div>
</section>

<section id="theme">
  <div class="wrap">
    <div class="card center"><p class="eyebrow">Change the atmosphere</p><h2>Pink Day or Dreamy Night? 🌙</h2><p>Switch the mood of your little universe.</p><button class="btn" onclick="toggleDreamTheme()">Switch day / night 🌙</button></div>
  </div>
</section>

<section id="letter">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A few words from my heart</p><h2>Dear Anuska 💌</h2><p>A little letter to read whenever you need a smile.</p></div>
    <div class="card" style="max-width:700px;margin:auto">
      <div class="letter">Dear Kyuutu,

Happy Birthday, Anuska! 🎂💗

Today is a reminder of how wonderful it is to have someone who can make an ordinary day feel a little more special.

I hope this new chapter brings you peaceful mornings, beautiful opportunities, genuine laughter and people who treat your heart with kindness.

Never forget that you deserve to feel appreciated, supported and happy. Keep being yourself, keep dreaming big, and keep finding little reasons to smile.

May your favourite songs sound sweeter, your dreams feel closer, and your days be filled with lovely surprises.

This little website is a collection of moments, music and words, made especially for you. I hope it makes you smile whenever you visit it.

Happy Birthday once again, my Kyuutu. 🎀

With lots of good wishes,
Biraja 💗</div>
      <div class="center" style="margin-top:20px"><button class="btn" onclick="celebrate()">Send a little love 💖</button></div>
    </div>
  </div>
</section>

<section id="wishes">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A sky full of possibilities</p><h2>Wish Upon a Star 🌠</h2><p>Think of something you hope for, then release your wish into the galaxy.</p></div>
    <div class="card center" style="max-width:590px;margin:auto">
      <div style="font-size:3rem">🌌✨🌙</div>
      <textarea id="wishInput" rows="3" placeholder="Write your birthday wish here..."></textarea>
      <button class="btn" onclick="releaseWish()">Release my wish ✨</button>
      <div class="game-output" id="wishOutput"></div>
      <p class="small muted">Your wish stays on this page while it is open. It isn't sent anywhere.</p>
    </div>
  </div>
</section>

<section id="timecapsule">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A note for another day</p><h2>Future You's Time Capsule ⏳</h2><p>Write a little message to your future self.</p></div>
    <div class="card" style="max-width:590px;margin:auto">
      <label for="futureNote"><strong>Dear future Anuska...</strong></label>
      <textarea id="futureNote" rows="4" placeholder="What do you want to remember? What are you dreaming about?"></textarea>
      <button class="btn" onclick="saveNote()">Save my time capsule 💌</button>
      <button class="btn secondary" onclick="loadNote()">Read saved note</button>
      <p id="noteOutput" class="game-output"></p>
      <p class="small muted">Saved in this browser on this device, not automatically shared across devices.</p>
    </div>
  </div>
</section>

<section id="surprise">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">One last little thing</p><h2>The Birthday Surprise 🎂</h2><p>Take a breath, make a wish, and open your final surprise.</p></div>
    <div class="card center" style="max-width:620px;margin:auto">
      <div id="cake" style="font-size:6rem">🎂</div>
      <h3 id="surpriseTitle">Ready for your surprise, Kyuutu?</h3>
      <p id="surpriseText">This little universe was made to celebrate you and the happiness you deserve.</p>
      <button class="btn" onclick="finalSurprise()">Open the surprise ✨</button>
      <div id="finalMessage" class="game-output"></div>
    </div>
  </div>
</section>

<section id="bonus">
  <div class="wrap">
    <div class="section-head"><p class="eyebrow">A bonus celebration</p><h2>Make the Sky Sparkle 🎊</h2><p>One more little celebration, just because.</p></div>
    <div class="card center">
      <div style="font-size:4rem">🎉🎀🎂</div>
      <h3>Three cheers for Anuska!</h3>
      <button class="btn" onclick="bonusCelebration()">Celebrate again! 💖</button>
      <p id="bonusOutput" class="game-output"></p>
    </div>
  </div>
</section>

<section id="last">
  <div class="wrap center">
    <div style="font-size:3rem">🌷💗🎀</div>
    <h2>End of the page, not the good wishes.</h2>
    <p class="muted">Whenever you return, may this little corner bring back a happy thought.</p>
    <button class="btn secondary" onclick="window.scrollTo({top:0,behavior:'smooth'})">Back to the beginning ↑</button>
  </div>
</section>

<footer>
  <p>Made with 💗 by Biraja, especially for Anuska.</p>
  <p class="small">Kyuutuverse © 2026 · A tiny universe of memories ✨</p>
</footer>

<div id="toast" role="status" aria-live="polite"></div>

<script>
/* BIRTHDAY COUNTDOWN: 5 October 2026 at midnight IST */
const birthday=new Date("2026-10-05T00:00:00+05:30").getTime();

function updateCountdown(){
  const distance=birthday-Date.now();
  const message=document.getElementById("countdownMessage");
  if(distance<=0){
    ["days","hours","minutes","seconds"].forEach(id=>document.getElementById(id).textContent="00");
    message.textContent="It's your birthday, Anuska! Happy Birthday, Kyuutu! 🎂💗";
    return;
  }
  document.getElementById("days").textContent=Math.floor(distance/86400000);
  document.getElementById("hours").textContent=String(Math.floor(distance%86400000/3600000)).padStart(2,"0");
  document.getElementById("minutes").textContent=String(Math.floor(distance%3600000/60000)).padStart(2,"0");
  document.getElementById("seconds").textContent=String(Math.floor(distance%60000/1000)).padStart(2,"0");
}
updateCountdown();
setInterval(updateCountdown,1000);

/* FLOATING DECORATIONS */
const floatEmojis=["♡","💗","✦","🌷","✨","🎀"];
for(let i=0;i<18;i++){
  const el=document.createElement("span");
  el.className="float";el.textContent=floatEmojis[i%floatEmojis.length];
  el.style.left=Math.random()*100+"%";el.style.bottom="-50px";
  el.style.fontSize=(15+Math.random()*20)+"px";
  el.style.animationDelay=Math.random()*9+"s";
  el.style.animationDuration=(7+Math.random()*7)+"s";
  document.body.appendChild(el);
}

/* SONG PLAYER */
const song=document.getElementById("ourSong");
const equalizer=document.getElementById("equalizer");
song.addEventListener("play",()=>equalizer.classList.add("playing"));
song.addEventListener("pause",()=>equalizer.classList.remove("playing"));
song.addEventListener("ended",()=>equalizer.classList.remove("playing"));

/* TOAST */
let toastTimer;
function showToast(message){
  const toast=document.getElementById("toast");
  toast.textContent=message;toast.classList.add("show");
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>toast.classList.remove("show"),3000);
}

/* HEART GAME */
let hearts=0;
function collectHeart(){
  if(hearts>=5)return;
  hearts++;
  document.getElementById("heartCount").textContent="Hearts collected: "+hearts+" / 5";
  document.getElementById("heartProgress").style.width=hearts*20+"%";
  if(hearts===5){
    document.getElementById("heartOutput").textContent="You collected all five! A pocketful of happiness for you 💗";
    document.getElementById("heartButton").textContent="All hearts collected 💖";
    showToast("Mission complete, Kyuutu! 💗");
  }else{
    document.getElementById("heartOutput").textContent=["A little heart for you!","Another one, just because!","You're doing great!","Almost there!"][hearts-1];
  }
}

/* NICKNAME GAME */
function checkNickname(){
  const value=document.getElementById("nicknameInput").value.trim().toLowerCase();
  const output=document.getElementById("nicknameOutput");
  if(value==="kyuutu"||value==="kyu u tu"||value==="kyuutu 💗"){
    output.textContent="Correct! Kyuutu is the star of this universe! 🎀";
    celebrate();
  }else output.textContent="Hint: It starts with K and is extra cute. Try again! 💗";
}

/* MYSTERY GIFTS */
const gifts=[
  "🎀 Your gift: a reminder that you deserve kindness and happiness.",
  "🌷 Your gift: may this year bring new memories and beautiful surprises.",
  "💖 Your gift: a little pocket of courage for every dream you chase."
];
const openedGifts=new Set();
function openGift(index){
  document.getElementById("giftOutput").textContent=gifts[index];
  if(!openedGifts.has(index)){openedGifts.add(index);showToast("A little gift opened just for you 🎁");}
}

/* COMPLIMENT */
const compliments=[
  "Your smile can brighten an ordinary day. 🌷",
  "You deserve people who listen and care. 💗",
  "Your dreams are worth making time for. ✨",
  "You don't need to be perfect to be wonderful. 🎀",
  "May you always find reasons to laugh. 🌸",
  "You are allowed to grow at your own pace. 🌱",
  "The world has room for your own kind of magic. 🌙"
];
let lastCompliment=-1;
function compliment(){
  let n;
  do{n=Math.floor(Math.random()*compliments.length)}while(n===lastCompliment);
  lastCompliment=n;
  document.getElementById("complimentOutput").textContent=compliments[n];
}

/* WISH GALAXY */
function releaseWish(){
  const input=document.getElementById("wishInput");
  const output=document.getElementById("wishOutput");
  if(!input.value.trim()){output.textContent="Write a little wish first. 🌠";return;}
  output.textContent="✨ Wish released into your imaginary galaxy. May you keep working towards it! 🌠";
  input.value="";celebrate();
}

/* TIME CAPSULE */
function saveNote(){
  const note=document.getElementById("futureNote").value.trim();
  const output=document.getElementById("noteOutput");
  if(!note){output.textContent="Write a little note before saving it. 💌";return;}
  try{
    localStorage.setItem("kyuutuFutureNote",note);
    output.textContent="Your note has been saved in this browser on this device. 💗";
  }catch(e){output.textContent="Browser storage isn't available. Keep a copy somewhere safe.";}
}
function loadNote(){
  const output=document.getElementById("noteOutput");
  try{
    const note=localStorage.getItem("kyuutuFutureNote");
    if(note){document.getElementById("futureNote").value=note;output.textContent="Your saved note is back. 💌";}
    else output.textContent="No saved note found in this browser yet.";
  }catch(e){output.textContent="Browser storage isn't available right now.";}
}

/* CONFETTI */
function celebrate(){
  const box=document.getElementById("confetti");
  const colors=["💗","🌸","🎀","✨","💕","🌷"];
  for(let i=0;i<38;i++){
    const piece=document.createElement("span");
    piece.className="confetti-piece";
    piece.textContent=colors[Math.floor(Math.random()*colors.length)];
    piece.style.left=Math.random()*100+"%";
    piece.style.fontSize=(12+Math.random()*18)+"px";
    piece.style.animationDelay=Math.random()*1.4+"s";
    box.appendChild(piece);
    setTimeout(()=>piece.remove(),5000);
  }
}

/* FINAL BIRTHDAY SURPRISE */
let finalOpened=false;
function finalSurprise(){
  const message=document.getElementById("finalMessage");
  if(!finalOpened){
    finalOpened=true;
    document.getElementById("cake").textContent="🎂🎉💗";
    document.getElementById("surpriseTitle").textContent="Happy Birthday, Anuska! 🌷";
    document.getElementById("surpriseText").textContent="May this new chapter bring laughter, growth, kindness, peaceful moments and wonderful memories.";
    message.textContent="Surprise unlocked! You deserve all the happiness in the world, Kyuutu. 💖 — Biraja";
  }else message.textContent="One more birthday hug in emoji form: 🫂💗🎀";
  celebrate();
}

/* OPEN-WHEN LETTERS */
const openWhenMessages=[
  "Hey Kyuutu 💗 Take a breath and remember that you deserve laughter, kindness and beautiful days. I hope something makes you smile today. 🌷",
  "Not every day has to be perfect. Take things one step at a time, be kind to yourself, and remember that difficult moments do not define your whole story. 🌈",
  "You have your own strengths, dreams and pace. You do not need to compare your journey with anyone else's. Keep learning and believe in what you can build. ✨",
  "Happy birthday again, Anuska! 🎂 I hope another year brings new experiences, peaceful days, laughter and countless reasons to be proud of yourself. 💗"
];
function openLetter(index){
  const el=document.getElementById("openLetter"+index);
  el.hidden=!el.hidden;
  el.textContent=openWhenMessages[index];
}

/* BIRTHDAY QUIZ */
const quizData=[
  {q:"What nickname appears throughout this website?",a:["Kyuutu","Sunshine","Princess","Moon"],correct:0},
  {q:"Which date is the birthday countdown set for?",a:["1 January","5 October","13 January","25 December"],correct:1},
  {q:"Which song is featured on the website?",a:["Perfect","Tera Naam Doon","Kesariya","Heeriye"],correct:1},
  {q:"What is the main idea behind Kyuutuverse?",a:["Shopping page","News page","Birthday universe","School timetable"],correct:2}
];
let quizIndex=0,quizPoints=0,quizAnswered=false;
function renderQuiz(){
  const item=quizData[quizIndex];
  document.getElementById("quizProgress").textContent="Question "+(quizIndex+1)+" of "+quizData.length;
  document.getElementById("quizQuestion").textContent=item.q;
  document.getElementById("quizFeedback").textContent="";
  document.getElementById("quizNext").disabled=true;
  document.getElementById("quizNext").textContent=quizIndex===quizData.length-1?"See my result ✨":"Next question →";
  document.getElementById("quizScore").textContent="";
  quizAnswered=false;
  const answers=document.getElementById("quizAnswers");
  answers.innerHTML="";
  item.a.forEach((answer,index)=>{
    const button=document.createElement("button");
    button.className="btn secondary";button.textContent=answer;
    button.onclick=()=>answerQuiz(index);
    answers.appendChild(button);
  });
}
function answerQuiz(index){
  if(quizAnswered)return;
  quizAnswered=true;
  const item=quizData[quizIndex];
  document.querySelectorAll("#quizAnswers button").forEach(button=>button.disabled=true);
  if(index===item.correct){
    quizPoints++;
    document.getElementById("quizFeedback").textContent="Correct! You're a Kyuutuverse expert! 💗";
  }else{
    document.getElementById("quizFeedback").textContent="Nice try! The answer is "+item.a[item.correct]+". 🌷";
  }
  document.getElementById("quizNext").disabled=false;
}
function nextQuiz(){
  if(!quizAnswered)return;
  if(quizIndex<quizData.length-1){quizIndex++;renderQuiz();}
  else{
    document.getElementById("quizQuestion").textContent="Quiz completed! 🎉";
    document.getElementById("quizAnswers").innerHTML="";
    document.getElementById("quizFeedback").textContent="You scored "+quizPoints+" out of "+quizData.length+".";
    document.getElementById("quizScore").textContent=quizPoints===quizData.length?"Perfect score! 💖":"Thanks for playing, Kyuutu! 🌸";
    document.getElementById("quizNext").disabled=true;
    document.getElementById("quizNext").textContent="Quiz finished";
  }
}
renderQuiz();

/* FLOWER GARDEN */
const flowers=["🌷","🌸","🌹","🌼","🌻","💐","🪻"];
let flowerTotal=0;
function plantFlower(){
  const span=document.createElement("span");
  span.textContent=flowers[flowerTotal%flowers.length]+" ";
  document.getElementById("flowerGarden").appendChild(span);
  flowerTotal++;
  document.getElementById("flowerCount").textContent=flowerTotal+(flowerTotal===1?" flower planted! Your garden has begun. 🌱":" flowers planted! Look at your little garden! 💗");
}
function resetGarden(){
  flowerTotal=0;
  document.getElementById("flowerGarden").textContent="🌱";
  document.getElementById("flowerCount").textContent="Your garden is waiting for its first flower.";
}

/* RANDOM PETAL MESSAGE */
const petalMessages=[
  "You deserve a day filled with little reasons to smile. 🌸",
  "One small step is still progress. Keep going. 🌱",
  "May your favourite song find you at the perfect moment. 🎧",
  "Your dreams deserve patience, effort and hope. ✨",
  "Take a breath and be kind to yourself. 💗",
  "May today bring a surprise that makes you laugh. 🎀",
  "You can start fresh whenever you need to. 🌷",
  "Never underestimate the magic of an ordinary happy moment. 🌈",
  "Your birthday is one more chapter waiting to be written. 📖"
];
let lastPetalIndex=-1;
function newPetalMessage(){
  let index;
  do{index=Math.floor(Math.random()*petalMessages.length)}while(index===lastPetalIndex);
  lastPetalIndex=index;
  document.getElementById("petalMessage").textContent=petalMessages[index];
}

/* BUCKET LIST */
const bucketItems=document.querySelectorAll(".bucket-item");
function updateBucketProgress(){
  const completed=[...bucketItems].filter(item=>item.checked).length;
  document.getElementById("bucketProgress").style.width=(completed/bucketItems.length*100)+"%";
  document.getElementById("bucketCount").textContent=completed+" of "+bucketItems.length+" little adventures completed";
}
bucketItems.forEach(item=>item.addEventListener("change",updateBucketProgress));
updateBucketProgress();

/* DAY/NIGHT THEME */
let dreamNight=false;
function toggleDreamTheme(){
  dreamNight=!dreamNight;
  document.body.classList.toggle("night-mode",dreamNight);
  showToast(dreamNight?"Dreamy night mode activated 🌙":"Pink day mode is back 🌷");
}

/* BONUS CELEBRATION */
function bonusCelebration(){
  const messages=[
    "May your year be full of little adventures! 🎀",
    "Sending a sky full of imaginary stars your way! 🌠",
    "Here's to more laughter and beautiful memories! 🌷",
    "May you keep discovering new things to love about life! 💗"
  ];
  document.getElementById("bonusOutput").textContent=messages[Math.floor(Math.random()*messages.length)];
  celebrate();
}

/* PHOTO LIGHTBOX */
document.querySelectorAll(".photo").forEach(img=>{
  img.style.cursor="zoom-in";
  img.addEventListener("click",()=>{
    if(img.complete&&img.naturalWidth>0){
      const win=window.open();
      if(win){
        const image=win.document.createElement("img");
        image.src=img.src;
        image.alt=img.alt;
        image.style.cssText="max-width:100%;max-height:100vh;object-fit:contain";
        win.document.body.style.cssText="margin:0;background:#170e19;display:grid;place-items:center;min-height:100vh";
        win.document.body.appendChild(image);
        win.document.title="Memory 💗";
      }else showToast("Your browser blocked the new tab. Allow pop-ups to view the picture.");
    }else showToast("Check that the photo is uploaded with the exact filename.");
  });
});

/* MISSING MEDIA HINTS */
document.querySelectorAll("img").forEach(img=>{
  img.addEventListener("error",()=>{
    if(img.dataset.errorShown)return;
    img.dataset.errorShown="true";
    img.style.display="none";
    const hint=document.createElement("p");
    hint.className="muted small center";
    hint.textContent="Photo not found — check its filename and letter case in your repository.";
    img.parentElement.appendChild(hint);
  });
});
document.querySelectorAll("video").forEach(video=>{
  video.addEventListener("error",()=>showToast("A video could not load. Check its filename and upload status."));
});
</script>

<style>
/* NIGHT MODE */
body.night-mode{
  color:#fff0fa;
  background:radial-gradient(circle at 20% 10%,#45365e,transparent 40%),linear-gradient(145deg,#19152c,#30213e);
}
body.night-mode nav{background:#21182df0;border-color:#49344f}
body.night-mode nav a,body.night-mode .portal,body.night-mode .card,
body.night-mode .timebox,body.night-mode .gift{
  background:#382b48;color:#fff0fa;border-color:#614767;
}
body.night-mode .letter{background:#493448;color:#fff0fa;border-color:#614767}
body.night-mode input:not([type=checkbox]),body.night-mode textarea{background:#382b48;color:#fff0fa;border-color:#614767}
body.night-mode .muted,body.night-mode .section-head p{color:#d4bad1}
body.night-mode footer{color:#d4bad1}
</style>
</body>
</html>
