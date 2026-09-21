# Fot-Fun-2

<html lang="my">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>ချစ်သူ ရှိပြီး အချစ်မခံရတဲ့သူလား</title>
<style>
*{box-sizing:border-box} :root{--ink:#302544;--purple:#b79ae9;--yellow:#ffe583}
body{margin:0;min-height:100svh;padding:28px 18px;display:grid;place-items:center;color:var(--ink);font-family:'Myanmar Text','Noto Sans Myanmar',Padauk,sans-serif;background:radial-gradient(ellipse at 10% 0,#e2ccff,transparent 55%),radial-gradient(ellipse at 100% 100%,#ffe69d,transparent 60%),#f7f0ff}
body::before{content:'';position:fixed;inset:0;pointer-events:none;background:radial-gradient(#63438226 1.5px,transparent 1.5px) 0 0/24px 24px}
.card{position:relative;width:min(100%,570px);min-height:620px;border:2px solid var(--ink);border-radius:30px;box-shadow:8px 9px 0 #b99bdc;background:#fff9e7;overflow:hidden}
.page{position:relative;text-align:center;min-height:620px;padding:52px 24px 30px;isolation:isolate}
[hidden]{display:none!important}.decoration{position:absolute;pointer-events:none;color:#b897dc;font-size:29px;z-index:-1}.one{top:35px;left:28px;transform:rotate(-15deg)}.two{right:28px;top:100px;color:#dfa62d}.three{left:26px;bottom:64px}.four{right:24px;bottom:30px;color:#dfa62d}
.character{display:block;width:240px;max-width:76%;height:225px;margin:0 auto;overflow:visible;animation:chuckle 1.5s ease-in-out infinite;transform-origin:50% 90%}
@keyframes chuckle{0%,70%,100%{transform:rotate(-3deg) translateY(0)}20%,50%{transform:rotate(3deg) translateY(-5px)}35%{transform:rotate(-2deg) translateY(-2px)}}
h1{font-size:clamp(23px,5.4vw,33px);line-height:1.9;margin:24px 0 14px;font-weight:800;overflow-wrap:anywhere}
.playground{position:relative;width:100%;height:195px;margin-top:12px}
button{font:700 17px/1.8 'Myanmar Text','Noto Sans Myanmar',Padauk,sans-serif;border:2px solid var(--ink);border-radius:14px;cursor:pointer;padding:12px 20px;min-height:58px;box-shadow:3px 5px 0 var(--ink);color:var(--ink);-webkit-tap-highlight-color:transparent;touch-action:manipulation}
button:focus-visible{outline:3px solid #8156c3;outline-offset:7px}
#yes,#no{position:absolute;top:28px;min-width:115px}#yes{left:calc(50% - 130px);background:var(--purple)}#no{left:calc(50% + 15px);background:var(--yellow);transition:left .12s ease-out,top .12s ease-out}
#yes:hover{background:#cbb3f1;transform:translateY(-2px)}#yes:active{transform:translateY(3px);box-shadow:1px 2px 0 var(--ink)}
#result{padding-top:75px;background:radial-gradient(ellipse at 50% 20%,#f4eaff,transparent 65%)}#result h1{margin-top:36px}#result .character{width:265px;height:245px}#result .one{font-family:sans-serif;font-weight:900;font-size:22px;top:70px}.again{margin-top:28px;background:white;font-size:13px;padding:9px 20px;min-height:44px}
.symbols{position:absolute;width:0;height:0;overflow:hidden}
@media(max-width:380px){body{padding:20px 12px}.page{padding-inline:14px}.card,.page{min-height:590px}.character{height:205px}h1{font-size:23px}#yes,#no{min-width:105px;padding-inline:12px}#yes{left:calc(50% - 119px)}#no{left:calc(50% + 12px)}}
@media(prefers-reduced-motion:reduce){.character{animation:none}#no{transition:none}}

/* Full desktop layout, with a responsive mobile fallback. */
body { display:block; padding:0; }
.card { width:100%; min-height:100svh; border:0; border-radius:0; box-shadow:none; background:transparent; }
.page { width:100%; min-height:100svh; display:flex; flex-direction:column; align-items:center; justify-content:center; padding:40px 5vw 24px; }
.character { flex-shrink:0; width:clamp(240px,23vw,350px); height:clamp(220px,30vh,320px); max-width:80%; margin:0 auto; }
h1 { max-width:1100px; font-size:clamp(25px,3.2vw,48px); line-height:1.9; margin:24px 0 12px; }
.playground { width:min(100%,1000px); height:220px; flex-shrink:0; margin-top:10px; }
button { font-size:20px; padding:14px 26px; }
#yes,#no { min-width:155px; }
#yes { left:calc(50% - 180px); }
#no { left:calc(50% + 25px); }
#result { padding:40px 5vw; background:radial-gradient(ellipse at 50% 35%,#fff6dccc,transparent 65%); }
#result .character { width:clamp(270px,27vw,410px); height:clamp(250px,36vh,380px); }
#result h1 { margin-top:34px; }
.decoration { font-size:clamp(30px,4vw,65px); }
.one { left:12%; top:12%; }.two { right:12%; top:22%; }.three { left:15%; bottom:14%; }.four { right:14%; bottom:12%; }
#result .one { font-size:clamp(24px,3vw,44px); top:16%; }
.again { font-size:15px; }
@media(max-width:600px) {
 .page,#result { padding:32px 16px; }
 .character { width:230px; height:220px; }
 h1 { font-size:25px; }
 #yes,#no { min-width:125px; padding:12px 14px; font-size:16px; }
 #yes { left:calc(50% - 137px); } #no { left:calc(50% + 10px); }
 .playground { height:220px; }
 .one { left:5%; top:5%; }.two { right:5%; top:12%; }
 #result .one { top:5%; }
}
</style>
</head>
<body>
<!-- Self-contained cartoon artwork: no external images or fonts required. -->
<svg class="symbols" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
<symbol id="laughing-character" viewBox="0 0 240 220">
<ellipse cx="119" cy="206" rx="67" ry="8" fill="#382746" opacity=".1"/>
<g stroke="#302544" stroke-width="4" stroke-linecap="round" stroke-linejoin="round">
<path d="M91 174l-8 27H64m77-27 12 27h17" fill="none"/>
<path d="M66 116Q35 132 35 104l6-15m123 27q29-20 40-43" fill="none"/>
<path d="M195 77l8-21q4-5 7 0l-2 18q13-10 16-3l-8 15q-8 9-21 0" fill="#ffe083"/>
<path d="M69 57Q80 36 125 41q49 2 50 48l-6 56q-2 43-53 43-52-1-55-38l-1-55q-2-23 9-38Z" fill="#ffe083"/>
<path d="M102 41q-13-21-4-26m13 24q0-17 15-21" fill="none"/>
<path d="M77 86l20 9-19 7" fill="none"/>
<path d="M152 83l-20 11 20 5" fill="none"/>
<path d="M83 118q33 13 65-2-3 44-32 44-27-1-33-42Z" fill="#302544"/>
<path d="M88 121l4 12 45-1 5-12" fill="white" stroke-width="2"/>
<path d="M103 156q12-19 28-5" fill="#ef8e99" stroke="none"/>
<path d="M72 101q-15 10-9 18 10 7 9-18m84-4q17 7 12 17-9 7-12-17" fill="#85d5ec" stroke="#5094b0" stroke-width="2"/>
<path d="M74 151q-29-9-32 4 1 10 29 12" fill="#ffe083"/>
</g>
<ellipse cx="77" cy="111" rx="11" ry="6" fill="#f4ad8f"/><ellipse cx="155" cy="109" rx="10" ry="6" fill="#f4ad8f"/>
<g fill="none" stroke="#9a75c5" stroke-width="4" stroke-linecap="round"><path d="M36 52l-9-9m13 25-16-1m173 52 14 1m-13 16 10 7"/></g>
</symbol>
</svg>
<main class="card">
<section class="page" id="question" aria-labelledby="question-title">
<span class="decoration one" aria-hidden="true">✦</span><span class="decoration two" aria-hidden="true">✧</span><span class="decoration three" aria-hidden="true">✧</span><span class="decoration four" aria-hidden="true">✦</span>
<svg class="character" role="img" aria-label="စနောက်ပြီး ရယ်မောနေတဲ့ ကာတွန်း"><use href="#laughing-character"/></svg>
<h1 id="question-title">ချစ်သူ ရှိပြီး အချစ်မခံရတဲ့သူလား</h1>
<div class="playground" id="playground">
<button id="yes" type="button">ဟုတ်တယ်</button>
<button id="no" type="button">မဟုတ်ပါဖူး</button>
</div>
</section>
<section class="page" id="result" aria-labelledby="result-title" hidden>
<span class="decoration one" aria-hidden="true">HA HA!</span><span class="decoration two" aria-hidden="true">✦</span><span class="decoration three" aria-hidden="true">✧</span><span class="decoration four" aria-hidden="true">✦</span>
<svg class="character" role="img" aria-label="လက်ညှိုးထိုးပြီး ဟာသလုပ်ရယ်မောနေတဲ့ ကာတွန်း"><use href="#laughing-character"/></svg>
<h1 id="result-title" tabindex="-1">နောက်လဲ အချစ်ခံရမှာ မဟုတ်ဖူး</h1>
<button class="again" id="again" type="button">ပြန်စမယ်</button>
</section>
</main>
<script>
// JavaScript handles the moving button and the two page-like screens.
const no = document.getElementById('no');
const yes = document.getElementById('yes');
const playground = document.getElementById('playground');
const question = document.getElementById('question');
const result = document.getElementById('result');
function moveNo() {
  const maxX = playground.clientWidth - no.offsetWidth - 6;
  const maxY = playground.clientHeight - no.offsetHeight - 6;
  const oldX = no.offsetLeft, oldY = no.offsetTop;
  // Keep the button inside its area and clear of the Yes button.
  const choices = [];
  for (let y = 6; y <= maxY; y += 8) {
    for (let x = 6; x <= maxX; x += 8) {
      const clear = x + no.offsetWidth + 14 < yes.offsetLeft || x > yes.offsetLeft + yes.offsetWidth + 14 || y + no.offsetHeight + 14 < yes.offsetTop || y > yes.offsetTop + yes.offsetHeight + 14;
      if (clear && Math.hypot(x-oldX,y-oldY) > 65) choices.push({x,y});
    }
  }
  if (!choices.length) return;
  const next = choices[Math.floor(Math.random()*choices.length)];
  no.style.left = next.x + 'px';
  no.style.top = next.y + 'px';
}
// A click works for touch, mouse, and keyboard. No never advances the page.
no.addEventListener('click', moveNo);
yes.addEventListener('click', () => {
  question.hidden = true;
  result.hidden = false;
  document.getElementById('result-title').focus({preventScroll:true});
});
document.getElementById('again').addEventListener('click', () => {
  result.hidden = true;
  question.hidden = false;
  no.style.left = '';
  no.style.top = '';
  yes.focus({preventScroll:true});
});
window.addEventListener('resize', () => { no.style.left=''; no.style.top=''; });
</script>
</body>
</html>
