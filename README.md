
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f6">
<title>Kyuutuverse ♡ | Anuska's Birthday</title>

<style>
:root {
  --pink:#ff6fae;
  --pink2:#ffc4dc;
  --purple:#a78bfa;
  --cream:#fff8fb;
  --ink:#513047;
  --muted:#936d83;
  --glass:rgba(255,255,255,.78);
}
* { box-sizing:border-box; }
html { scroll-behavior:smooth; scroll-padding-top:82px; }
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
a { color:inherit; }
img,video { max-width:100%; }
section { padding:66px 18px; }
.wrap { width:min(100%,920px); margin:auto; }
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
  border:1px solid rgba(255,255,255,.9);
  border-radius:24px;
  padding:22px;
  box-shadow:0 12px 38px rgba(184,92,139,.10);
  backdrop-filter:blur(12px);
}
.btn {
  border:0; border-radius:999px; padding:13px 21px;
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
.btn:disabled { opacity:.55; cursor:not-allowed; }
.pill {
  display:inline-block; padding:7px 12px; border-radius:30px;
  background:#ffe2ef; color:#a54c7b; font-size:.8rem;
}
.grid { display:grid; gap:17px; }
.two { grid-template-columns:repeat(2,minmax(0,1fr)); }
.three { grid-template-columns:repeat(3,minmax(0,1fr)); }
nav {
  position:sticky; top:0; z-index:10;
  display:flex; gap:9px; align-items:center;
  padding:11px 13px; overflow-x:auto; white-space:nowrap;
  background:#fff8f2eF;
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
.hero-inner { width:min(100%,800px); text-align:center; position:relative; z-index:1; }
.hero h1 {
  font-size:clamp(3rem,13vw,6.4rem);
  letter-spacing:-3px; margin:18px 0 10px;
  background:linear-gradient(100deg,#f05b9f,#ad80f2,#f05b9f);
  color:transparent; background-clip:text;
}
.hero p { max-width:620px; margin:12px auto 24px; }
.hero-heart { font-size:3rem; animation:heartbeat 1.5s infinite; display:inline-block; }
@keyframes heartbeat { 50% { transform:scale(1.15); } }
.float {
  position:absolute; pointer-events:none; opacity:.6;
  animation:floatUp 8s linear infinite;
}
@keyframes floatUp {
  from { transform:translateY(15vh) rotate(0deg); opacity:0; }
  15% { opacity:.65; }
  to { transform:translateY(-110vh) rotate(260deg); opacity:0; }
}
.countdown {
  display:flex; justify-content:center; gap:10px;
  flex-wrap:wrap; margin:24px 0;
}
.timebox {
  min-width:72px; padding:15px 11px;
  background:#ffffffb8; border:1px solid #f5c9df;
  border-radius:18px; box-shadow:0 7px 20px #e9a5c522;
}
.timebox strong { display:block; font-size:1.65rem; color:#c94d91; }
.timebox span { font-size:.72rem; color:var(--muted); }
.section-head { text-align:center; margin:0 auto 28px; max-width:650px; }
.section-head p { color:var(--muted); }
.photo {
  width:100%; height:290px; object-fit:cover;
  border-radius:18px; background:#f8dfea;
  display:block;
}
.photo-card { padding:12px; transform:rotate(-1deg); }
.photo-card:nth-child(even) { transform:rotate(1deg); }
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
footer { padding:38px 18px 65px; text-align:center; color:#9b6c87; }
#toast {
  position:fixed; left:50%; bottom:25px; z-index:50;
  transform:translate(-50%,25px); opacity:0; pointer-events:none;
  padding:13px 20px; border-radius:30px;
  color:#fff; background:#a54c7b; transition:.25s;
  max-width:90%; text-align:center;
}
#toast.show { opacity:1; transform:translate(-50%,0); }
#confetti { position:fixed; inset:0; pointer-events:none; z-index:30; overflow:hidden; }
.confetti-piece { position:absolute; top:-15px; animation:fall 3.5s linear forwards; }
@keyframes fall { to { transform:translateY(110vh) rotate(800deg); opacity:.2; } }
details summary { cursor:pointer; font-weight:bold; }
details { margin-top:12px; }
@media(max-width:620px) {
  .two,.three { grid-template-columns:1fr; }
  section { padding:50px 15px; }
  .hero { min-height:84vh; }
  .photo { height:320px; }
  .card { padding:18px; }
  .timebox { min-width:65px; }
}
</style>
</head>

<body>
<div id="confetti"></div>

<nav>
  <span class="brand">♡ Kyuutuverse</span>
  <a href="#home">Home</a>
  <a href="#memories">Memories</a>
  <a href="#song">Our Song</a>
  <a href="#videos">Videos</a>
  <a href="#games">Games</a>
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

    <a href="#universe"><button class="btn">Enter your universe ✨</button></a>
    <button class="btn secondary" onclick="showToast('A little reminder: you deserve happiness, Kyuutu 💗')">A little reminder 💌</button>
  </div>
</header>

<section id="universe">
  <div class="wrap">
    <div class="section-head">
      <p class="eyebrow">Choose your adventure</p>
      <h2>Your little universe 🌷</h2>
      <p>Every corner holds a different little surprise. Explore wherever your heart takes you.</p>
    </div>
    <div class="grid three">
      <a class="portal" href="#memories"><span class="emoji">📸</span><strong>Our Memory Lane</strong><span class="muted small">Little moments, forever saved.</span></a>
      <a class="portal" href="#song"><span class="emoji">🎧</span><strong>Our Song</strong><span class="muted small">Press play and stay a while.</span></a>
      <a class="portal" href="#videos"><span class="emoji">🎬</span><strong>Moving Memories</strong><span class="muted small">Three little video moments.</span></a>
      <a class="portal" href="#games"><span class="emoji">🎮</span><strong>Kyuutu Games</strong><span class="muted small">Tiny challenges and cute rewards.</span></a>
      <a class="portal" href="#letter"><span class="emoji">💌</span><strong>Open When Ready</strong><span class="muted small">A letter written just for you.</span></a>
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
    <p class="center muted small">Tip: Tap a picture to open it in a new tab.</p>
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
      <h3 style="margin-bottom:4px">Tera Naam Doon</h3>
      <p class="muted small">A song for my Kyuutu 💗</p>
      <div class="equalizer" id="equalizer">
        <span></span><span></span><span></span><span></span><span></span>
      </div>
      <audio id="ourSong" controls preload="metadata">
        <source src="tera naam doon.mp3" type="audio/mpeg">
        Your browser does not support audio playback.
      </audio>
      <p class="small muted">Use the player above to play or pause the song.</p>
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
        <h3>A Little More of Us 🎀</h3>
        <video class="media" controls preload="metadata" playsinline>
          <source src="VIDEO2.mp4" type="video/mp4">
          Your browser does not support video.
        </video>
      </div>
      <div class="card">
        <span class="pill">VIDEO 03</span>
        <h3>One to Remember 💗</h3>
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
        <p>Tap the button to collect 5 hearts.</p>
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
        <p>Choose one box to reveal a little message.</p>
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

This little website is just a collection of moments, music and words, made especially for you. I hope it makes you smile whenever you visit it.

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
/* BIRTHDAY COUNTDOWN
   Date: 5 October 2026 at midnight, India Standard Time.
*/
const birthday = new Date("2026-10-05T00:00:00+05:30").getTime();

function updateCountdown() {
  const now = Date.now();
  let distance = birthday - now;
  const message = document.getElementById("countdownMessage");

  if (distance <= 0) {
    ["days","hours","minutes","seconds"].forEach(id => {
      document.getElementById(id).textContent = "00";
    });
    message.textContent = "It's your birthday, Anuska! Happy Birthday, Kyuutu! 🎂💗";
    return;
  }

  const d = Math.floor(distance / 86400000);
  const h = Math.floor((distance % 86400000) / 3600000);
  const m = Math.floor((distance % 3600000) / 60000);
  const s = Math.floor((distance % 60000) / 1000);

  document.getElementById("days").textContent = d;
  document.getElementById("hours").textContent = String(h).padStart(2,"0");
  document.getElementById("minutes").textContent = String(m).padStart(2,"0");
  document.getElementById("seconds").textContent = String(s).padStart(2,"0");
}
updateCountdown();
setInterval(updateCountdown, 1000);

/* FLOATING DECORATIONS */
const floatEmojis = ["♡","💗","✦","🌷","✨","🎀"];
for (let i = 0; i < 18; i++) {
  const el = document.createElement("span");
  el.className = "float";
  el.textContent = floatEmojis[i % floatEmojis.length];
  el.style.left = Math.random() * 100 + "%";
  el.style.bottom = "-50px";
  el.style.fontSize = (15 + Math.random() * 20) + "px";
  el.style.animationDelay = (Math.random() * 9) + "s";
  el.style.animationDuration = (7 + Math.random() * 7) + "s";
  document.body.appendChild(el);
}

/* SONG PLAYER VISUALIZER */
const song = document.getElementById("ourSong");
const equalizer = document.getElementById("equalizer");
song.addEventListener("play", () => equalizer.classList.add("playing"));
song.addEventListener("pause", () => equalizer.classList.remove("playing"));
song.addEventListener("ended", () => equalizer.classList.remove("playing"));

/* TOAST MESSAGE */
let toastTimer;
function showToast(message) {
  const toast = document.getElementById("toast");
  toast.textContent = message;
  toast.classList.add("show");
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => toast.classList.remove("show"), 3000);
}

/* HEART COLLECTION GAME */
let hearts = 0;
function collectHeart() {
  if (hearts >= 5) return;
  hearts++;
  document.getElementById("heartCount").textContent =
    "Hearts collected: " + hearts + " / 5";
  document.getElementById("heartProgress").style.width = (hearts * 20) + "%";

  if (hearts === 5) {
    document.getElementById("heartOutput").textContent =
      "You collected all five! Sending you a pocketful of happiness 💗";
    document.getElementById("heartButton").textContent = "All hearts collected 💖";
    showToast("Mission complete, Kyuutu! 💗");
  } else {
    document.getElementById("heartOutput").textContent =
      ["A little heart for you!","Another one, just because!","You're doing great!","Almost there!"][hearts - 1];
  }
}

/* NICKNAME GAME */
function checkNickname() {
  const value = document.getElementById("nicknameInput").value.trim().toLowerCase();
  const output = document.getElementById("nicknameOutput");
  if (value === "kyuutu" || value === "kyu u tu" || value === "kyuutu 💗") {
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
  if (openedGifts.has(index)) {
    document.getElementById("giftOutput").textContent = gifts[index];
    return;
  }
  openedGifts.add(index);
  document.getElementById("giftOutput").textContent = gifts[index];
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
  while (n === lastCompliment && compliments.length > 1);
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
    localStorage.setItem("kyuutuFutureNote", note);
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

/* BIRTHDAY SURPRISE + CONFETTI */
function celebrate() {
  const box = document.getElementById("confetti");
  const colors = ["💗","🌸","🎀","✨","💕","🌷"];
  for (let i = 0; i < 38; i++) {
    const piece = document.createElement("span");
    piece.className = "confetti-piece";
    piece.textContent = colors[Math.floor(Math.random() * colors.length)];
    piece.style.left = Math.random() * 100 + "%";
    piece.style.fontSize = (12 + Math.random() * 18) + "px";
    piece.style.animationDelay = (Math.random() * 1.4) + "s";
    box.appendChild(piece);
    setTimeout(() => piece.remove(), 5000);
  }
}
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
    celebrate();
  } else {
    message.textContent =
      "One more birthday hug in emoji form: 🫂💗🎀 Happy Birthday again!";
    celebrate();
  }
}

/* OPEN PHOTOS IN A NEW TAB WHEN TAPPED */
document.querySelectorAll(".photo").forEach(img => {
  img.style.cursor = "zoom-in";
  img.addEventListener("click", () => {
    if (img.complete && img.naturalWidth > 0) {
      const win = window.open();
      if (win) {
        win.document.write(
          '<title>Memory 💗</title><meta name="viewport" content="width=device-width,initial-scale=1">' +
          '<body style="margin:0;background:#170e19;display:grid;place-items:center;min-height:100vh">' +
          '<img src="' + img.src + '" style="max-width:100%;max-height:100vh;object-fit:contain"></body>'
        );
        win.document.close();
      }
    } else {
      showToast("Check that this photo is uploaded with the exact filename.");
    }
  });
});

/* FRIENDLY MEDIA ERROR HINTS */
document.querySelectorAll("img").forEach(img => {
  img.addEventListener("error", () => {
    img.style.display = "none";
    const hint = document.createElement("p");
    hint.className = "muted small center";
    hint.textContent = "Photo not found — check the filename and letter case in your repository.";
    img.parentElement.appendChild(hint);
  });
});
document.querySelectorAll("video").forEach(video => {
  video.addEventListener("error", () => {
    showToast("A video could not load. Check its filename and upload status.");
  });
});
</script>
</body>
</html>
