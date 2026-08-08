<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maafin Aku Ya Sayang 🧸🤍</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');

*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

body{
  min-height:100vh;
  font-family:'Poppins',sans-serif;
  background:
    radial-gradient(circle at 20% 20%, #ffffff 0 5%, transparent 25%),
    radial-gradient(circle at 80% 80%, #ffdce9 0 5%, transparent 25%),
    linear-gradient(135deg,#dff5ff,#eef0ff,#ffe8f1);
  color:#555b72;
  overflow-x:hidden;
}

.hearts span{
  position:fixed;
  bottom:-50px;
  font-size:22px;
  opacity:.7;
  animation:floatUp linear infinite;
  z-index:0;
  pointer-events:none;
}

.hearts span:nth-child(1){left:7%;animation-duration:8s;}
.hearts span:nth-child(2){left:22%;animation-duration:10s;animation-delay:2s;}
.hearts span:nth-child(3){left:43%;animation-duration:7s;animation-delay:1s;}
.hearts span:nth-child(4){left:65%;animation-duration:11s;animation-delay:3s;}
.hearts span:nth-child(5){left:86%;animation-duration:9s;animation-delay:1.5s;}

@keyframes floatUp{
  0%{
    transform:translateY(0) rotate(0deg);
    opacity:0;
  }
  15%{opacity:.8;}
  100%{
    transform:translateY(-115vh) rotate(25deg);
    opacity:0;
  }
}

.wrapper{
  width:92%;
  max-width:700px;
  margin:40px auto;
  position:relative;
  z-index:2;
}

.card{
  background:rgba(255,255,255,.82);
  backdrop-filter:blur(18px);
  border:1px solid rgba(255,255,255,.9);
  border-radius:32px;
  padding:30px 22px 35px;
  box-shadow:0 20px 60px rgba(89,105,155,.18);
}

.badge{
  display:inline-block;
  background:#fff;
  color:#e38baa;
  padding:7px 15px;
  border-radius:30px;
  font-size:12px;
  font-weight:600;
  box-shadow:0 5px 15px rgba(100,100,150,.08);
  margin-bottom:15px;
}

h1{
  color:#687ab9;
  font-size:28px;
  line-height:1.3;
  margin-bottom:6px;
}

.subtitle{
  color:#999fb4;
  font-size:13px;
  margin-bottom:22px;
}

.teddy{
  width:170px;
  height:165px;
  margin:0 auto 20px;
  position:relative;
  animation:bounce 3s ease-in-out infinite;
}

@keyframes bounce{
  0%,100%{transform:translateY(0) rotate(-2deg);}
  50%{transform:translateY(-8px) rotate(2deg);}
}

.ear{
  position:absolute;
  width:48px;
  height:48px;
  background:#b98265;
  border-radius:50%;
  top:5px;
  z-index:1;
}

.ear:after{
  content:"";
  position:absolute;
  width:28px;
  height:28px;
  background:#edb9a9;
  border-radius:50%;
  left:10px;
  top:10px;
}

.ear.left{left:18px;}
.ear.right{right:18px;}

.head{
  position:absolute;
  width:120px;
  height:108px;
  background:#c79270;
  border-radius:50%;
  top:25px;
  left:25px;
  z-index:2;
}

.eye{
  position:absolute;
  width:9px;
  height:13px;
  background:#49352d;
  border-radius:50%;
  top:44px;
}

.eye.left{left:35px;}
.eye.right{right:35px;}

.nose{
  position:absolute;
  width:18px;
  height:14px;
  background:#4b362e;
  border-radius:50%;
  top:60px;
  left:51px;
}

.mouth{
  position:absolute;
  width:25px;
  height:13px;
  border-bottom:3px solid #4b362e;
  border-radius:50%;
  top:67px;
  left:47px;
}

.body{
  position:absolute;
  width:108px;
  height:78px;
  background:#b98265;
  border-radius:50px 50px 35px 35px;
  left:31px;
  top:98px;
  z-index:1;
}

.belly{
  position:absolute;
  width:60px;
  height:48px;
  background:#e9c3a2;
  border-radius:50%;
  left:24px;
  top:14px;
}

.teddy-heart{
  position:absolute;
  z-index:5;
  font-size:28px;
  left:40px;
  top:20px;
}

.open-btn{
  border:0;
  padding:14px 25px;
  border-radius:30px;
  background:linear-gradient(135deg,#8095dd,#e18cab);
  color:white;
  font-family:inherit;
  font-weight:600;
  font-size:14px;
  cursor:pointer;
  box-shadow:0 9px 25px rgba(117,137,210,.3);
  transition:.3s;
}

.open-btn:hover{
  transform:scale(1.05);
}

.message{
  display:none;
  margin-top:25px;
  padding:23px 19px;
  border-radius:24px;
  background:rgba(248,250,255,.9);
  border:1px solid rgba(220,226,245,.8);
  text-align:left;
  animation:appear .8s ease;
}

@keyframes appear{
  from{
    opacity:0;
    transform:translateY(20px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

.message p{
  font-size:14px;
  line-height:2;
  margin-bottom:18px;
}

.divider{
  text-align:center;
  color:#e48ba9;
  font-size:22px;
  margin:18px 0;
}

.end{
  text-align:center;
  margin-top:25px;
  color:#7c8298;
  font-size:14px;
}

.end .big{
  display:block;
  font-size:23px;
  color:#df7f9f;
  margin-top:7px;
}

@media(max-width:500px){
  .wrapper{
    width:94%;
    margin:22px auto;
  }

  .card{
    padding:25px 15px 30px;
    border-radius:27px;
  }

  h1{
    font-size:24px;
  }

  .message{
    padding:20px 15px;
  }

  .message p{
    font-size:13px;
    line-height:1.9;
  }
}
</style>
</head>

<body>

<!-- LAGU YANG KAMU KASIH -->
<audio id="lagu" loop preload="auto">
  <source src="https://files.catbox.moe/0tbeyf.mp3" type="audio/mpeg">
</audio>

<div class="hearts">
  <span>💗</span>
  <span>🤍</span>
  <span>🩷</span>
  <span>💞</span>
  <span>🤍</span>
</div>

<div class="wrapper">
<div class="card">

<div style="text-align:center;">

<div class="badge">
a little message from me for youuu 🥺🤍
</div>

<h1>
maafin aku ya sayanggggg 🥺🤍
</h1>

<div class="subtitle">
ada seseorang yang mau ngerayu pacarnyaaa 😭
</div>

<!-- TEDDY BEAR -->
<div class="teddy">

<div class="ear left"></div>
<div class="ear right"></div>

<div class="head">
<div class="eye left"></div>
<div class="eye right"></div>
<div class="nose"></div>
<div class="mouth"></div>
</div>

<div class="body">
<div class="belly"></div>
<div class="teddy-heart">💗</div>
</div>

</div>

<button class="open-btn" onclick="openMessage()">
buka pesannyaaa 🧸💗
</button>

</div>

<!-- PESAN KAMU -->
<div class="message" id="message">

<p>
sayanggggggggggggggggg 😭😭😭
sininiii duluuuuuuuuuuuuuuuuu 🥺🤍 akuuuuu mauuu
mintaaaa maaffff samaaaa kamuuuuuuuuuuuu, bolehhh yaaaaa?? 😭
akuuuuu tauuu semalemmm akuuuuu naaa salahhhhhh, akuuuuu tauuu kamuuuu
kesellll, kecewaaaaa, badmooddddd, passs kitaa lagiiii nontonnn barenggggggggg 😭😭
</p>

<p>
maafinnn akuuuuu yaaaaaaa sayanggggggggggggggg 🥺🥺
akuuuuu benerrrr-benerrr mintaaaa maafff dariii hatiii akuuuu yanggg
palInggh dalemmmmmmmmm 😭🤍 akuuuuu
gaaaaa bermaksuddd samaaaa sekaliiii buattttt ninggalinnn kamuuuuuuu, gaaaaaa
bermaksuddd bikinnnn kamuuuu ngerasaaaa sendiriannnnnnn, apalagiii bikinnn
kamuuuu ngerasaaa kayakkkkk akuuuu gaaaaaa menghargaiiii waktuuuu kitaaaaaaaa 😭
</p>

<p>
akuuuuu cumaaaa ketiduran sayanggggggggg 😭😭
akuuuuu cumaaa kalahhhh samaaaa ngantukkkkk semalemmmmmm, tubuhhhh akuuuuu tibaaa-tibaaa
tumbanggggggg 😭😭 kalauuuu bisaaaa milihhhh, akuuuuu
jugaaaa maunyaaaa teteppppp melekkkk nemeninnnn kamuuuu sampaiiii filmnyaaaa
selesaiiii
</p>

<p>
akuuuuu tauu mungkinnnn buattttt akuuuuu keliatannya cumaaaaa
“ketiduran”, tapiiiiii akuuuuu ngertiiiii kalauuuuu dariii sisiiiii kamuuuu rasanyaaa
bisaaa bedaaaaa bangettttt. apalagiii kitaaaa lagiiii punyaaaa waktuuuuu buattttt
nontonnnn barenggggggg, terussss akuuuuu malahhhh tidurrrrr 😭
</p>

<p>
jadiiii kalauuuuu kamuuuu kecewaaaaa, akuuuuu ngertiiiii kokkkkk.
kalauuuuuu kamuuuu kesellllll, akuuuuu ngertiiiii kokkkkk.
kalauuuu kamuuuu masihhhh badmood samaaaa akuuuuu,
akuuuuu jugaaaa gaaaaaa bakalll nyalahin kamuuuu 🥺🤍
</p>

<div class="divider">♡ ♡ ♡</div>

<p>
tapiii bolehhh akuuuuu rayuuuuuu kamuuuuuu sekarangggggg? 😭😭😭
bolehhh akuuuuu bujukkkk pacarkuuuuuu yanggg palinggggg akuuuuu sayanggggggg iniiii
supayaaaaa jangannn badmoodddddd lagiiii maaa akuuuu🥺👉🏻👈🏻
</p>

<p>
sayanggggggg jangannnn ngambekkk lamaaa-lamaaa yaaaaaaaa 😭
akuuuuu tuhhhhh gaaaaaa kuattttt kalauuuu kamuuuu jadiii diemmmmm samaaaa
akuuuuu 😭😭 rasanyaa akuuuuu pengen nyamperinnnn
kamuuuu terussss bilanggg “iyaaa akuuuuu salahhhhhh, maafinnnn akuuuuu yaaaaaa”
sambil nundukkkkk-nundukkkk sampaiiii kamuuuu akhirnyaa ketawaaaa lagiiiii 😭🤏🏻
</p>

<p>
AKUUUUU MASIH SAYANGGGGGGGGGGGGG BANGETTTTTTTTTTTTTTTTT SAMA
KAMUUUU 😭❤️ bahkan kalauuuu disuruhhhh milihhhh antaraaaa
tidurrrrrrr samaaaa nontonnnn samaaa kamuuuu, sebenarnyaaaa akuuuuu pengen nontonnnn
samaaaa kamuuuu terussssssss, cumaaaaa badannnn akuuuuu semalammmmm yanggg tibaaa-tibaaa
ngalahinnnn akuuuuu 😭😭😭 waktuuuu samaaaa kamuuuu jugaaaa
pentinggggggggg. makanyaaaa akuuuuu malahhhh ngerasaaaa bersalahhhhh bangettttt
karenaaaa semalammmm waktuuuu kitaakitaaaahhhhh kebuangggg garaaaa-garaaaa
akuuuuu ketidurannnnnn 😭
</p>

<p>
jadiii maafin akuuuuu yaaaaaaaa sayanggggggggg 🥺🤍
jangannnn dipendem sendiriannn kalauuuu kamuuuu masihhhh kesellll atauuu
kecewaaaaaa. ceritainnn keeee akuuuuu, marahinnnn akuuuuu kalauuuu emangggg
kamuuuu butuhhhhh ngeluarinnnnn rasaaaa keselmuuuu 😭
akuuuuu bakalll dengerinnnnnn,
</p>

<p>
tapiii abissss ituuu kitaa baikannnnn yaaaaaaaa? 😭👉🏻👈🏻
kitaa lanjuttt nontonnnn lagiii, akuuuuu temenin kamuuuu, akuuuuu dudukkkk
manisssss, akuuuuu fokussssss, akuuuuu gaaaaaa bolehhh meremmmmm, gaaaaaa
bolehhh ngilanggggg, gaaaaaa bolehhh ketidurannnnnn 😭😭😭
kalauuu mataaaa akuuuuu mulaii berattttt, akuuuuu bakalll bilangggg
“sayanggggg akuuuuu ngantukkkk” bukannyaaa tibaaa-tibaaa tumbanggggg 😭😭
</p>

<p>
akuuuuu janjiiii bakalll lebihhh perhatiannnn samaaaa halll kecilll kayakkkk giniiiiiii,
karenaaa akuuuuu gaaaaaa mauuuu bikinnnn kamuuuu ngerasaaaa
gaaaaa dianggaptttttt. akuuuuu pengennn kamuuuu ngerasaaaa disayanggggggg,
diperhatiinnnn, didengerinnnnn, dannnn ditemeninnnn samaaaa akuuuuu 🥺🤍
</p>

<p>
jadiii sekarangggggg, bolehhh yaaaaaaaa pacarkuuuuuu yanggggg
cantikkkkkk iniiii pelannn-pelannnnn balikinnn moodnyaaaa??🥺😭
akuuuuu gaaaaaa maksaaaa kamuuuu harussss langsunggg ceriaaaaa,
akuuuuu cumaaa mauuuu kamuuuu tauuuuu kalauuu akuuuuu diii siniiiiiiii,
akuuuuu masihhhh sayanggggggg samaaaa kamuuuu,
akuuuuu masihhhh peduliiiiii samaaaa kamuuuu,
dannn akuuuuu masihhh pengennnn nemenin kamuuuu sepertiiii biasanyaaaaaaa 🤍
</p>

<p>
maafinnnn akuuuuu yaaaaaaaa sayanggggggggggggg 😭😭😭
jangannnn jauhhh-jauhhhh dariii akuuuuu yaaaaaaaa 🥺
jangannn mikirrrr yanggg anehhhh-anehh yaaaaaa sayanggggg😭🤍
dannn jangannn lupaaa kalauuuu adaaa satuuu cowokkkkk diii
siniiiiiiiiii yanggg sayanggggggggg bangettttttttt samaaaa kamuuuu 😭❤️❤️❤️
</p>

<p style="text-align:center;">
siniiiiii baikannnnn samaaaa akuuuuu 🥺👉🏻👈🏻
</p>

<p style="text-align:center;font-weight:600;">
akuuuuu sayangggggggggggggggg<br>
bangetttttttttttttttttttttttttt samaaaa<br>
kamuuuuuuuuuuuuuu 😭❤️‍🩹❤️‍🩹❤️‍🩹
</p>

<div class="end">
LOPEEEEE UUUUU 🤍🫶🏻
<span class="big">🧸💗🤍</span>
</div>

</div>
</div>
</div>

<script>

function openMessage(){

  const message = document.getElementById("message");
  const button = document.querySelector(".open-btn");
  const lagu = document.getElementById("lagu");

  /* PESAN MUNCUL */
  message.style.display = "block";

  /* LAGU MULAI */
  lagu.volume = 0.7;
  lagu.play();

  /* TOMBOL */
  button.innerHTML = "udah dibaca yaaaaa 🥺🤍";
  button.disabled = true;
  button.style.opacity = "0.8";

  /* EFEK HATI */
  for(let i=0;i<18;i++){

    const heart=document.createElement("div");

    heart.innerHTML=["💗","🤍","🩷","💞","🧸"]
      [Math.floor(Math.random()*5)];

    heart.style.position="fixed";
    heart.style.left="50%";
    heart.style.top="50%";
    heart.style.fontSize=(15+Math.random()*18)+"px";
    heart.style.zIndex="999";
    heart.style.pointerEvents="none";
    heart.style.transition="all 1.8s ease";

    document.body.appendChild(heart);

    setTimeout(()=>{
      heart.style.transform=
      `translate(${(Math.random()-.5)*450}px,
      ${-150-Math.random()*400}px)
      rotate(${Math.random()*360}deg)`;

      heart.style.opacity="0";
    },50);

    setTimeout(()=>heart.remove(),2000);
  }

  /* SCROLL KE PESAN */
  setTimeout(()=>{
    message.scrollIntoView({
      behavior:"smooth",
      block:"start"
    });
  },300);

}

</script>

</body>
</html>
