<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>E Saiprasad Dora | Portfolio</title>
<style>
:root{--bg:#0b0f1a;--card:#141a2b;--line:#222b45;--tx:#e8ecf8;--mut:#8f9ac0;--a:#7c5cff;--b:#00d4ff}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:'Segoe UI',system-ui,sans-serif;background:var(--bg);color:var(--tx);line-height:1.6}
a{color:inherit;text-decoration:none}
.grad{background:linear-gradient(90deg,var(--a),var(--b));-webkit-background-clip:text;background-clip:text;color:transparent}
nav{position:sticky;top:0;z-index:9;display:flex;justify-content:space-between;align-items:center;padding:14px 6%;background:#0b0f1acc;backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
nav b{font-size:1.1rem}nav div a{margin-left:20px;color:var(--mut);font-size:.95rem}nav div a:hover{color:var(--b)}
section{padding:80px 6%;max-width:1100px;margin:auto}
h2{font-size:2rem;margin-bottom:30px}
.hero{display:flex;gap:50px;align-items:center;flex-wrap:wrap-reverse;min-height:80vh}
.hero .t{flex:1;min-width:280px}
.hero h1{font-size:clamp(2.2rem,6vw,3.6rem);line-height:1.15}
.type{color:var(--b);font-size:1.3rem;margin:12px 0;min-height:2em;font-weight:600}
.hero p{color:var(--mut);max-width:520px}
.btns{margin-top:26px;display:flex;gap:12px;flex-wrap:wrap}
.btn{padding:12px 24px;border-radius:30px;font-weight:600;border:1px solid var(--a);transition:.25s;display:inline-block}
.btn.p{background:linear-gradient(90deg,var(--a),var(--b));border:0;color:#fff}
.btn:hover{transform:translateY(-3px);box-shadow:0 8px 25px #7c5cff55}
.photo{width:270px;height:270px;border-radius:50%;padding:5px;background:conic-gradient(var(--a),var(--b),var(--a));animation:spin 8s linear infinite;cursor:pointer;position:relative;margin:auto}
.photo .in{width:100%;height:100%;border-radius:50%;background:var(--card);overflow:hidden;display:grid;place-items:center;animation:spin 8s linear infinite reverse;font-size:4rem;font-weight:700}
.photo img{width:100%;height:100%;object-fit:cover;display:block}
@keyframes spin{to{transform:rotate(360deg)}}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:16px;margin-top:30px}
.stat{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px;text-align:center}
.stat b{font-size:1.8rem;display:block}.stat span{color:var(--mut);font-size:.85rem}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:24px;transition:.3s}
.card:hover{transform:translateY(-6px);border-color:var(--a);box-shadow:0 12px 30px #7c5cff30}
.skill{margin-bottom:16px}.skill div{display:flex;justify-content:space-between;font-size:.92rem;margin-bottom:6px}
.bar{height:8px;background:var(--line);border-radius:8px;overflow:hidden}
.bar i{display:block;height:100%;width:0;background:linear-gradient(90deg,var(--a),var(--b));border-radius:8px;transition:width 1.4s ease}
.chips{display:flex;flex-wrap:wrap;gap:10px}
.chip{padding:10px 18px;background:var(--card);border:1px solid var(--line);border-radius:30px;font-size:.93rem;transition:.25s}
.chip:hover{border-color:var(--b);color:var(--b);transform:scale(1.06)}
.proj .ic{font-size:2.2rem}.proj h3{margin:8px 0}.proj p{color:var(--mut);font-size:.93rem}
.tags{margin:14px 0;display:flex;gap:8px;flex-wrap:wrap}.tags span{font-size:.75rem;padding:4px 10px;border-radius:20px;background:#7c5cff22;color:#b7a6ff}
.proj a{color:var(--b);font-weight:600;font-size:.92rem}
/* Visible by default so preview always works; animation is progressive enhancement */
.rev{opacity:1;transform:none;transition:opacity .8s,transform .8s}
.rev.pending{opacity:0;transform:translateY(30px)}
.rev.on{opacity:1;transform:none}
.contact{text-align:center}.contact p{color:var(--mut);margin-bottom:24px}
footer{text-align:center;color:var(--mut);padding:30px;border-top:1px solid var(--line);font-size:.85rem}
@media(max-width:600px){nav div a:not(:last-child){display:none}}
</style>
</head>
<body>
<nav><b class="grad">&lt;SaiPrasad /&gt;</b>
<div><a href="#about">About</a><a href="#skills">Skills</a><a href="#ai">AI Tools</a><a href="#projects">Projects</a><a href="#contact">Contact</a></div></nav>
<section class="hero" id="home">
<div class="t">
<p>👋 Hello, I'm</p>
<h1><span class="grad">E Saiprasad Dora</span></h1>
<div class="type" id="type"></div>
<p>B.Tech CSE student who learns by building. I make AI-powered apps, web projects and problem-solving tools, and I'm aiming for a top software engineering role.</p>
<div class="btns">
<a class="btn p" href="#projects">View Projects</a>
<a class="btn" href="https://github.com/dorasaiprasad77-oss" target="_blank" rel="noopener">GitHub</a>
<a class="btn" href="https://www.linkedin.com/in/e-saiprasad-dora-6131a2330" target="_blank" rel="noopener">LinkedIn</a>
</div></div>
<div>
<div class="photo" id="photo" title="Click to change photo"><div class="in" id="pin">SD</div></div>
<input type="file" id="file" accept="image/*" hidden>
</div>
</section>
<section id="about" class="rev">
<h2>About <span class="grad">Me</span></h2>
<div class="card"><p>I'm a Computer Science Engineering student who loves understanding how things work internally. I build real-world projects in Python, Java, C++ and web technologies, and I use modern AI tools to learn and ship faster. I practise DSA daily and believe in <b>learning by building</b>.</p></div>
<div class="stats">
<div class="stat"><b class="grad" data-n="22">0</b><span>Repositories</span></div>
<div class="stat"><b class="grad" data-n="9">0</b><span>Languages &amp; Tech</span></div>
<div class="stat"><b class="grad" data-n="6">0</b><span>AI Tools Used</span></div>
<div class="stat"><b class="grad" data-n="8">0</b><span>Featured Projects</span></div>
</div>
</section>
<section id="skills" class="rev">
<h2>Languages &amp; <span class="grad">Skills</span></h2>
<div class="grid"><div class="card" id="langs"></div>
<div class="card"><h3 style="margin-bottom:16px">Tech Stack</h3><div class="chips" id="stack"></div></div></div>
</section>
<section id="ai" class="rev">
<h2>AI <span class="grad">Tools</span> I Use</h2>
<div class="grid" id="aitools"></div>
</section>
<section id="projects" class="rev">
<h2>Top <span class="grad">Projects</span></h2>
<div class="grid" id="projs"></div>
</section>
<section id="contact" class="contact rev">
<h2>Let's <span class="grad">Connect</span></h2>
<p>Open to internships, collaborations and learning opportunities.</p>
<div class="btns" style="justify-content:center">
<a class="btn p" href="https://www.linkedin.com/in/e-saiprasad-dora-6131a2330" target="_blank" rel="noopener">Message on LinkedIn</a>
<a class="btn" href="https://github.com/dorasaiprasad77-oss?tab=repositories" target="_blank" rel="noopener">All Repositories</a>
</div></section>
<footer>© 2026 E Saiprasad Dora · Code + Debug + Repeat</footer>
<script>
// ===== EDIT YOUR DATA HERE =====
const PHOTO = "https://avatars.githubusercontent.com/u/229964646?v=4";
const GH = "https://github.com/dorasaiprasad77-oss/";
const roles = ["B.Tech CSE Student", "Web Developer", "AI Project Builder", "DSA Problem Solver"];
const langs = [["Python", 80], ["Java", 70], ["C++", 75], ["JavaScript", 72], ["HTML & CSS", 88], ["C", 70]];
const stack = ["React", "Tailwind CSS", "Node.js", "Git", "GitHub", "Figma", "VS Code", "DSA", "OOP"];
const ai = [
  ["🤖", "Claude", "Coding help, debugging, learning concepts"],
  ["💬", "ChatGPT", "Brainstorming & explanations"],
  ["🧑‍✈️", "GitHub Copilot", "AI pair programming in the editor"],
  ["✨", "Gemini", "Research & quick prototyping"],
  ["🎨", "AI Image Tools", "Design inspiration & assets"],
  ["🧠", "Prompt Engineering", "Writing precise prompts for better results"]
];
const projs = [
  ["🌾", "AgroVision", "AI-based crop and species identification app that helps farmers recognise plants.", ["Python", "AI/ML"], "https://github.com/dorasaiprasad77-oss?tab=repositories"],
  ["🎨", "PicAura", "Image enhancement and processing tool to improve photo quality.", ["Image Processing", "Python"], "https://github.com/dorasaiprasad77-oss?tab=repositories"],
  ["🔐", "PassNest", "Secure password manager to store and protect credentials.", ["Security", "Java"], "https://github.com/dorasaiprasad77-oss?tab=repositories"],
  ["🎙️", "Jarvis AI", "Voice assistant that listens, plays YouTube music, and tells date and time.", ["Python", "Speech AI"], GH + "jarves-ai-"],
  ["📡", "NIST 5G Dashboard", "Dashboard for visualising 5G network data.", ["Web", "Dashboard"], GH + "nist-5g-dashboard-"],
  ["📷", "5G Camera Dashboard", "Camera monitoring dashboard built around 5G connectivity.", ["Web", "IoT"], GH + "5g-camera-dashbord"],
  ["🏨", "Hotel Management", "Hotel management system built with C++ and OOP concepts.", ["C++", "OOP"], GH + "Hotel-management-management-"],
  ["🌐", "My Portfolio", "This personal portfolio website.", ["HTML", "CSS", "JS"], GH + "projects"]
];

// DOM refs (avoid relying on id globals)
const pin = document.getElementById("pin");
const photo = document.getElementById("photo");
const file = document.getElementById("file");
const typeEl = document.getElementById("type");
const langsEl = document.getElementById("langs");
const stackEl = document.getElementById("stack");
const aitoolsEl = document.getElementById("aitools");
const projsEl = document.getElementById("projs");

// Photo: GitHub avatar, localStorage override, click-to-upload
function setImg(src) {
  const i = new Image();
  i.alt = "Sai Prasad";
  i.onload = () => { pin.textContent = ""; pin.appendChild(i); };
  i.onerror = () => { pin.textContent = "SD"; };
  i.src = src;
}
setImg(PHOTO);
try {
  const s = localStorage.getItem("photo");
  if (s) setImg(s);
} catch (e) {}
photo.addEventListener("click", () => file.click());
file.addEventListener("change", e => {
  const f = e.target.files[0];
  if (!f) return;
  const r = new FileReader();
  r.onload = () => {
    setImg(r.result);
    try { localStorage.setItem("photo", r.result); } catch (e) {}
  };
  r.readAsDataURL(f);
});

// Typing effect
let ri = 0, ci = 0, del = false;
(function tick() {
  const w = roles[ri];
  ci += del ? -1 : 1;
  typeEl.textContent = w.slice(0, ci) + "|";
  let d = del ? 40 : 90;
  if (!del && ci === w.length) { del = true; d = 1400; }
  else if (del && ci === 0) { del = false; ri = (ri + 1) % roles.length; d = 300; }
  setTimeout(tick, d);
})();

// Render content
langs.forEach(([n, v]) => {
  langsEl.insertAdjacentHTML("beforeend",
    `<div class="skill"><div><span>${n}</span><span>${v}%</span></div><div class="bar"><i data-w="${v}"></i></div></div>`);
});
stack.forEach(s => stackEl.insertAdjacentHTML("beforeend", `<span class="chip">${s}</span>`));
ai.forEach(([ic, n, d]) => {
  aitoolsEl.insertAdjacentHTML("beforeend",
    `<div class="card proj"><div class="ic">${ic}</div><h3>${n}</h3><p>${d}</p></div>`);
});
projs.forEach(([ic, n, d, t, l]) => {
  projsEl.insertAdjacentHTML("beforeend",
    `<div class="card proj"><div class="ic">${ic}</div><h3>${n}</h3><p>${d}</p><div class="tags">${t.map(x => `<span>${x}</span>`).join("")}</div><a href="${l}" target="_blank" rel="noopener">View on GitHub →</a></div>`);
});

// Scroll reveal + bars + counters (with fallback so preview never stays blank)
function activate(el) {
  el.classList.remove("pending");
  el.classList.add("on");
  el.querySelectorAll(".bar i").forEach(b => { b.style.width = b.dataset.w + "%"; });
  el.querySelectorAll("[data-n]").forEach(c => {
    if (c.dataset.done) return;
    c.dataset.done = "1";
    let n = 0, m = +c.dataset.n;
    const t = setInterval(() => {
      c.textContent = ++n + (n === m ? "+" : "");
      if (n >= m) clearInterval(t);
    }, 60);
  });
}

document.querySelectorAll(".rev").forEach(s => s.classList.add("pending"));

if ("IntersectionObserver" in window) {
  const io = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (!e.isIntersecting) return;
      activate(e.target);
      io.unobserve(e.target);
    });
  }, { threshold: 0.12, rootMargin: "0px 0px -40px 0px" });
  document.querySelectorAll(".rev").forEach(s => io.observe(s));
  // Safety: if observer never fires (some previews), show everything after 1.2s
  setTimeout(() => document.querySelectorAll(".rev.pending").forEach(activate), 1200);
} else {
  document.querySelectorAll(".rev").forEach(activate);
}
</script>
</body>
</html>
