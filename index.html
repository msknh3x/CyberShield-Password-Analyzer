<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CyberShield - Password Strength Analyzer V2</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Inter:wght@300;400;600&display=swap');
*{margin:0;padding:0;box-sizing:border-box}
body{
font-family:Inter,sans-serif;
background:linear-gradient(135deg,#06111f,#0a1f36,#071625);
color:white;min-height:100vh;padding:30px;
}
.container{max-width:1100px;margin:auto}
.header{text-align:center;margin-bottom:25px}
.header h1{font-family:Orbitron,sans-serif;color:#00ff9d;font-size:3rem}
.header p{color:#9fb6c9}
.card{
background:rgba(255,255,255,.05);
backdrop-filter:blur(10px);
border:1px solid rgba(0,255,157,.15);
border-radius:20px;padding:20px;
box-shadow:0 0 20px rgba(0,255,157,.08)
}
.grid{display:grid;grid-template-columns:1.2fr .8fr;gap:20px}
.input-group{position:relative}
input{
width:100%;padding:16px;border:none;border-radius:12px;
background:#081523;color:white;font-size:16px
}
button{
margin-top:10px;padding:10px 16px;border:none;border-radius:10px;
background:#00ff9d;color:#04131f;font-weight:700;cursor:pointer
}
.bar{height:14px;background:#102235;border-radius:30px;margin-top:18px;overflow:hidden}
.progress{height:100%;width:0%;transition:.4s}
.result{display:flex;justify-content:space-between;margin-top:12px}
.score{
display:flex;justify-content:center;align-items:center;
height:180px;width:180px;border-radius:50%;
border:10px solid #00ff9d;margin:auto;font-size:2rem;font-weight:bold
}
.stats,.tips{margin-top:15px}
.stats div,.tips div{padding:8px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.good{color:#00ff9d}
.bad{color:#ff5c5c}
.breach{margin-top:15px;padding:15px;border-radius:12px;background:#081523}
.footer{text-align:center;margin-top:20px;color:#8aa1b3}
@media(max-width:800px){.grid{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="container">

<div class="header">
<h1>CyberShield</h1>
<p>Password Strength Analyzer Version 2</p>
</div>

<div class="grid">

<div class="card">
<h2>Password Analysis</h2><br>

<input type="password" id="password" placeholder="Enter your password">

<button onclick="togglePassword()">Show / Hide Password</button>

<div class="bar">
<div class="progress" id="progress"></div>
</div>

<div class="result">
<span id="strength">Very Weak</span>
<span id="percent">0%</span>
</div>

<div class="tips">
<h3>Requirements</h3>
<div id="len">❌ 8+ Characters</div>
<div id="upper">❌ Uppercase Letter</div>
<div id="num">❌ Number</div>
<div id="sym">❌ Symbol</div>
</div>

<div class="breach">
<h3>Breach Database</h3>
<p id="breach">Waiting for input...</p>
</div>
</div>

<div class="card">
<div class="score" id="scoreCircle">0%</div>

<div class="stats">
<h3>Security Stats</h3>
<div>Entropy Score: <span id="entropy">0</span></div>
<div>Password Length: <span id="length">0</span></div>
<div>Risk Level: <span id="risk">High</span></div>
</div>
</div>

</div>

<div class="footer">
CyberShield Security Suite © 2026
</div>

</div>

<script>
const pass=document.getElementById("password");

pass.addEventListener("input",()=>{

let p=pass.value;
let score=0;

if(p.length>=8)score+=25;
if(/[A-Z]/.test(p))score+=25;
if(/[0-9]/.test(p))score+=25;
if(/[!@#$%^&*(),.?":{}|<>]/.test(p))score+=25;

document.getElementById("progress").style.width=score+"%";
document.getElementById("percent").innerText=score+"%";
document.getElementById("scoreCircle").innerText=score+"%";

let color="#ff4d4d";
let text="Very Weak";
let risk="High";

if(score>=25){text="Weak";color="#ff9f43";}
if(score>=50){text="Medium";color="#ffd32a";risk="Medium";}
if(score>=75){text="Strong";color="#2ed573";risk="Low";}
if(score==100){text="Very Strong";color="#00ff9d";risk="Very Low";}

document.getElementById("strength").innerText=text;
document.getElementById("risk").innerText=risk;
document.getElementById("progress").style.background=color;
document.getElementById("scoreCircle").style.borderColor=color;

document.getElementById("len").innerHTML=(p.length>=8?"✅":"❌")+" 8+ Characters";
document.getElementById("upper").innerHTML=(/[A-Z]/.test(p)?"✅":"❌")+" Uppercase Letter";
document.getElementById("num").innerHTML=(/[0-9]/.test(p)?"✅":"❌")+" Number";
document.getElementById("sym").innerHTML=(/[!@#$%^&*(),.?\":{}|<>]/.test(p)?"✅":"❌")+" Symbol";

document.getElementById("length").innerText=p.length;
document.getElementById("entropy").innerText=Math.round(p.length*score/10);

const common=["password","123456","admin","qwerty","abc123"];
if(common.includes(p.toLowerCase())){
document.getElementById("breach").innerHTML="⚠ Found in common breached passwords list";
document.getElementById("breach").style.color="#ff4d4d";
}else{
document.getElementById("breach").innerHTML="✅ No common breach detected";
document.getElementById("breach").style.color="#00ff9d";
}
});

function togglePassword(){
const p=document.getElementById("password");
p.type=p.type==="password"?"text":"password";
}
</script>
</body>
</html>
