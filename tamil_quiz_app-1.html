index.html
<html lang="ta">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>தமிழ் Quiz</title>
<style>
*{box-sizing:border-box}body{margin:0;font-family:Arial,sans-serif;background:#f3f5f9;color:#18202a}
.app{max-width:520px;margin:auto;min-height:100vh;padding:18px}
.card{background:#fff;border-radius:22px;padding:22px;box-shadow:0 8px 25px #00000012;margin-bottom:16px}
h1,h2,p{margin-top:0}.title{text-align:center;padding:18px 5px}
.title h1{font-size:32px;margin-bottom:8px}.title p{color:#68727d}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.cat{padding:18px 10px;border:0;border-radius:16px;background:#eef1f6;font-size:17px;cursor:pointer}
.cat:active,.answer:active{transform:scale(.98)}
.top{display:flex;justify-content:space-between;gap:10px;font-weight:bold;margin-bottom:16px}
.progress{height:8px;background:#e7e9ee;border-radius:10px;overflow:hidden;margin-bottom:22px}
.bar{height:100%;width:0;background:#222;border-radius:10px}
.question{font-size:22px;font-weight:bold;line-height:1.5;margin-bottom:18px}
.answer{width:100%;padding:15px;margin:7px 0;border:2px solid #e4e7ec;border-radius:13px;background:#fff;text-align:left;font-size:17px;cursor:pointer}
.answer.correct{border-color:#27a65b;background:#e9f8ef}.answer.wrong{border-color:#d64545;background:#fff0f0}
button.primary{width:100%;padding:15px;border:0;border-radius:13px;background:#222;color:white;font-size:17px;cursor:pointer;margin-top:14px}
button.secondary{width:100%;padding:13px;border:0;border-radius:13px;background:#eceff3;font-size:16px;cursor:pointer;margin-top:10px}
.hidden{display:none}.score{text-align:center;font-size:34px;font-weight:bold;margin:25px 0 10px}.small{text-align:center;color:#69727c}
#timer{font-variant-numeric:tabular-nums}
</style>
</head>
<body>
<div class="app">
  <section id="home" class="card title">
    <h1>🧠 தமிழ் Quiz</h1>
    <p>தினமும் புதிதாக கற்றுக்கொள்வோம்!</p>
    <h2>வகையை தேர்வு செய்யுங்கள்</h2>
    <div class="grid">
      <button class="cat" onclick="start('gk')">🌍 பொது அறிவு</button>
      <button class="cat" onclick="start('science')">🔬 அறிவியல்</button>
      <button class="cat" onclick="start('history')">📜 வரலாறு</button>
      <button class="cat" onclick="start('tamil')">📖 தமிழ்</button>
    </div>
  </section>

  <section id="quiz" class="card hidden">
    <div class="top"><span id="counter"></span><span>⏱️ <span id="timer">15</span>s</span></div>
    <div class="progress"><div id="bar" class="bar"></div></div>
    <div id="question" class="question"></div>
    <div id="answers"></div>
    <button id="next" class="primary hidden" onclick="next()">அடுத்த கேள்வி ➡️</button>
  </section>

  <section id="result" class="card hidden">
    <h2 style="text-align:center">🎉 Quiz முடிந்தது!</h2>
    <div id="score" class="score"></div>
    <p id="message" class="small"></p>
    <button class="primary" onclick="restart()">🔄 மீண்டும் விளையாடு</button>
    <button class="secondary" onclick="goHome()">🏠 Home</button>
  </section>
</div>

<script>
const data={
gk:[
["இந்தியாவின் தலைநகரம் எது?",["சென்னை","புதுடெல்லி","மும்பை","கொல்கத்தா"],1],
["இந்தியாவின் தேசிய விலங்கு எது?",["சிங்கம்","யானை","புலி","மான்"],2],
["தமிழ்நாட்டின் தலைநகரம் எது?",["மதுரை","சென்னை","திருச்சி","சேலம்"],1],
["இந்தியாவின் தேசிய பறவை எது?",["மயில்","கிளி","கழுகு","காகம்"],0],
["உலகின் மிகப்பெரிய கண்டம் எது?",["ஆப்பிரிக்கா","ஐரோப்பா","ஆசியா","ஆஸ்திரேலியா"],2],
["இந்தியாவின் நாணயம் எது?",["டாலர்","ரூபாய்","யென்","பவுண்ட்"],1],
["இந்தியாவின் தேசிய மலர் எது?",["ரோஜா","தாமரை","மல்லிகை","சூரியகாந்தி"],1],
["பூமியின் இயற்கை துணைக்கோள் எது?",["சூரியன்","செவ்வாய்","நிலா","வெள்ளி"],2],
["தமிழ்நாட்டின் மாநில விலங்கு எது?",["வரையாடு","புலி","யானை","சிங்கம்"],0],
["உலகின் மிகப்பெரிய பெருங்கடல் எது?",["இந்தியப் பெருங்கடல்","அட்லாண்டிக்","பசிபிக்","ஆர்க்டிக்"],2]
],
science:[
["தாவரங்கள் உணவு தயாரிக்கும் செயல்முறை எது?",["சுவாசம்","ஒளிச்சேர்க்கை","செரிமானம்","ஆவியாதல்"],1],
["நீரின் வேதியியல் வாய்ப்பாடு எது?",["CO2","O2","H2O","NaCl"],2],
["மனித உடலில் இரத்தத்தை பம்ப் செய்யும் உறுப்பு எது?",["நுரையீரல்","இதயம்","மூளை","சிறுநீரகம்"],1],
["சூரியனுக்கு மிக அருகிலுள்ள கோள் எது?",["புதன்","பூமி","செவ்வாய்","சுக்கிரன்"],0],
["மனிதர்கள் சுவாசிக்க முக்கியமாக பயன்படுத்தும் வாயு எது?",["நைட்ரஜன்","ஆக்சிஜன்","ஹைட்ரஜன்","ஹீலியம்"],1],
["பூமியில் உயிர்களுக்கு முக்கியமான ஆற்றல் மூலாதாரம் எது?",["சந்திரன்","சூரியன்","காற்று","மண்"],1],
["மனித உடலின் கட்டுப்பாட்டு மையம் எது?",["இதயம்","மூளை","கல்லீரல்","தோல்"],1],
["பனி என்பது நீரின் எந்த நிலை?",["திரவம்","வாயு","திடம்","பிளாஸ்மா"],2],
["ஒளியின் வேகம் எதைவிட அதிகம்?",["ஒலி","ஒளி","இரண்டும் சமம்","எதுவுமில்லை"],0],
["தாவரங்களில் நீரை எடுத்துச் செல்லும் திசு எது?",["புளோயம்","சைலம்","வேர்","இலை"],1]
],
history:[
["திருக்குறளை இயற்றியவர் யார்?",["கம்பர்","திருவள்ளுவர்","இளங்கோவடிகள்","அவ்வையார்"],1],
["சிலப்பதிகாரத்தை இயற்றியவர் யார்?",["இளங்கோவடிகள்","கம்பர்","சேக்கிழார்","பாரதியார்"],0],
["இந்திய சுதந்திர தினம் எப்போது?",["ஜனவரி 26","ஆகஸ்ட் 15","அக்டோபர் 2","நவம்பர் 14"],1],
["இந்திய குடியரசு தினம் எப்போது?",["ஜனவரி 26","ஆகஸ்ட் 15","மே 1","ஜூலை 4"],0],
["மகாத்மா காந்தியின் பிறந்தநாள் எப்போது?",["ஜனவரி 26","ஆகஸ்ட் 15","அக்டோபர் 2","நவம்பர் 14"],2],
["தமிழ்நாட்டில் உள்ள தஞ்சைப் பெரிய கோயிலை கட்டிய சோழ மன்னர் யார்?",["ராஜராஜ சோழன்","கரிகாலன்","ராஜேந்திர சோழன்","குலோத்துங்கன்"],0],
["இந்தியாவின் முதல் பிரதமர் யார்?",["சர்தார் படேல்","ஜவஹர்லால் நேரு","ராஜேந்திர பிரசாத்","அம்பேத்கர்"],1],
["இந்திய அரசியலமைப்பு ஏற்றுக்கொள்ளப்பட்ட ஆண்டு எது?",["1947","1949","1950","1952"],1],
["வ.உ.சிதம்பரனார் பொதுவாக எந்த பெயரில் அழைக்கப்படுகிறார்?",["கப்பலோட்டிய தமிழன்","தமிழ்த்தாத்தா","மகாகவி","பெருந்தலைவர்"],0],
["‘மகாகவி’ என்று அழைக்கப்படும் தமிழ் கவிஞர் யார்?",["பாரதியார்","பாரதிதாசன்","கம்பர்","அவ்வையார்"],0]
],
tamil:[
["தமிழ் எழுத்துக்களின் மொத்த எண்ணிக்கை எவ்வளவு?",["216","247","300","12"],1],
["தமிழில் உயிரெழுத்துக்கள் எத்தனை?",["10","12","18","247"],1],
["தமிழில் மெய்யெழுத்துக்கள் எத்தனை?",["12","18","216","247"],1],
["தமிழின் முதல் இலக்கண நூலாகக் கருதப்படுவது எது?",["திருக்குறள்","தொல்காப்பியம்","சிலப்பதிகாரம்","நன்னூல்"],1],
["திருக்குறளில் மொத்த அதிகாரங்கள் எத்தனை?",["100","108","133","150"],2],
["திருக்குறளில் மொத்த குறள்கள் எத்தனை?",["1000","1200","1330","1500"],2],
["‘யாதும் ஊரே யாவரும் கேளிர்’ என்ற வரியை கூறியவர் யார்?",["கணியன் பூங்குன்றனார்","திருவள்ளுவர்","கம்பர்","அவ்வையார்"],0],
["கம்பரின் புகழ்பெற்ற படைப்பு எது?",["கம்பராமாயணம்","மணிமேகலை","பெரியபுராணம்","நாலடியார்"],0],
["தமிழின் செம்மொழி அந்தஸ்து அறிவிக்கப்பட்ட ஆண்டு எது?",["2004","1999","2010","1987"],0],
["‘தமிழ்த்தாத்தா’ என்று அழைக்கப்படுபவர் யார்?",["உ.வே.சாமிநாதையர்","பாரதியார்","கம்பர்","திருவள்ளுவர்"],0]
]
};

let category="gk", list=[], index=0, score=0, timer=15, interval=null, locked=false;

function start(cat){
 category=cat; list=[...data[cat]].sort(()=>Math.random()-.5); index=0; score=0;
 document.getElementById("home").classList.add("hidden");
 document.getElementById("result").classList.add("hidden");
 document.getElementById("quiz").classList.remove("hidden");
 show();
}
function show(){
 locked=false; timer=15;
 clearInterval(interval);
 const q=list[index];
 document.getElementById("counter").textContent=`கேள்வி ${index+1} / ${list.length}`;
 document.getElementById("timer").textContent=timer;
 document.getElementById("bar").style.width=((index)/list.length*100)+"%";
 document.getElementById("question").textContent=q[0];
 const box=document.getElementById("answers"); box.innerHTML="";
 q[1].forEach((a,i)=>{
   const b=document.createElement("button"); b.className="answer"; b.textContent=a;
   b.onclick=()=>answer(i,b); box.appendChild(b);
 });
 document.getElementById("next").classList.add("hidden");
 interval=setInterval(()=>{timer--;document.getElementById("timer").textContent=timer;if(timer<=0)answer(-1,null)},1000);
}
function answer(choice,btn){
 if(locked)return; locked=true; clearInterval(interval);
 const q=list[index], buttons=[...document.querySelectorAll(".answer")];
 buttons.forEach((b,i)=>{b.disabled=true;if(i===q[2])b.classList.add("correct")});
 if(choice===q[2])score++; else if(btn)btn.classList.add("wrong");
 document.getElementById("next").classList.remove("hidden");
}
function next(){
 index++;
 if(index<list.length)show(); else finish();
}
function finish(){
 clearInterval(interval);
 document.getElementById("quiz").classList.add("hidden");
 document.getElementById("result").classList.remove("hidden");
 document.getElementById("score").textContent=`${score} / ${list.length}`;
 document.getElementById("message").textContent=
 score===list.length?"🔥 அற்புதம்! எல்லாம் சரி!":score>=7?"👏 மிகவும் நன்று!":score>=5?"👍 நல்ல முயற்சி!":"💪 இன்னும் முயற்சி செய்யுங்கள்!";
}
function restart(){start(category)}
function goHome(){
 clearInterval(interval);
 document.getElementById("quiz").classList.add("hidden");
 document.getElementById("result").classList.add("hidden");
 document.getElementById("home").classList.remove("hidden");
}
</script>
</body>
</html>
