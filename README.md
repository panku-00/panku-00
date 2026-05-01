## Hi there 👋

<!--
**panku-00/panku-00** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
[pankaj_github_profile_preview.html](https://github.com/user-attachments/files/27270194/pankaj_github_profile_preview.html)

<style>
@import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Nunito:wght@400;600;700;800&display=swap');

*{margin:0;padding:0;box-sizing:border-box;}

.pk-root{
  background:#fffdf7;
  font-family:'Nunito',sans-serif;
  padding:28px 24px;
  border-radius:20px;
  overflow:hidden;
  position:relative;
}

.confetti-bg{
  position:absolute;inset:0;
  background-image:
    radial-gradient(circle at 10% 20%, #ffd6e744 0%, transparent 40%),
    radial-gradient(circle at 90% 10%, #d6f0ff44 0%, transparent 40%),
    radial-gradient(circle at 50% 90%, #d6ffd644 0%, transparent 40%);
  pointer-events:none;z-index:0;
}

.pk-root>*{position:relative;z-index:1;}

.wave-top{
  display:flex;gap:6px;align-items:center;
  margin-bottom:18px;flex-wrap:wrap;
}

.pill{
  font-size:11px;font-weight:700;padding:4px 12px;border-radius:20px;
  letter-spacing:.5px;animation:popIn .4s cubic-bezier(.34,1.56,.64,1) both;
}
.pill-pink{background:#ffe4ef;color:#c2185b;}
.pill-blue{background:#dbeeff;color:#1565c0;}
.pill-yellow{background:#fff8d6;color:#f57f17;}
.pill-green{background:#d6ffe4;color:#1b5e20;}

@keyframes popIn{from{transform:scale(0);opacity:0;}to{transform:scale(1);opacity:1;}}

.hero{text-align:center;margin-bottom:24px;}

.avatar-ring{
  width:88px;height:88px;border-radius:50%;
  border:4px solid transparent;
  background:linear-gradient(white,white) padding-box,
             linear-gradient(135deg,#ff6b9d,#ffb347,#56d8ff,#a8ff78) border-box;
  display:inline-flex;align-items:center;justify-content:center;
  font-family:'Fredoka One',cursive;font-size:32px;
  color:#ff6b9d;margin-bottom:12px;
  animation:spin-border 4s linear infinite;
}

@keyframes spin-border{
  0%{filter:hue-rotate(0deg);}
  100%{filter:hue-rotate(360deg);}
}

.hero-name{
  font-family:'Fredoka One',cursive;
  font-size:30px;letter-spacing:1px;
  background:linear-gradient(135deg,#ff6b9d,#ffb347,#56d8ff);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  background-clip:text;
  animation:shimmer 3s linear infinite;
  background-size:200%;
}

@keyframes shimmer{0%{background-position:0%;}100%{background-position:200%;}}

.hero-sub{font-size:13px;color:#888;margin-top:4px;font-weight:600;}

.typed-wrap{
  display:inline-flex;align-items:center;gap:6px;
  background:#fff0f5;border-radius:12px;padding:6px 14px;
  margin-top:10px;font-size:13px;font-weight:700;color:#e91e8c;
}

.cursor{display:inline-block;width:2px;height:14px;background:#e91e8c;animation:blink .8s step-end infinite;}
@keyframes blink{50%{opacity:0;}}

.section-head{
  display:flex;align-items:center;gap:8px;
  font-family:'Fredoka One',cursive;font-size:16px;
  color:#444;margin:20px 0 10px;
}
.section-head .emoji-icon{font-size:18px;}
.section-head::after{content:'';flex:1;height:2px;border-radius:2px;
  background:linear-gradient(to right,#ffb34744,transparent);}

.about-card{
  background:#fff;border-radius:16px;
  border:2px solid #ffe4a0;
  padding:16px;font-size:13px;line-height:1.9;
  font-family:'Courier New',monospace;color:#444;
}
.about-card .k{color:#e91e8c;font-weight:700;}
.about-card .v{color:#1565c0;}
.about-card .cm{color:#bbb;}

.skills-grid{
  display:grid;grid-template-columns:1fr 1fr;gap:10px;
  margin-bottom:4px;
}

.skill-card{
  background:#fff;border-radius:14px;
  border:2px solid #eee;
  padding:12px 14px;
  transition:transform .2s,border-color .2s;
  cursor:default;
}
.skill-card:hover{transform:translateY(-3px);}
.skill-card:nth-child(1){border-color:#ffb3c6;}
.skill-card:nth-child(2){border-color:#b3d9ff;}
.skill-card:nth-child(3){border-color:#b3f5d5;}
.skill-card:nth-child(4){border-color:#ffd6b3;}
.skill-card:nth-child(5){border-color:#d6b3ff;}
.skill-card:nth-child(6){border-color:#b3f0ff;}

.sk-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px;}
.sk-name{font-size:12px;font-weight:800;color:#333;}
.sk-pct{font-size:11px;font-weight:700;}

.sk-bar{height:7px;border-radius:4px;background:#f0f0f0;overflow:hidden;}
.sk-fill{height:100%;border-radius:4px;transform:scaleX(0);transform-origin:left;
  transition:transform 1.1s cubic-bezier(.16,1,.3,1);}
.sk-fill-1{background:linear-gradient(to right,#ff6b9d,#ff9a8b);}
.sk-fill-2{background:linear-gradient(to right,#56d8ff,#4facfe);}
.sk-fill-3{background:linear-gradient(to right,#43e97b,#38f9d7);}
.sk-fill-4{background:linear-gradient(to right,#ffb347,#ffcc02);}
.sk-fill-5{background:linear-gradient(to right,#a18cd1,#fbc2eb);}
.sk-fill-6{background:linear-gradient(to right,#0acffe,#495aff);}

.stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:4px;}

.stat-bubble{
  background:#fff;border-radius:16px;
  border:2px solid #ffe4a0;
  text-align:center;padding:12px 8px;
  transition:transform .2s;cursor:default;
}
.stat-bubble:hover{transform:scale(1.06);}
.stat-num{
  font-family:'Fredoka One',cursive;font-size:20px;
  background:linear-gradient(135deg,#ff6b9d,#ffb347);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
}
.stat-lbl{font-size:10px;font-weight:700;color:#aaa;letter-spacing:.5px;margin-top:2px;}

.badge-cloud{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:4px;}
.tag{
  font-size:11px;font-weight:700;padding:5px 12px;border-radius:20px;
  cursor:default;transition:transform .15s;
}
.tag:hover{transform:scale(1.08);}
.t1{background:#ffe4ef;color:#c2185b;}
.t2{background:#dbeeff;color:#1565c0;}
.t3{background:#d6ffe4;color:#1b5e20;}
.t4{background:#fff3d6;color:#e65100;}
.t5{background:#ede7ff;color:#4527a0;}
.t6{background:#d6faff;color:#006064;}

.goal-list{display:flex;flex-direction:column;gap:8px;}
.goal-item{
  background:#fff;border-radius:12px;border:2px solid #f0f0f0;
  padding:10px 14px;display:flex;align-items:center;gap:10px;
  font-size:12px;font-weight:700;color:#444;
}
.goal-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0;}

.connect-wrap{display:flex;flex-wrap:wrap;gap:8px;}
.c-btn{
  display:inline-flex;align-items:center;gap:6px;
  font-family:'Nunito',sans-serif;font-size:11px;font-weight:800;
  padding:7px 16px;border-radius:20px;border:none;cursor:pointer;
  letter-spacing:.3px;transition:transform .2s,opacity .2s;
}
.c-btn:hover{transform:translateY(-2px);opacity:.9;}
.cb1{background:#ffe4ef;color:#c2185b;}
.cb2{background:#dbeeff;color:#1565c0;}
.cb3{background:#d6ffe4;color:#1b5e20;}
.cb4{background:#fff3d6;color:#e65100;}

.footer-fun{
  text-align:center;margin-top:20px;
  font-size:11px;color:#bbb;font-weight:700;letter-spacing:.5px;
}

.float-shapes{position:absolute;top:0;right:0;pointer-events:none;z-index:0;}
</style>

<div class="pk-root">
  <div class="confetti-bg"></div>

  <div class="wave-top">
    <span class="pill pill-pink" style="animation-delay:.05s">Student</span>
    <span class="pill pill-blue" style="animation-delay:.1s">Developer</span>
    <span class="pill pill-yellow" style="animation-delay:.15s">Chandigarh, India</span>
    <span class="pill pill-green" style="animation-delay:.2s">Open to opportunities</span>
  </div>

  <div class="hero">
    <div class="avatar-ring">PK</div>
    <div class="hero-name">Pankaj Kumar</div>
    <div class="hero-sub">Building cool stuff, learning every day ✨</div>
    <div class="typed-wrap">
      <span id="typed-text"></span><span class="cursor"></span>
    </div>
  </div>

  <div class="section-head"><span class="emoji-icon">🧑‍💻</span> About me</div>
  <div class="about-card">
    <span class="cm">// hello world!</span><br/>
    <span class="k">const</span> pankaj = {<br/>
    &nbsp;&nbsp;<span class="k">name:</span> <span class="v">"Pankaj Kumar"</span>,<br/>
    &nbsp;&nbsp;<span class="k">from:</span> <span class="v">"Chandigarh, India 🇮🇳"</span>,<br/>
    &nbsp;&nbsp;<span class="k">role:</span> <span class="v">"Student &amp; Developer"</span>,<br/>
    &nbsp;&nbsp;<span class="k">loves:</span> [<span class="v">"coding"</span>, <span class="v">"learning"</span>, <span class="v">"chai ☕"</span>],<br/>
    &nbsp;&nbsp;<span class="k">currently:</span> <span class="v">"levelling up every day"</span><br/>
    }
  </div>

  <div class="section-head"><span class="emoji-icon">⚡</span> Skills</div>
  <div class="skills-grid" id="skills-grid"></div>

  <div class="section-head"><span class="emoji-icon">📊</span> Stats</div>
  <div class="stats-row">
    <div class="stat-bubble"><div class="stat-num" id="s1">0</div><div class="stat-lbl">COMMITS</div></div>
    <div class="stat-bubble"><div class="stat-num" id="s2">0</div><div class="stat-lbl">REPOS</div></div>
    <div class="stat-bubble"><div class="stat-num" id="s3">0</div><div class="stat-lbl">STARS</div></div>
    <div class="stat-bubble"><div class="stat-num" id="s4">0</div><div class="stat-lbl">PRs</div></div>
  </div>

  <div class="section-head"><span class="emoji-icon">🏷️</span> Tech stack</div>
  <div class="badge-cloud" id="badge-cloud"></div>

  <div class="section-head"><span class="emoji-icon">🎯</span> Current goals</div>
  <div class="goal-list">
    <div class="goal-item"><div class="goal-dot" style="background:#ff6b9d;"></div>Master System Design & DSA</div>
    <div class="goal-item"><div class="goal-dot" style="background:#56d8ff;"></div>Build my first open-source project</div>
    <div class="goal-item"><div class="goal-dot" style="background:#43e97b;"></div>Get deeper into ML / AI</div>
    <div class="goal-item"><div class="goal-dot" style="background:#ffb347;"></div>Land my first dev internship</div>
  </div>

  <div class="section-head"><span class="emoji-icon">🌐</span> Connect with me</div>
  <div class="connect-wrap">
    <button class="c-btn cb1">💼 LinkedIn</button>
    <button class="c-btn cb2">🐦 Twitter</button>
    <button class="c-btn cb3">🌍 Portfolio</button>
    <button class="c-btn cb4">✉️ Email</button>
  </div>

  <div class="footer-fun">✨ Made with curiosity + chai in Chandigarh ✨</div>
</div>

<script>
const skills=[
  {name:'Java',pct:78,cls:'sk-fill-1'},
  {name:'JavaScript / TypeScript',pct:82,cls:'sk-fill-2'},
  {name:'React / Next.js',pct:75,cls:'sk-fill-3'},
  {name:'Node.js',pct:72,cls:'sk-fill-4'},
  {name:'Docker / DevOps',pct:60,cls:'sk-fill-5'},
  {name:'Machine Learning / AI',pct:58,cls:'sk-fill-6'},
];
const pctColors=['#ff6b9d','#56d8ff','#43e97b','#ffb347','#a18cd1','#0acffe'];

const sg=document.getElementById('skills-grid');
skills.forEach((s,i)=>{
  sg.innerHTML+=`<div class="skill-card">
    <div class="sk-top">
      <span class="sk-name">${s.name}</span>
      <span class="sk-pct" style="color:${pctColors[i]}">${s.pct}%</span>
    </div>
    <div class="sk-bar"><div class="sk-fill ${s.cls}" data-pct="${s.pct/100}" id="sf${i}"></div></div>
  </div>`;
});

const tags=[
  {t:'Java',c:'t1'},{t:'JavaScript',c:'t2'},{t:'TypeScript',c:'t2'},
  {t:'React',c:'t3'},{t:'Next.js',c:'t3'},{t:'Node.js',c:'t4'},
  {t:'Docker',c:'t5'},{t:'Git',c:'t6'},{t:'ML / AI',c:'t1'},
  {t:'REST APIs',c:'t2'},{t:'Linux',c:'t4'},{t:'SQL',c:'t3'},
];
const bc=document.getElementById('badge-cloud');
tags.forEach(({t,c})=>{ bc.innerHTML+=`<span class="tag ${c}">${t}</span>`; });

const phrases=['Java Developer','React Builder','ML Explorer','Open Source Fan','Chai Lover ☕'];
let pi=0,ci=0,del=false;
const tel=document.getElementById('typed-text');
function typeLoop(){
  const word=phrases[pi];
  if(!del){
    tel.textContent=word.slice(0,ci+1);
    ci++;
    if(ci===word.length){del=true;setTimeout(typeLoop,1400);return;}
  } else {
    tel.textContent=word.slice(0,ci-1);
    ci--;
    if(ci===0){del=false;pi=(pi+1)%phrases.length;}
  }
  setTimeout(typeLoop,del?60:90);
}
typeLoop();

function countUp(id,target,dur){
  let v=0;const step=Math.ceil(target/(dur/30));
  const t=setInterval(()=>{v=Math.min(v+step,target);document.getElementById(id).textContent=v;if(v>=target)clearInterval(t);},30);
}
setTimeout(()=>{
  countUp('s1',342,900);
  countUp('s2',18,700);
  countUp('s3',54,800);
  countUp('s4',23,600);
},300);

setTimeout(()=>{
  document.querySelectorAll('.sk-fill').forEach(el=>{
    el.style.transform=`scaleX(${el.dataset.pct})`;
  });
},500);
</script>
