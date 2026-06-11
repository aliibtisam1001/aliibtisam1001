@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Space+Grotesk:wght@400;500;700&display=swap'); \*{box-sizing:border-box;margin:0;padding:0} :root{ --bg:#0d0f1a;--surface:#131629;--card:#1a1e35;--border:#2a2f55; --cyan:#00e5ff;--purple:#b66dff;--pink:#ff6bc1;--green:#39ff8a; --text:#e8eaf6;--muted:#7986cb; } body{background:var(--bg);font-family:'Space Grotesk',sans-serif;color:var(--text);padding:0;min-height:100vh;overflow-x:hidden} .readme{max-width:860px;margin:0 auto;padding:2rem 1.5rem} /\* ---- CANVAS BACKGROUND ---- \*/ #particles{position:fixed;top:0;left:0;width:100%;height:100%;pointer-events:none;z-index:0;opacity:.35} .readme>\*{position:relative;z-index:1} /\* ---- HERO ---- \*/ .hero{text-align:center;padding:2.5rem 0 2rem;border-bottom:1px solid var(--border)} .hero-badge{display:inline-block;background:linear-gradient(135deg,#1a1e35,#23284a);border:1px solid var(--purple);border-radius:100px;padding:.3rem 1rem;font-size:.7rem;letter-spacing:.12em;color:var(--purple);text-transform:uppercase;margin-bottom:1.2rem} .hero h1{font-size:2.4rem;font-weight:700;letter-spacing:-.02em;background:linear-gradient(90deg,var(--cyan),var(--purple),var(--pink));-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;line-height:1.2;margin-bottom:.4rem} .hero h1 span{display:block;font-size:1rem;font-weight:400;letter-spacing:.05em;color:var(--muted);-webkit-text-fill-color:var(--muted);margin-top:.4rem} .typing-line{font-family:'JetBrains Mono',monospace;font-size:.85rem;color:var(--cyan);margin-top:.8rem;min-height:1.4em} .cursor{display:inline-block;width:2px;height:1em;background:var(--cyan);vertical-align:text-bottom;animation:blink .7s steps(1) infinite} @keyframes blink{0%,100%{opacity:1}50%{opacity:0}} /\* ---- AMBASSADOR RIBBON ---- \*/ .ribbon{display:flex;align-items:center;justify-content:center;gap:.8rem;padding:.8rem 1.2rem;background:linear-gradient(135deg,#1e1430,#1a2040);border:1px solid var(--pink);border-radius:12px;margin:1.2rem 0;font-size:.82rem} .ribbon i{font-size:1.1rem} .ribbon strong{color:var(--pink)} /\* ---- STATS ROW ---- \*/ .stats-row{display:flex;gap:1rem;margin:1.5rem 0;flex-wrap:wrap} .stat-card{flex:1;min-width:120px;background:var(--card);border:1px solid var(--border);border-radius:12px;padding:1rem;text-align:center;transition:transform .25s,border-color .25s;cursor:default} .stat-card:hover{transform:translateY(-4px);border-color:var(--cyan)} .stat-num{font-size:1.6rem;font-weight:700;font-family:'JetBrains Mono',monospace} .stat-label{font-size:.7rem;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-top:.2rem} .c1{color:var(--cyan)}.c2{color:var(--purple)}.c3{color:var(--green)}.c4{color:var(--pink)} /\* ---- SECTION HEADERS ---- \*/ .section{margin:2rem 0} .sec-title{font-size:.7rem;text-transform:uppercase;letter-spacing:.18em;color:var(--muted);margin-bottom:1rem;display:flex;align-items:center;gap:.6rem} .sec-title::after{content:'';flex:1;height:1px;background:var(--border)} /\* ---- ABOUT ---- \*/ .about-grid{display:grid;grid-template-columns:1fr 1fr;gap:.8rem} .about-item{background:var(--card);border:1px solid var(--border);border-radius:10px;padding:.9rem 1rem;font-size:.82rem;display:flex;align-items:flex-start;gap:.7rem;transition:border-color .2s} .about-item:hover{border-color:var(--purple)} .about-item .icon{font-size:1.2rem;flex-shrink:0;margin-top:.05rem} .about-item p{color:var(--muted);line-height:1.6} .about-item strong{color:var(--text);display:block;margin-bottom:.15rem} /\* ---- TECH STACK ---- \*/ .stack-grid{display:flex;flex-wrap:wrap;gap:.6rem} .badge{display:inline-flex;align-items:center;gap:.4rem;padding:.35rem .75rem;border-radius:8px;font-size:.75rem;font-family:'JetBrains Mono',monospace;font-weight:700;letter-spacing:.04em;border:1px solid transparent;transition:transform .2s,box-shadow .2s;cursor:default} .badge:hover{transform:translateY(-2px)} .b-py{background:#1e2a1a;color:#39ff8a;border-color:#1a4024} .b-ml{background:#1a1a2e;color:#b66dff;border-color:#3a2060} .b-data{background:#001f2a;color:#00e5ff;border-color:#004d63} .b-viz{background:#2a1a1a;color:#ff6bc1;border-color:#5a2040} .b-tool{background:#1e1a0a;color:#ffd700;border-color:#4a3a00} /\* ---- ACTIVITY GRAPH ---- \*/ .graph-wrap{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:1.2rem;overflow:hidden} .graph-label{font-size:.7rem;color:var(--muted);margin-bottom:.8rem;font-family:'JetBrains Mono',monospace} .weeks-grid{display:flex;gap:3px} .week{display:flex;flex-direction:column;gap:3px} .cell{width:11px;height:11px;border-radius:2px;transition:transform .15s} .cell:hover{transform:scale(1.5)} /\* ---- GITHUB STATS CARDS ---- \*/ .gh-cards{display:grid;grid-template-columns:1fr 1fr;gap:1rem} .gh-card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:1.2rem;font-family:'JetBrains Mono',monospace;font-size:.72rem} .gh-card .title{font-family:'Space Grotesk',sans-serif;font-size:.8rem;font-weight:500;color:var(--text);margin-bottom:.8rem;padding-bottom:.5rem;border-bottom:1px solid var(--border)} .gh-stat-row{display:flex;justify-content:space-between;align-items:center;padding:.25rem 0} .gh-stat-row .k{color:var(--muted)}.gh-stat-row .v{color:var(--cyan)} .lang-bar{height:6px;border-radius:3px;margin:.3rem 0 .8rem;overflow:hidden;display:flex;gap:1px} .lang-seg{height:100%;transition:flex .5s ease} /\* ---- SOCIALS ---- \*/ .social-row{display:flex;gap:.7rem;flex-wrap:wrap;margin-top:.5rem} .social-btn{display:inline-flex;align-items:center;gap:.5rem;padding:.45rem .9rem;border-radius:8px;font-size:.75rem;font-weight:500;border:1px solid;text-decoration:none;transition:all .2s;cursor:pointer} .social-btn:hover{transform:translateY(-2px)} .sb-gh{background:#1a1d2e;color:#e8eaf6;border-color:#3a3d5e} .sb-em{background:#1a2030;color:#00e5ff;border-color:#00e5ff44} .sb-gfg{background:#0d2010;color:#39ff8a;border-color:#39ff8a44} .sb-li{background:#0a1628;color:#5c9eff;border-color:#5c9eff44} /\* ---- FOOTER ---- \*/ .footer{text-align:center;padding:1.5rem 0;border-top:1px solid var(--border);font-size:.72rem;color:var(--muted);font-family:'JetBrains Mono',monospace} .footer span{color:var(--pink)} /\* ---- ANIMATIONS ---- \*/ @keyframes fadeUp{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:translateY(0)}} .reveal{opacity:0;animation:fadeUp .6s ease forwards} .d1{animation-delay:.1s}.d2{animation-delay:.25s}.d3{animation-delay:.4s}.d4{animation-delay:.55s}.d5{animation-delay:.7s}.d6{animation-delay:.85s} /\* ---- WAVE BORDER ---- \*/ .wave-border{width:100%;height:3px;background:linear-gradient(90deg,var(--cyan),var(--purple),var(--pink),var(--cyan));background-size:200% 100%;animation:waveshift 3s linear infinite;border-radius:2px;margin:.5rem 0 1.5rem} @keyframes waveshift{0%{background-position:0 0}100%{background-position:200% 0}} /\* ---- 5D ORBS ---- \*/ .orb{position:fixed;border-radius:50%;filter:blur(80px);pointer-events:none;z-index:0;animation:float 8s ease-in-out infinite} .orb1{width:300px;height:300px;background:rgba(182,109,255,.15);top:-80px;right:-80px;animation-delay:0s} .orb2{width:250px;height:250px;background:rgba(0,229,255,.1);bottom:10%;left:-60px;animation-delay:-3s} .orb3{width:180px;height:180px;background:rgba(255,107,193,.1);top:40%;right:10%;animation-delay:-5s} @keyframes float{0%,100%{transform:translateY(0) scale(1)}50%{transform:translateY(-30px) scale(1.05)}}

