<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Nexplan Readability Analyzer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,400;12..96,600;12..96,700&family=Newsreader:opsz,wght@6..72,400;6..72,500&display=swap" rel="stylesheet">
<style>
:root{--bg:#0c0f22;--panel:rgba(20,25,56,.62);--panel2:rgba(255,255,255,.04);--line:rgba(170,180,255,.17);--text:#eceefc;--muted:#9ba3cf;--accent:#8b7cff;--focus:#2dd4bf;--sh:0 22px 50px -26px rgba(0,0,0,.75);color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#eef0fc;--panel:rgba(255,255,255,.68);--panel2:rgba(40,50,130,.05);--line:rgba(50,60,140,.17);--text:#171b3d;--muted:#5b6392;--accent:#5b49e0;--focus:#0d9488;--sh:0 22px 44px -28px rgba(40,50,130,.45);color-scheme:light}}
:root[data-theme="light"]{--bg:#eef0fc;--panel:rgba(255,255,255,.68);--panel2:rgba(40,50,130,.05);--line:rgba(50,60,140,.17);--text:#171b3d;--muted:#5b6392;--accent:#5b49e0;--focus:#0d9488;--sh:0 22px 44px -28px rgba(40,50,130,.45);color-scheme:light}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;background:radial-gradient(900px 520px at 10% -6%,rgba(124,108,255,.30),transparent 62%),radial-gradient(800px 520px at 100% 8%,rgba(45,212,191,.17),transparent 60%),var(--bg);background-attachment:fixed;color:var(--text);font:15px/1.55 'Bricolage Grotesque',system-ui,sans-serif}
#bg{position:fixed;inset:0;width:100%;height:100%;z-index:0;pointer-events:none}
.wrap{position:relative;z-index:1;max-width:1180px;margin:auto;padding:24px 20px 56px}
:focus-visible{outline:2px solid var(--focus);outline-offset:2px}
header{display:flex;justify-content:space-between;align-items:center;gap:12px}
.brand{display:flex;align-items:center;gap:10px;font-weight:600;color:var(--muted)}
.tools{display:flex;gap:8px}
h1{font-size:clamp(32px,5.4vw,56px);line-height:1.03;letter-spacing:-.025em;font-weight:700;margin:26px 0 12px;max-width:15ch}
.lead{color:var(--muted);font-size:17px;max-width:54ch;margin:0}
.main{display:grid;grid-template-columns:minmax(0,1.1fr) minmax(0,1fr);gap:20px;margin-top:30px}
.full{grid-column:1/-1}
@media(max-width:900px){.main{grid-template-columns:minmax(0,1fr)}}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:20px;padding:20px;backdrop-filter:blur(16px) saturate(1.2);-webkit-backdrop-filter:blur(16px) saturate(1.2);box-shadow:var(--sh)}
.panel h2{font-size:16px;font-weight:600;margin:0}
.sub{color:var(--muted);font-size:13.5px;margin:2px 0 0}
.editor{display:flex;flex-direction:column}
textarea{flex:1;width:100%;min-height:360px;margin-top:14px;resize:vertical;background:var(--panel2);color:var(--text);border:1px solid var(--line);border-radius:14px;padding:16px 18px;font:17px/1.7 'Newsreader',Georgia,serif;outline:0;transition:border-color .2s,box-shadow .2s}
textarea:focus{border-color:var(--accent);box-shadow:0 0 0 4px color-mix(in srgb,var(--accent) 25%,transparent)}
textarea::placeholder{color:var(--muted)}
.bar{display:flex;flex-wrap:wrap;gap:8px;align-items:center;margin-top:14px}
.count{margin-left:auto;color:var(--muted);font-size:13.5px;font-variant-numeric:tabular-nums}
.btn{font:inherit;font-weight:600;color:var(--text);border:1px solid var(--line);background:var(--panel2);padding:10px 15px;border-radius:11px;cursor:pointer;transition:transform .15s,background .2s}
.btn:hover{background:color-mix(in srgb,var(--accent) 16%,transparent)}
.btn:active{transform:translateY(1px)}
.btn.pri{border:0;color:#fff;background:linear-gradient(120deg,#7c6cff,#4b8bf5);box-shadow:0 10px 24px -12px #6d5cff}
.btn.pri:hover{filter:brightness(1.1)}
.icon{width:40px;height:40px;padding:0;display:grid;place-items:center;border-radius:12px}
.icon[aria-pressed="false"]{opacity:.5}
.gauge{position:relative;max-width:360px;margin:10px auto 0}
.gauge svg{display:block;width:100%;height:auto;overflow:visible}
.gtxt{position:absolute;left:0;right:0;bottom:4px;text-align:center}
#score{font-size:54px;font-weight:700;line-height:1;font-variant-numeric:tabular-nums;letter-spacing:-.02em}
#band{font-weight:600;margin-top:4px}
.bdesc{text-align:center;color:var(--muted);font-size:13.5px;margin:12px 0 0;min-height:1.5em}
.tiles{display:grid;grid-template-columns:repeat(auto-fit,minmax(105px,1fr));gap:10px;margin-top:18px}
.tile{background:var(--panel2);border:1px solid var(--line);border-radius:12px;padding:12px}
.tile .l{color:var(--muted);font-size:12.5px}
.tile .v{font-size:24px;font-weight:700;margin-top:2px;font-variant-numeric:tabular-nums}
.tile .s{font-size:12px;color:var(--muted);line-height:1.35}
.tip{margin-top:14px;padding:11px 14px;border-radius:12px;background:color-mix(in srgb,var(--accent) 13%,transparent);font-size:14px}
.strip{display:flex;gap:1px;height:44px;margin:16px 0 18px;cursor:crosshair;touch-action:pan-y;border-radius:6px}
.seg{flex:1;min-width:1px;border-radius:2px;position:relative;transition:transform .15s,opacity .3s}
.seg.idle{background:var(--line);opacity:.6}
.seg.on{transform:scaleY(1.28)}
.seg.flash{animation:fl .9s}
.seg.top::after{content:"";position:absolute;left:50%;bottom:-9px;width:5px;height:5px;border-radius:50%;background:var(--text);transform:translateX(-50%)}
@keyframes fl{0%{transform:scaleY(2.4)}100%{transform:scaleY(1.28)}}
.pk{font-size:13px;color:var(--muted)}
#peek p{margin:4px 0 0;font:17px/1.65 'Newsreader',Georgia,serif;max-width:78ch}
.hard{display:grid;gap:12px;margin-top:14px}
.hs{display:grid;grid-template-columns:36px 1fr;gap:14px;padding:16px;border-radius:14px;background:var(--panel2);border:1px solid var(--line);cursor:pointer;transition:border-color .2s,transform .2s}
.hs:hover{border-color:var(--c);transform:translateX(3px)}
.rk{width:34px;height:34px;border-radius:50%;display:grid;place-items:center;font-weight:700;background:var(--c);color:#10142e}
.hs p{margin:0;font:17px/1.65 'Newsreader',Georgia,serif;max-width:72ch}
.m{height:5px;border-radius:9px;background:var(--line);margin-top:12px;overflow:hidden;max-width:360px}
.m i{display:block;height:100%;width:0;background:var(--c);border-radius:9px;transition:width .9s cubic-bezier(.2,.8,.2,1)}
.meta{font-size:12.5px;color:var(--muted);margin-top:8px}
.empty{color:var(--muted);padding:14px 2px}
.note{color:var(--muted);font-size:12.5px;margin-top:22px;max-width:70ch}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<canvas id="bg" aria-hidden="true"></canvas>
<div class="wrap">
<header>
<div class="brand">
<svg width="30" height="30" viewBox="0 0 30 30" aria-hidden="true"><defs><linearGradient id="lg" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#8b7cff"/><stop offset="1" stop-color="#2dd4bf"/></linearGradient></defs><rect width="30" height="30" rx="9" fill="url(#lg)"/><path d="M7 10h16M7 15h12M7 20h8" stroke="#fff" stroke-width="2.2" stroke-linecap="round"/></svg>
Nexplan
</div>
<div class="tools">
<button class="btn icon" id="mot" aria-pressed="true" aria-label="Toggle background motion" title="Background motion"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M3 12c3-6 6-6 9 0s6 6 9 0"/></svg></button>
<button class="btn icon" id="theme" aria-label="Switch light or dark theme" title="Light / dark"></button>
</div>
</header>

<h1>Chapter Readability Analyzer</h1>
<p class="lead">Paste a chapter to see how easy it is to read, and which five sentences are slowing your readers down.</p>

<main class="main">
<section class="panel editor" aria-labelledby="eh">
<h2 id="eh">Your chapter</h2>
<p class="sub">Results update as you type. Press Ctrl or ⌘ + Enter to analyze at once.</p>
<textarea id="chapter" placeholder="Paste your chapter here..." aria-label="Chapter text" spellcheck="false"></textarea>
<div class="bar">
<button class="btn pri" id="go">Analyze chapter</button>
<button class="btn" id="sample">Load sample</button>
<button class="btn" id="clear">Clear</button>
<span class="count" id="count">0 words</span>
</div>
</section>

<section class="panel" id="results" aria-live="polite" aria-labelledby="rh">
<h2 id="rh">Readability score</h2>
<p class="sub">Flesch Reading Ease: higher means easier.</p>
<div class="gauge">
<svg viewBox="0 0 220 125" role="img" aria-label="Readability gauge">
<defs><linearGradient id="gg" gradientUnits="userSpaceOnUse" x1="20" y1="0" x2="200" y2="0">
<stop offset="0" stop-color="hsl(350,80%,64%)"/><stop offset=".25" stop-color="hsl(305,75%,66%)"/><stop offset=".5" stop-color="hsl(259,80%,70%)"/><stop offset=".75" stop-color="hsl(213,80%,62%)"/><stop offset="1" stop-color="hsl(168,72%,52%)"/></linearGradient></defs>
<path d="M20 110A90 90 0 0 1 200 110" fill="none" stroke="var(--line)" stroke-width="14" stroke-linecap="round"/>
<path id="arc" d="M20 110A90 90 0 0 1 200 110" pathLength="100" fill="none" stroke="url(#gg)" stroke-width="14" stroke-linecap="round" stroke-dasharray="100" stroke-dashoffset="100"/>
<circle id="dot" cx="20" cy="110" r="8" fill="var(--text)" stroke="var(--bg)" stroke-width="3"/>
</svg>
<div class="gtxt"><div id="score">—</div><div id="band">Waiting for text</div></div>
</div>
<p class="bdesc" id="bdesc">Paste a chapter or load the sample.</p>
<div class="tiles">
<div class="tile"><div class="l">Estimated grade</div><div class="v" id="grade">—</div><div class="s">US school level</div></div>
<div class="tile"><div class="l">Words</div><div class="v" id="words">—</div><div class="s" id="wsub">&nbsp;</div></div>
<div class="tile"><div class="l">Sentences</div><div class="v" id="sentences">—</div><div class="s" id="ssub">&nbsp;</div></div>
<div class="tile"><div class="l">Reading time</div><div class="v" id="read">—</div><div class="s">at 238 words/min</div></div>
</div>
<div class="tip" id="tip" hidden></div>
</section>

<section class="panel full" aria-labelledby="mh">
<h2 id="mh">Sentence map</h2>
<p class="sub">Every sentence in order, colored from easy (teal) to hard (rose) relative to this chapter. Dots mark the five hardest.</p>
<div class="strip" id="strip" tabindex="0" role="group" aria-label="Sentence difficulty map. Use left and right arrow keys to read sentences."></div>
<div id="peek"><div class="pk">Hover, tap, or use the arrow keys on the map to read any sentence.</div></div>
</section>

<section class="panel full" aria-labelledby="hh">
<h2 id="hh">Five hardest sentences</h2>
<p class="sub">Select one to find it on the map.</p>
<div class="hard" id="hard"><div class="empty">Your hardest sentences will appear here.</div></div>
<p class="note">Hardness is estimated from sentence length, syllable density, long words, and punctuation. Everything runs in your browser, so nothing you paste is uploaded.</p>
</section>
</main>
</div>

<script>
/* ---------- original analysis logic (unchanged) ---------- */
function protect(t){const a=['Mr.','Mrs.','Ms.','Dr.','Prof.','Sr.','Jr.','St.','vs.','e.g.','i.e.','etc.','U.S.','U.K.','No.','Fig.','Inc.','Ltd.'];for(const x of a)t=t.replaceAll(x,x.replaceAll('.','∯'));return t}
function splitSentences(t){return (protect(t).match(/[^.!?]+[.!?]+(?=\s+|$)|[^.!?]+$/g)||[]).map(s=>s.replaceAll('∯','.').trim()).filter(Boolean)}
function words(s){return s.match(/[A-Za-z]+(?:['’-][A-Za-z]+)*/g)||[]}
function syll(w){w=w.toLowerCase().replace(/[^a-z]/g,'');if(!w)return 0;if(w.length<=3)return 1;w=w.replace(/(?:[^aeiouy]e)$/,'');let g=w.match(/[aeiouy]{1,2}/g);let n=g?g.length:1;if(/le$/.test(w)&&!/[aeiouy][aeiouy]le$/.test(w))n++;if(/ed$/.test(w)&&!/(ted|ded)$/.test(w))n=Math.max(1,n-1);if(/es$/.test(w)&&!/(ses|zes|xes|ches|shes)$/.test(w))n=Math.max(1,n-1);return Math.max(1,n)}
function difficulty(s){const ws=words(s);const sy=ws.reduce((a,w)=>a+syll(w),0);const long=ws.filter(w=>w.replace(/[^A-Za-z]/g,'').length>=9).length;const clauses=(s.match(/[,;:—-]/g)||[]).length;return ws.length+(sy/Math.max(ws.length,1))*12+long*2.5+clauses*1.5}

/* ---------- interface ---------- */
const $=id=>document.getElementById(id);
const root=document.documentElement;
const reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
const isDark=()=>root.dataset.theme?root.dataset.theme==='dark':!matchMedia('(prefers-color-scheme: light)').matches;
const tc=(t,a=1)=>`hsla(${168+182*t},72%,${isDark()?64:46}%,${a})`;
const store=(k,v)=>{try{v===undefined?0:localStorage.setItem(k,v);return localStorage.getItem(k)}catch(e){return null}};
const SAMPLE=`Dr. Alvarez arrived at the station before dawn. The platform was empty. She waited.

By the time the first train appeared, however, the accumulated uncertainties of the preceding weeks—the contradictory telegrams, the unexplained postponements, the whispered suggestions that the entire expedition had been quietly compromised by administrative indifference—had settled into a dull, persistent apprehension that no amount of deliberate reasoning could entirely dispel.

She boarded anyway. The carriage smelled of coal and oranges. A boy across the aisle was reading a comic, e.g. the kind her brother used to hide under his mattress. She smiled.

Notwithstanding the unequivocal assurances provided by the committee's representatives, the geological surveys that had ostensibly justified the expedition's considerable expense remained, to any reasonably sceptical observer, conspicuously incomplete. Still, she had made her choice. The train began to move.`;
const bands=[[90,'Very easy','Around 5th-grade reading level.'],[80,'Easy','Around 6th grade. Conversational.'],[70,'Fairly easy','Around 7th grade.'],[60,'Plain English','Around 8th–9th grade. Most adults read this comfortably.'],[50,'Fairly difficult','Around 10th–12th grade.'],[30,'Difficult','College level.'],[0,'Very difficult','Graduate level.']];
let S=null,sel=-1,cur=0,raf,dt;

/* gauge */
function paintGauge(v,idle){$('arc').style.strokeDashoffset=100-v;const a=Math.PI*(1-v/100);$('dot').setAttribute('cx',110+90*Math.cos(a));$('dot').setAttribute('cy',110-90*Math.sin(a));$('score').textContent=idle?'—':v.toFixed(1)}
function tween(to,idle){cancelAnimationFrame(raf);const from=cur,t0=performance.now(),dur=reduce?0:900;const step=n=>{const k=dur?Math.min(1,(n-t0)/dur):1,e=1-Math.pow(1-k,3);cur=from+(to-from)*e;paintGauge(cur,idle);if(k<1)raf=requestAnimationFrame(step)};raf=requestAnimationFrame(step)}

/* analysis */
function liveCount(){const n=words($('chapter').value).length;$('count').textContent=n?`${n.toLocaleString()} words · ${n<238?'<1':Math.round(n/238)} min read`:'0 words'}
function analyze(go){
 const t=$('chapter').value.trim(),ws=words(t);
 if(!ws.length){if(go)$('chapter').focus();idle();return}
 const sents=splitSentences(t),sy=ws.reduce((a,w)=>a+syll(w),0);
 const wps=ws.length/Math.max(sents.length,1),spw=sy/Math.max(ws.length,1);
 const sc=Math.max(0,Math.min(100,206.835-1.015*wps-84.6*spw)),gr=Math.max(0,.39*wps+11.8*spw-15.59);
 const scored=sents.map((s,i)=>({s,i,d:difficulty(s)}));
 const top=[...scored].sort((a,b)=>b.d-a.d).slice(0,5);
 const ds=scored.map(x=>x.d);
 S={scored,top,min:Math.min(...ds),max:Math.max(...ds),sc,gr,wps,spw,n:ws.length,rank:new Map(top.map((x,i)=>[x.i,i+1]))};
 sel=-1;paint(true);
 if(go&&innerWidth<900)$('results').scrollIntoView({behavior:reduce?'auto':'smooth',block:'start'});
}
const rel=d=>(d-S.min)/((S.max-S.min)||1);
function paint(anim){
 const b=bands.find(x=>S.sc>=x[0]);
 $('band').textContent=b[1];$('bdesc').textContent=b[2];
 $('grade').textContent=S.gr.toFixed(1);
 $('words').textContent=S.n.toLocaleString();$('wsub').textContent=`${S.spw.toFixed(2)} syllables each`;
 $('sentences').textContent=S.scored.length.toLocaleString();$('ssub').textContent=`${S.wps.toFixed(1)} words each`;
 $('read').textContent=S.n<238?'<1 min':Math.round(S.n/238)+' min';
 const tip=S.wps>22?`Sentences average ${S.wps.toFixed(1)} words. Splitting the longest ones is the quickest way to raise your score.`:S.spw>1.55?`Words average ${S.spw.toFixed(2)} syllables. Swapping a few long words for shorter ones will lift your score.`:'Sentence length and word choice are in a comfortable range. Polish the five hardest sentences below.';
 $('tip').hidden=false;$('tip').textContent=tip;
 $('strip').innerHTML=S.scored.map((x,i)=>`<i class="seg${S.rank.has(i)?' top':''}" style="background:${tc(rel(x.d))}"></i>`).join('');
 const box=$('hard');box.innerHTML='';
 S.top.forEach((x,i)=>{const ws=words(x.s),sy=ws.reduce((a,w)=>a+syll(w),0),lg=ws.filter(w=>w.length>=9).length;
  const d=document.createElement('div');d.className='hs';d.tabIndex=0;d.style.setProperty('--c',tc(rel(x.d)));
  d.innerHTML='<div class="rk"></div><div><p></p><div class="m"><i></i></div><div class="meta"></div></div>';
  d.querySelector('.rk').textContent=i+1;d.querySelector('p').textContent=x.s;
  d.querySelector('.meta').textContent=`Sentence ${x.i+1} of ${S.scored.length} · ${ws.length} words · ${(sy/Math.max(ws.length,1)).toFixed(1)} syllables each · ${lg} long word${lg===1?'':'s'}`;
  const go=()=>{peek(x.i,true);$('strip').scrollIntoView({behavior:reduce?'auto':'smooth',block:'center'})};
  d.onclick=go;d.onkeydown=e=>{if(e.key==='Enter'||e.key===' '){e.preventDefault();go()}};
  box.appendChild(d);requestAnimationFrame(()=>requestAnimationFrame(()=>d.querySelector('.m i').style.width=(x.d/S.top[0].d*100)+'%'))});
 anim?tween(S.sc):(cur=S.sc,paintGauge(S.sc));
 hueT=168+182*(1-S.sc/100);if(!motion)draw();
}
function idle(){
 S=null;sel=-1;tween(0,true);
 ['grade','words','sentences','read'].forEach(k=>$(k).textContent='—');$('wsub').innerHTML=$('ssub').innerHTML='&nbsp;';
 $('band').textContent='Waiting for text';$('bdesc').textContent='Paste a chapter or load the sample.';$('tip').hidden=true;
 $('strip').innerHTML='<i class="seg idle"></i>'.repeat(48);
 $('peek').innerHTML='<div class="pk">Hover, tap, or use the arrow keys on the map to read any sentence.</div>';
 $('hard').innerHTML='<div class="empty">Your hardest sentences will appear here.</div>';
 hueT=255;if(!motion)draw();
}
function peek(i,flash){
 if(!S)return;sel=i;const x=S.scored[i],st=$('strip');
 st.querySelectorAll('.on').forEach(e=>e.classList.remove('on'));
 const seg=st.children[i];seg.classList.add('on');
 if(flash){seg.classList.remove('flash');void seg.offsetWidth;seg.classList.add('flash')}
 const r=S.rank.get(i),n=words(x.s).length;
 $('peek').innerHTML='<div class="pk"></div><p></p>';
 $('peek').firstChild.textContent=`Sentence ${i+1} of ${S.scored.length} · ${n} words${r?` · hardest #${r}`:''}`;
 $('peek').lastChild.textContent=x.s;
}
const st=$('strip');
const at=e=>{if(!S)return;const r=st.getBoundingClientRect();peek(Math.min(S.scored.length-1,Math.max(0,Math.floor((e.clientX-r.left)/r.width*S.scored.length))))};
st.addEventListener('pointermove',at);st.addEventListener('pointerdown',at);
st.addEventListener('keydown',e=>{if(!S)return;if(e.key==='ArrowRight'){peek(Math.min(S.scored.length-1,sel+1));e.preventDefault()}if(e.key==='ArrowLeft'){peek(Math.max(0,sel-1));e.preventDefault()}});

/* controls */
$('chapter').addEventListener('input',()=>{liveCount();clearTimeout(dt);dt=setTimeout(()=>analyze(false),350)});
$('chapter').addEventListener('keydown',e=>{if(e.key==='Enter'&&(e.ctrlKey||e.metaKey)){e.preventDefault();clearTimeout(dt);analyze(true)}});
$('go').onclick=()=>{clearTimeout(dt);analyze(true)};
$('sample').onclick=()=>{$('chapter').value=SAMPLE;liveCount();analyze(true)};
$('clear').onclick=()=>{$('chapter').value='';liveCount();idle();$('chapter').focus()};

/* theme + motion */
const ICON={sun:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M2 12h2M20 12h2M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/></svg>',moon:'<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 13A9 9 0 1 1 11 3a7 7 0 0 0 10 10z"/></svg>'};
const sv=store('nx-theme');if(sv==='light'||sv==='dark')root.dataset.theme=sv;
function themeIcon(){$('theme').innerHTML=isDark()?ICON.sun:ICON.moon}
$('theme').onclick=()=>{root.dataset.theme=isDark()?'light':'dark';store('nx-theme',root.dataset.theme);themeIcon();if(S)paint(false);if(!motion)draw()};
themeIcon();

/* living background: drifting letters that scatter from the pointer and take on the score's color */
const cv=$('bg'),cx=cv.getContext('2d');
const chars=['the','and','but','which','e','a','t','—',';',',','.','?','“','”','¶','&','however','so','Aa','§','of'];
let W,H,gl=[],hue=255,hueT=255,mouse={x:0,y:0,sx:0,sy:0},motion=store('nx-motion')?store('nx-motion')==='1':!reduce;
function mk(){const s=14+Math.pow(Math.random(),2)*40,bx=(Math.random()-.5)*.3,by=(Math.random()-.5)*.3-.05;return{x:Math.random()*W,y:Math.random()*H,bx,by,vx:bx,vy:by,ch:chars[Math.random()*chars.length|0],s,r:(Math.random()-.5)*.7,vr:(Math.random()-.5)*.002,a:.1+Math.random()*.22,z:.4+s/54,o:(Math.random()-.5)*30}}
function size(){const d=Math.min(2,devicePixelRatio||1);W=innerWidth;H=innerHeight;cv.width=W*d;cv.height=H*d;cx.setTransform(d,0,0,d,0,0);const n=Math.round(Math.min(70,Math.max(24,W*H/24000)));while(gl.length<n)gl.push(mk());gl.length=n}
function draw(){
 const dark=isDark();hue+=(hueT-hue)*(motion?.03:1);
 mouse.sx+=(mouse.x-mouse.sx)*(motion?.08:1);mouse.sy+=(mouse.y-mouse.sy)*(motion?.08:1);
 cx.clearRect(0,0,W,H);
 const g=cx.createRadialGradient(mouse.sx,mouse.sy,0,mouse.sx,mouse.sy,400);
 g.addColorStop(0,`hsla(${hue},80%,${dark?60:68}%,${dark?.22:.26})`);g.addColorStop(1,`hsla(${hue},80%,60%,0)`);
 cx.fillStyle=g;cx.fillRect(0,0,W,H);
 cx.textAlign='center';cx.textBaseline='middle';
 for(const p of gl){
  if(motion){
   const dx=p.x-mouse.x,dy=p.y-mouse.y,d2=dx*dx+dy*dy;
   if(d2<28900){const d=Math.sqrt(d2)||1,f=(170-d)/170;p.vx+=dx/d*f*.6*p.z;p.vy+=dy/d*f*.6*p.z;p.vr+=(dx>0?1:-1)*.0007}
   p.vx+=(p.bx-p.vx)*.02;p.vy+=(p.by-p.vy)*.02;p.vr*=.99;
   p.x+=p.vx*p.z;p.y+=p.vy*p.z;p.r+=p.vr;
   if(p.x<-80)p.x=W+80;if(p.x>W+80)p.x=-80;if(p.y<-80)p.y=H+80;if(p.y>H+80)p.y=-80;
  }
  cx.save();cx.translate(p.x,p.y);cx.rotate(p.r);
  cx.font=`${p.s}px Newsreader,Georgia,serif`;cx.fillStyle=`hsla(${hue+p.o},70%,${dark?74:42}%,${p.a})`;
  cx.fillText(p.ch,0,0);cx.restore();
 }
}
function loop(){draw();if(motion)requestAnimationFrame(loop)}
addEventListener('pointermove',e=>{mouse.x=e.clientX;mouse.y=e.clientY},{passive:true});
addEventListener('resize',()=>{size();if(!motion)draw()});
$('mot').setAttribute('aria-pressed',motion);
$('mot').onclick=()=>{motion=!motion;store('nx-motion',motion?'1':'0');$('mot').setAttribute('aria-pressed',motion);motion?loop():draw()};

size();mouse.x=mouse.sx=W*.72;mouse.y=mouse.sy=H*.22;
idle();loop();
</script>
</body>
</html>
