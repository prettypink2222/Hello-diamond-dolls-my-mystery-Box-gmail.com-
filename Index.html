<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Diamond Doll's Mystery Box</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@400;600;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg: #150a24;
    --bg-2: #1f1136;
    --ice: #8eecff;
    --rose: #ff8fcb;
    --gold: #f7c948;
    --cream: #f6f1fb;
    --muted: #b6a6d6;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background: radial-gradient(circle at 20% 0%, var(--bg-2), var(--bg) 60%);
    color: var(--cream);
    font-family: 'Inter', sans-serif;
    min-height:100vh;
    overflow-x:hidden;
  }
  .eyebrow{
    font-size:0.75rem;
    letter-spacing:0.28em;
    text-transform:uppercase;
    color: var(--gold);
    font-weight:600;
  }
  h1,h2,h3{ font-family:'Unbounded', sans-serif; }
  nav{
    display:flex; justify-content:space-between; align-items:center;
    padding: 1.5rem 6vw;
  }
  nav .logo{ font-family:'Unbounded'; font-weight:800; font-size:1.1rem; letter-spacing:0.02em; }
  nav .logo span{ color: var(--rose); }
  nav a.cta{
    border:1px solid var(--ice); color:var(--ice);
    padding:0.5rem 1.1rem; border-radius:999px;
    text-decoration:none; font-size:0.85rem; font-weight:500;
    transition: all 0.25s ease;
  }
  nav a.cta:hover{ background:var(--ice); color:var(--bg); }
  .hero{
    display:flex; flex-direction:column; align-items:center; text-align:center;
    padding: 4rem 6vw 3rem;
    position:relative;
  }
  .hero h1{
    font-size: clamp(2.4rem, 7vw, 4.4rem);
    line-height:1.05;
    margin: 1rem 0 1rem;
    background: linear-gradient(100deg, var(--cream) 20%, var(--ice) 45%, var(--rose) 65%, var(--gold) 85%);
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
  }
  .hero p.sub{
    max-width: 34rem;
    color: var(--muted);
    font-size:1.05rem;
    margin-bottom: 2.5rem;
  }
  .box-wrap{
    perspective: 900px;
    margin: 1rem 0 2.5rem;
  }
  .box{
    width: 190px; height:190px;
    position:relative;
    cursor:pointer;
    transform-style:preserve-3d;
    transition: transform 0.6s cubic-bezier(.2,.8,.3,1.2);
  }
  .box.open{ transform: rotateX(-18deg) rotateY(18deg) scale(1.06); }
  .box .face{
    position:absolute; inset:0;
    border-radius:18px;
    background: linear-gradient(145deg, #2a1748, #170b2b);
    border:1px solid rgba(255,255,255,0.08);
    box-shadow: 0 20px 60px rgba(0,0,0,0.45);
  }
  .box .facet{
    position:absolute; inset:0;
    border-radius:18px;
    background: conic-gradient(from 220deg, var(--ice), var(--rose), var(--gold), var(--ice));
    opacity:0.14;
    mix-blend-mode: screen;
    animation: spin 7s linear infinite;
  }
  @keyframes spin{ to{ transform: rotate(360deg);} }
  .box .ribbon{
    position:absolute; inset:0;
    background:
      linear-gradient(90deg, transparent 46%, var(--gold) 46%, var(--gold) 54%, transparent 54%),
      linear-gradient(0deg, transparent 46%, var(--gold) 46%, var(--gold) 54%, transparent 54%);
    border-radius:18px;
    transition: opacity 0.4s ease;
  }
  .box.open .ribbon{ opacity:0; }
  .box .glow{
    position:absolute; inset:-40px;
    border-radius:50%;
    background: radial-gradient(circle, rgba(255,255,255,0.55), transparent 60%);
    opacity:0;
    transition: opacity 0.5s ease;
    pointer-events:none;
  }
  .box.open .glow{ opacity:1; }
  .hint{ font-size:0.85rem; color: var(--muted); margin-top:0.75rem; letter-spacing:0.03em;}
  .inside{
    padding: 3rem 6vw 4rem;
    max-width: 1000px;
    margin: 0 auto;
  }
  .inside h2{
    font-size: clamp(1.6rem, 4vw, 2.2rem);
    text-align:center;
    margin-bottom: 2.5rem;
  }
  .grid{
    display:grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.25rem;
  }
  .card{
    background: rgba(255,255,255,0.03);
    border:1px solid rgba(255,255,255,0.07);
    border-radius: 16px;
    padding: 1.6rem;
    transition: transform 0.25s ease, border-color 0.25s ease;
  }
  .card:hover{ transform: translateY(-4px); border-color: rgba(255,255,255,0.18); }
  .card .mark{ font-family:'Unbounded'; font-size:0.85rem; color:var(--rose); margin-bottom:0.6rem; display:block; }
  .card h3{ font-size:1.1rem; margin-bottom:0.5rem; font-weight:600; }
  .card p{ color: var(--muted); font-size:0.92rem; line-height:1.5; }
  footer{
    text-align:center;
    padding: 3rem 6vw 4rem;
    border-top: 1px solid rgba(255,255,255,0.06);
    margin-top: 2rem;
  }
  footer h2{ font-size: clamp(1.4rem, 4vw, 2rem); margin-bottom:1rem; }
  .buy{
    display:inline-block;
    margin-top:1rem;
    background: linear-gradient(100deg, var(--rose), var(--gold));
    color:#1a0f2e;
    font-weight:600;
    padding: 0.9rem 2rem;
    border-radius: 999px;
    text-decoration:none;
    font-size:0.95rem;
    transition: filter 0.25s ease;
  }
  .buy:hover{ filter:brightness(1.08); }
  .foot-note{ color:var(--muted); font-size:0.8rem; margin-top:2rem; }
  @media (prefers-reduced-motion: reduce){
    *{ animation:none !important; transition:none !important; }
  }
</style>
</head>
<body>

<nav>
  <div class="logo">Diamond<span>Doll</span></div>
  <a class="cta" href="#reveal">Get a Box</a>
</nav>

<section class="hero">
  <span class="eyebrow">Limited Drop · One Box, One Surprise</span>
  <h1>The Mystery Box<br>Worth Unwrapping</h1>
  <p class="sub">Every box is sealed by hand and hides a curated set of jewelry, beauty, and charm pieces. You won't know what's inside until you open it — that's the whole point.</p>

  <div class="box-wrap" id="reveal">
    <div class="box" id="box">
      <div class="glow"></div>
      <div class="face"></div>
      <div class="facet"></div>
      <div class="ribbon"></div>
    </div>
  </div>
  <p class="hint" id="hint">Tap the box to open it</p>
</section>

<section class="inside">
  <h2>What might be inside</h2>
  <div class="grid">
    <div class="card">
      <span class="mark">01</span>
      <h3>Signature Charm</h3>
      <p>A hand-picked pendant or charm, never repeated across two boxes in the same month.</p>
    </div>
    <div class="card">
      <span class="mark">02</span>
      <h3>Sparkle Pick</h3>
      <p>A small piece of statement jewelry — rings, studs, or a bracelet — chosen for shine.</p>
    </div>
    <div class="card">
      <span class="mark">03</span>
      <h3>Beauty Extra</h3>
      <p>A mini beauty or self-care item that pairs with the season's box theme.</p>
    </div>
    <div class="card">
      <span class="mark">04</span>
      <h3>Doll's Note</h3>
      <p>A handwritten card explaining the story behind this box's theme.</p>
    </div>
  </div>
</section>

<footer>
  <h2>Ready for your box?</h2>
  <p class="foot-note" style="margin-top:0;">Boxes restock in limited batches — once they're gone, that theme is gone for good.</p>
  <a class="buy" href="#">Claim This Month's Box</a>
  <p class="foot-note">Diamond Doll's Mystery Box · Made with sparkle</p>
</footer>

<script>
  const box = document.getElementById('box');
  const hint = document.getElementById('hint');
  let opened = false;
  box.addEventListener('click', () => {
    opened = !opened;
    box.classList.toggle('open', opened);
    hint.textContent = opened ? "It's open — tap again to seal it back up" : "Tap the box to open it";
  });
</script>

</body>
</html>
