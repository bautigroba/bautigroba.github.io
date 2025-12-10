# bautigroba.github.io
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>IMAGINE ORAL EXAM — Escape the Upside Down</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="wrap">
    <header>
      <h1>IMAGINE ORAL EXAM</h1>
      <p class="lead">Stranger Things — themed oral escape room. Speak your answers aloud to progress.</p>
    </header>

    <nav class="route-select">
      <button class="route-btn" data-route="A">Hawkins Lab</button>
      <button class="route-btn" data-route="B">The Arcade</button>
      <button class="route-btn" data-route="C">Byers' House</button>
    </nav>

    <main id="game">
      <!-- Route A panel -->
      <section class="route-panel" id="route-A" aria-hidden="true">
        <h2>Hawkins Lab</h2>
        <div class="step" data-index="0">
          <p class="q">What are your plans for the future?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="1">
          <p class="q">Are you going to study at university after school? anything in mind?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="2">
          <p class="q">Is it better to stay at home while you are in college or to live independently? Why?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="3">
          <p class="q">Recognize and put in order according to your plans the following images.</p>
          <div class="images">
            <!-- replace these with your real images in /images -->
            <img src="images/q4_1.jpg" alt="image 1 for question 4">
            <img src="images/q4_2.jpg" alt="image 2 for question 4">
            <img src="images/q4_3.jpg" alt="image 3 for question 4">
          </div>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="4">
          <p class="q">Which are your 3 least favorite chores at home? why?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="5">
          <p class="q">Would you consider getting a part time job when you get to college ?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="6">
          <p class="q">Which are the differences between make and do?Could you give me some examples?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="7">
          <p class="q">What does “take a break” mean?</p>
          <div class="images">
            <img src="images/q10_1.jpg" alt="image for take a break">
          </div>
          <button class="next">I answered correctly</button>
        </div>
      </section>

      <!-- Route B panel -->
      <section class="route-panel" id="route-B" aria-hidden="true">
        <h2>The Arcade</h2>
        <div class="step" data-index="0">
          <p class="q">Where did you meet your best friend?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="1">
          <p class="q">Which are your favorite things to do with a friend?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="2">
          <p class="q">What makes a good TV show,in your opinion?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="3">
          <p class="q">Do you have a favorite movie? which one?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="4">
          <p class="q">Could you make a top 5 of your favorite movie genres ?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="5">
          <p class="q">Do you exercise? How many times per week?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="6">
          <p class="q">Which are the 3 pieces of advice that you would give someone that wants a healthier life ?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="7">
          <p class="q">Which are the following injuries?</p>
          <div class="images">
            <img src="images/q16_1.jpg" alt="injury 1">
            <img src="images/q16_2.jpg" alt="injury 2">
            <img src="images/q16_3.jpg" alt="injury 3">
          </div>
          <button class="next">I answered correctly</button>
        </div>
      </section>

      <!-- Route C panel -->
      <section class="route-panel" id="route-C" aria-hidden="true">
        <h2>Byers' House</h2>
        <div class="step" data-index="0">
          <p class="q">What can people do to protect the environment?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="1">
          <p class="q">Will you recycle more in the future?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="2">
          <p class="q">Mention 3 things related to renewable energies</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="3">
          <p class="q">Do you consider art important? why?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="4">
          <p class="q">Which kind of art is this one?</p>
          <div class="images">
            <img src="images/q21_1.jpg" alt="art example 1">
            <img src="images/q21_2.jpg" alt="art example 2">
            <img src="images/q21_3.jpg" alt="art example 3">
          </div>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="5">
          <p class="q">Do you have a favorite artist? What do they do?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="6">
          <p class="q">Where did you go in your last vacations?</p>
          <button class="next">I answered correctly</button>
        </div>
        <div class="step" data-index="7">
          <p class="q">If you could travel anywhere, what type of vacation would you choose?</p>
          <button class="finish">Board the train — Escape</button>
        </div>
      </section>

      <!-- Final Screen -->
      <section id="final" class="final" aria-hidden="true">
        <h2>You escaped the Upside Down!</h2>
        <p class="lead">Great job — your spoken answers guided you out. Choose another route to challenge yourself again.</p>
        <div class="final-actions">
          <button class="route-btn" data-route="A">Play Hawkins Lab</button>
          <button class="route-btn" data-route="B">Play The Arcade</button>
          <button class="route-btn" data-route="C">Play Byers' House</button>
        </div>
      </section>
    </main>

    <footer class="footer">
      <small>Questions exactly as provided in your file. (Teacher: listen and validate oral answers.)</small>
    </footer>
  </div>

  <script src="script.js"></script>
