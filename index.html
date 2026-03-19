<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Birthday Surprise 🎉</title>

<link href="https://fonts.googleapis.com/css2?family=Niconne&family=Pacifico&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

<style>
body {
  margin:0;
  font-family:'Roboto', sans-serif;
  overflow:hidden;
  background: linear-gradient(270deg,#ff9ec4,#ffc3a0,#ffdde1,#fbc2eb);
  background-size: 600% 600%;
  animation: gradientMove 12s ease infinite;
}

@keyframes gradientMove {
  0%{background-position:0% 50%;}
  50%{background-position:100% 50%;}
  100%{background-position:0% 50%;}
}

section {
  width:100vw;
  height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-direction:column;
  position:absolute;
  top:0; left:0;
  transition: all .8s ease;
}

.hidden {
  opacity:0;
  pointer-events:none;
  transform:scale(0.9);
}

section:not(.hidden) {
  opacity:1;
  transform:scale(1);
}

.greet-card {
  background:rgba(255,255,255,0.95);
  border-radius:22px;
  box-shadow:0 4px 48px #ffd6f3b2;
  padding:36px 28px;
  text-align:center;
}

.greet-heading {
  font-family:'Pacifico', cursive;
  font-size:2rem;
  color:#ff6db8;
  margin-bottom:12px;
  animation:glowText 1.6s infinite alternate;
}

@keyframes glowText {
  from { text-shadow:0 0 8px #ffb8ef;}
  to { text-shadow:0 0 20px #ff74c0;}
}

.sub-heading {
  color:#e070a3;
  margin-bottom:6px;
}

.pink-btn, .next-btn {
  background:linear-gradient(94deg,#ff8fab,#ff63a8);
  color:#fff;
  padding:12px 32px;
  border:none;
  border-radius:28px;
  cursor:pointer;
  margin-top:16px;
  transition:0.3s;
}

.pink-btn:hover, .next-btn:hover {
  transform: scale(1.08);
}

.pink-btn:active, .next-btn:active {
  transform: scale(0.95);
}

/* Hearts */
@keyframes floatHearts {
  to {transform:translateY(-100vh); opacity:0;}
}
.heart {
  position:absolute;
  bottom:-10px;
  animation:floatHearts 5s linear forwards;
}

/* Letter */
.letter-card {
  background:#fff;
  border-radius:20px;
  padding:25px;
  max-width:400px;
  width:90%;
  text-align:center;
  animation:fadeUp 1s forwards;
}

@keyframes fadeUp {
  from {opacity:0; transform:translateY(30px);}
  to {opacity:1; transform:translateY(0);}
}

#letter {
  font-family:'Niconne', cursive;
  font-size:1.3rem;
  color:#7b4a7b;
}

/* Confetti */
.confetti {
  position:absolute;
  width:8px;
  height:8px;
  border-radius:50%;
  animation:fall linear forwards;
}
@keyframes fall {
  to {transform:translateY(100vh);}
}
</style>
</head>

<body>

<section id="page1">
  <div class="greet-card">
    <h2 class="greet-heading">Happy Birthday Sister 💖</h2>
    <p class="sub-heading">Special Surprise For You</p>
    <button class="pink-btn" onclick="nextPage(2)">Start</button>
  </div>
</section>

<section id="page2" class="hidden">
  <div class="greet-card">
    <h2 class="greet-heading">Ready? 💌</h2>
    <button class="next-btn" onclick="nextPage(3)">Next</button>
  </div>
</section>

<section id="page3" class="hidden">
  <div class="letter-card">
    <h3>💖 Message 💖</h3>
    <div id="letter"></div>
  </div>
</section>

<script>
let heartIntervals = {};

function nextPage(num) {
  document.querySelectorAll('section').forEach(s => s.classList.add('hidden'));
  const page = document.getElementById('page' + num);
  page.classList.remove('hidden');

  if(!heartIntervals[num]) {
    heartIntervals[num] = setInterval(()=>createHeart(page), 500);
  }

  if(num === 3){
    revealLetter();
    startConfetti();
  }
}

function createHeart(page) {
  const heart = document.createElement('div');
  heart.className = 'heart';
  heart.textContent = ['💗','💖','💕'][Math.floor(Math.random()*3)];
  heart.style.left = Math.random()*100+'vw';
  page.appendChild(heart);
  setTimeout(()=>heart.remove(),5000);
}

function typeWriter(text, element, speed=35){
  let i=0;
  element.innerHTML='';

  function typing(){
    if(i<text.length){
      element.innerHTML =
        text.substring(0,i).replace(/\n/g,'<br>') + '|';
      i++;
      setTimeout(typing,speed);
    } else {
      element.innerHTML = text.replace(/\n/g,'<br>');
    }
  }
  typing();
}

function revealLetter(){
  const text = `💖🎉 Happy Birthday meri choti behan 🎂💖  

Tu meri life ka sabse pyara hissa hai 😊💫  
Teri smile meri sabse badi khushi hai 😄✨  

Tu hamesha aise hi hansti rehna 😘💖  
Aur apni cuteness se sabka dil jeetti rehna 🥰💕  

Bhagwan kare tera har sapna pura ho 🌸🌟  
Aur tu life me bohot aage badhe 🚀✨  

Aaj ka din full enjoy kar 🎂🎉🍫  
Kyuki aaj sirf tera din hai 🎁💃💫  

Hamesha khush rehna meri choti behan 💖🥺✨`;

  typeWriter(text, document.getElementById('letter'));
}

function startConfetti(){
  setInterval(()=>{
    const c = document.createElement('div');
    c.className='confetti';
    c.style.left=Math.random()*100+'vw';
    c.style.background=`hsl(${Math.random()*360},100%,70%)`;
    document.body.appendChild(c);
    setTimeout(()=>c.remove(),4000);
  },150);
}
</script>

</body>
</html>
