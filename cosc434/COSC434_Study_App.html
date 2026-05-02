<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>COSC434 Exam Prep</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0a0a0f;
  --surface:#12121a;
  --surface2:#1a1a26;
  --border:#2a2a3d;
  --accent:#7c6af7;
  --accent2:#f76a8a;
  --accent3:#6af7c8;
  --text:#e8e8f0;
  --text-dim:#7a7a9a;
  --correct:#4ade80;
  --wrong:#f87171;
  --warning:#f7c06a;
  --mono:'Space Mono',monospace;
  --sans:'Syne',sans-serif;
}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--bg);color:var(--text);font-family:var(--sans);min-height:100vh;overflow-x:hidden;}
body::before{content:'';position:fixed;inset:0;background-image:linear-gradient(rgba(124,106,247,.03) 1px,transparent 1px),linear-gradient(90deg,rgba(124,106,247,.03) 1px,transparent 1px);background-size:40px 40px;pointer-events:none;z-index:0;}
nav{position:sticky;top:0;z-index:100;background:rgba(10,10,15,.92);backdrop-filter:blur(20px);border-bottom:1px solid var(--border);padding:0 1.5rem;display:flex;align-items:center;}
.nav-logo{font-family:var(--mono);font-size:.82rem;color:var(--accent);padding:1rem 1.25rem 1rem 0;border-right:1px solid var(--border);margin-right:.75rem;white-space:nowrap;}
.nav-tabs{display:flex;overflow-x:auto;scrollbar-width:none;}
.nav-tabs::-webkit-scrollbar{display:none;}
.nav-tab{padding:1rem 1rem;font-size:.78rem;font-weight:700;letter-spacing:.05em;text-transform:uppercase;color:var(--text-dim);cursor:pointer;border-bottom:2px solid transparent;transition:all .2s;white-space:nowrap;}
.nav-tab:hover{color:var(--text);}
.nav-tab.active{color:var(--accent);border-bottom-color:var(--accent);}
.page{display:none;padding:2rem;max-width:960px;margin:0 auto;position:relative;z-index:1;}
.page.active{display:block;animation:fadeIn .3s ease;}
@keyframes fadeIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:translateY(0)}}
.page-header{margin-bottom:2rem;padding-bottom:1.5rem;border-bottom:1px solid var(--border);}
.page-header h1{font-size:2rem;font-weight:800;background:linear-gradient(135deg,var(--accent),var(--accent2));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;margin-bottom:.3rem;}
.page-header p{color:var(--text-dim);font-size:.88rem;line-height:1.5;}
.hero{background:linear-gradient(135deg,rgba(124,106,247,.1),rgba(247,106,138,.1));border:1px solid var(--border);border-radius:16px;padding:2rem;margin-bottom:2rem;position:relative;overflow:hidden;}
.hero::after{content:'COSC434';position:absolute;right:-5px;top:50%;transform:translateY(-50%);font-size:7rem;font-weight:800;color:rgba(124,106,247,.05);font-family:var(--mono);pointer-events:none;}
.hero h2{font-size:1.5rem;font-weight:800;margin-bottom:.4rem;}
.hero p{color:var(--text-dim);max-width:520px;line-height:1.6;font-size:.9rem;}
.home-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1rem;margin-top:1rem;}
.home-card{background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:1.5rem;cursor:pointer;transition:all .25s;position:relative;overflow:hidden;}
.home-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:var(--ca,var(--accent));transform:scaleX(0);transition:transform .3s;transform-origin:left;}
.home-card:hover{transform:translateY(-3px);border-color:var(--ca,var(--accent));}
.home-card:hover::before{transform:scaleX(1);}
.home-card .icon{font-size:1.8rem;margin-bottom:.6rem;}
.home-card h3{font-size:.95rem;font-weight:700;margin-bottom:.35rem;}
.home-card p{color:var(--text-dim);font-size:.8rem;line-height:1.5;}
.home-card .badge{display:inline-block;margin-top:.6rem;padding:.15rem .55rem;background:rgba(124,106,247,.12);border:1px solid rgba(124,106,247,.25);border-radius:20px;font-size:.7rem;color:var(--accent);font-family:var(--mono);}
.fc-controls{display:flex;gap:.75rem;align-items:center;margin-bottom:1.5rem;flex-wrap:wrap;}
.fc-filters{display:flex;gap:.4rem;flex-wrap:wrap;}
.filter-btn{padding:.3rem .7rem;border:1px solid var(--border);border-radius:20px;background:transparent;color:var(--text-dim);font-family:var(--sans);font-size:.75rem;cursor:pointer;transition:all .2s;}
.filter-btn:hover,.filter-btn.active{background:var(--accent);border-color:var(--accent);color:#fff;}
.fc-prog{font-family:var(--mono);font-size:.78rem;color:var(--text-dim);margin-left:auto;}
.flashcard-wrap{perspective:1200px;height:300px;margin-bottom:1.5rem;cursor:pointer;}
.flashcard{width:100%;height:100%;position:relative;transform-style:preserve-3d;transition:transform .55s cubic-bezier(.4,0,.2,1);}
.flashcard.flipped{transform:rotateY(180deg);}
.fc-face{position:absolute;inset:0;backface-visibility:hidden;border-radius:16px;padding:2rem;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center;border:1px solid var(--border);}
.fc-front{background:var(--surface);}
.fc-back{background:linear-gradient(135deg,var(--surface),rgba(124,106,247,.08));transform:rotateY(180deg);border-color:rgba(124,106,247,.3);}
.fc-tag,.q-cat{font-family:var(--mono);font-size:.68rem;color:var(--accent);letter-spacing:.1em;text-transform:uppercase;margin-bottom:.8rem;padding:.15rem .55rem;border:1px solid rgba(124,106,247,.3);border-radius:20px;display:inline-block;}
.fc-q{font-size:1.2rem;font-weight:700;line-height:1.4;max-width:620px;}
.fc-hint{margin-top:.8rem;font-size:.75rem;color:var(--text-dim);font-family:var(--mono);}
.fc-ans{font-size:.95rem;line-height:1.65;max-width:650px;}
.fc-ans strong,.explanation strong{color:var(--accent3);}
code{background:rgba(106,247,200,.1);color:var(--accent3);padding:.1em .35em;border-radius:4px;font-family:var(--mono);font-size:.88em;}
.fc-nav{display:flex;gap:.75rem;justify-content:center;align-items:center;flex-wrap:wrap;}
.btn{padding:.55rem 1.2rem;border-radius:8px;border:1px solid var(--border);background:var(--surface2);color:var(--text);font-family:var(--sans);font-size:.82rem;font-weight:700;cursor:pointer;transition:all .2s;}
.btn:hover{border-color:var(--accent);color:var(--accent);}
.btn.primary{background:var(--accent);border-color:var(--accent);color:#fff;}
.btn.primary:hover{opacity:.85;color:#fff;}
.btn.danger{background:rgba(248,113,113,.1);border-color:var(--wrong);color:var(--wrong);}
.btn:disabled{opacity:.45;cursor:not-allowed;}
.quiz-meta{display:flex;gap:.75rem;margin-bottom:1.25rem;flex-wrap:wrap;}
.quiz-stat{background:var(--surface);border:1px solid var(--border);border-radius:8px;padding:.4rem .85rem;font-family:var(--mono);font-size:.75rem;}
.quiz-stat span{color:var(--accent);font-weight:700;}
.prog-bar{height:3px;background:var(--surface2);border-radius:2px;margin-bottom:1.25rem;overflow:hidden;}
.prog-fill{height:100%;background:linear-gradient(90deg,var(--accent),var(--accent2));border-radius:2px;transition:width .4s ease;}
.q-card{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:1.75rem;margin-bottom:1.25rem;}
.q-text{font-size:1.05rem;font-weight:600;line-height:1.5;margin-bottom:1.25rem;}
.q-code{background:rgba(10,10,15,.85);border:1px solid var(--border);border-radius:8px;padding:.9rem;font-family:var(--mono);font-size:.78rem;color:var(--accent3);margin-bottom:1.25rem;line-height:1.6;white-space:pre-wrap;overflow-x:auto;}
.options{display:flex;flex-direction:column;gap:.55rem;}
.option{padding:.8rem 1.1rem;border:1px solid var(--border);border-radius:10px;background:var(--surface2);cursor:pointer;transition:all .2s;font-size:.88rem;line-height:1.4;display:flex;align-items:flex-start;gap:.7rem;}
.option:hover:not(.locked){border-color:var(--accent);background:rgba(124,106,247,.08);}
.option .ol{font-family:var(--mono);font-size:.72rem;color:var(--text-dim);min-width:18px;margin-top:2px;}
.option.correct{border-color:var(--correct);background:rgba(74,222,128,.08);color:var(--correct);}
.option.wrong{border-color:var(--wrong);background:rgba(248,113,113,.08);color:var(--wrong);}
.explanation{margin-top:.9rem;padding:.9rem 1.1rem;background:rgba(124,106,247,.06);border-left:3px solid var(--accent);border-radius:0 8px 8px 0;font-size:.85rem;line-height:1.6;color:var(--text-dim);display:none;}
.explanation.show{display:block;animation:fadeIn .3s ease;}
.results-card{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:2.5rem;text-align:center;}
.score-circle{width:110px;height:110px;border-radius:50%;background:conic-gradient(var(--accent) calc(var(--pct)*1%),var(--surface2) 0);display:flex;align-items:center;justify-content:center;margin:0 auto 1.25rem;position:relative;}
.score-circle::before{content:'';position:absolute;inset:8px;border-radius:50%;background:var(--surface);}
.score-num{position:relative;z-index:1;font-family:var(--mono);font-size:1.2rem;font-weight:700;color:var(--accent);}
.exam-hdr{background:linear-gradient(135deg,rgba(247,106,138,.1),rgba(124,106,247,.1));border:1px solid rgba(247,106,138,.2);border-radius:12px;padding:1.25rem;margin-bottom:1.25rem;display:flex;align-items:center;gap:1.25rem;flex-wrap:wrap;}
.exam-hdr h2{font-size:1.1rem;font-weight:700;margin-bottom:.2rem;}
.exam-hdr p{font-size:.82rem;color:var(--text-dim);}
.exam-timer{margin-left:auto;font-family:var(--mono);font-size:1.3rem;font-weight:700;color:var(--accent2);background:rgba(247,106,138,.1);border:1px solid rgba(247,106,138,.2);padding:.4rem .85rem;border-radius:8px;}
.exam-timer.warn{color:var(--wrong);border-color:var(--wrong);background:rgba(248,113,113,.1);}
.type-pill{font-family:var(--mono);font-size:.68rem;color:#fff;background:rgba(247,106,138,.2);border:1px solid rgba(247,106,138,.35);padding:.15rem .55rem;border-radius:20px;text-transform:uppercase;display:inline-block;margin-left:.4rem;}
.answer-box{width:100%;min-height:120px;background:var(--surface2);border:1px solid var(--border);border-radius:10px;color:var(--text);padding:1rem;font-family:var(--sans);font-size:.9rem;line-height:1.5;resize:vertical;outline:none;}
.answer-box:focus{border-color:var(--accent);box-shadow:0 0 0 3px rgba(124,106,247,.12);}
.order-list{display:flex;flex-direction:column;gap:.6rem;}
.order-item{display:flex;align-items:center;gap:.75rem;background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:.75rem;}
.order-text{flex:1;font-size:.88rem;line-height:1.45;}
.order-controls{display:flex;gap:.35rem;}
.tiny-btn{width:30px;height:30px;border-radius:8px;border:1px solid var(--border);background:rgba(255,255,255,.03);color:var(--text);cursor:pointer;font-weight:700;}
.tiny-btn:hover{border-color:var(--accent);color:var(--accent);}
.match-grid{display:grid;grid-template-columns:1fr 1.3fr;gap:.75rem;align-items:center;}
.match-term{background:var(--surface2);border:1px solid var(--border);border-radius:10px;padding:.8rem;font-weight:700;font-size:.88rem;}
.match-select{width:100%;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:10px;padding:.75rem;font-family:var(--sans);outline:none;}
.match-select:focus{border-color:var(--accent);}
.cheat-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(360px,1fr));gap:1rem;}
.cc{background:var(--surface);border:1px solid var(--border);border-radius:12px;overflow:hidden;}
.cc-hdr{padding:.6rem 1.1rem;background:var(--surface2);border-bottom:1px solid var(--border);font-size:.75rem;font-weight:700;letter-spacing:.05em;text-transform:uppercase;color:var(--accent);font-family:var(--mono);}
.cc-body{padding:1.1rem;}
.ct{width:100%;border-collapse:collapse;font-size:.8rem;}
.ct th{padding:.45rem .65rem;background:rgba(124,106,247,.1);color:var(--accent);font-family:var(--mono);font-size:.7rem;text-align:left;border-bottom:1px solid var(--border);}
.ct td{padding:.45rem .65rem;border-bottom:1px solid rgba(42,42,61,.5);line-height:1.4;vertical-align:top;}
.ct tr:last-child td{border-bottom:none;}
.dl{list-style:none;}
.dl li{padding:.5rem 0;border-bottom:1px solid rgba(42,42,61,.5);font-size:.83rem;line-height:1.5;}
.dl li:last-child{border-bottom:none;}
.dl li strong{color:var(--accent3);font-family:var(--mono);font-size:.76rem;display:block;margin-bottom:.15rem;}
::-webkit-scrollbar{width:5px;height:5px;}
::-webkit-scrollbar-track{background:var(--bg);}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:3px;}
@media(max-width:700px){.page{padding:1rem}.flashcard-wrap{height:280px}.cheat-grid,.match-grid{grid-template-columns:1fr}.exam-timer{margin-left:0}.hero::after{display:none}}
</style>
</head>
<body>
<nav>
  <div class="nav-logo">COSC434</div>
  <div class="nav-tabs">
    <div class="nav-tab active" onclick="goTo('home')">Home</div>
    <div class="nav-tab" onclick="goTo('flashcards')">Flashcards</div>
    <div class="nav-tab" onclick="goTo('quiz')">Quick Quiz</div>
    <div class="nav-tab" onclick="goTo('exam')">Mock Exam</div>
    <div class="nav-tab" onclick="goTo('cheat')">Cheat Sheet</div>
  </div>
</nav>

<div class="page active" id="page-home">
  <div class="hero">
    <h2>Advanced Web Programming — Exam Prep</h2>
    <p>Study with flashcards, instant quizzes, a mixed-format final exam, and a compact cheat sheet covering PHP, Laravel, MVC, Blade, AJAX, databases, APIs, security, and performance.</p>
  </div>
  <div class="home-grid">
    <div class="home-card" style="--ca:var(--accent)" onclick="goTo('flashcards')">
      <div class="icon">🃏</div><h3>Flashcards</h3>
      <p>Flip cards covering definitions, comparisons, and important Laravel concepts.</p>
      <div class="badge">Topic filters</div>
    </div>
    <div class="home-card" style="--ca:var(--accent3)" onclick="goTo('quiz')">
      <div class="icon">⚡</div><h3>Quick Quiz</h3>
      <p>Multiple choice practice with instant feedback and detailed explanations.</p>
      <div class="badge">Fast review</div>
    </div>
    <div class="home-card" style="--ca:var(--accent2)" onclick="goTo('exam')">
      <div class="icon">📝</div><h3>Mock Exam</h3>
      <p>Mixed final exam with MCQ, short answer, ordering, matching, and scenarios.</p>
      <div class="badge">35 q · 40 min</div>
    </div>
    <div class="home-card" style="--ca:var(--warning)" onclick="goTo('cheat')">
      <div class="icon">📋</div><h3>Cheat Sheet</h3>
      <p>Quick tables and definitions for last-minute review.</p>
      <div class="badge">Reference</div>
    </div>
  </div>
</div>

<div class="page" id="page-flashcards">
  <div class="page-header"><h1>Flashcards</h1><p>Click the card to flip. Filter by topic or shuffle for random practice.</p></div>
  <div class="fc-controls">
    <div class="fc-filters" id="fc-filters"></div>
    <div class="fc-prog" id="fc-prog"></div>
  </div>
  <div class="flashcard-wrap" onclick="flipCard()">
    <div class="flashcard" id="flashcard">
      <div class="fc-face fc-front"><div class="fc-tag" id="fc-tag"></div><div class="fc-q" id="fc-q"></div><div class="fc-hint">click to flip</div></div>
      <div class="fc-face fc-back"><div class="fc-ans" id="fc-ans"></div></div>
    </div>
  </div>
  <div class="fc-nav">
    <button class="btn" onclick="prevCard()">← Prev</button>
    <button class="btn" onclick="shuffleCards()">Shuffle</button>
    <button class="btn primary" onclick="nextCard()">Next →</button>
  </div>
</div>

<div class="page" id="page-quiz">
  <div class="page-header"><h1>Quick Quiz</h1><p>Select an answer for instant feedback.</p></div>
  <div id="quiz-container"></div>
</div>

<div class="page" id="page-exam">
  <div class="page-header"><h1>Mock Final Exam</h1><p>40 minutes · mixed question types · immediate marking after each question.</p></div>
  <div id="exam-container"></div>
</div>

<div class="page" id="page-cheat">
  <div class="page-header"><h1>Cheat Sheet</h1><p>Key comparisons and definitions at a glance.</p></div>
  <div class="cheat-grid" id="cheat-grid"></div>
</div>

<script>
const FC = [
  {tag:'Web Fundamentals',q:'What does SSR mean?',a:'<strong>Server-Side Rendering</strong>: the server builds and returns complete HTML. Good first load and SEO.'},
  {tag:'Web Fundamentals',q:'What does CSR mean?',a:'<strong>Client-Side Rendering</strong>: the browser receives a shell and JavaScript builds the UI. Great for interactive apps.'},
  {tag:'Web Fundamentals',q:'Website vs web application?',a:'A <strong>website</strong> mainly displays information. A <strong>web application</strong> lets users create, edit, delete, and interact with data.'},
  {tag:'HTTP & AJAX',q:'GET vs POST?',a:'<strong>GET</strong> retrieves data and puts parameters in the URL. <strong>POST</strong> sends data in the request body and is used for creating/submitting data.'},
  {tag:'HTTP & AJAX',q:'What is AJAX?',a:'AJAX lets JavaScript exchange data with the server without reloading the whole page. The server usually returns JSON.'},
  {tag:'Database & PDO',q:'What is a prepared statement?',a:'A safe SQL method where query structure and user values are separated. It prevents <strong>SQL injection</strong>.'},
  {tag:'Database & PDO',q:'fetch() vs fetchAll()?',a:'<code>fetch()</code> returns one row. <code>fetchAll()</code> returns all rows as an array.'},
  {tag:'Database & PDO',q:'What is the N+1 problem?',a:'One query fetches N records, then N extra queries load related data inside a loop. Fix with eager loading.'},
  {tag:'MVC & Laravel',q:'What does MVC stand for?',a:'<strong>Model-View-Controller</strong>: Model handles data, View handles presentation, Controller coordinates requests and responses.'},
  {tag:'MVC & Laravel',q:'What does $fillable do?',a:'It lists fields allowed for mass assignment, preventing users from submitting unsafe fields like <code>is_admin</code>.'},
  {tag:'Blade',q:'{{ }} vs {!! !!}?',a:'<code>{{ }}</code> escapes output and protects against XSS. <code>{!! !!}</code> outputs raw HTML and should only be used with trusted content.'},
  {tag:'Blade',q:'What does @csrf do?',a:'It adds a hidden CSRF token field to forms. Laravel checks it on POST/PUT/DELETE requests.'},
  {tag:'Eloquent',q:'hasMany() vs belongsTo()?',a:'<code>hasMany()</code> means one model owns many related records. <code>belongsTo()</code> is the inverse relationship.'},
  {tag:'Eloquent',q:'attach() vs sync()?',a:'<code>attach()</code> adds pivot rows. <code>sync()</code> replaces pivot rows to exactly match the new set.'},
  {tag:'Auth & Security',q:'Authentication vs authorization?',a:'Authentication verifies who the user is. Authorization checks what the user is allowed to do.'},
  {tag:'Performance',q:'What are Laravel queues?',a:'Queues store background jobs so slow work like emails or image processing does not block the HTTP response.'}
];

const QQ = [
  {cat:'Web Fundamentals',q:'Which approach sends a full HTML page from the server?',opts:['CSR','SSR','AJAX','JSON API'],ans:1,exp:'SSR builds the page on the server and returns complete HTML.'},
  {cat:'HTTP & AJAX',q:'Which method places form data in the URL?',opts:['POST','PUT','GET','DELETE'],ans:2,exp:'GET sends parameters in the URL query string.'},
  {cat:'Database & PDO',q:'What prevents SQL injection?',opts:['Raw query strings','Prepared statements','HTML forms','CSS validation'],ans:1,exp:'Prepared statements separate SQL structure from user data.'},
  {cat:'MVC & Laravel',q:'Which MVC part handles database logic?',opts:['View','Controller','Model','Route'],ans:2,exp:'The Model represents data and database/business logic.'},
  {cat:'Blade',q:'What does @yield do?',opts:['Creates a route','Defines a layout placeholder','Submits a form','Runs SQL'],ans:1,exp:'@yield marks a section in a master layout that child views fill.'},
  {cat:'Eloquent',q:'Which method fixes N+1?',opts:['with()','attach()','csrf()','route()'],ans:0,exp:'with() eager-loads related models.'},
  {cat:'Auth & Security',q:'Logged in user tries to delete another user\'s recipe. What check is needed?',opts:['Authentication','Ownership authorization','CSS escaping','GET request'],ans:1,exp:'Ownership ensures users only modify their own data.'},
  {cat:'Performance',q:'Why use queues?',opts:['To make HTML prettier','To delay slow tasks into background jobs','To replace databases','To remove routes'],ans:1,exp:'Queues let slow tasks run after the response is returned.'}
];

const EXAM = [
  {type:'mcq',cat:'Web Fundamentals',q:'A Laravel Blade app returns complete HTML pages for each navigation. What rendering style is this closest to?',opts:['CSR','SSR','AJAX-only rendering','Mobile rendering'],ans:1,exp:'Returning complete HTML from the server is server-side rendering.'},
  {type:'mcq',cat:'HTTP & AJAX',q:'A form sends username and password. Which method should it use?',opts:['GET','POST','DELETE','HEAD'],ans:1,exp:'Sensitive data should be sent in the request body with POST, not exposed in the URL.'},
  {type:'mcq',cat:'Database & PDO',q:'Which code style is safest for user input?',opts:['Concatenate input into SQL','Use prepare() and execute()','Trust hidden inputs','Only validate with CSS'],ans:1,exp:'Prepared statements keep user values separate from SQL code.'},
  {type:'mcq',cat:'MVC & Laravel',q:'What does Route::apiResource() exclude compared to Route::resource()?',opts:['index and show','store and update','create and edit','destroy only'],ans:2,exp:'API resources exclude create/edit because APIs do not serve HTML forms.'},
  {type:'mcq',cat:'Blade',q:'Which Blade output is safer for user content?',opts:['{!! $text !!}','{{ $text }}','<?php echo $text ?>','@raw($text)'],ans:1,exp:'{{ }} escapes HTML and helps prevent XSS.'},
  {type:'mcq',cat:'Eloquent',q:'When updating a recipe\'s tags, which method should usually be used?',opts:['attach()','sync()','fetchAll()','yield()'],ans:1,exp:'sync() replaces the pivot table rows to match the submitted tag list.'},
  {type:'mcq',cat:'Auth & Security',q:'What does authorization answer?',opts:['Who are you?','What can you do?','What is your password?','What database is used?'],ans:1,exp:'Authorization checks permissions after the user is authenticated.'},
  {type:'mcq',cat:'Performance',q:'What does a queue worker do?',opts:['Defines routes','Executes queued jobs in the background','Creates Blade templates','Encrypts passwords'],ans:1,exp:'A worker continuously takes jobs from the queue and processes them.'},

  {type:'short',cat:'Web Fundamentals',q:'Explain the difference between a website and a web application in 1–3 sentences.',keywords:['website','web application','interactive','data'],sample:'A website mainly displays information, while a web application is interactive and lets users create, edit, delete, or manage data.'},
  {type:'short',cat:'Database & PDO',q:'Why do prepared statements prevent SQL injection?',keywords:['separate','placeholder','input','sql'],sample:'Prepared statements send the SQL structure with placeholders first, then send user input separately. The database treats input as data, not executable SQL.'},
  {type:'short',cat:'MVC & Laravel',q:'What is the role of a controller in MVC?',keywords:['request','model','view','response'],sample:'A controller receives the request, asks the model for data or business logic, then returns a view or JSON response.'},
  {type:'short',cat:'Blade',q:'Why should {!! $var !!} be used carefully?',keywords:['raw','unescaped','xss','trusted'],sample:'It outputs raw unescaped HTML, so malicious scripts could run if the content is not trusted. {{ }} is safer for user content.'},
  {type:'short',cat:'Auth & Security',q:'Explain authentication vs authorization.',keywords:['identity','permission','who','allowed'],sample:'Authentication verifies identity, meaning who the user is. Authorization checks permissions, meaning what the user is allowed to do.'},

  {type:'order',cat:'HTTP & AJAX',q:'Arrange the AJAX flow in the correct order.',items:['JavaScript updates part of the page','Server processes the request','User triggers an event','JavaScript sends request to server','Server returns JSON'],answer:['User triggers an event','JavaScript sends request to server','Server processes the request','Server returns JSON','JavaScript updates part of the page'],exp:'AJAX starts from a browser event, sends a background request, gets JSON back, then updates the UI without a full reload.'},
  {type:'order',cat:'MVC & Laravel',q:'Arrange the Laravel request lifecycle.',items:['Controller handles logic','Browser sends request','Route matches URL','Middleware checks request','Response is returned'],answer:['Browser sends request','Route matches URL','Middleware checks request','Controller handles logic','Response is returned'],exp:'A request enters Laravel, matches a route, passes middleware, reaches the controller, then returns a response.'},
  {type:'order',cat:'Database & PDO',q:'Arrange the prepared statement process.',items:['Execute with user values','Write SQL with placeholders','Database returns result','Prepare the SQL statement'],answer:['Write SQL with placeholders','Prepare the SQL statement','Execute with user values','Database returns result'],exp:'Prepared statements are written with placeholders, prepared, executed with values, then results are returned.'},
  {type:'order',cat:'Auth & Security',q:'Arrange a basic Fortify registration flow.',items:['Hash password','Validate input','Start authenticated session','Save user to database'],answer:['Validate input','Hash password','Save user to database','Start authenticated session'],exp:'Good registration validates first, hashes the password, saves the user, then logs the user in by starting a session.'},
  {type:'order',cat:'Eloquent',q:'Arrange many-to-many setup steps.',items:['Use belongsToMany() in both models','Create pivot table','Use attach() or sync()','Create the two main tables'],answer:['Create the two main tables','Create pivot table','Use belongsToMany() in both models','Use attach() or sync()'],exp:'The models need tables first, then a pivot table, then relationship methods, then attach/sync for pivot records.'},

  {type:'match',cat:'Web Fundamentals',q:'Match each concept to its definition.',pairs:[['SSR','Server returns complete HTML'],['CSR','Browser JavaScript builds the UI'],['AJAX','Updates part of page without full reload'],['GET','Sends data in URL'],['POST','Sends data in request body']]},
  {type:'match',cat:'MVC & Laravel',q:'Match each MVC part to its job.',pairs:[['Model','Handles data and business logic'],['View','Displays the UI'],['Controller','Receives request and returns response'],['Route','Maps URL to controller/action']]},
  {type:'match',cat:'Blade',q:'Match each Blade directive/syntax to its purpose.',pairs:[['@extends','Inherits a master layout'],['@yield','Creates a layout placeholder'],['@section','Fills a layout section'],['@include','Inserts a partial view'],['@csrf','Adds CSRF token field']]},
  {type:'match',cat:'Eloquent',q:'Match each relationship/tool to its meaning.',pairs:[['hasMany','One model owns many records'],['belongsTo','Current model belongs to one parent'],['belongsToMany','Many-to-many relationship'],['pivot table','Junction table for many-to-many'],['sync','Replaces pivot rows with new set']]},
  {type:'match',cat:'Performance',q:'Match queue terms to definitions.',pairs:[['Job','Single unit of background work'],['Queue','Waiting list of jobs'],['Worker','Process that executes jobs'],['Dispatch','Send job to queue']]},

  {type:'scenario',cat:'Database & PDO',q:'A developer writes: SELECT * FROM users WHERE email = " + userInput. Identify the problem and the fix.',keywords:['sql injection','prepared','placeholder','execute'],sample:'The problem is SQL injection because user input is directly inserted into SQL. The fix is to use a prepared statement with placeholders and execute the query with separate values.'},
  {type:'scenario',cat:'Eloquent',q:'A page loads 100 recipes, then inside a loop it accesses $recipe->category. What problem may happen and how do you fix it?',keywords:['n+1','eager','with','category'],sample:'This may cause the N+1 query problem. Fix it by eager loading the relationship, for example Recipe::with("category")->get().' },
  {type:'scenario',cat:'Auth & Security',q:'A logged-in user can delete another user\'s post by changing the URL ID. What security check is missing?',keywords:['ownership','authorization','belongs','policy'],sample:'An ownership authorization check is missing. The app must verify that the post belongs to the logged-in user or use a policy/gate.'},
  {type:'scenario',cat:'Blade',q:'A user enters &lt;script&gt;alert(1)&lt;/script&gt; as a comment, and the page executes it. What likely caused this and how should it be fixed?',keywords:['xss','raw','escaped','{{'],sample:'The app likely used raw output like {!! $comment !!}. Use escaped output {{ $comment }} so HTML is displayed as text instead of executed.'},
  {type:'scenario',cat:'Performance',q:'Users wait 10 seconds after registration because the app sends emails and processes images immediately. What architecture improvement should you use?',keywords:['queue','job','worker','background'],sample:'Move slow tasks into background jobs using Laravel queues. The controller should dispatch jobs and return a response immediately while a worker processes the tasks.'}
];

const CHEAT = [
  {title:'GET vs POST',rows:[['GET','Retrieves data; visible URL parameters; bookmarkable'],['POST','Sends data in request body; used for create/submit; not bookmarkable']]},
  {title:'MVC',rows:[['Model','Data, database, business logic'],['View','Presentation layer'],['Controller','Request handler and coordinator']]},
  {title:'Blade Safety',rows:[['{{ $var }}','Escaped output; safer for user content'],['{!! $var !!}','Raw output; use only with trusted HTML'],['@csrf','Adds token to protect forms']]},
  {title:'Relationships',rows:[['hasMany','One-to-many owner side'],['belongsTo','Inverse one-to-many side'],['belongsToMany','Many-to-many using pivot table'],['attach','Adds pivot records'],['sync','Replaces pivot records']]},
  {title:'Security',rows:[['Authentication','Who are you?'],['Authorization','What can you do?'],['Ownership','Can you modify this specific record?'],['APP_DEBUG=false','Prevents leaking stack traces/secrets in production']]},
  {title:'Queues',rows:[['Job','Unit of background work'],['Queue','Waiting list'],['Worker','Runs queued jobs'],['Benefit','Faster response, scalability, retry support']]}
];

let fcCards=[...FC], fcIdx=0, fcFlipped=false, fcTag='All';
let qqState={idx:0,score:0,questions:[]};
let eqState={idx:0,score:0,questions:[],timer:null,timeLeft:2400,answered:false};
let currentOrder=[];
let currentMatches={};

function goTo(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nav-tab').forEach(t=>t.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  const order=['home','flashcards','quiz','exam','cheat'];
  document.querySelectorAll('.nav-tab')[order.indexOf(id)].classList.add('active');
  if(id==='flashcards') initFC();
  if(id==='quiz') initQQ();
  if(id==='exam') initEQ();
  if(id==='cheat') initCheat();
}

function initFC(){
  const tags=['All',...new Set(FC.map(c=>c.tag))];
  document.getElementById('fc-filters').innerHTML=tags.map(t=>`<button class="filter-btn ${t===fcTag?'active':''}" onclick="setFCTag('${t}')">${t}</button>`).join('');
  filterFC();
}
function setFCTag(t){fcTag=t;filterFC();initFC();}
function filterFC(){fcCards=fcTag==='All'?[...FC]:FC.filter(c=>c.tag===fcTag);fcIdx=0;showCard();}
function showCard(){
  const c=fcCards[fcIdx];
  document.getElementById('fc-tag').textContent=c.tag;
  document.getElementById('fc-q').textContent=c.q;
  document.getElementById('fc-ans').innerHTML=c.a;
  document.getElementById('fc-prog').textContent=`${fcIdx+1} / ${fcCards.length}`;
  document.getElementById('flashcard').classList.remove('flipped');
  fcFlipped=false;
}
function flipCard(){fcFlipped=!fcFlipped;document.getElementById('flashcard').classList.toggle('flipped',fcFlipped);}
function nextCard(){fcIdx=(fcIdx+1)%fcCards.length;showCard();}
function prevCard(){fcIdx=(fcIdx-1+fcCards.length)%fcCards.length;showCard();}
function shuffleCards(){fcCards.sort(()=>Math.random()-.5);fcIdx=0;showCard();}

function initQQ(){qqState.questions=[...QQ].sort(()=>Math.random()-.5);qqState.idx=0;qqState.score=0;renderQQ();}
function renderQQ(){
  const c=document.getElementById('quiz-container');
  if(qqState.idx>=qqState.questions.length){
    const pct=Math.round((qqState.score/qqState.questions.length)*100);
    c.innerHTML=`<div class="results-card"><div class="score-circle" style="--pct:${pct}"><div class="score-num">${pct}%</div></div><h2>Quiz Complete</h2><p>You scored ${qqState.score}/${qqState.questions.length}</p><button class="btn primary" onclick="initQQ()">Restart Quiz</button></div>`;
    return;
  }
  const q=qqState.questions[qqState.idx];
  const pct=Math.round((qqState.idx/qqState.questions.length)*100);
  c.innerHTML=`<div class="quiz-meta"><div class="quiz-stat">Question <span>${qqState.idx+1}/${qqState.questions.length}</span></div><div class="quiz-stat">Score <span>${qqState.score}</span></div><div class="quiz-stat">Topic <span>${q.cat}</span></div></div><div class="prog-bar"><div class="prog-fill" style="width:${pct}%"></div></div><div class="q-card"><div class="q-cat">${q.cat}</div><div class="q-text">${q.q}</div><div class="options">${q.opts.map((o,i)=>`<div class="option" onclick="pickQQ(${i})" id="qq${i}"><span class="ol">${'ABCD'[i]}</span><span>${o}</span></div>`).join('')}</div><div class="explanation" id="qqexp"><strong>Explanation:</strong> ${q.exp}</div></div><button class="btn primary" id="qnext" onclick="nextQQ()" style="display:none">Next →</button>`;
}
function pickQQ(chosen){
  const q=qqState.questions[qqState.idx];
  document.querySelectorAll('.option').forEach(o=>o.style.pointerEvents='none');
  q.opts.forEach((_,i)=>{
    if(i===q.ans) document.getElementById('qq'+i).classList.add('correct');
    else if(i===chosen) document.getElementById('qq'+i).classList.add('wrong');
  });
  if(chosen===q.ans) qqState.score++;
  document.getElementById('qqexp').classList.add('show');
  document.getElementById('qnext').style.display='inline-block';
}
function nextQQ(){qqState.idx++;renderQQ();}

function initEQ(){
  if(eqState.timer) clearInterval(eqState.timer);
  eqState.questions=[...EXAM].sort(()=>Math.random()-.5);
  eqState.idx=0;eqState.score=0;eqState.timeLeft=2400;eqState.answered=false;
  const counts=EXAM.reduce((acc,q)=>{acc[q.type]=(acc[q.type]||0)+1;return acc;},{});
  document.getElementById('exam-container').innerHTML=`<div class="exam-hdr"><div class="icon">📝</div><div><h2>Mock Final Exam — COSC434</h2><p>${EXAM.length} questions · 40 minutes · MCQ, short answer, order, matching, scenario</p></div></div><div class="q-card" style="text-align:center;padding:2.5rem"><h3 style="margin-bottom:1rem">Exam Rules</h3><p style="color:var(--text-dim);margin-bottom:.5rem">• ${counts.mcq||0} multiple choice questions</p><p style="color:var(--text-dim);margin-bottom:.5rem">• ${counts.short||0} short answer questions</p><p style="color:var(--text-dim);margin-bottom:.5rem">• ${counts.order||0} arrange-the-steps questions</p><p style="color:var(--text-dim);margin-bottom:.5rem">• ${counts.match||0} matching questions</p><p style="color:var(--text-dim);margin-bottom:2rem">• ${counts.scenario||0} scenario questions</p><button class="btn primary" style="font-size:1rem;padding:.75rem 2rem" onclick="startEQ()">Begin Exam</button></div>`;
}
function startEQ(){eqState.timer=setInterval(tickEQ,1000);renderEQ();}
function tickEQ(){
  eqState.timeLeft--;
  const el=document.getElementById('eq-timer');
  if(!el){clearInterval(eqState.timer);return;}
  el.textContent=formatTime(eqState.timeLeft);
  if(eqState.timeLeft<=300) el.classList.add('warn');
  if(eqState.timeLeft<=0){clearInterval(eqState.timer);showEQResults(true);}
}
function formatTime(sec){const m=Math.floor(sec/60),s=sec%60;return `${String(m).padStart(2,'0')}:${String(s).padStart(2,'0')}`;}
function renderEQ(){
  const q=eqState.questions[eqState.idx];
  eqState.answered=false;
  currentMatches={};
  if(q.type==='order') currentOrder=[...q.items];
  const pct=Math.round((eqState.idx/eqState.questions.length)*100);
  document.getElementById('exam-container').innerHTML=`<div class="exam-hdr"><div><h2>Q ${eqState.idx+1}/${eqState.questions.length}<span class="type-pill">${labelType(q.type)}</span></h2><p>Score: ${eqState.score} · ${q.cat}</p></div><div class="exam-timer" id="eq-timer">${formatTime(eqState.timeLeft)}</div></div><div class="prog-bar"><div class="prog-fill" style="width:${pct}%"></div></div><div class="q-card"><div class="q-cat">${q.cat}</div><div class="q-text">${q.q}</div>${renderQuestionBody(q)}<div class="explanation" id="eqexp"></div></div><div style="display:flex;gap:.75rem;flex-wrap:wrap"><button class="btn primary" id="checkBtn" onclick="checkEQ()">Check Answer</button><button class="btn primary" id="nextBtn" onclick="nextEQ()" style="display:none">Next →</button><button class="btn danger" onclick="showEQResults(false)">Finish Now</button></div>`;
}
function labelType(type){return {mcq:'MCQ',short:'Short Answer',order:'Arrange',match:'Match',scenario:'Scenario'}[type]||type;}
function renderQuestionBody(q){
  if(q.type==='mcq') return `<div class="options">${q.opts.map((o,i)=>`<div class="option" onclick="selectEQ(${i})" id="eqopt${i}" data-selected="false"><span class="ol">${'ABCD'[i]}</span><span>${o}</span></div>`).join('')}</div>`;
  if(q.type==='short'||q.type==='scenario') return `<textarea class="answer-box" id="shortAnswer" placeholder="Write your answer here..."></textarea><p style="margin-top:.7rem;color:var(--text-dim);font-size:.8rem">Auto-marking checks for key terms. Compare your answer with the sample after checking.</p>`;
  if(q.type==='order') return `<div class="order-list" id="orderList">${renderOrderItems()}</div>`;
  if(q.type==='match'){
    const defs=q.pairs.map(p=>p[1]).sort(()=>Math.random()-.5);
    return `<div class="match-grid">${q.pairs.map((p,i)=>`<div class="match-term">${i+1}. ${p[0]}</div><select class="match-select" id="match${i}"><option value="">Choose definition...</option>${defs.map(d=>`<option value="${escapeAttr(d)}">${d}</option>`).join('')}</select>`).join('')}</div>`;
  }
  return '';
}
function escapeAttr(str){return String(str).replace(/"/g,'&quot;');}
function renderOrderItems(){
  return currentOrder.map((item,i)=>`<div class="order-item"><span class="ol">${i+1}</span><div class="order-text">${item}</div><div class="order-controls"><button class="tiny-btn" onclick="moveOrder(${i},-1)">↑</button><button class="tiny-btn" onclick="moveOrder(${i},1)">↓</button></div></div>`).join('');
}
function moveOrder(i,dir){
  const j=i+dir;
  if(j<0||j>=currentOrder.length) return;
  [currentOrder[i],currentOrder[j]]=[currentOrder[j],currentOrder[i]];
  document.getElementById('orderList').innerHTML=renderOrderItems();
}
function selectEQ(i){
  document.querySelectorAll('.option').forEach(o=>{o.dataset.selected='false';o.style.borderColor='var(--border)';});
  const el=document.getElementById('eqopt'+i);
  el.dataset.selected='true';
  el.style.borderColor='var(--accent)';
}
function checkEQ(){
  if(eqState.answered) return;
  const q=eqState.questions[eqState.idx];
  let correct=false;
  let feedback='';
  if(q.type==='mcq'){
    const selected=[...document.querySelectorAll('.option')].findIndex(o=>o.dataset.selected==='true');
    if(selected<0){alert('Choose an answer first.');return;}
    q.opts.forEach((_,i)=>{
      const el=document.getElementById('eqopt'+i);
      el.style.pointerEvents='none';
      if(i===q.ans) el.classList.add('correct');
      else if(i===selected) el.classList.add('wrong');
    });
    correct=selected===q.ans;
    feedback=`<strong>Explanation:</strong> ${q.exp}`;
  }
  if(q.type==='short'||q.type==='scenario'){
    const answer=document.getElementById('shortAnswer').value.toLowerCase();
    if(answer.trim().length<8){alert('Write a little more before checking.');return;}
    const hits=q.keywords.filter(k=>answer.includes(k.toLowerCase())).length;
    correct=hits>=Math.ceil(q.keywords.length/2);
    feedback=`<strong>${correct?'Good answer.':'Partially correct / needs improvement.'}</strong><br><br><strong>Sample answer:</strong> ${q.sample}<br><br><strong>Key terms checked:</strong> ${q.keywords.join(', ')}`;
    document.getElementById('shortAnswer').disabled=true;
  }
  if(q.type==='order'){
    correct=JSON.stringify(currentOrder)===JSON.stringify(q.answer);
    feedback=`<strong>${correct?'Correct order.':'Incorrect order.'}</strong><br><br><strong>Correct order:</strong><ol style="margin-top:.5rem;margin-left:1.2rem">${q.answer.map(x=>`<li>${x}</li>`).join('')}</ol><br>${q.exp}`;
    document.querySelectorAll('.tiny-btn').forEach(b=>b.disabled=true);
  }
  if(q.type==='match'){
    const selected=q.pairs.map((_,i)=>document.getElementById('match'+i).value);
    if(selected.some(v=>!v)){alert('Match every item first.');return;}
    correct=selected.every((v,i)=>v===q.pairs[i][1]);
    feedback=`<strong>${correct?'All matches correct.':'Some matches are incorrect.'}</strong><br><br><table class="ct" style="margin-top:.5rem"><tr><th>Concept</th><th>Correct Definition</th></tr>${q.pairs.map(p=>`<tr><td>${p[0]}</td><td>${p[1]}</td></tr>`).join('')}</table>`;
    document.querySelectorAll('.match-select').forEach(s=>s.disabled=true);
  }
  if(correct) eqState.score++;
  eqState.answered=true;
  document.getElementById('eqexp').innerHTML=feedback;
  document.getElementById('eqexp').classList.add('show');
  document.getElementById('checkBtn').style.display='none';
  document.getElementById('nextBtn').style.display='inline-block';
}
function nextEQ(){
  eqState.idx++;
  if(eqState.idx>=eqState.questions.length){showEQResults(false);return;}
  renderEQ();
}
function showEQResults(timeUp){
  if(eqState.timer) clearInterval(eqState.timer);
  const pct=Math.round((eqState.score/eqState.questions.length)*100);
  const message=pct>=80?'Excellent work.':pct>=60?'Good, but review weak areas.':'Keep practicing the core definitions and flows.';
  document.getElementById('exam-container').innerHTML=`<div class="results-card"><div class="score-circle" style="--pct:${pct}"><div class="score-num">${pct}%</div></div><h2>${timeUp?'Time is up':'Exam Complete'}</h2><p>You scored ${eqState.score}/${eqState.questions.length}. ${message}</p><button class="btn primary" onclick="initEQ()">Restart Exam</button></div>`;
}

function initCheat(){
  document.getElementById('cheat-grid').innerHTML=CHEAT.map(card=>`<div class="cc"><div class="cc-hdr">${card.title}</div><div class="cc-body"><table class="ct">${card.rows.map(r=>`<tr><td>${r[0]}</td><td>${r[1]}</td></tr>`).join('')}</table></div></div>`).join('');
}
</script>
</body>
</html>
