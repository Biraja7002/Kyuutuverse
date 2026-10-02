# Kyuutuverse
💗 A little corner of the internet made with love, especially for my Kyuutu, Anuska. 🎀✨ A place filled with our memories, cute surprises, and all the little things that remind me of you. Happy Birthday, my girl! 🎂💕 You deserve all the happiness in the world. 🌷🫶🏻
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f7">
<title>For Kyuutu ♡ — The Birthday Universe</title>

<style>
:root {
  --bg: #fff4fa;
  --paper: #fffafd;
  --ink: #512b48;
  --muted: #956b87;
  --pink: #f08ab9;
  --hot: #d94e93;
  --lav: #c8b7ff;
  --line: #f2cde0;
  --shadow: 0 18px 50px #9e47741b;
}

* { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  background:
    radial-gradient(circle at 10% 5%, #ffe1ef 0, transparent 28rem),
    radial-gradient(circle at 90% 25%, #e9e3ff 0, transparent 30rem),
    var(--bg);
  color: var(--ink);
  font-family: "Trebuchet MS", system-ui, sans-serif;
  line-height: 1.65;
}

body.night {
  --bg: #191426;
  --paper: #282038;
  --ink: #fff0fa;
  --muted: #d5b8ce;
  --line: #57405c;
  --shadow: 0 18px 50px #0004;
  background:
    radial-gradient(circle at 10% 5%, #56304e 0, transparent 28rem),
    radial-gradient(circle at 90% 25%, #342e61 0, transparent 30rem),
    var(--bg);
}

a { color: inherit; }
button, input, textarea { font: inherit; }
button { border: 0; cursor: pointer; }

.wrap {
  width: min(1100px, 92%);
  margin: auto;
}

.topbar {
  position: sticky;
  top: 0;
  z-index: 10;
  background: var(--paper);
  border-bottom: 1px solid var(--line);
}

.nav {
  display: flex;
  gap: 12px;
  align-items: center;
  justify-content: space-between;
  padding: 10px 0;
}

.brand {
  font-weight: 900;
  letter-spacing: .04em;
}

.navlinks {
  display: flex;
  gap: 7px;
  flex-wrap: wrap;
}

.navlinks a, .pill {
  padding: 7px 12px;
  border: 1px solid var(--line);
  border-radius: 99px;
  text-decoration: none;
  font-size: .82rem;
  background: var(--paper);
}

.btn {
  background: linear-gradient(135deg, var(--pink), var(--hot));
  color: white;
  border-radius: 99px;
  padding: 11px 18px;
  box-shadow: 0 8px 20px #d94e9330;
  font-weight: 800;
}

.btn.secondary {
  background: var(--paper);
  color: var(--ink);
  border: 1px solid var(--line);
  box-shadow: none;
}

.hero {
  min-height: 86vh;
  display: grid;
  place-items: center;
  text-align: center;
  padding: 70px 0 45px;
  position: relative;
  overflow: hidden;
}

.eyebrow {
  letter-spacing: .18em;
  text-transform: uppercase;
  color: var(--hot);
  font-weight: 900;
  font-size: .76rem;
}

.hero h1 {
  font-size: clamp(3rem, 9vw, 6.8rem);
  line-height: .98;
  letter-spacing: -.06em;
  margin: 18px auto;
  max-width: 850px;
}

.gradient {
  background: linear-gradient(110deg, #d84f98, #9c7de8, #ee83ac);
  background-clip: text;
  color: transparent;
}

.hero p {
  max-width: 630px;
  margin: 20px auto;
  color: var(--muted);
  font-size: 1.1rem;
}

.orb {
  position: absolute;
  border-radius: 50%;
  filter: blur(1px);
  opacity: .5;
  animation: float 7s ease-in-out infinite;
  pointer-events: none;
}

.orb.one {
  width: 90px;
  height: 90px;
  background: #ffbad9;
  top: 18%;
  left: 8%;
}

.orb.two {
  width: 55px;
  height: 55px;
  background: #c4b2ff;
  right: 10%;
  top: 27%;
  animation-delay: -3s;
}

.orb.three {
  width: 34px;
  height: 34px;
  background: #ffdf9c;
  bottom: 17%;
  left: 16%;
  animation-delay: -1s;
}

@keyframes float {
  50% { transform: translateY(-22px) rotate(12deg); }
}

.hero-actions {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
  margin-top: 25px;
}

.countdown {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
  margin: 30px 0;
}

.timebox {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 18px;
  padding: 12px 18px;
  min-width: 76px;
  box-shadow: var(--shadow);
}

.timebox b {
  display: block;
  font-size: 1.6rem;
}

.timebox small { color: var(--muted); }

section {
  padding: 70px 0;
  scroll-margin-top: 75px;
}

.sectionhead {
  text-align: center;
  max-width: 700px;
  margin: 0 auto 30px;
}

.sectionhead h2 {
  font-size: clamp(2rem, 5vw, 3.4rem);
  letter-spacing: -.04em;
  line-height: 1.1;
  margin: 8px 0;
}

.sectionhead p { color: var(--muted); }

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}

.card {
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 24px;
  padding: 22px;
  box-shadow: var(--shadow);
  min-width: 0;
}

.card h3 { margin: 8px 0; }
.card p { color: var(--muted); margin: 7px 0; }
.emoji { font-size: 2rem; }

.tag {
  display: inline-block;
  border-radius: 99px;
  background: #ffe3f0;
  color: #a73570;
  padding: 4px 10px;
  font-size: .76rem;
  font-weight: 800;
}

.night .tag {
  background: #54314c;
  color: #ffd5eb;
}

.portal {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 13px;
}

.portal button {
  background: var(--paper);
  color: var(--ink);
  border: 1px solid var(--line);
  border-radius: 20px;
  padding: 18px 10px;
  box-shadow: var(--shadow);
  transition: .2s;
}

.portal button:hover { transform: translateY(-4px); }
.portal span { display: block; font-size: 2rem; }
.portal small { color: var(--muted); }

.notice {
  border: 1px dashed var(--pink);
  border-radius: 18px;
  padding: 14px 17px;
  color: var(--muted);
  background: var(--paper);
}

.timeline {
  position: relative;
  max-width: 760px;
  margin: auto;
}

.timeline:before {
  content: "";
  position: absolute;
  left: 17px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: var(--line);
}

.moment {
  position: relative;
  margin: 0 0 18px 42px;
}

.moment:before {
  content: "♡";
  position: absolute;
  left: -38px;
  top: 14px;
  color: var(--hot);
  background: var(--paper);
  font-size: 1.3rem;
}

.memory-photo {
  height: 160px;
  border-radius: 16px;
  border: 1px dashed var(--pink);
  display: grid;
  place-items: center;
  background: linear-gradient(135deg, #ffe4f0, #eee8ff);
  color: #a45c86;
  text-align: center;
  padding: 12px;
  overflow: hidden;
}

.memory-photo img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.video-frame {
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 16px;
  background: #1c1423;
  display: grid;
  place-items: center;
  color: white;
  overflow: hidden;
}

.video-frame video {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.letter {
  font-family: Georgia, serif;
  font-size: 1.08rem;
  white-space: pre-line;
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 8px 28px 8px 28px;
  padding: clamp(20px, 5vw, 45px);
  box-shadow: var(--shadow);
}

.inputrow {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
}

.inputrow input {
  min-width: 0;
  flex: 1;
  background: var(--paper);
  border: 1px solid var(--line);
  border-radius: 99px;
  padding: 11px 15px;
  color: var(--ink);
}

.output {
  margin-top: 15px;
  padding: 15px;
  border-radius: 16px;
  background: var(--paper);
  border: 1px solid var(--line);
  min-height: 45px;
}

.starfield {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 10px;
}

.star {
  font-size: 2rem;
  border-radius: 15px;
  background: var(--paper);
  border: 1px solid var(--line);
  padding: 14px 0;
  color: var(--pink);
}

.star.found {
  background: #fff0bd;
  color: #d38b20;
}

.meter {
  height: 10px;
  border-radius: 99px;
  background: var(--line);
  overflow: hidden;
}

.meter div {
  height: 100%;
  width: 0;
  background: linear-gradient(90deg, var(--pink), var(--lav));
  transition: width .3s;
}

.cake {
  font-size: 6rem;
  text-align: center;
  filter: drop-shadow(0 8px 8px #d94e9324);
  animation: bob 2.5s infinite;
}

@keyframes bob {
  50% { transform: translateY(-7px); }
}

.wishlist {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.wish {
  border: 1px solid var(--line);
  border-radius: 99px;
  padding: 8px 13px;
  background: var(--paper);
}

.footer {
  text-align: center;
  padding: 45px 0 70px;
  color: var(--muted);
}

.toast {
  position: fixed;
  bottom: 18px;
  left: 50%;
  transform: translate(-50%, 130px);
  transition: .35s;
  background: var(--ink);
  color: var(--paper);
  padding: 12px 18px;
  border-radius: 99px;
  z-index: 30;
  box-shadow: var(--shadow);
  max-width: 90%;
  text-align: center;
}

.toast.show { transform: translate(-50%, 0); }

.spark {
  position: fixed;
  pointer-events: none;
  z-index: 20;
  animation: rise 1.4s ease-out forwards;
}

@keyframes rise {
  to {
    transform: translateY(-120px) rotate(160deg);
    opacity: 0;
  }
}

.hide { display: none !important; }
.small { font-size: .85rem; color: var(--muted); }

@media (max-width: 760px) {
  .grid { grid-template-columns: 1fr 1fr; }
  .portal { grid-template-columns: repeat(2, 1fr); }
  .nav { align-items: flex-start; }
  .navlinks { display: none; }
  .hero { min-height: 75vh; }
  .starfield { grid-template-columns: repeat(5, 1fr); gap: 6px; }
  .star { font-size: 1.5rem; padding: 10px 0; }
}

@media (max-width: 450px) {
  .grid { grid-template-columns: 1fr; }
  .timebox { min-width: 65px; padding: 10px; }
  .timebox b { font-size: 1.3rem; }
}
</style>
</head>

<body>

<div class="topbar">
  <div class="wrap nav">
    <div class="brand">✦ KYUUTUVERSE</div>
    <div class="navlinks">
      <a href="#map">Explore</a>
      <a href="#memories">Memories</a>
      <a href="#vault">Video vault</a>
      <a href="#games">Games</a>
      <a href="#letter">Letter</a>
    </div>
    <button class="btn secondary" id="themeBtn">🌙 Night mode</button>
  </div>
</div>

<header class="hero">
  <div class="orb one"></div>
  <div class="orb two"></div>
  <div class="orb three"></div>

  <div class="wrap">
    <div class="eyebrow">A tiny universe, made for one girl</div>
    <h1>Welcome to<br><span class="gradient">Kyuutu's Universe</span> ♡</h1>

    <p>
      Dear Anuska, this isn't just a birthday website.
      It's a little universe of memories, silly games, secret notes,
      dreams, and all the tiny things that make you wonderfully you.
    </p>

    <div class="countdown">
      <div class="timebox"><b id="days">--</b><small>Days</small></div>
      <div class="timebox"><b id="hours">--</b><small>Hours</small></div>
      <div class="timebox"><b id="mins">--</b><small>Minutes</small></div>
      <div class="timebox"><b id="secs">--</b><small>Seconds</small></div>
    </div>

    <div class="small">Counting down to 5 October 2026 · midnight IST</div>

    <div class="hero-actions">
      <a class="btn" href="#map" style="text-decoration:none">🚀 Start exploring</a>
      <button class="btn secondary" id="surpriseBtn">🎁 Give me a surprise</button>
    </div>
  </div>
</header>

<main>

<section id="map">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Choose your destination</div>
      <h2>The Universe Map 🪐</h2>
      <p>Every planet opens a different corner of this little world. Pick any destination.</p>
    </div>

    <div class="portal">
      <button data-go="memories"><span>📸</span><b>Memory Moon</b><small>Little moments</small></button>
      <button data-go="vault"><span>🎞️</span><b>Movie Planet</b><small>Photos & videos</small></button>
      <button data-go="games"><span>🕹️</span><b>Play Planet</b><small>Mini games</small></button>
      <button data-go="letter"><span>💌</span><b>Letter Nebula</b><small>Words from me</small></button>
      <button data-go="wishes"><span>🌠</span><b>Wish Galaxy</b><small>Future dreams</small></button>
      <button data-go="garden"><span>🌷</span><b>Compliment Garden</b><small>Kind reminders</small></button>
      <button data-go="timecapsule"><span>⏳</span><b>Time Capsule</b><small>Notes for later</small></button>
      <button data-go="finale"><span>🎆</span><b>Final Orbit</b><small>Birthday finale</small></button>
    </div>
  </div>
</section>

<section id="memories">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Memory Moon</div>
      <h2>Little moments, big feelings 📸</h2>
      <p>Add your favourite pictures and turn this page into a scrapbook.</p>
    </div>

    <div class="grid">
      <article class="card">
        <div class="memory-photo">
          <img src="photo1.jpg" alt="A favourite memory"
               onerror="this.style.display='none';this.parentElement.textContent='📷 Add photo1.jpg here';">
        </div>
        <h3>Memory No. 1</h3>
        <p>A little moment worth keeping forever.</p>
      </article>

      <article class="card">
        <div class="memory-photo">
          <img src="photo2.jpg" alt="Another favourite memory"
               onerror="this.style.display='none';this.parentElement.textContent='📷 Add photo2.jpg here';">
        </div>
        <h3>Memory No. 2</h3>
        <p>One more page in our memory book.</p>
      </article>

      <article class="card">
        <div class="memory-photo">
          <img src="photo3.jpg" alt="A special picture"
               onerror="this.style.display='none';this.parentElement.textContent='📷 Add photo3.jpg here';">
        </div>
        <h3>Memory No. 3</h3>
        <p>Some pictures say more than words.</p>
      </article>
    </div>

    <div class="notice" style="margin-top:18px">
      💗 Tip: Put your photos in the same folder as this HTML file.
      Change the filenames in the code if your photos have different names.
    </div>
  </div>
</section>

<section id="vault">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Movie Planet</div>
      <h2>Our Little Cinema 🎞️</h2>
      <p>A space for video messages, favourite clips and birthday memories.</p>
    </div>

    <div class="grid">
      <article class="card">
        <div class="video-frame">
          <video controls playsinline preload="metadata">
            <source src="memory1.mp4" type="video/mp4">
            Your browser does not support video.
          </video>
        </div>
        <h3>Memory Film</h3>
        <p>Replace <b>memory1.mp4</b> with your video filename.</p>
      </article>

      <article class="card">
        <div class="video-frame">
          <video controls playsinline preload="metadata">
            <source src="birthday-message.mp4" type="video/mp4">
            Your browser does not support video.
          </video>
        </div>
        <h3>A Message for You</h3>
        <p>Add a personal birthday wish video here.</p>
      </article>

      <article class="card">
        <div class="video-frame">
          <video controls playsinline preload="metadata">
            <source src="surprise.mp4" type="video/mp4">
            Your browser does not support video.
          </video>
        </div>
        <h3>The Surprise Film</h3>
        <p>A final clip for a special moment.</p>
      </article>
    </div>
  </div>
</section>

<section id="games">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Play Planet</div>
      <h2>Find the five hidden stars ⭐</h2>
      <p>Tap each star to reveal a little message.</p>
    </div>

    <div class="card">
      <div class="starfield" id="starfield"></div>
      <div class="meter" style="margin-top:18px">
        <div id="starMeter"></div>
      </div>
      <p id="starCount" style="text-align:center">0 of 5 stars found</p>
      <div class="output" id="starOutput">Your star messages will appear here. ✨</div>
    </div>

    <div class="grid" style="margin-top:18px">
      <article class="card">
        <div class="emoji">🔐</div>
        <h3>The Secret Code</h3>
        <p>Enter the nickname written in this universe.</p>
        <form id="codeForm" class="inputrow">
          <input id="secretInput" placeholder="Enter secret word..." maxlength="40">
          <button class="btn" type="submit">Unlock</button>
        </form>
        <div id="codeOutput" class="output">A secret message is waiting.</div>
      </article>

      <article class="card">
        <div class="emoji">🎁</div>
        <h3>Mystery Gift Boxes</h3>
        <p>Choose a box to reveal a surprise.</p>
        <div class="hero-actions">
          <button class="btn secondary mystery" data-box="0">🎁 Box 1</button>
          <button class="btn secondary mystery" data-box="1">🎀 Box 2</button>
          <button class="btn secondary mystery" data-box="2">💝 Box 3</button>
        </div>
        <div id="boxOutput" class="output">Pick any gift box!</div>
      </article>
    </div>
  </div>
</section>

<section id="garden">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Compliment Garden</div>
      <h2>Flowers with kind reminders 🌷</h2>
      <p>Tap a flower whenever you need a small reminder that you matter.</p>
    </div>

    <div class="grid">
      <button class="card flower" data-message="🌸 You deserve kindness, including from yourself.">
        <div class="emoji">🌸</div>
        <h3>Flower of kindness</h3>
        <p>Tap to bloom</p>
      </button>

      <button class="card flower" data-message="🌻 Your dreams deserve time, patience and room to grow.">
        <div class="emoji">🌻</div>
        <h3>Flower of dreams</h3>
        <p>Tap to bloom</p>
      </button>

      <button class="card flower" data-message="🌷 You deserve to be appreciated exactly as you are.">
        <div class="emoji">🌷</div>
        <h3>Flower of courage</h3>
        <p>Tap to bloom</p>
      </button>
    </div>

    <div id="flowerOutput" class="output" style="text-align:center">
      🌱 Your kind reminder will appear here.
    </div>
  </div>
</section>

<section id="wishes">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Wish Galaxy</div>
      <h2>A galaxy of future dreams 🌠</h2>
      <p>A little list of things to hope for, try, laugh about, and remember.</p>
    </div>

    <div class="card">
      <div class="wishlist" id="wishlist">
        <span class="wish">🌊 A peaceful day by the sea</span>
        <span class="wish">🍰 Try a new dessert</span>
        <span class="wish">📸 Take silly photos</span>
        <span class="wish">🌧️ Enjoy a rainy evening</span>
        <span class="wish">🎶 Make a shared playlist</span>
        <span class="wish">🌇 Watch a sunset</span>
      </div>

      <form id="wishForm" class="inputrow" style="margin-top:18px">
        <input id="wishInput" placeholder="Add a little dream…" maxlength="90">
        <button class="btn" type="submit">Add wish +</button>
      </form>

      <p class="small">These wishes stay in this browser session; they aren't sent to anyone.</p>
    </div>
  </div>
</section>

<section id="timecapsule">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Time Capsule</div>
      <h2>A note for the future ⏳</h2>
      <p>Write a message for a future version of yourselves.</p>
    </div>

    <div class="card">
      <label for="capsuleText"><b>Dear future us…</b></label>

      <textarea id="capsuleText" rows="5" maxlength="700"
        style="width:100%;margin-top:10px;border:1px solid var(--line);border-radius:18px;padding:15px;background:var(--paper);color:var(--ink);font:inherit"
        placeholder="I hope when we read this, we remember…"></textarea>

      <div class="inputrow" style="margin-top:10px">
        <button class="btn" id="saveCapsule">Save time capsule</button>
        <button class="btn secondary" id="readCapsule">Read saved note</button>
      </div>

      <div id="capsuleOutput" class="output">Your future note will appear here.</div>
      <p class="small">The note is saved in this browser on this device, not sent to anyone.</p>
    </div>
  </div>
</section>

<section id="letter">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Letter Nebula</div>
      <h2>A letter for my Kyuutu 💌</h2>
      <p>A birthday letter you can personalise before sharing the website.</p>
    </div>

    <article class="letter" id="letterText">Dear Anuska, my Kyuutu ♡

Happy birthday! I hope this new year of your life brings you peaceful days, genuine laughter, kind people, exciting little adventures, and the courage to follow the dreams that matter to you.

I made this tiny universe because a normal birthday wish felt too small for everything I wanted to celebrate about you. Every planet is a little reminder to smile, explore, play, remember, and imagine what comes next.

Please remember that you deserve care and respect on ordinary days too—not just on birthdays. Keep being curious, keep growing at your own pace, and never feel that you have to be perfect to be wonderful.

I hope you enjoy exploring this little world as much as I enjoyed making it. Here's to more laughter, more memories, and many new chapters ahead.

Happy birthday, Kyuutu. 🌷

With lots of warm wishes,
Biraja ♡</article>

    <div class="hero-actions">
      <button class="btn" id="typeBtn">✨ Reveal letter slowly</button>
      <button class="btn secondary" id="copyLetter">Copy letter text</button>
    </div>
  </div>
</section>

<section id="birthday">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Birthday Garden</div>
      <h2>Make a little birthday wish 🎂</h2>
      <p>Tap the cake to make the garden sparkle.</p>
    </div>

    <div class="card" style="text-align:center">
      <div class="cake" id="cake">🎂</div>
      <h3 id="cakeTitle">One wish, just for you</h3>
      <p id="cakeText" class="small">Tap the cake to celebrate.</p>
      <button class="btn" id="cakeBtn">✨ Celebrate</button>
    </div>
  </div>
</section>

<section id="finale">
  <div class="wrap">
    <div class="sectionhead">
      <div class="eyebrow">Final Orbit</div>
      <h2>One last little surprise 🎆</h2>
      <p>Before you leave this universe, collect a final message.</p>
    </div>

    <div class="card" style="text-align:center">
      <div class="emoji">💝</div>
      <h3>Dear Kyuutu, this universe was made just for you.</h3>
      <p id="finalMessage">May your next chapter be full of soft mornings, brave dreams, belly laughs, and people who celebrate the real you.</p>
      <button class="btn" id="finalBtn">Open the final surprise ♡</button>
      <div id="finalOutput" class="output hide"></div>
    </div>
  </div>
</section>

</main>

<footer class="footer">
  <div class="wrap">
    <div style="font-size:2rem">♡ ✦ ♡</div>
    <b>Made with care by Biraja Prasad Jena</b>
    <p>A tiny universe for Anuska · 5 October 2026</p>
    <p class="small">A birthday universe made with love and imagination.</p>
  </div>
</footer>

<div id="toast" class="toast" role="status" aria-live="polite"></div>

<script>
const $ = selector => document.querySelector(selector);
const $$ = selector => [...document.querySelectorAll(selector)];

function toast(message) {
  const element = $("#toast");
  element.textContent = message;
  element.classList.add("show");

  setTimeout(() => element.classList.remove("show"), 2600);
}

function sparkles(amount = 14) {
  const symbols = ["💗", "✨", "🌸", "⭐", "🎀", "♡"];

  for (let i = 0; i < amount; i++) {
    const element = document.createElement("span");

    element.className = "spark";
    element.textContent =
      symbols[Math.floor(Math.random() * symbols.length)];

    element.style.left = Math.random() * 100 + "vw";
    element.style.bottom = Math.random() * 12 + "px";
    element.style.fontSize = 14 + Math.random() * 22 + "px";

    document.body.appendChild(element);

    setTimeout(() => element.remove(), 1500);
  }
}

/* Birthday countdown: midnight IST on 5 October 2026 */
function updateCountdown() {
  const birthday = new Date("2026-10-05T00:00:00+05:30").getTime();
  const difference = birthday - Date.now();

  if (difference <= 0) {
    $("#days").textContent = "00";
    $("#hours").textContent = "00";
    $("#mins").textContent = "00";
    $("#secs").textContent = "00";
    return;
  }

  $("#days").textContent =
    String(Math.floor(difference / 86400000)).padStart(2, "0");

  $("#hours").textContent =
    String(Math.floor((difference % 86400000) / 3600000)).padStart(2, "0");

  $("#mins").textContent =
    String(Math.floor((difference % 3600000) / 60000)).padStart(2, "0");

  $("#secs").textContent =
    String(Math.floor((difference % 60000) / 1000)).padStart(2, "0");
}

updateCountdown();
setInterval(updateCountdown, 1000);

/* Day and night theme */
$("#themeBtn").onclick = () => {
  document.body.classList.toggle("night");

  $("#themeBtn").textContent =
    document.body.classList.contains("night")
      ? "☀️ Day mode"
      : "🌙 Night mode";
};

/* Navigate between planets */
$$("[data-go]").forEach(button => {
  button.onclick = () => {
    document.getElementById(button.dataset.go)
      .scrollIntoView({ behavior: "smooth" });
  };
});

/* Surprise button */
$("#surpriseBtn").onclick = () => {
  sparkles(25);
  toast("Surprise! You are the main character of this little universe 💗");
};

/* Hidden-star treasure hunt */
const starMessages = [
  "You make ordinary moments worth remembering. ♡",
  "Your dreams deserve space to grow. 🌷",
  "A little reminder: you are appreciated. ✨",
  "May something lovely surprise you today. 🎀",
  "Keep a little room for wonder. 🌠"
];

const starField = $("#starfield");

for (let i = 0; i < 5; i++) {
  const button = document.createElement("button");

  button.className = "star";
  button.textContent = "☆";
  button.setAttribute("aria-label", "Find star " + (i + 1));

  button.onclick = () => {
    if (button.classList.contains("found")) return;

    button.classList.add("found");
    button.textContent = "★";

    $("#starOutput").textContent = starMessages[i];

    const found = $$(".star.found").length;

    $("#starCount").textContent = found + " of 5 stars found";
    $("#starMeter").style.width = found * 20 + "%";

    if (found === 5) {
      sparkles(20);
      toast("All five stars found! You completed the little galaxy ✨");
    }
  };

  starField.appendChild(button);
}

/* Secret nickname game */
$("#codeForm").onsubmit = event => {
  event.preventDefault();

  const value = $("#secretInput").value.trim().toLowerCase();

  if (value === "kyuutu") {
    $("#codeOutput").textContent =
      "Unlocked! 💗 You deserve to feel celebrated, supported, and appreciated in every season of life.";

    sparkles(12);
  } else {
    $("#codeOutput").textContent =
      "Not quite! Try the nickname from the website title. 🌸";
  }
};

/* Mystery gift boxes */
const boxMessages = [
  "A virtual hug for the day you need one. 🫂",
  "A tiny reminder that your dreams matter. 🌙",
  "A wish for more laughter and lovely surprises. 🎁"
];

$$(".mystery").forEach(button => {
  button.onclick = () => {
    $("#boxOutput").textContent = boxMessages[Number(button.dataset.box)];
    sparkles(8);
  };
});

/* Compliment garden */
$$(".flower").forEach(button => {
  button.onclick = () => {
    $("#flowerOutput").textContent = button.dataset.message;
    sparkles(5);
  };
});

/* Add future dreams */
$("#wishForm").onsubmit = event => {
  event.preventDefault();

  const input = $("#wishInput");
  const value = input.value.trim();

  if (!value) return;

  const item = document.createElement("span");
  item.className = "wish";
  item.textContent = "✨ " + value;

  $("#wishlist").appendChild(item);
  input.value = "";

  toast("A new dream has joined the galaxy 🌠");
};

/* Save a time capsule in this browser */
$("#saveCapsule").onclick = () => {
  try {
    localStorage.setItem(
      "kyuutu-universe-capsule",
      $("#capsuleText").value
    );

    $("#capsuleOutput").textContent =
      "Saved on this browser. Come back to read it whenever you like. ♡";

    toast("Time capsule saved on this device ⏳");
  } catch (error) {
    $("#capsuleOutput").textContent =
      "This browser could not save the note. You can copy it somewhere safe.";
  }
};

$("#readCapsule").onclick = () => {
  try {
    const saved = localStorage.getItem("kyuutu-universe-capsule");

    $("#capsuleOutput").textContent =
      saved || "No saved note yet. Write one above and tap Save.";
  } catch (error) {
    $("#capsuleOutput").textContent =
      "Could not read saved note in this browser.";
  }
};

/* Typewriter birthday letter */
const originalLetter = $("#letterText").textContent;

$("#typeBtn").onclick = () => {
  const element = $("#letterText");
  element.textContent = "";

  let index = 0;

  const timer = setInterval(() => {
    element.textContent += originalLetter[index] || "";
    index++;

    if (index >= originalLetter.length) {
      clearInterval(timer);
    }
  }, 12);
};

/* Copy letter */
$("#copyLetter").onclick = async () => {
  try {
    await navigator.clipboard.writeText(originalLetter);
    toast("Letter copied 💌");
  } catch (error) {
    toast("Select and copy the letter text manually 💗");
  }
};

/* Birthday cake */
let cakeCount = 0;

$("#cakeBtn").onclick = () => {
  cakeCount++;

  const titles = [
    "Make a wish, Kyuutu!",
    "Let the good things find you.",
    "Here's to a bright new chapter!"
  ];

  $("#cakeTitle").textContent =
    titles[Math.min(cakeCount - 1, titles.length - 1)];

  $("#cakeText").textContent =
    "Birthday sparkle number " + cakeCount + " ✨";

  sparkles(18);
};

$("#cake").onclick = () => $("#cakeBtn").click();

/* Final surprise */
$("#finalBtn").onclick = () => {
  $("#finalOutput").classList.remove("hide");

  $("#finalOutput").textContent =
    "Anuska, may you always find reasons to laugh, people who listen, " +
    "places where you feel safe being yourself, and dreams that make you " +
    "excited to wake up. Happy birthday, Kyuutu. With love and warm wishes, Biraja. ♡";

  $("#finalBtn").textContent = "Surprise opened 💗";

  sparkles(35);
};
</script>

</body>
</html>
