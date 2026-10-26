
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Для Кирочки ❤️</title>
<style>
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 margin:0;color:#fff;font-family:Arial,sans-serif;text-align:center;
 background:linear-gradient(180deg,#100d2c,#28152f,#100d25);
 overflow-x:hidden
}
#stars{position:fixed;inset:0;pointer-events:none;z-index:0}
.star{position:absolute;background:white;border-radius:50%;animation:blink 2s infinite alternate}
@keyframes blink{to{opacity:.2;transform:scale(.6)}}
header,main,footer{position:relative;z-index:1}
header{min-height:100vh;padding:70px 20px;display:flex;flex-direction:column;align-items:center;justify-content:center}
.bigheart{font-size:76px;animation:pulse 1.3s infinite}
@keyframes pulse{50%{transform:scale(1.15)}}
h1{font-size:clamp(36px,9vw,60px);color:#ffb6d0;margin:20px 0}
h2{font-size:28px;color:#ffb6d0}
h3{color:#ffc6db}
p{line-height:1.8}
.intro{max-width:480px;color:#eee0f7}
section{padding:40px 17px;max-width:720px;margin:auto}
.card{background:#ffffff0d;border:1px solid #ffffff20;border-radius:22px;padding:23px;margin:16px 0;box-shadow:0 10px 30px #0002}
button{background:linear-gradient(135deg,#ff4f89,#a54cff);color:white;border:0;border-radius:30px;padding:14px 21px;font-size:16px;cursor:pointer;margin:8px}
button:active{transform:scale(.96)}
.line{height:3px;width:70px;margin:20px auto;background:#ff6f9e;border-radius:5px}
.counter{font-size:19px;color:#ffbad3;font-weight:bold;overflow-wrap:anywhere}
.small{font-size:13px;color:#c9bfd8}
#letter,#secret{display:none;margin-top:20px;line-height:1.9;color:#ffe1ed;white-space:pre-line}
#photos{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px;margin-top:15px}
#photos img{width:100%;height:190px;object-fit:cover;border-radius:14px}
input{max-width:100%;margin:12px 0}
audio{width:100%;margin-top:15px}
.float{position:fixed;bottom:-40px;z-index:10;pointer-events:none;animation:rise 4s linear forwards}
@keyframes rise{to{transform:translateY(-110vh) rotate(30deg);opacity:0}}
footer{padding:35px 15px 60px;color:#e0c8e7}
</style>
</head>
<body>
<div id="stars"></div>

<header>
 <div class="bigheart">❤️</div>
 <h1>Моей Кирочке</h1>
 <p class="intro">
  Среди миллионов людей наши дороги однажды пересеклись.
  Тогда я ещё не знал, что ты станешь такой важной частью моей жизни.
  Этот сайт — только для тебя, любимая.
 </p>
 <button onclick="document.getElementById('story').scrollIntoView()">Наша история 💌</button>
</header>

<main>
<section id="story">
 <h2>С чего всё началось 🌙</h2><div class="line"></div>
 <div class="card">
  <div style="font-size:40px">🌲</div>
  <h3>Последний звонок</h3>
  <p>Кто бы мог подумать, что наша история начнётся на пьянке в лесу на последнем звонке? Вокруг были люди, разговоры и веселье, а среди всего этого была ты. Тогда я и представить не мог, что однажды буду создавать для тебя сайт, чтобы сказать, как сильно ты мне дорога.</p>
 </div>
 <div class="card">
  <div style="font-size:40px">🌳</div>
  <h3>Ленинский парк, Сарапул</h3>
  <p>Сарапул, Ленинский парк, тот самый период нашей жизни… Теперь эти воспоминания стали частью нашей истории. Иногда самые важные события начинаются совсем не так, как мы могли себе представить.</p>
 </div>
 <div class="card">
  <div style="font-size:40px">⏳</div>
  <h3>Время шло</h3>
  <p>Тогда у тебя были свои отношения, своя жизнь и свои обстоятельства. Прошло время — вроде бы меньше года, — и всё изменилось. Мы начали встречаться, и появилась новая глава нашей истории. Я рад, что мы дали этой истории начаться.</p>
 </div>
 <div class="card">
  <div style="font-size:40px">💗</div>
  <h3>Теперь есть мы</h3>
  <p>Теперь ты моя любимая Кирочка. Я хочу, чтобы у нас было больше счастливых дней, долгих разговоров, прогулок, объятий и воспоминаний, над которыми мы когда-нибудь будем улыбаться вместе.</p>
 </div>
</section>

<section>
 <h2>Что мне нравится в тебе 💕</h2><div class="line"></div>
 <div class="card">🌸 Твоя улыбка, которая делает день светлее.</div>
 <div class="card">🫂 Твоё тепло и чувство, что рядом с тобой хорошо.</div>
 <div class="card">✨ Твои особенности, привычки и характер.</div>
 <div class="card">💌 Наши моменты, разговоры и общие воспоминания.</div>
 <div class="card">❤️ То, что ты — именно ты, моя Кирочка.</div>
</section>

<section>
 <h2>Сколько мы вместе? ⏰</h2><div class="line"></div>
 <div class="card">
  <p>Каждый день нашей истории имеет значение.</p>
  <div class="counter" id="counter">Наша история продолжается ❤️</div>
  <p class="small">С 28 января 2026 года — и дальше, день за днём.</p>
 </div>
</section>

<section>
 <h2>Наши фотографии 📸</h2><div class="line"></div>
 <div class="card">
  <p>Выбери ваши любимые фотографии, чтобы посмотреть их на этой странице.</p>
  <input type="file" id="photoInput" accept="image/*" multiple>
  <div id="photos"></div>
  <p class="small">Выбранные здесь фотографии видны только на устройстве, где их выбрали. Чтобы Кирочка тоже их увидела, добавь изображения в файлы сайта.</p>
 </div>
</section>

<section>
 <h2>Мелодия для тебя 🎵</h2><div class="line"></div>
 <div class="card">
  <p>Выбери песню, которая напоминает тебе о вашей истории.</p>
  <input type="file" id="musicInput" accept="audio/*">
  <audio id="player" controls style="display:none"></audio>
 </div>
</section>

<section>
 <h2>Письмо для моей любимой 💌</h2><div class="line"></div>
 <div class="card">
  <p>Здесь есть кое-что, что я хочу тебе сказать.</p>
  <button onclick="toggle('letter')">Открыть письмо ❤️</button>
  <div id="letter">Кирочка, любимая моя ❤️

Иногда я думаю о том, насколько необычно началась наша история. Последний звонок, лес, Сарапул, Ленинский парк… Тогда я не знал, что однажды ты станешь настолько дорогим мне человеком.

28 января 2026 года началась наша история как пары. И я хочу, чтобы впереди было ещё много счастливых дат, прогулок, разговоров и объятий.

Я хочу заботиться о тебе, поддерживать тебя, радовать и чаще видеть твою улыбку. Не обещаю, что каждый день будет идеальным, но хочу стараться ради нас.

Спасибо, что ты есть в моей жизни.
Я очень тебя люблю, моя Кирочка. ❤️

Твой любимый 💋</div>
 </div>
</section>

<section>
 <h2>Маленький секрет 🤫</h2><div class="line"></div>
 <div class="card">
  <p>Нажми, если готова узнать кое-что важное.</p>
  <button onclick="toggle('secret');hearts()">Открыть секрет 💗</button>
  <div id="secret">Из всех случайностей я рад, что однажды встретил именно тебя.<br><br>Если бы мне снова пришлось прожить эту историю, я бы хотел, чтобы в ней опять появилась ты. ❤️<br><br>Люблю тебя, Кирочка! 💋</div>
 </div>
</section>

<section>
 <h2>Обнимашка для тебя 🫂</h2><div class="line"></div>
 <div class="card">
  <p id="hugText">Представь, что я сейчас крепко-крепко тебя обнимаю.</p>
  <button onclick="hug()">Получить обнимашку 🫂</button>
 </div>
</section>

<section>
 <div class="card">
  <div class="bigheart">💖</div>
  <h2>Это всё для тебя</h2>
  <p>Я рад, что наши дороги пересеклись. Хочу, чтобы впереди у нас было ещё много счастливых моментов. Спасибо за нашу историю, моя любимая.</p>
  <h3>Я люблю тебя, Кирочка! ❤️</h3>
  <button onclick="hearts()">Нажми на сердечко 💝</button>
 </div>
</section>
</main>

<footer>Сделано с любовью для Кирочки ❤️<br>Наша история ещё пишется… ✨</footer>

<script>
/* Звёзды */
const sky=document.getElementById("stars");
for(let i=0;i<100;i++){
 const s=document.createElement("div");
 s.className="star";
 s.style.left=Math.random()*100+"%";
 s.style.top=Math.random()*100+"%";
 s.style.width=(1+Math.random()*2)+"px";
 s.style.height=s.style.width;
 s.style.animationDelay=Math.random()*3+"s";
 sky.appendChild(s);
}

/* Письмо и секрет */
function toggle(id){
 const el=document.getElementById(id);
 el.style.display=el.style.display==="block"?"none":"block";
}

/* Сердечки */
function hearts(){
 for(let i=0;i<28;i++){
  setTimeout(()=>{
   const h=document.createElement("div");
   h.className="float";
   h.textContent=["❤️","💗","💕","💖","💋"][Math.floor(Math.random()*5)];
   h.style.left=Math.random()*100+"vw";
   h.style.fontSize=(18+Math.random()*24)+"px";
   h.style.animationDuration=(2.5+Math.random()*2)+"s";
   document.body.appendChild(h);
   setTimeout(()=>h.remove(),5000);
  },i*70);
 }
}

/* Обнимашка */
function hug(){
 document.getElementById("hugText").textContent=
 "Крепко-крепко обнимаю тебя, моя любимая Кирочка! 🫂❤️";
 hearts();
}

/* Фотографии */
document.getElementById("photoInput").addEventListener("change",function(){
 const box=document.getElementById("photos");
 box.innerHTML="";
 Array.from(this.files).forEach(file=>{
  const img=document.createElement("img");
  img.src=URL.createObjectURL(file);
  img.alt="Наше фото";
  box.appendChild(img);
 });
});

/* Музыка */
document.getElementById("musicInput").addEventListener("change",function(){
 if(!this.files.length)return;
 const player=document.getElementById("player");
 player.src=URL.createObjectURL(this.files[0]);
 player.style.display="block";
 player.play().catch(()=>{});
});

/* Счётчик отношений: 28 января 2026 года */
const startDate=new Date(2026,0,28);

function updateCounter(){
 const now=new Date();
 const diff=now-startDate;
 const el=document.getElementById("counter");
 if(diff<0){
  el.textContent="Ваша история скоро начнётся ❤️";
  return;
 }
 const days=Math.floor(diff/86400000);
 const hours=Math.floor(diff/3600000)%24;
 const minutes=Math.floor(diff/60000)%60;
 const seconds=Math.floor(diff/1000)%60;
 el.textContent=days+" дней · "+hours+" ч · "+minutes+" мин · "+seconds+" сек ❤️";
}
updateCounter();
setInterval(updateCounter,1000);
</script>
</body>
</html>