</body>
</html>
:root{
  --bg1:#150005;
  --neon:#ff2a2a;
  --neon-soft:#ffdede;
}
*{box-sizing:border-box}
body{margin:0;font-family:Inter, Arial, sans-serif;background:radial-gradient(circle,#1a0000,#050005);color:var(--neon-soft)}
.wrap{max-width:980px;margin:18px auto;padding:16px}
header h1{font-family:'Press Start 2P',monospace;color:var(--neon);text-align:center;text-shadow:0 0 12px var(--neon)}
.lead{text-align:center;font-family:Arial,sans-serif;color:#ffdede;margin-top:8px}
.route-select{display:flex;gap:10px;justify-content:center;margin:18px 0}
.route-btn{background:transparent;border:2px solid var(--neon);color:var(--neon-soft);padding:10px 16px;border-radius:10px;cursor:pointer}
.route-panel{display:none;background:linear-gradient(180deg,rgba(30,0,0,0.9),#050000);padding:18px;border-radius:12px;border:1px solid rgba(255,40,40,0.15);box-shadow:0 20px 40px rgba(0,0,0,0.6)}
.route-panel.active{display:block;animation:appear .35s ease}
.step{display:none;margin-top:12px;border-left:4px solid rgba(255,40,40,0.85);padding-left:12px}
.step.active{display:block}
.q{font-family:Arial,sans-serif;font-size:16px;margin-bottom:8px}
.images{display:flex;gap:10px;flex-wrap:wrap;margin:10px 0}
.images img{width:calc(33% - 10px);border-radius:8px;object-fit:cover;border:2px solid rgba(255,255,255,0.04)}
.next, .finish{background:var(--neon);color:#000;padding:10px 12px;border-radius:8px;border:none;cursor:pointer;font-weight:700}
.final{text-align:center;padding:24px;display:none;background:linear-gradient(180deg,#2a0000,#060006);border-radius:12px;margin-top:18px}
.final.active{display:block}
@keyframes appear{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
@media(max-width:720px){
  .images img{width:100%}
  .q{font-size:15px}
}
// Lightweight controller for progression and routing
document.addEventListener('DOMContentLoaded', ()=>{

  const panels = {
    A: document.getElementById('route-A'),
    B: document.getElementById('route-B'),
    C: document.getElementById('route-C'),
  };
  const final = document.getElementById('final');

  // route buttons
  document.querySelectorAll('.route-btn').forEach(btn=>{
    btn.addEventListener('click', ()=> {
      const r = btn.dataset.route;
      showRoute(r);
    });
  });

  // control next buttons inside each panel
  document.querySelectorAll('.route-panel').forEach(panel=>{
    const steps = Array.from(panel.querySelectorAll('.step'));
    // show first step
    steps.forEach(s=>s.classList.remove('active'));
    if(steps[0]) steps[0].classList.add('active');

    panel.querySelectorAll('.next').forEach((n, idx)=>{
      n.addEventListener('click', ()=>{
        steps[idx].classList.remove('active');
        if(steps[idx+1]) {
          steps[idx+1].classList.add('active');
        } else {
          // end of this panel -> show final
          showFinal();
        }
      });
    });

    // finish button handler (last route)
    panel.querySelectorAll('.finish').forEach(btn=>{
      btn.addEventListener('click', showFinal);
    });
  });

  function hideAll() {
    Object.values(panels).forEach(p=>p.classList.remove('active'));
    final.classList.remove('active');
  }

  function showRoute(r) {
    hideAll();
    const panel = panels[r];
    if(!panel) return;
    panel.classList.add('active');
    // reset steps inside panel to first step
    const steps = Array.from(panel.querySelectorAll('.step'));
    steps.forEach((s,i)=> s.classList.toggle('active', i===0));
    window.scrollTo({top:0, behavior:'smooth'});
  }

  function showFinal() {
    hideAll();
    final.classList.add('active');
    final.scrollIntoView({behavior:'smooth'});
  }

  // default open route A
  showRoute('A');
});

