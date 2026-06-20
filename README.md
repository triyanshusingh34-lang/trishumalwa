<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Triyanshu Malwa | Premium V5</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Poppins,sans-serif;background:#0b1020;color:#fff;overflow-x:hidden}
body:before{content:"";position:fixed;inset:0;background:
radial-gradient(circle at 20% 20%,rgba(124,58,237,.25),transparent 30%),
radial-gradient(circle at 80% 30%,rgba(6,182,212,.2),transparent 30%),
radial-gradient(circle at 50% 80%,rgba(236,72,153,.2),transparent 30%);z-index:-1}
nav{position:fixed;top:0;width:100%;padding:18px 8%;backdrop-filter:blur(15px);background:rgba(0,0,0,.2);display:flex;justify-content:space-between}
nav a{color:#fff;text-decoration:none;margin-left:20px}
.hero{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:120px 8%;gap:60px;flex-wrap:wrap}
.glass{background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.12);backdrop-filter:blur(18px);border-radius:24px}
.hero img{width:350px;height:350px;object-fit:cover;border-radius:30px;box-shadow:0 0 40px #7c3aed}
h1{font-size:64px}
.accent{color:#a78bfa}
.btn{display:inline-block;padding:14px 24px;border-radius:12px;background:#7c3aed;color:#fff;text-decoration:none;margin:8px}
section{padding:90px 8%}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{padding:25px}
.card:hover{transform:translateY(-8px);transition:.3s}
h2{margin-bottom:25px;font-size:38px}
footer{text-align:center;padding:30px;border-top:1px solid rgba(255,255,255,.1)}
.whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:15px 18px;border-radius:50%;text-decoration:none;font-size:22px}
#type{color:#22d3ee}
</style>
</head>
<body>
<nav>
<div><b>Triyanshu.</b></div>
<div>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</nav>

<section class="hero">
<div>
<h1>Triyanshu <span class="accent">Malwa</span></h1>
<h3>I build <span id="type"></span></h3>
<p style="margin:20px 0">BBA 2nd Semester â€¢ Digital Marketing Student â€¢ Future Media Buyer</p>
<a class="btn" href="resume.pdf">Download Resume</a>
<a class="btn" href="#contact">Hire Me</a>
</div>
<div class="glass" style="padding:15px">
<img src="profile.jpg" alt="profile">
</div>
</section>

<section id="about">
<h2>About Me</h2>
<div class="glass card">
Passionate about Facebook Ads, Google Ads, SEO, AI Tools, Content Strategy and Business Growth. Currently pursuing BBA and Digital Marketing training.
</div>
</section>

<section id="skills">
<h2>Skills</h2>
<div class="cards">
<div class="glass card">Facebook Ads</div>
<div class="glass card">Google Ads</div>
<div class="glass card">SEO</div>
<div class="glass card">Copywriting</div>
<div class="glass card">AI Tools</div>
<div class="glass card">Tally ERP 9</div>
</div>
</section>

<section id="projects">
<h2>Projects</h2>
<div class="cards">
<div class="glass card">Psychology Instagram Page</div>
<div class="glass card">Lead Generation Campaign</div>
<div class="glass card">Google Ads Practice Project</div>
</div>
</section>

<section>
<h2>Certificates</h2>
<div class="cards">
<div class="glass card">Digital Marketing Certificate</div>
<div class="glass card">ADCA Certificate</div>
<div class="glass card">Future Certifications</div>
</div>
</section>

<section id="contact">
<h2>Contact</h2>
<div class="glass card">
Email: your@email.com<br><br>
Instagram: @trishu_malwa<br><br>
WhatsApp: +91 XXXXX XXXXX<br><br>
LinkedIn: linkedin.com/in/yourprofile
</div>
</section>

<footer>Â© 2026 Triyanshu Malwa â€¢ Premium V5 Portfolio</footer>

<a class="whatsapp" href="#">ðŸ’¬</a>

<script>
const words=["Facebook Ads","Google Ads","SEO Strategies","Digital Marketing"];
let i=0,j=0,d=false;
const t=document.getElementById("type");
function run(){
 let w=words[i];
 t.textContent=d?w.slice(0,j--):w.slice(0,j++);
 if(!d && j>w.length){d=true;setTimeout(run,1000);return;}
 if(d && j<0){d=false;i=(i+1)%words.length;j=0;}
 setTimeout(run,d?60:120);
}
run();
</script>
</body>
</html>