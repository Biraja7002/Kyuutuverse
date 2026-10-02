
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f6">
<meta name="description" content="A little birthday universe made with love for Anuska, my Kyuutu.">
<title>Kyuutuverse ♡ | Anuska's Birthday</title>

<style>
:root {
  --pink:#ff6fae;
  --pink2:#ffc4dc;
  --purple:#a78bfa;
  --cream:#fff8fb;
  --ink:#513047;
  --muted:#936d83;
  --glass:rgba(255,255,255,.82);
}
* { box-sizing:border-box; }
html { scroll-behavior:smooth; scroll-padding-top:75px; }
body {
  margin:0;
  font-family:"Trebuchet MS",Arial,sans-serif;
  color:var(--ink);
  background:
    radial-gradient(circle at 10% 5%,#ffe0ee 0,transparent 28%),
    radial-gradient(circle at 95% 25%,#e9ddff 0,transparent 28%),
    linear-gradient(145deg,#fff8fb,#fff0f6 45%,#f6efff);
  overflow-x:hidden;
}
button,input,textarea { font:inherit; }
button { cursor:pointer; }
img,video { max-width:100%; }
section { padding:65px 18px; position:relative; }
.wrap { width:min(100%,1000px); margin:auto; }
.center { text-align:center; }
.eyebrow {
  text-transform:uppercase; letter-spacing:3px;
  color:#d45b98; font-size:.76rem; font-weight:bold;
}
h1,h2,h3 { line-height:1.2; }
h2 { font-size:clamp(1.8rem,6vw,2.8rem); margin:10px 0 14px; }
p { line-height:1.8; }
.muted { color:var(--muted); }
.small { font-size:.87rem; }
.card {
  background:var(--glass);
  border:1px solid rgba(255,255,255,.94);
  border-radius:24px;
  padding:22px;
  box-shadow:0 12px 38px rgba(184,92,139,.12);
  backdrop-filter:blur(12px);
}
.btn {
  display:inline-block;
  border:0; border-radius:999px; padding:13px 21px;
  margin:4px;
  background:linear-gradient(120deg,#ff75b5,#c5a0ff);
  color:white; font-weight:bold;
  box-shadow:0 7px 20px #ec8cbb40;
  transition:.2s;
}
.btn:hover { transform:translateY(-2px); }
.btn.secondary {
  color:#a4497a; background:white;
  border:1px solid #f4c5dc; box-shadow:none;
}
.pill {
  display:inline-block; padding:7px 12px; border-radius:30px;
  background:#ffe2ef; color:#a54c7b; font-size:.8rem;
}
.grid { display:grid; gap:17px; }
.two { grid-template-columns:repeat(2,minmax(0,1fr)); }
.three { grid-template-columns:repeat(3,minmax(0,1fr)); }
nav {
  position:sticky; top:0; z-index:30;
  display:flex; gap:9px; align-items:center;
  padding:11px 13px; overflow-x:auto; white-space:nowrap;
  background:#fff8f2ed;
  border-bottom:1px solid #f7dce9;
  backdrop-filter:blur(16px);
}
nav .brand { font-weight:bold; color:#c64d8b; margin-right:8px; }
nav a {
  text-decoration:none; font-size:.8rem; padding:8px 10px;
  border-radius:30px; background:#fff; border:1px solid #f6dce8;
}
nav a:hover { background:#ffe2ef; }
.hero {
  min-height:88vh; display:flex; align-items:center;
  justify-content:center; padding:55px 18px 70px;
  position:relative; overflow:hidden;
}
.hero-inner { width:min(100%,800px); text-align:center; position:relative; z-index:2; }
.hero h1 {
  font-size:clamp(3rem,13vw,6.4rem);
  letter-spacing:-3px; margin:18px 0 10px;
  background:linear-gradient(100deg,#f05b9f,#ad80f2,#f05b9f);
  color:transparent; background-clip:text;
}
.hero p { max-width:620px; margin:12px auto 24px; }
.hero-heart { font-size:3rem; animation:heartbeat 1.5s infinite; display:inline-block; }
@keyframes heartbeat { 50% { transform:scale(1.15); } }
.countdown {
  display:flex; justify-content:center; gap:10px;
  flex-wrap:wrap; margin:24px 0;
}
.timebox {
  min-width:72px; padding:15px 11px;
  background:#ffffffd9; border:1px solid #f5c9df;
  border-radius:18px; box-shadow:0 7px 20px #e9a5c522;
}
.timebox strong { display:block; font-size:1.65rem; color:#c94d91; }
.timebox span { font-size:.72rem; color:var(--muted); }
.section-head { text-align:center; margin:0 auto 28px; max-width:700px; }
.section-head p { color:var(--muted); }
.photo {
  width:100%; height:290px; object-fit:cover;
  border-radius:18px; background:#f8dfea;
  display:block;
}
.photo-card { padding:12px; }
.photo-card:nth-child(odd) { transform:rotate(-.5deg); }
.photo-card:nth-child(even) { transform:rotate(.5deg); }
.photo-card p { margin:10px 4px 2px; text-align:center; }
.memory-number { color:#cf5997; font-size:.78rem; }
.media {
  display:block; width:100%; border-radius:17px;
  background:#f4d8e7; max-height:460px;
}
audio { width:100%; margin:12px 0; }
.song-cover {
  font-size:4rem; width:115px; height:115px;
  margin:0 auto 16px; border-radius:50%;
  display:grid; place-items:center;
  background:linear-gradient(140deg,#ffd2e7,#d9c8ff);
  box-shadow:0 0 0 10px #fff7fb,0 0 0 12px #f6d6e7;
}
.equalizer { display:flex; justify-content:center; gap:5px; height:30px; align-items:center; }
.equalizer span { width:5px; height:9px; border-radius:8px; background:#dc75ac; }
.equalizer.playing span { animation:bars .65s ease-in-out infinite alternate; }
.equalizer span:nth-child(2) { animation-delay:.1s; }
.equalizer span:nth-child(3) { animation-delay:.2s; }
.equalizer span:nth-child(4) { animation-delay:.3s; }
.equalizer span:nth-child(5) { animation-delay:.4s; }
@keyframes bars { to { height:28px; } }
.portal {
  display:block; padding:20px; border-radius:20px;
  text-decoration:none; background:#fff9fd;
  border:1px solid #f4d9e8; transition:.2s;
}
.portal:hover { transform:translateY(-4px); background:white; }
.portal .emoji { font-size:2rem; }
.portal strong { display:block; margin:9px 0; }
.letter {
  font-family:Georgia,serif; line-height:2;
  white-space:pre-line; background:#fffaf4;
  border:1px solid #f6dfd0; padding:23px;
  border-radius:15px; transform:rotate(-.3deg);
}
.game-output { min-height:35px; color:#b34581; font-weight:bold; margin-top:12px; }
.gift {
  font-size:3.2rem; border:0; border-radius:20px;
  padding:25px 8px; background:#fff5fb;
  border:1px solid #f3d4e6; width:100%;
}
.gift:hover { transform:scale(1.03); }
.progress { height:8px; background:#f5d8e7; border-radius:20px; overflow:hidden; }
.progress div { height:100%; width:0; background:linear-gradient(90deg,#ff6fae,#ac88f5); transition:.3s; }
textarea,input {
  width:100%; border:1px solid #efcbdc; background:#fffafd;
  border-radius:14px; padding:13px; color:var(--ink);
  outline-color:#f18bbd; margin:7px 0 12px;
}
details summary { cursor:pointer; font-weight:bold; padding:12px 0; }
details { margin-top:12px; }
.timeline { border-left:3px solid #f4b4d4; padding-left:22px; margin:20px 0; }
.timeline-item { position:relative; margin:22px 0; }
.timeline-item:before {
  content:"💗"; position:absolute; left:-36px; top:0;
  background:#fff0f6; border-radius:50%;
}
.flower-garden { display:flex; flex-wrap:wrap; justify-content:center; gap:10px; font-size:2rem; min-height:65px; }
.flower { animation:flowerPop .5s ease-out; }
@keyframes flowerPop { from { transform:scale(0); } to { transform:scale(1); } }
footer { padding:38px 18px 65px; text-align:center; color:#9b6c87; }

/* FLOATING HEARTS AND DECORATIONS ACROSS THE WHOLE WEBSITE */
#floating-love {
  position:fixed;
  inset:0;
  overflow:hidden;
  pointer-events:none;
  z-index:25;
  contain:strict;
}
.love-particle {
  position:absolute;
  bottom:-55px;
  left:var(--left);
  font-size:var(--size);
  opacity:0;
  animation:loveFloat var(--duration) linear var(--delay) infinite;
  filter:drop-shadow(0 2px 5px #ff78b455);
  will-change:transform,opacity;
}
@keyframes loveFloat {
  0% { transform:translate3d(0,0,0) rotate(0deg) scale(.7); opacity:0; }
  10% { opacity:.8; }
  50% { transform:translate3d(var(--drift),-55vh,0) rotate(25deg) scale(1); opacity:.9; }
  90% { opacity:.7; }
  100% { transform:translate3d(calc(var(--drift) * -.5),-115vh,0) rotate(-30deg) scale(.8); opacity:0; }
}
.love-sparkle {
  position:absolute;
  left:var(--left);
  top:var(--top);
  color:#ff80bd;
  font-size:var(--size);
  animation:sparkleGlow var(--duration) ease-in-out var(--delay) infinite alternate;
}
@keyframes sparkleGlow {
  from { opacity:.2; transform:scale(.7) rotate(0deg); }
  to { opacity:.95; transform:scale(1.25) rotate(35deg); }
}

/* CONFETTI */
#confetti { position:fixed; inset:0; pointer-events:none; z-index:60; overflow:hidden; }
.confetti-piece { position:absolute; top:-15px; animation:fall 3.5s linear forwards; }
@keyframes fall { to { transform:translateY(110vh) rotate(800deg); opacity:.2; } }
#toast {
  position:fixed; left:50%; bottom:25px; z-index:70;
  transform:translate(-50%,25px); opacity:0; pointer-events:none;
  padding:13px 20px; border-radius:30px;
  color:#fff; background:#a54c7b; transition:.25s;
  max-width:90%; text-align:center;
}
#toast.show { opacity:1; transform:translate(-50%,0); }

@media(max-width:620px) {
  .two,.three { grid-template-columns:1fr; }
  section { padding:50px 15px; }
  .hero { min-height:84vh; }
  .photo { height:320px; }
  .card { padding:18px; }
  .timebox { min-width:65px; }
}
@media(prefers-reduced-motion:reduce) {
  html { scroll-behavior:auto; }
  .love-particle,.love-sparkle { animation-duration:30s; }
}
</style>
</head>

<body>
<div id="floating-love" aria-hidden="true"></div>
<div id="confetti" aria-hidden="true"></div>

<nav>
  <span class="brand">♡ Kyuutuverse</span>
  <a href="#home">Home</a>
  <a href="#universe">Explore</a>
  <a href="#memories">Memories</a>
  <a href="#song">Song</a>
  <a href="#videos">Videos</a>
  <a href="#games">Games</a>
  <a href="#timeline">Story</a>
  <a href="#letter">Letter</a>
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
    <p>
      Welcome to your own little corner of the internet, Kyuutu.
      Filled with memories, music, silly games, warm wishes and
      all the little things that remind me of you. 🎀✨
    </p>

    <div class="countdown" id="countdown">
      <div class="timebox"><strong id="days">--</strong><span>DAYS</span></div>
      <div class="timebox"><strong id="hours">--</strong><span>HOURS</span></div>
      <div class="timebox"><strong id="minutes">--</strong><span>MINUTES</span></div>
      <div class="timebox"><strong id="seconds">--</strong><span>SECONDS</span></div>
    </div>
    <p id="countdownMessage" class="muted small">Counting down to your special day 💕</p>

    <a class="btn" href="#universe">Enter your universe ✨</a>
    <button class="btn secondary" onclick="showToast('A little reminder: you deserve happiness, Kyuutu 💗')">A little reminder 💌</button>
  </div>
</header>

<section id="universe">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Choose your adventure</p>
      <h2>Your Little Universe 🌷</h2>
      <p>Every corner holds a different little surprise. Explore wherever your heart takes you.</p>
    </div>
    <div class="grid three">
      <a class="portal" href="#memories"><span class="emoji">📸</span><strong>Our Memory Lane</strong><span class="muted small">Little moments, forever saved.</span></a>
      <a class="portal" href="#song"><span class="emoji">🎧</span><strong>Our Song</strong><span class="muted small">Press play and stay a while.</span></a>
      <a class="portal" href="#videos"><span class="emoji">🎬</span><strong>Mini Cinema</strong><span class="muted small">Three little video moments.</span></a>
      <a class="portal" href="#games"><span class="emoji">🎮</span><strong>Kyuutu Games</strong><span class="muted small">Tiny challenges and cute rewards.</span></a>
      <a class="portal" href="#timeline"><span class="emoji">💗</span><strong>Our Story</strong><span class="muted small">Little chapters of memories.</span></a>
      <a class="portal" href="#openwhen"><span class="emoji">💌</span><strong>Open When...</strong><span class="muted small">Letters for different days.</span></a>
      <a class="portal" href="#quiz"><span class="emoji">🧩</span><strong>Birthday Quiz</strong><span class="muted small">A tiny challenge.</span></a>
      <a class="portal" href="#garden"><span class="emoji">🌸</span><strong>Flower Garden</strong><span class="muted small">Plant a digital flower.</span></a>
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
    <p class="center muted small">Tap a picture to view it larger. 📷</p>
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
      <div class="equalizer" id="equalizer">
        <span></span><span></span><span></span><span></span><span></span>
      </div>
      <audio id="ourSong" controls preload="metadata">
        <source src="tera naam doon.mp3" type="audio/mpeg">
        Your browser does not support audio playback.
      </audio>
      <p class="small muted">Press play to listen to your birthday soundtrack.</p>
      <button class="btn secondary" onclick="showToast('Imagine a little pink sky and your favourite song 💕')">Song dedication 💌</button>
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
      <div class="card">
        <span class="pill">VIDEO 01</span>
        <h3>Memory in Motion 🌸</h3>
        <video class="media" controls preload="metadata" playsinline>
          <source src="VIDEO1.mp4" type="video/mp4">
          Your browser does not support video.
        </video>
      </div>
      <div class="card">
        <span class="pill">VIDEO 02</span>
        <h3>Cutiepie 🎀</h3>
        <video class="media" controls preload="metadata" playsinline>
          <source src="VIDEO2.mp4" type="video/mp4">
          Your browser does not support video.
        </video>
      </div>
      <div class="card">
        <span class="pill">VIDEO 03</span>
        <h3>Happy Birthday 💗</h3>
        <video class="media" controls preload="metadata" playsinline>
          <source src="VIDEO3.mp4" type="video/mp4">
          Your browser does not support video.
        </video>
      </div>
    </div>
  </div>
</section>

<section id="games">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Play a little</p>
      <h2>Kyuutu's Fun Corner 🎮</h2>
      <p>Little games made to bring a smile to your face.</p>
    </div>
    <div class="grid two">
      <div class="card center">
        <h3>1. Catch the Hearts 💗</h3>
        <p>Tap the button to collect five hearts.</p>
        <div class="progress"><div id="heartProgress"></div></div>
        <p id="heartCount">Hearts collected: 0 / 5</p>
        <button class="btn" id="heartButton" onclick="collectHeart()">Collect a heart 💗</button>
        <div class="game-output" id="heartOutput"></div>
      </div>

      <div class="card center">
        <h3>2. Guess the Nickname 🎀</h3>
        <p>What cute nickname is used on this website?</p>
        <input id="nicknameInput" placeholder="Type your answer..." autocomplete="off">
        <button class="btn" onclick="checkNickname()">Check answer</button>
        <div class="game-output" id="nicknameOutput"></div>
      </div>

      <div class="card center">
        <h3>3. Pick a Mystery Gift 🎁</h3>
        <p>Choose a box to reveal a little message.</p>
        <div class="grid three">
          <button class="gift" onclick="openGift(0)" aria-label="Gift one">🎁</button>
          <button class="gift" onclick="openGift(1)" aria-label="Gift two">🎀</button>
          <button class="gift" onclick="openGift(2)" aria-label="Gift three">💝</button>
        </div>
        <div class="game-output" id="giftOutput"></div>
      </div>

      <div class="card center">
        <h3>4. Daily Compliment 🌷</h3>
        <p>Tap for a small reminder of how special you are.</p>
        <div style="font-size:2.6rem">🌸</div>
        <button class="btn" onclick="compliment()">Give me a compliment</button>
        <div class="game-output" id="complimentOutput"></div>
      </div>
    </div>
  </div>
</section>

<section id="timeline">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Every memory has a chapter</p>
      <h2>Our Story in Little Chapters 📖</h2>
      <p>A tiny timeline for the moments, conversations and memories that make a story special.</p>
    </div>
    <div class="card">
      <div class="timeline">
        <div class="timeline-item">
          <h3>The Beginning 🌷</h3>
          <p>Every story begins somewhere. Sometimes, the smallest moments become the ones we remember.</p>
        </div>
        <div class="timeline-item">
          <h3>The Conversations 💬</h3>
          <p>Random talks, silly jokes, shared thoughts and little moments that make an ordinary day brighter.</p>
        </div>
        <div class="timeline-item">
          <h3>Today and Beyond ✨</h3>
          <p>More memories, more laughter, more things to learn and many new chapters still waiting to be written.</p>
        </div>
      </div>
      <p class="center muted small">You can edit these chapters to include your real memories together.</p>
    </div>
  </div>
</section>

<section id="openwhen">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Little letters for different days</p>
      <h2>Open When... 💌</h2>
      <p>Choose a letter for the moment you're having.</p>
    </div>
    <div class="card">
      <details>
        <summary>💗 Open when you need a smile</summary>
        <p>Hey Kyuutu, take a little pause and remember that not every day has to be perfect. There can still be one small thing worth smiling about. I hope this message brings you one. 🌷</p>
      </details>
      <details>
        <summary>🌧️ Open on a difficult day</summary>
        <p>You don't have to figure everything out at once. Take things one step at a time, give yourself room to breathe, and remember that asking someone you trust for support is always okay. You deserve kindness, especially from yourself. 💗</p>
      </details>
      <details>
        <summary>🌟 Open when you doubt yourself</summary>
        <p>You are still learning, growing and discovering what you can do. One difficult moment does not define your whole story. Keep going at your own pace and give yourself credit for every small step. 🌱</p>
      </details>
      <details>
        <summary>🎂 Open on your next birthday</summary>
        <p>Happy Birthday again, Anuska! I hope you can look back at this year and notice how much you have learned, how many moments made you laugh, and how many possibilities are still ahead of you. 🎀</p>
      </details>
    </div>
  </div>
</section>

<section id="quiz">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A tiny challenge</p>
      <h2>The Kyuutu Quiz 🧩</h2>
      <p>Answer these little questions to unlock a cute message.</p>
    </div>
    <div class="card" style="max-width:650px;margin:auto">
      <h3>Question 1 of 3</h3>
      <p>What nickname appears on this website?</p>
      <div class="grid">
        <button class="btn secondary" onclick="answerQuiz(this,false)">Sunshine ☀️</button>
        <button class="btn secondary" onclick="answerQuiz(this,true)">Kyuutu 🎀</button>
        <button class="btn secondary" onclick="answerQuiz(this,false)">Moon 🌙</button>
      </div>
      <p id="quizOutput" class="game-output"></p>
      <button class="btn" onclick="nextQuiz()">Next question →</button>
    </div>
  </div>
</section>

<section id="garden">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A little garden just for you</p>
      <h2>Flower Garden 🌷</h2>
      <p>Plant a digital flower every time you want to add a little colour to the garden.</p>
    </div>
    <div class="card center">
      <div class="flower-garden" id="flowerGarden" aria-live="polite">
        <span>🌱</span><span>🌷</span><span>🌼</span>
      </div>
      <p id="gardenOutput" class="game-output">Your garden is waiting for its first flower.</p>
      <button class="btn" onclick="plantFlower()">Plant a flower 🌸</button>
      <button class="btn secondary" onclick="waterGarden()">Water the garden 💧</button>
    </div>
  </div>
</section>

<section id="messagepetal">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A message hidden in a flower</p>
      <h2>Message in a Petal 🌸</h2>
      <p>Tap the flower to discover a tiny message.</p>
    </div>
    <div class="card center">
      <button class="gift" style="max-width:180px" onclick="petalMessage()" aria-label="Reveal a petal message">🌺</button>
      <div class="game-output" id="petalOutput">Your little message is waiting...</div>
    </div>
  </div>
</section>

<section id="bucketlist">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Little adventures ahead</p>
      <h2>The Little Bucket List ✨</h2>
      <p>Check off the things you want to do in your new year.</p>
    </div>
    <div class="card">
      <label><input type="checkbox" class="bucket" style="width:auto"> Take a picture together 📸</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Share favourite songs 🎧</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Watch the sunset 🌅</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Have a long conversation 💬</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Try a new food 🍰</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Make a memory scrapbook 📖</label><br>
      <label><input type="checkbox" class="bucket" style="width:auto"> Celebrate another birthday 🎂</label>
      <p id="bucketProgress" class="game-output">0 / 7 adventures checked</p>
      <div class="progress"><div id="bucketBar"></div></div>
    </div>
  </div>
</section>

<section id="songnote">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Music and memories</p>
      <h2>Song Dedication 🎶</h2>
      <p>A little place for the songs that remind you of a special moment.</p>
    </div>
    <div class="grid two">
      <div class="card center">
        <div style="font-size:3rem">🎧</div>
        <h3>Tera Naam Doon</h3>
        <p>Our featured soundtrack. Play it while exploring the rest of the page.</p>
        <a class="btn secondary" href="#song">Go to the song player ↑</a>
      </div>
      <div class="card center">
        <div style="font-size:3rem">🎼</div>
        <h3>A song for every mood</h3>
        <p>Happy songs, calm songs, favourite songs and the ones that bring back memories.</p>
        <button class="btn" onclick="showToast('May every song bring a lovely memory 🎵')">Play a little imagination 💗</button>
      </div>
    </div>
  </div>
</section>

<section id="letter">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A few words from my heart</p>
      <h2>Dear Anuska 💌</h2>
      <p>A little letter for you to read whenever you need a smile.</p>
    </div>
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
      <div class="center" style="margin-top:20px">
        <button class="btn" onclick="celebrate()">Send a little love 💖</button>
      </div>
    </div>
  </div>
</section>

<section id="wishes">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A sky full of possibilities</p>
      <h2>Wish Upon a Star 🌠</h2>
      <p>Think of something you hope for in your new year, then release your wish into the galaxy.</p>
    </div>
    <div class="card center" style="max-width:590px;margin:auto">
      <div style="font-size:3rem">🌌✨🌙</div>
      <textarea id="wishInput" rows="3" placeholder="Write your birthday wish here..."></textarea>
      <button class="btn" onclick="releaseWish()">Release my wish ✨</button>
      <div class="game-output" id="wishOutput"></div>
      <p class="small muted">Your wish stays in this page while it is open. It isn't sent anywhere.</p>
    </div>
  </div>
</section>

<section id="timecapsule">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">A note for another day</p>
      <h2>Future You's Time Capsule ⏳</h2>
      <p>Write a little message to your future self.</p>
    </div>
    <div class="card" style="max-width:590px;margin:auto">
      <label for="futureNote"><strong>Dear future Anuska...</strong></label>
      <textarea id="futureNote" rows="4" placeholder="What do you want to remember? What are you dreaming about?"></textarea>
      <button class="btn" onclick="saveNote()">Save my time capsule 💌</button>
      <button class="btn secondary" onclick="loadNote()">Read saved note</button>
      <p id="noteOutput" class="game-output"></p>
      <p class="small muted">This uses browser storage on this device. It may not appear on another phone or browser.</p>
    </div>
  </div>
</section>

<section id="surprise">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">One last little thing</p>
      <h2>The Birthday Surprise 🎂</h2>
      <p>Take a breath, make a wish, and open your final surprise.</p>
    </div>
    <div class="card center" style="max-width:620px;margin:auto">
      <div id="cake" style="font-size:6rem">🎂</div>
      <h3 id="surpriseTitle">Ready for your surprise, Kyuutu?</h3>
      <p id="surpriseText">This little universe was made to celebrate you and the happiness you deserve.</p>
      <button class="btn" onclick="finalSurprise()">Open the surprise ✨</button>
      <div id="finalMessage" class="game-output"></div>
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
/* BIRTHDAY COUNTDOWN — 5 OCTOBER 2026, MIDNIGHT IST */
const birthday = new Date("2026-10-05T00:00:00+05:30").getTime();

function updateCountdown() {
  const distance = birthday - Date.now();
  const message = document.getElementById("countdownMessage");

  if (distance <= 0) {
    ["days","hours","minutes","seconds"].forEach(id => {
      document.getElementById(id).textContent = "00";
    });
    message.textContent = "It's your birthday, Anuska! Happy Birthday, Kyuutu! 🎂💗";
    return;
  }

  document.getElementById("days").textContent = Math.floor(distance / 86400000);
  document.getElementById("hours").textContent = String(Math.floor(distance % 86400000 / 3600000)).padStart(2,"0");
  document.getElementById("minutes").textContent = String(Math.floor(distance % 3600000 / 60000)).padStart(2,"0");
  document.getElementById("seconds").textContent = String(Math.floor(distance % 60000 / 1000)).padStart(2,"0");
}
updateCountdown();
setInterval(updateCountdown,1000);

/* FLOATING HEARTS, BOWS, FLOWERS AND SPARKLES */
(function createFloatingLove() {
  const layer = document.getElementById("floating-love");
  const emojis = ["💗","💕","💖","💞","♡","🎀","🌸","✨","💘","🌷"];
  const hearts = window.innerWidth < 600 ? 22 : 38;
  const sparkles = window.innerWidth < 600 ? 12 : 22;

  for (let i = 0; i < hearts; i++) {
    const el = document.createElement("span");
    el.className = "love-particle";
    el.textContent = emojis[Math.floor(Math.random() * emojis.length)];
    el.style.setProperty("--left",Math.random() * 100 + "%");
    el.style.setProperty("--size",14 + Math.random() * 19 + "px");
    el.style.setProperty("--duration",9 + Math.random() * 13 + "s");
    el.style.setProperty("--delay",-Math.random() * 22 + "s");
    el.style.setProperty("--drift",-65 + Math.random() * 130 + "px");
    layer.appendChild(el);
  }

  for (let i = 0; i < sparkles; i++) {
    const el = document.createElement("span");
    el.className = "love-sparkle";
    el.textContent = Math.random() > .5 ? "✦" : "✧";
    el.style.setProperty("--left",Math.random() * 100 + "%");
    el.style.setProperty("--top",Math.random() * 100 + "%");
    el.style.setProperty("--size",10 + Math.random() * 15 + "px");
    el.style.setProperty("--duration",1.5 + Math.random() * 3 + "s");
    el.style.setProperty("--delay",-Math.random() * 4 + "s");
    layer.appendChild(el);
  }
})();

/* SONG VISUALIZER */
const song = document.getElementById("ourSong");
const equalizer = document.getElementById("equalizer");
song.addEventListener("play",() => equalizer.classList.add("playing"));
song.addEventListener("pause",() => equalizer.classList.remove("playing"));
song.addEventListener("ended",() => equalizer.classList.remove("playing"));

/* TOAST */
let toastTimer;
function showToast(message) {
  const toast = document.getElementById("toast");
  toast.textContent = message;
  toast.classList.add("show");
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => toast.classList.remove("show"),3000);
}

/* HEART GAME */
let hearts = 0;
function collectHeart() {
  if (hearts >= 5) return;
  hearts++;
  document.getElementById("heartCount").textContent = `Hearts collected: ${hearts} / 5`;
  document.getElementById("heartProgress").style.width = hearts * 20 + "%";

  if (hearts === 5) {
    document.getElementById("heartOutput").textContent = "You collected all five! A pocketful of happiness for you 💗";
    document.getElementById("heartButton").textContent = "All hearts collected 💖";
    showToast("Mission complete, Kyuutu! 💗");
    celebrate();
  } else {
    document.getElementById("heartOutput").textContent = "A little heart for you! 💗";
  }
}

/* NICKNAME GAME */
function checkNickname() {
  const value = document.getElementById("nicknameInput").value.trim().toLowerCase();
  const output = document.getElementById("nicknameOutput");
  if (value === "kyuutu" || value === "kyu u tu") {
    output.textContent = "Correct! Kyuutu is the star of this universe! 🎀";
    celebrate();
  } else {
    output.textContent = "Hint: It starts with K and is extra cute. Try again! 💗";
  }
}

/* MYSTERY GIFTS */
const gifts = [
  "🎀 Your gift: a reminder that you deserve kindness and happiness.",
  "🌷 Your gift: may this year bring new memories and beautiful surprises.",
  "💖 Your gift: a little pocket of courage for every dream you chase."
];
const openedGifts = new Set();

function openGift(index) {
  document.getElementById("giftOutput").textContent = gifts[index];
  openedGifts.add(index);
  showToast("A little gift opened just for you 🎁");
}

/* COMPLIMENT GARDEN */
const compliments = [
  "Your smile can brighten an ordinary day. 🌷",
  "You deserve people who listen and care. 💗",
  "Your dreams are worth making time for. ✨",
  "You don't need to be perfect to be wonderful. 🎀",
  "May you always find reasons to laugh. 🌸",
  "You are allowed to grow at your own pace. 🌱",
  "The world has room for your own kind of magic. 🌙"
];
let lastCompliment = -1;

function compliment() {
  let n;
  do { n = Math.floor(Math.random() * compliments.length); }
  while (n === lastCompliment);
  lastCompliment = n;
  document.getElementById("complimentOutput").textContent = compliments[n];
}

/* WISH GALAXY */
function releaseWish() {
  const input = document.getElementById("wishInput");
  const output = document.getElementById("wishOutput");
  if (!input.value.trim()) {
    output.textContent = "Write a little wish first, then send it into the stars. 🌠";
    return;
  }
  output.textContent = "✨ Wish released into your imaginary galaxy. May you keep working towards it! 🌠";
  input.value = "";
  celebrate();
}

/* TIME CAPSULE */
function saveNote() {
  const note = document.getElementById("futureNote").value.trim();
  const output = document.getElementById("noteOutput");
  if (!note) {
    output.textContent = "Write a little note before saving it. 💌";
    return;
  }
  try {
    localStorage.setItem("kyuutuFutureNote",note);
    output.textContent = "Your note has been saved in this browser on this device. 💗";
  } catch (e) {
    output.textContent = "Browser storage isn't available. Keep a copy of your note somewhere safe.";
  }
}
function loadNote() {
  const output = document.getElementById("noteOutput");
  try {
    const note = localStorage.getItem("kyuutuFutureNote");
    if (note) {
      document.getElementById("futureNote").value = note;
      output.textContent = "Your saved note is back. Read it whenever you like. 💌";
    } else {
      output.textContent = "No saved note found in this browser yet.";
    }
  } catch (e) {
    output.textContent = "Browser storage isn't available right now.";
  }
}

/* BIRTHDAY QUIZ */
let quizAnswered = false;
function answerQuiz(button,correct) {
  if (quizAnswered) return;
  quizAnswered = true;
  const output = document.getElementById("quizOutput");
  if (correct) {
    output.textContent = "Correct! You are the star of this little universe, Kyuutu! 💗";
    button.style.background = "#ffd9eb";
    celebrate();
  } else {
    output.textContent = "Not quite! The answer is Kyuutu 🎀";
  }
}
function nextQuiz() {
  quizAnswered = false;
  document.getElementById("quizOutput").textContent = "Question 2: What is this website celebrating? 🎂 Your birthday, Anuska!";
  showToast("You unlocked another little quiz clue 🎀");
}

/* FLOWER GARDEN */
let flowersPlanted = 0;
const flowerEmojis = ["🌷","🌸","🌼","🌺","💐","🌻","🪻"];

function plantFlower() {
  if (flowersPlanted >= 30) {
    document.getElementById("gardenOutput").textContent = "Your garden is full of flowers! What a lovely sight. 🌷";
    return;
  }
  const flower = document.createElement("span");
  flower.className = "flower";
  flower.textContent = flowerEmojis[Math.floor(Math.random() * flowerEmojis.length)];
  document.getElementById("flowerGarden").appendChild(flower);
  flowersPlanted++;
  document.getElementById("gardenOutput").textContent = `Flower ${flowersPlanted} planted! Your garden is growing. 🌱`;
}
function waterGarden() {
  document.getElementById("gardenOutput").textContent = "A little water, a little patience, and room to grow. 💧🌷";
  showToast("Your digital garden feels refreshed! 🌸");
}

/* MESSAGE IN A PETAL */
const petalMessages = [
  "You deserve gentle days and happy surprises. 🌷",
  "Keep a little space for dreams that make you smile. ✨",
  "May kindness find you wherever you go. 💗",
  "You are allowed to learn, change and grow. 🌱",
  "A little joy can make an ordinary day special. 🎀"
];
function petalMessage() {
  const message = petalMessages[Math.floor(Math.random() * petalMessages.length)];
  document.getElementById("petalOutput").textContent = message;
}

/* BUCKET LIST */
const bucketChecks = document.querySelectorAll(".bucket");
function updateBucketProgress() {
  const checked = [...bucketChecks].filter(item => item.checked).length;
  document.getElementById("bucketProgress").textContent = `${checked} / ${bucketChecks.length} adventures checked`;
  document.getElementById("bucketBar").style.width = checked / bucketChecks.length * 100 + "%";
}
bucketChecks.forEach(item => item.addEventListener("change",updateBucketProgress));

/* CONFETTI CELEBRATION */
function celebrate() {
  const box = document.getElementById("confetti");
  const symbols = ["💗","🌸","🎀","✨","💕","🌷"];
  for (let i = 0; i < 38; i++) {
    const piece = document.createElement("span");
    piece.className = "confetti-piece";
    piece.textContent = symbols[Math.floor(Math.random() * symbols.length)];
    piece.style.left = Math.random() * 100 + "%";
    piece.style.fontSize = 12 + Math.random() * 18 + "px";
    piece.style.animationDelay = Math.random() * 1.4 + "s";
    box.appendChild(piece);
    setTimeout(() => piece.remove(),5000);
  }
}

/* FINAL BIRTHDAY SURPRISE */
let finalOpened = false;
function finalSurprise() {
  const message = document.getElementById("finalMessage");
  if (!finalOpened) {
    finalOpened = true;
    document.getElementById("cake").textContent = "🎂🎉💗";
    document.getElementById("surpriseTitle").textContent = "Happy Birthday, Anuska! 🌷";
    document.getElementById("surpriseText").textContent =
      "Today is your day. May this new chapter bring you laughter, growth, kindness, peaceful moments and wonderful memories.";
    message.textContent =
      "Surprise unlocked! You deserve all the happiness in the world, Kyuutu. 💖 — Biraja";
  } else {
    message.textContent = "One more birthday hug in emoji form: 🫂💗🎀 Happy Birthday again!";
  }
  celebrate();
}

/* OPEN PHOTOS IN A NEW TAB */
document.querySelectorAll(".photo").forEach(img => {
  img.style.cursor = "zoom-in";
  img.addEventListener("click",() => {
    if (img.complete && img.naturalWidth > 0) {
      const win = window.open();
      if (win) {
        const image = win.document.createElement("img");
        image.src = img.src;
        image.alt = img.alt;
        image.style.cssText = "max-width:100%;max-height:100vh;object-fit:contain";
        win.document.body.style.cssText = "margin:0;background:#170e19;display:grid;place-items:center;min-height:100vh";
        win.document.title = "Memory 💗";
        win.document.body.appendChild(image);
      }
    } else {
      showToast("Check that this photo is uploaded with the exact filename.");
    }
  });
});

/* FRIENDLY MEDIA ERROR HINTS */
document.querySelectorAll("img").forEach(img => {
  img.addEventListener("error",() => {
    if (img.dataset.errorShown) return;
    img.dataset.errorShown = "yes";
    img.style.display = "none";
    const hint = document.createElement("p");
    hint.className = "muted small center";
    hint.textContent = "Photo not found — check the filename and letter case in your repository.";
    img.parentElement.appendChild(hint);
  });
});
document.querySelectorAll("video").forEach(video => {
  video.addEventListener("error",() => {
    showToast("A video could not load. Check its filename and upload status.");
  });
});
</script>
</body>
</html>