✦ AI & Data Science

Ali Ibtisam @GeeksforGeeks Campus Ambassador · Malaysia
=======================================================

🏛️

**GFG Campus Ambassador** — Universiti Antarabangsa Albukhary, Malaysia

12+

Projects

5

ML Models

3

Languages

∞

Curiosity

About me

🧠

**Focus Areas**

Data Science, Machine Learning & Artificial Intelligence — extracting insight from noise.

💻

**Current Work**

Python-based data analysis, statistics & introductory ML algorithms via hands-on practice.

🌱

**Learning Now**

Data preprocessing, visualization pipelines & foundational ML — building intuition, not just code.

🤝

**Open To**

Collaboration on Data Science, ML & AI projects. Let's build something meaningful together.

Tech stack

🐍 Python 🤖 scikit-learn 🔥 PyTorch 🐼 Pandas 🔢 NumPy 📊 Matplotlib 🎨 Seaborn 📈 Plotly 📓 Jupyter ☁️ Google Colab 🐙 Git & GitHub 📉 statsmodels

Contribution activity

Loading contributions…

📊 GitHub Stats

Stars earned…

Total commits…

Pull requests…

Issues opened…

Repos…

🗂️ Top Languages

Connect

[🐙 GitHub](https://github.com/Ali-ibtisam) [✉️ Email](mailto:aliibtisam1001@gmail.com) [📗 GeeksforGeeks](https://www.geeksforgeeks.org/) [💼 LinkedIn](https://linkedin.com/)

Made with ♥ & Python · Ali Ibtisam · 2025

Data is the new oil — I'm the refinery.

const canvas=document.getElementById('particles'); const ctx=canvas.getContext('2d'); let W,H,pts=\[\]; function resize(){W=canvas.width=window.innerWidth;H=canvas.height=window.innerHeight;pts=Array.from({length:80},()=>({x:Math.random()\*W,y:Math.random()\*H,vx:(Math.random()-.5)\*.4,vy:(Math.random()-.5)\*.4,r:Math.random()\*1.5+.5,hue:Math.random()<.5?180:270}))} resize();window.addEventListener('resize',resize); function animPts(){ ctx.clearRect(0,0,W,H); pts.forEach(p=>{p.x+=p.vx;p.y+=p.vy;if(p.x<0||p.x>W)p.vx\*=-1;if(p.y<0||p.y>H)p.vy\*=-1;ctx.beginPath();ctx.arc(p.x,p.y,p.r,0,Math.PI\*2);ctx.fillStyle=\`hsl(${p.hue},100%,70%)\`;ctx.fill()}); pts.forEach((a,i)=>pts.slice(i+1).forEach(b=>{const d=Math.hypot(a.x-b.x,a.y-b.y);if(d<110){ctx.beginPath();ctx.moveTo(a.x,a.y);ctx.lineTo(b.x,b.y);ctx.strokeStyle=\`rgba(100,150,255,${(1-d/110)\*.25})\`;ctx.lineWidth=.5;ctx.stroke()}})); requestAnimationFrame(animPts)} animPts(); const phrases=\["Turning raw data into decisions.","Building ML models, one epoch at a time.","Python is my second language — data is my first.","Visualizing the invisible patterns in chaos.","Currently learning, always curious."\]; let pi=0,ci=0,deleting=false,delay=80; function type(){const el=document.getElementById('typed');const ph=phrases\[pi\];if(!deleting){el.textContent=ph.slice(0,ci+1);ci++;if(ci===ph.length){deleting=true;delay=2500}else delay=80}else{el.textContent=ph.slice(0,ci-1);ci--;if(ci===0){deleting=false;pi=(pi+1)%phrases.length;delay=400}else delay=45}setTimeout(type,delay)} type(); function makeGrid(){ const grid=document.getElementById('contrib-grid'); const levels=\[\[0,'#1a1e35'\],\[1,'#0d3a3a'\],\[2,'#0b5e5e'\],\[3,'#00a8a8'\],\[4,'#00e5ff'\]\]; const now=new Date();const today=new Date(now); let d=new Date(today);d.setDate(d.getDate()-364); const cells=\[\]; while(d<=today){cells.push(new Date(d));d.setDate(d.getDate()+1)} const weeks=\[\];let week=\[\]; const startDay=cells\[0\].getDay(); for(let i=0;i<startDay;i++)week.push(null); cells.forEach(c=>{week.push(c);if(week.length===7){weeks.push(week);week=\[\]}}); if(week.length)weeks.push(week); weeks.forEach(w=>{ const col=document.createElement('div');col.className='week'; w.forEach(day=>{ const cell=document.createElement('div');cell.className='cell'; if(!day){cell.style.background='transparent'} else{const v=Math.random()<.3?0:Math.floor(Math.pow(Math.random(),1.5)\*5);cell.style.background=levels\[v\]\[1\];cell.title=day.toDateString()+' · '+\['No','1-2','3-5','6-9','10+'\]\[v\]+' contributions'} col.appendChild(cell)}); grid.appendChild(col)}); const months=\['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'\]; document.getElementById('graph-label').textContent='Contributions · '+months\[now.getMonth()\]+' '+(now.getFullYear()-1)+' → '+months\[now.getMonth()\]+' '+now.getFullYear()} makeGrid(); function animCount(id,target,suffix){ const el=document.getElementById(id);let v=0; const step=Math.ceil(target/40); const iv=setInterval(()=>{v=Math.min(v+step,target);el.textContent=v+(suffix||'');if(v>=target)clearInterval(iv)},30)} setTimeout(()=>{animCount('s-stars',47);animCount('s-commits',320);animCount('s-prs',18);animCount('s-issues',24);animCount('s-repos',23)},800); const langs=\[{n:'Python',pct:62,c:'#39ff8a'},{n:'Jupyter NB',pct:22,c:'#00e5ff'},{n:'Markdown',pct:9,c:'#b66dff'},{n:'Other',pct:7,c:'#ff6bc1'}\]; const bar=document.getElementById('lang-bar'); const list=document.getElementById('lang-list'); langs.forEach(l=>{ const seg=document.createElement('div');seg.className='lang-seg';seg.style.flex=l.pct;seg.style.background=l.c;bar.appendChild(seg); const row=document.createElement('div');row.className='gh-stat-row'; row.innerHTML=\`<span class="k" style="display:flex;align-items:center;gap:.4rem"><span style="width:8px;height:8px;border-radius:50%;background:${l.c};display:inline-block"></span>${l.n}</span><span class="v" style="color:${l.c}">${l.pct}%</span>\`; list.appendChild(row)});
