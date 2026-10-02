
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f6">
<meta name="description" content="A birthday universe made especially for Anuska, my Kyuutu.">
<title>Kyuutuverse ♡ | Anuska's Birthday</title>

<style>
:root{
 --pink:#ff6fae;--pink2:#ffc4dc;--purple:#a78bfa;
 --cream:#fff8fb;--ink:#513047;--muted:#936d83;
 --glass:rgba(255,255,255,.86);
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:80px}
body{
 margin:0;font-family:"Trebuchet MS",Arial,sans-serif;color:var(--ink);
 background:radial-gradient(circle at 10% 5%,#ffe0ee,transparent 28%),
 radial-gradient(circle at 95% 25%,#e9ddff,transparent 28%),
 linear-gradient(145deg,#fff8fb,#fff0f6 45%,#f6efff);
 overflow-x:hidden
}
button,input,textarea{font:inherit}
button{cursor:pointer}
a{color:inherit}
section{padding:65px 17px;position:relative}
.wrap{width:min(100%,920px);margin:auto;position:relative;z-index:1}
.center{text-align:center}
h1,h2,h3{line-height:1.2}
h2{font-size:clamp(1.8rem,6vw,2.8rem);margin:10px 0 14px}
p{line-height:1.8}
img,video{max-width:100%}
.eyebrow{text-transform:uppercase;letter-spacing:3px;color:#d45b98;font-size:.76rem;font-weight:bold}
.muted{color:var(--muted)}
.small{font-size:.87rem}
.card{background:var(--glass);border:1px solid #ffffffed;border-radius:24px;padding:22px;box-shadow:0 12px 38px #b85c8b1a;backdrop-filter:blur(12px)}
.btn{border:0;border-radius:999px;padding:13px 20px;background:linear-gradient(120deg,var(--pink),var(--purple));color:white;font-weight:bold;box-shadow:0 7px 20px #ec8cbb40;transition:.2s;display:inline-block;margin:5px 3px}
.btn:hover{transform:translateY(-2px)}
.secondary{background:white!important;color:#a4497a!important;border:1px solid #f4c5dc!important;box-shadow:none!important}
.pill{display:inline-block;padding:7px 12px;border-radius:30px;background:#ffe2ef;color:#a54c7b;font-size:.8rem}
.grid{display:grid;gap:17px}
.two{grid-template-columns:repeat(2,minmax(0,1fr))}
.three{grid-template-columns:repeat(3,minmax(0,1fr))}
nav{position:sticky;top:0;z-index:25;display:flex;gap:8px;align-items:center;padding:11px 12px;overflow-x:auto;white-space:nowrap;background:#fff8f2ed;border-bottom:1px solid #f7dce9;backdrop-filter:blur(16px)}
nav .brand{font-weight:bold;color:#c64d8b;margin-right:8px}
nav a{text-decoration:none;font-size:.8rem;padding:8px 10px;border-radius:30px;background:#fff;border:1px solid #f6dce8}
nav a:hover{background:#ffe2ef}
.hero{min-height:90vh;display:flex;align-items:center;justify-content:center;padding:48px 16px 65px;position:relative;overflow:hidden}
.hero-inner{width:min(100%,800px);text-align:center;position:relative;z-index:2}
.hero h1{font-size:clamp(3rem,13vw,6.4rem);letter-spacing:-3px;margin:18px 0 10px;background:linear-gradient(100deg,#f05b9f,#ad80f2,#f05b9f);color:transparent;background-clip:text}
.hero p{max-width:620px;margin:12px auto 22px}
.hero-heart{font-size:3rem;display:inline-block;animation:heartbeat 1.5s infinite}
@keyframes heartbeat{50%{transform:scale(1.15)}}
.section-head{text-align:center;margin:0 auto 28px;max-width:650px}
.section-head p{color:var(--muted)}
.countdown{display:flex;justify-content:center;gap:9px;flex-wrap:wrap;margin:22px 0}
.timebox{min-width:68px;padding:14px 10px;background:#ffffffd4;border:1px solid #f5c9df;border-radius:18px;box-shadow:0 7px 20px #e9a5c522}
.timebox strong{display:block;font-size:1.6rem;color:#c94d91}
.timebox span{font-size:.7rem;color:var(--muted)}
.song-cover{font-size:4rem;width:110px;height:110px;margin:12px auto 16px;border-radius:50%;display:grid;place-items:center;background:linear-gradient(140deg,#ffd2e7,#d9c8ff);box-shadow:0 0 0 9px #fff7fb,0 0 0 11px #f6d6e7}
audio{width:100%;margin:12px 0}
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
.photo{width:100%;height:285px;object-fit:cover;border-radius:18px;background:#f8dfea;display:block;cursor:zoom-in}
.photo-card{padding:12px;transform:rotate(-1deg)}
.photo-card:nth-child(even){transform:rotate(1deg)}
.photo-card p{text-align:center;margin:10px 4px 2px}
.memory-number{color:#cf5997;font-size:.78rem}
.media{display:block;width:100%;border-radius:17px;background:#f4d8e7;max-height:460px}
.letter{font-family:Georgia,serif;line-height:2;white-space:pre-line;background:#fffaf4;border:1px solid #f6dfd0;padding:23px;border-radius:15px}
.game-output{min-height:35px;color:#b34581;font-weight:bold;margin-top:12px}
.gift{font-size:3rem;border:0;border-radius:20px;padding:23px 5px;background:#fff5fb;border:1px solid #f3d4e6;width:100%;transition:.2s}
.gift:hover{transform:scale(1.04)}
.progress{height:8px;background:#f5d8e7;border-radius:20px;overflow:hidden}
.progress div{height:100%;width:0;background:linear-gradient(90deg,var(--pink),var(--purple));transition:.3s}
textarea,input{width:100%;border:1px solid #efcbdc;background:#fffafd;border-radius:14px;padding:13px;color:var(--ink);outline-color:#f18bbd;margin:7px 0 12px}
.note-card{background:#fff9fd;border:1px solid #f4d9e8;border-radius:18px;padding:17px}
.note-card summary{cursor:pointer;font-weight:bold;color:#bd4f8d}
.note-card p{margin-bottom:0}
.theme-buttons{display:flex;gap:10px;justify-content:center;flex-wrap:wrap}
.theme-dot{width:43px;height:43px;border-radius:50%;border:3px solid white;box-shadow:0 0 0 1px #e8c5d9}
#floatingLayer{position:fixed;inset:0;overflow:hidden;pointer-events:none;z-index:15}
.float-item{position:absolute;bottom:-70px;opacity:0;user-select:none;will-change:transform,opacity;animation:floatAcross linear infinite;filter:drop-shadow(0 3px 5px #e89acb30)}
@keyframes floatAcross{
 0%{transform:translate3d(0,0,0) rotate(0) scale(.7);opacity:0}
 10%{opacity:.75}
 50%{transform:translate3d(var(--drift),-55vh,0) rotate(180deg) scale(1);opacity:.8}
 90%{opacity:.6}
 100%{transform:translate3d(calc(var(--drift)*-.5),-115vh,0) rotate(360deg) scale(.75);opacity:0}
}
#toast{position:fixed;left:50%;bottom:22px;z-index:60;transform:translate(-50%,25px);opacity:0;pointer-events:none;padding:13px 20px;border-radius:30px;color:white;background:#a54c7b;transition:.25s;max-width:90%;text-align:center}
#toast.show{opacity:1;transform:translate(-50%,0)}
#confetti{position:fixed;inset:0;pointer-events:none;z-index:50;overflow:hidden}
.confetti-piece{position:absolute;top:-15px;animation:fall 3.5s linear forwards}
@keyframes fall{to{transform:translateY(110vh) rotate(800deg);opacity:.2}}
footer{padding:38px 18px 65px;text-align:center;color:#9b6c87}
@media(max-width:620px){
 .two,.three{grid-template-columns:1fr}
 section{padding:48px 14px}
 .hero{min-height:85vh}
 .photo{height:320px}
 .card{padding:17px}
 .timebox{min-width:62px}
}
@media(prefers-reduced-motion:reduce){
 *,*::before,*::after{animation-duration:.01ms!important;animation-iteration-count:1!important;scroll-behavior:auto!important;transition-duration:.01ms!important}
}
</style>
</head>

<body>
<div id="floatingLayer" aria-hidden="true"></div>
<div id="confetti" aria-hidden="true"></div>

<nav>
 <span class="brand">♡ Kyuutuverse</span>
 <a href="#home">Home</a><a href="#universe">Explore</a>
 <a href="#memories">Memories</a><a href="#song">Song</a>
 <a href="#videos">Videos</a><a href="#games">Games</a>
 <a href="#letter">Letter</a><a href="#wishes">Wishes</a>
 <a href="#secret">Secret</a><a href="#surprise">Surprise</a>
</nav>

<header class="hero" id="home">
 <div class="hero-inner">
  <span class="pill">A tiny universe for one special girl</span>
  <div class="hero-heart">💗</div>
  <p class="eyebrow">For my favourite person</p>
  <h1>Kyuutuverse</h1>
  <h2 style="font-size:clamp(1.25rem,5vw,2rem)">Happy Birthday, Anuska! 🎂</h2>
  <p>Welcome to your own little corner of the internet, Kyuutu. Filled with memories, music, silly games, warm wishes and little surprises. 🎀✨</p>

  <!-- MUSIC APPEARS ABOVE THE COUNTDOWN -->
  <div class="card center" id="song" style="max-width:590px;margin:28px auto">
   <p class="eyebrow">Our little soundtrack</p>
   <div class="song-cover">🎵</div>
   <h3>Tera Naam Doon</h3>
   <p class="muted small">A song for my Kyuutu 💗</p>
   <div class="equalizer" id="equalizer" aria-hidden="true"><span></span><span></span><span></span><span></span><span></span></div>
   <audio id="ourSong" controls preload="metadata">
    <source src="tera naam doon.mp3" type="audio/mpeg">
    Your browser does not support audio playback.
   </audio>
   <p class="small muted">Press play and let the music make this moment special. 🎧</p>
   <button class="btn secondary" id="songDedication">Song dedication 💌</button>
  </div>

  <p class="eyebrow">The birthday countdown</p>
  <div class="countdown">
   <div class="timebox"><strong id="days">--</strong><span>DAYS</span></div>
   <div class="timebox"><strong id="hours">--</strong><span>HOURS</span></div>
   <div class="timebox"><strong id="minutes">--</strong><span>MINUTES</span></div>
   <div class="timebox"><strong id="seconds">--</strong><span>SECONDS</span></div>
  </div>
  <p id="countdownMessage" class="muted small">Counting down to your special day 💕</p>
  <a href="#universe" class="btn">Enter your universe ✨</a>
  <button class="btn secondary" id="reminderButton">A little reminder 💌</button>
 </div>
</header>

<section id="universe">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">Choose your adventure</p><h2>Your Little Universe 🌷</h2><p>Every corner holds a different surprise. Explore wherever your heart takes you.</p></div>
  <div class="grid three">
   <a class="portal" href="#memories"><span class="emoji">📸</span><strong>Memory Lane</strong><span class="muted small">Little moments, forever saved.</span></a>
   <a class="portal" href="#song"><span class="emoji">🎧</span><strong>Our Song</strong><span class="muted small">Press play and stay a while.</span></a>
   <a class="portal" href="#videos"><span class="emoji">🎬</span><strong>Mini Cinema</strong><span class="muted small">Moments in motion.</span></a>
   <a class="portal" href="#games"><span class="emoji">🎮</span><strong>Kyuutu Games</strong><span class="muted small">Tiny challenges and rewards.</span></a>
   <a class="portal" href="#openwhen"><span class="emoji">💌</span><strong>Open When...</strong><span class="muted small">A note for every kind of day.</span></a>
   <a class="portal" href="#wishes"><span class="emoji">🌠</span><strong>Wish Galaxy</strong><span class="muted small">Make a wish for your new year.</span></a>
   <a class="portal" href="#quiz"><span class="emoji">🧩</span><strong>How Well Do You Know Yourself?</strong><span class="muted small">A tiny quiz with a cute ending.</span></a>
   <a class="portal" href="#themes"><span class="emoji">🎨</span><strong>Dreamy Themes</strong><span class="muted small">Choose your favourite colours.</span></a>
   <a class="portal" href="#secret"><span class="emoji">🔐</span><strong>Secret Corner</strong><span class="muted small">Unlock a hidden message.</span></a>
  </div>
 </div>
</section>

<section id="memories">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">Little pieces of forever</p><h2>Our Memory Lane 📸</h2><p>Three pictures, three little reminders that ordinary moments can feel special.</p></div>
  <div class="grid three">
   <div class="card photo-card"><img class="photo" src="IMG-20260829-WA0026.jpg" alt="Memory one" loading="lazy"><p><span class="memory-number">MEMORY 01</span><br>One for the memory book 💗</p></div>
   <div class="card photo-card"><img class="photo" src="IMG-20260917-WA0025.jpg" alt="Memory two" loading="lazy"><p><span class="memory-number">MEMORY 02</span><br>A moment worth keeping 🌷</p></div>
   <div class="card photo-card"><img class="photo" src="Snapchat-1339605840.jpg" alt="Memory three" loading="lazy"><p><span class="memory-number">MEMORY 03</span><br>Saved with a little love 🎀</p></div>
  </div>
  <p class="center muted small">Tap a photo to view it larger. Make sure each filename matches exactly.</p>
  <div class="card center" style="margin-top:20px">
   <h3>📷 A little memory note</h3>
   <p id="memoryCaption">Every picture keeps a tiny piece of a moment that happened only once.</p>
   <button class="btn secondary" id="memoryButton">Show another memory thought</button>
  </div>
 </div>
</section>

<section id="videos">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">Little moments in motion</p><h2>Our Mini Cinema 🎬</h2><p>Press play whenever you want to revisit these moments.</p></div>
  <div class="grid">
   <div class="card"><span class="pill">VIDEO 01</span><h3>Memory in Motion 🌸</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO1.mp4" type="video/mp4">Your browser does not support video.</video></div>
   <div class="card"><span class="pill">VIDEO 02</span><h3>Cutiepie 🎀</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO2.mp4" type="video/mp4">Your browser does not support video.</video></div>
   <div class="card"><span class="pill">VIDEO 03</span><h3>Hihihi 💗</h3><video class="media" controls preload="metadata" playsinline><source src="VIDEO3.mp4" type="video/mp4">Your browser does not support video.</video></div>
  </div>
 </div>
</section>

<section id="games">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">Play a little</p><h2>Kyuutu's Fun Corner 🎮</h2><p>Little games made to bring a smile to your face.</p></div>
  <div class="grid two">
   <div class="card center">
    <h3>1. Catch the Hearts 💗</h3><p>Tap to collect five hearts.</p>
    <div class="progress"><div id="heartProgress"></div></div><p id="heartCount">Hearts collected: 0 / 5</p>
    <button class="btn" id="heartButton">Collect a heart 💗</button><div class="game-output" id="heartOutput" aria-live="polite"></div>
   </div>
   <div class="card center">
    <h3>2. Guess the Nickname 🎀</h3><p>What cute nickname is used on this website?</p>
    <input id="nicknameInput" placeholder="Type your answer..." autocomplete="off">
    <button class="btn" id="nicknameButton">Check answer</button><div class="game-output" id="nicknameOutput" aria-live="polite"></div>
   </div>
   <div class="card center">
    <h3>3. Pick a Mystery Gift 🎁</h3><p>Choose a box to reveal a little message.</p>
    <div class="grid three"><button class="gift" data-gift="0" aria-label="Gift one">🎁</button><button class="gift" data-gift="1" aria-label="Gift two">🎀</button><button class="gift" data-gift="2" aria-label="Gift three">💝</button></div>
    <div class="game-output" id="giftOutput" aria-live="polite"></div>
   </div>
   <div class="card center">
    <h3>4. Daily Compliment 🌷</h3><p>Tap for a little reminder.</p><div style="font-size:2.6rem">🌸</div>
    <button class="btn" id="complimentButton">Give me a compliment</button><div class="game-output" id="complimentOutput" aria-live="polite"></div>
   </div>
  </div>
 </div>
</section>

<section id="quiz">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">A tiny brain teaser</p><h2>How Well Do You Know Kyuutu? 🧩</h2><p>Answer three playful questions to reveal your quiz result.</p></div>
  <div class="card" style="max-width:650px;margin:auto">
   <div id="quizArea">
    <p id="quizProgress" class="pill">Question 1 of 3</p>
    <h3 id="quizQuestion">Which nickname appears throughout this universe?</h3>
    <div id="quizOptions" class="grid"></div>
    <p id="quizFeedback" class="game-output" aria-live="polite"></p>
    <button class="btn" id="quizNext" disabled>Next question →</button>
   </div>
   <div id="quizResult" class="center" hidden><div style="font-size:3rem">🏆💗</div><h3>Your quiz is complete!</h3><p id="quizScore"></p><button class="btn" id="quizRestart">Play again</button></div>
  </div>
 </div>
</section>

<section id="openwhen">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">A note for different days</p><h2>Open When... 💌</h2><p>Choose a little envelope for the kind of day you're having.</p></div>
  <div class="grid two">
   <details class="note-card"><summary>🌧️ Open when you're having a difficult day</summary><p>Take one moment at a time. You don't have to solve everything today. Rest, breathe, and give yourself the same kindness you give others. 💗</p></details>
   <details class="note-card"><summary>🌟 Open when you need confidence</summary><p>You are allowed to try, learn, change your mind and begin again. You don't need to have everything figured out to take your next step. ✨</p></details>
   <details class="note-card"><summary>😂 Open when you need a laugh</summary><p>Official Kyuutu rule: one silly smile is compulsory. If that doesn't work, imagine a penguin wearing a tiny pink crown. 🐧👑</p></details>
   <details class="note-card"><summary>🌙 Open before you sleep</summary><p>Let today be today. Put down what can wait until tomorrow and give yourself permission to rest. Good night, Kyuutu. 🌙</p></details>
   <details class="note-card"><summary>🎂 Open on your birthday</summary><p>Happy Birthday, Anuska! I hope your day brings warm wishes, favourite songs, unexpected smiles and memories you'll be happy to look back on. 🎀</p></details>
   <details class="note-card"><summary>💗 Open when you miss this page</summary><p>This little corner will be here whenever you want to revisit the music, memories and messages. May it remind you of a happy moment. 🌷</p></details>
  </div>
 </div>
</section>

<section id="letter">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">A few words from my heart</p><h2>Dear Anuska 💌</h2><p>A little letter for you to read whenever you need a smile.</p></div>
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
   <div class="center" style="margin-top:20px"><button class="btn" id="letterLoveButton">Send a little love 💖</button></div>
  </div>
 </div>
</section>

<section id="wishes">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">A sky full of possibilities</p><h2>Wish Upon a Star 🌠</h2><p>Think of something you hope for in your new year, then release your wish into the galaxy.</p></div>
  <div class="card center" style="max-width:590px;margin:auto">
   <div style="font-size:3rem">🌌✨🌙</div>
   <textarea id="wishInput" rows="3" placeholder="Write your birthday wish here..."></textarea>
   <button class="btn" id="wishButton">Release my wish ✨</button>
   <div class="game-output" id="wishOutput" aria-live="polite"></div>
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
   <button class="btn" id="saveNoteButton">Save my time capsule 💌</button>
   <button class="btn secondary" id="loadNoteButton">Read saved note</button>
   <p id="noteOutput" class="game-output" aria-live="polite"></p>
   <p class="small muted">Saved only in this browser on this device; it may not appear on another phone.</p>
  </div>
 </div>
</section>

<section id="themes">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">Make it your own</p><h2>Choose a Dreamy Theme 🎨</h2><p>Tap a colour to give your universe a different mood.</p></div>
  <div class="card center">
   <div class="theme-buttons">
    <button class="theme-dot" style="background:linear-gradient(135deg,#ff6fae,#ffc4dc)" data-theme="pink" aria-label="Pink theme"></button>
    <button class="theme-dot" style="background:linear-gradient(135deg,#a78bfa,#e2d8ff)" data-theme="purple" aria-label="Purple theme"></button>
    <button class="theme-dot" style="background:linear-gradient(135deg,#ffb36b,#ffe0a8)" data-theme="peach" aria-label="Peach theme"></button>
    <button class="theme-dot" style="background:linear-gradient(135deg,#75cfc0,#d0fff2)" data-theme="mint" aria-label="Mint theme"></button>
   </div>
   <p id="themeOutput" class="game-output">Pink dreams are currently on. 💗</p>
   <button class="btn secondary" id="resetTheme">Back to pink</button>
  </div>
 </div>
</section>

<section id="secret">
 <div class="wrap">
  <div class="section-head"><p class="eyebrow">A tiny hidden corner</p><h2>The Secret Message 🔐</h2><p>A little surprise is waiting behind a code.</p></div>
  <div class="card center" style="max-width:590px;margin:auto">
   <div style="font-size:3rem">🔐💌</div>
   <p>Hint: it's the nickname used all over this website.</p>
   <input id="secretCode" type="password" placeholder="Enter the secret code" autocomplete="off">
   <button class="btn" id="unlockSecret">Unlock message ✨</button>
   <div id="secretMessage" class="game-output" aria-live="polite"></div>
   <p class="small muted">This is a fun page interaction, not secure password protection.</p>
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
   <button class="btn" id="finalSurpriseButton">Open the surprise ✨</button>
   <div id="finalMessage" class="game-output" aria-live="polite"></div>
  </div>
 </div>
</section>

<section id="last">
 <div class="wrap center">
  <div style="font-size:3rem">🌷💗🎀</div>
  <h2>End of the page, not the good wishes.</h2>
  <p class="muted">Whenever you return, may this little corner bring back a happy thought.</p>
  <button class="btn secondary" id="topButton">Back to the beginning ↑</button>
 </div>
</section>

<footer>
 <p>Made with 💗 by Biraja, especially for Anuska.</p>
 <p class="small">Kyuutuverse © 2026 · A tiny universe of memories ✨</p>
</footer>

<div id="toast" role="status" aria-live="polite"></div>

<script>
"use strict";

/* Birthday: 5 October 2026, midnight India time */
const birthday = new Date("2026-10-05T00:00:00+05:30").getTime();

function updateCountdown(){
 const distance = birthday - Date.now();
 const message = document.getElementById("countdownMessage");

 if(distance <= 0){
  ["days","hours","minutes","seconds"].forEach(id=>{
   document.getElementById(id).textContent="00";
  });
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

/* Flowing hearts, flowers, stars and ribbons across the whole page */
const floatingLayer=document.getElementById("floatingLayer");
const floatEmojis=["💗","💕","♡","🌸","✨","🎀","🌷","💖","✦","🩷"];
for(let i=0;i<32;i++){
 const item=document.createElement("span");
 item.className="float-item";
 item.textContent=floatEmojis[i%floatEmojis.length];
 item.style.left=Math.random()*100+"%";
 item.style.fontSize=(14+Math.random()*22)+"px";
 item.style.animationDelay=(-Math.random()*16)+"s";
 item.style.animationDuration=(9+Math.random()*12)+"s";
 item.style.setProperty("--drift",(Math.random()*150-75)+"px");
 floatingLayer.appendChild(item);
}

/* Toasts */
let toastTimer;
function showToast(message){
 const toast=document.getElementById("toast");
 toast.textContent=message;
 toast.classList.add("show");
 clearTimeout(toastTimer);
 toastTimer=setTimeout(()=>toast.classList.remove("show"),3000);
}

/* Song player */
const song=document.getElementById("ourSong");
const equalizer=document.getElementById("equalizer");
song.addEventListener("play",()=>equalizer.classList.add("playing"));
song.addEventListener("pause",()=>equalizer.classList.remove("playing"));
song.addEventListener("ended",()=>equalizer.classList.remove("playing"));
document.getElementById("songDedication").addEventListener("click",()=>{
 showToast("Imagine a pink sky, your favourite song, and a little happy moment. 💗");
});

/* Buttons and reminders */
document.getElementById("reminderButton").addEventListener("click",()=>{
 showToast("A little reminder: you deserve kindness, peace and happiness, Kyuutu. 💗");
});

/* Memory captions */
const memoryThoughts=[
 "Every picture keeps a tiny piece of a moment that happened only once. 💗",
 "Some ordinary days become lovely memories without us noticing. 🌷",
 "A little snapshot can bring back a whole world of feelings. ✨",
 "The best memories are often the small moments we keep returning to. 🎀"
];
let memoryIndex=0;
document.getElementById("memoryButton").addEventListener("click",()=>{
 memoryIndex=(memoryIndex+1)%memoryThoughts.length;
 document.getElementById("memoryCaption").textContent=memoryThoughts[memoryIndex];
});

/* Open photos in a new tab */
document.querySelectorAll(".photo").forEach(img=>{
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
   }
  }else showToast("Check the photo filename and upload status.");
 });
 img.addEventListener("error",()=>{
  img.style.display="none";
  const hint=document.createElement("p");
  hint.className="muted small center";
  hint.textContent="Photo not found — check the filename and letter case.";
  img.parentElement.appendChild(hint);
 });
});

/* Heart collection */
let hearts=0;
document.getElementById("heartButton").addEventListener("click",()=>{
 if(hearts>=5)return;
 hearts++;
 document.getElementById("heartCount").textContent="Hearts collected: "+hearts+" / 5";
 document.getElementById("heartProgress").style.width=(hearts*20)+"%";
 if(hearts===5){
  document.getElementById("heartOutput").textContent="You collected all five! A pocketful of happiness for you. 💗";
  document.getElementById("heartButton").textContent="All hearts collected 💖";
  celebrate();
 }else{
  document.getElementById("heartOutput").textContent=[
   "A little heart for you!","Another one, just because!","You're doing great!","Almost there!"
  ][hearts-1];
 }
});

/* Nickname game */
document.getElementById("nicknameButton").addEventListener("click",()=>{
 const value=document.getElementById("nicknameInput").value.trim().toLowerCase().replace(/\s+/g,"");
 const output=document.getElementById("nicknameOutput");
 if(value==="kyuutu"){
  output.textContent="Correct! Kyuutu is the star of this universe! 🎀";
  celebrate();
 }else output.textContent="Hint: it starts with K and is extra cute. Try again! 💗";
});
document.getElementById("nicknameInput").addEventListener("keydown",e=>{
 if(e.key==="Enter")document.getElementById("nicknameButton").click();
});

/* Mystery gifts */
const gifts=[
 "🎀 Your gift: a reminder that you deserve kindness and happiness.",
 "🌷 Your gift: may this year bring new memories and beautiful surprises.",
 "💖 Your gift: a little pocket of courage for every dream you chase."
];
document.querySelectorAll("[data-gift]").forEach(button=>{
 button.addEventListener("click",()=>{
  const index=Number(button.dataset.gift);
  document.getElementById("giftOutput").textContent=gifts[index];
  showToast("A little gift opened just for you! 🎁");
 });
});

/* Compliments */
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
document.getElementById("complimentButton").addEventListener("click",()=>{
 let n;
 do{n=Math.floor(Math.random()*compliments.length)}while(n===lastCompliment);
 lastCompliment=n;
 document.getElementById("complimentOutput").textContent=compliments[n];
});

/* Three-question quiz */
const quizQuestions=[
 {q:"Which nickname appears throughout this universe?",options:["Kyuutu","Princess Peach","Mooncake"],answer:0,why:"Kyuutu is the star of this website! 💗"},
 {q:"What song is featured near the countdown?",options:["A random ringtone","Tera Naam Doon","No song at all"],answer:1,why:"That's the featured song! 🎧"},
 {q:"What can you release into the imaginary galaxy?",options:["A paper plane","A birthday wish","A shoe"],answer:1,why:"A wish full of hopes and possibilities! 🌠"}
];
let quizIndex=0,quizScore=0,quizAnswered=false;
function renderQuiz(){
 const q=quizQuestions[quizIndex];
 document.getElementById("quizProgress").textContent="Question "+(quizIndex+1)+" of "+quizQuestions.length;
 document.getElementById("quizQuestion").textContent=q.q;
 document.getElementById("quizFeedback").textContent="";
 document.getElementById("quizNext").disabled=true;
 document.getElementById("quizNext").textContent=quizIndex===quizQuestions.length-1?"See my result ✨":"Next question →";
 quizAnswered=false;
 const options=document.getElementById("quizOptions");
 options.replaceChildren();
 q.options.forEach((label,index)=>{
  const button=document.createElement("button");
  button.className="btn secondary";
  button.textContent=label;
  button.addEventListener("click",()=>{
   if(quizAnswered)return;
   quizAnswered=true;
   const correct=index===q.answer;
   if(correct)quizScore++;
   document.getElementById("quizFeedback").textContent=(correct?"Correct! ":"Not quite! ")+q.why;
   document.getElementById("quizNext").disabled=false;
   options.querySelectorAll("button").forEach(b=>b.disabled=true);
  });
  options.appendChild(button);
 });
}
document.getElementById("quizNext").addEventListener("click",()=>{
 if(!quizAnswered)return;
 if(quizIndex<quizQuestions.length-1){quizIndex++;renderQuiz();}
 else{
  document.getElementById("quizArea").hidden=true;
  document.getElementById("quizResult").hidden=false;
  document.getElementById("quizScore").textContent="You got "+quizScore+" out of "+quizQuestions.length+" questions. Every answer deserves a little celebration! 💗";
  celebrate();
 }
});
document.getElementById("quizRestart").addEventListener("click",()=>{
 quizIndex=0;quizScore=0;
 document.getElementById("quizArea").hidden=false;
 document.getElementById("quizResult").hidden=true;
 renderQuiz();
});
renderQuiz();

/* Letter celebration */
document.getElementById("letterLoveButton").addEventListener("click",()=>{
 showToast("Sending a little bundle of happiness your way! 💖");
 celebrate();
});

/* Wish Galaxy */
document.getElementById("wishButton").addEventListener("click",()=>{
 const input=document.getElementById("wishInput");
 const output=document.getElementById("wishOutput");
 if(!input.value.trim()){
  output.textContent="Write a little wish first, then send it into the stars. 🌠";
  return;
 }
 output.textContent="✨ Wish released into your imaginary galaxy. May you keep working towards it! 🌠";
 input.value="";
 celebrate();
});

/* Time capsule: saved locally in this browser */
document.getElementById("saveNoteButton").addEventListener("click",()=>{
 const note=document.getElementById("futureNote").value.trim();
 const output=document.getElementById("noteOutput");
 if(!note){output.textContent="Write a little note before saving it. 💌";return;}
 try{
  localStorage.setItem("kyuutuFutureNote",note);
  output.textContent="Your note has been saved in this browser on this device. 💗";
 }catch(error){
  output.textContent="Browser storage isn't available. Keep a copy of your note somewhere safe.";
 }
});
document.getElementById("loadNoteButton").addEventListener("click",()=>{
 const output=document.getElementById("noteOutput");
 try{
  const note=localStorage.getItem("kyuutuFutureNote");
  if(note){
   document.getElementById("futureNote").value=note;
   output.textContent="Your saved note is back. Read it whenever you like. 💌";
  }else output.textContent="No saved note found in this browser yet.";
 }catch(error){output.textContent="Browser storage isn't available right now.";}
});

/* Theme changer */
const themes={
 pink:{pink:"#ff6fae",pink2:"#ffc4dc",purple:"#a78bfa",bg1:"#fff0f6",bg2:"#f6efff",message:"Pink dreams are currently on. 💗"},
 purple:{pink:"#9d7bea",pink2:"#d8c9ff",purple:"#b19aff",bg1:"#f2edff",bg2:"#eee8ff",message:"A little purple galaxy for you. 💜"},
 peach:{pink:"#f39a73",pink2:"#ffd1ad",purple:"#f5b8c7",bg1:"#fff3e9",bg2:"#fff0f2",message:"A warm peachy daydream. 🍑"},
 mint:{pink:"#54b9a7",pink2:"#b8eee1",purple:"#91cce5",bg1:"#effffb",bg2:"#eaf8ff",message:"A fresh minty little universe. 🌿"}
};
function setTheme(name){
 const t=themes[name];
 const root=document.documentElement;
 root.style.setProperty("--pink",t.pink);
 root.style.setProperty("--pink2",t.pink2);
 root.style.setProperty("--purple",t.purple);
 document.body.style.background="radial-gradient(circle at 10% 5%,"+t.pink2+",transparent 28%),radial-gradient(circle at 95% 25%,"+t.purple+"55,transparent 28%),linear-gradient(145deg,#fff8fb,"+t.bg1+" 45%,"+t.bg2+")";
 document.getElementById("themeOutput").textContent=t.message;
}
document.querySelectorAll("[data-theme]").forEach(button=>{
 button.addEventListener("click",()=>setTheme(button.dataset.theme));
});
document.getElementById("resetTheme").addEventListener("click",()=>setTheme("pink"));

/* Secret message. Change the code below if you want a different one. */
const secretCode="kyuutu";
document.getElementById("unlockSecret").addEventListener("click",()=>{
 const entered=document.getElementById("secretCode").value.trim().toLowerCase();
 const output=document.getElementById("secretMessage");
 if(entered===secretCode){
  output.textContent="Secret unlocked! Anuska, I hope life gives you countless reasons to smile, beautiful dreams to follow, and lovely memories to make. Happy Birthday, Kyuutu! 💗 — Biraja";
  celebrate();
 }else output.textContent="Not quite! Hint: it's the nickname used throughout this website. 🎀";
});
document.getElementById("secretCode").addEventListener("keydown",e=>{
 if(e.key==="Enter")document.getElementById("unlockSecret").click();
});

/* Confetti */
function celebrate(){
 const box=document.getElementById("confetti");
 const symbols=["💗","🌸","🎀","✨","💕","🌷","💖"];
 for(let i=0;i<42;i++){
  const piece=document.createElement("span");
  piece.className="confetti-piece";
  piece.textContent=symbols[Math.floor(Math.random()*symbols.length)];
  piece.style.left=Math.random()*100+"%";
  piece.style.fontSize=(12+Math.random()*18)+"px";
  piece.style.animationDelay=Math.random()*1.2+"s";
  box.appendChild(piece);
  setTimeout(()=>piece.remove(),5000);
 }
}

/* Final birthday surprise */
let finalOpened=false;
document.getElementById("finalSurpriseButton").addEventListener("click",()=>{
 const message=document.getElementById("finalMessage");
 if(!finalOpened){
  finalOpened=true;
  document.getElementById("cake").textContent="🎂🎉💗";
  document.getElementById("surpriseTitle").textContent="Happy Birthday, Anuska! 🌷";
  document.getElementById("surpriseText").textContent="Today is your day. May this new chapter bring you laughter, growth, kindness, peaceful moments and wonderful memories.";
  message.textContent="Surprise unlocked! You deserve all the happiness in the world, Kyuutu. 💖 — Biraja";
 }else{
  message.textContent="One more birthday hug in emoji form: 🫂💗🎀 Happy Birthday again!";
 }
 celebrate();
});

/* Back to top */
document.getElementById("topButton").addEventListener("click",()=>{
 window.scrollTo({top:0,behavior:"smooth"});
});

/* Friendly video-load hints */
document.querySelectorAll("video").forEach(video=>{
 video.addEventListener("error",()=>showToast("A video couldn't load. Check its filename and upload status."));
});
</script>
</body>
</html>
