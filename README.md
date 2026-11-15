
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>صدقة جارية</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;font-family:Tahoma,Arial,sans-serif;
 background:#f7f5ed;color:#234538;text-align:center;
}
header{
 background:linear-gradient(140deg,#103d30,#23614b);
 color:#f5e8c5;padding:65px 20px;
 border-radius:0 0 35px 35px;
}
header h1{font-size:36px;color:#e6ce91}
header p{line-height:2}
section{padding:25px 16px;max-width:850px;margin:auto}
.card{
 background:white;padding:25px;margin:16px 0;
 border-radius:20px;box-shadow:0 5px 20px #0000000c;
}
h2{color:#a98543}
p{line-height:2}
button{
 background:#205541;color:white;border:0;
 padding:13px 25px;border-radius:12px;
 font-size:16px;cursor:pointer;margin:7px;
}
button:hover{background:#a98543}
.counter{font-size:35px;color:#a98543;margin:15px}
footer{
 background:#123d30;color:#f5e8c5;
 padding:30px;margin-top:35px;line-height:2
}
a{color:#a98543;text-decoration:none}
</style>
</head>
<body>

<header>
 <div style="font-size:48px">🌙</div>
 <h1>صدقة جارية</h1>
 <h3>على روح فقيدتنا الغالية</h3>
 <p>
 اللهم ارحمها واغفر لها، وأنر قبرها،
 واجعل الجنة دارها ومستقرها.
 </p>
 <p>🤍 اللهم اجعل هذا العمل نوراً لها لا ينقطع 🤍</p>
</header>

<section>
 <div class="card">
  <h2>🤲 دعاء للمتوفاة</h2>
  <p>
  اللهم إنها في ذمتك وحبل جوارك،
  فقها فتنة القبر وعذاب النار،
  اللهم آنس وحشتها، ونوّر قبرها،
  واجعل قبرها روضة من رياض الجنة،
  واجمعها بمن تحب في الفردوس الأعلى.
  </p>
  <button onclick="copyDua()">نسخ الدعاء</button>
 </div>

 <div class="card">
  <h2>📖 القرآن الكريم</h2>
  <p>اقرأ ما تيسر من كتاب الله، واجعل الدعاء لها بعد قراءتك.</p>
  <a href="https://quran.com/ar" target="_blank">
   <button>افتح القرآن الكريم</button>
  </a>
 </div>

 <div class="card">
  <h2>📿 عداد التسبيح</h2>
  <p>سبحان الله وبحمده، سبحان الله العظيم</p>
  <div class="counter" id="count">0</div>
  <button onclick="increment()">تسبيح</button>
  <button onclick="resetCount()">إعادة العداد</button>
 </div>

 <div class="card">
  <h2>💧 سقيا الماء</h2>
  <p>
  ساهم في توفير الماء للمحتاجين،
  واجعلها صدقة جارية بنية الثواب لها.
  </p>
  <p>سيتم إضافة رابط التبرع إلى جهة خيرية موثوقة هنا.</p>
 </div>

 <div class="card">
  <h2>❤️ أبواب الخير</h2>
  <p>🌳 المساهمة في زراعة الأشجار</p>
  <p>🍞 إطعام المحتاجين</p>
  <p>💧 توفير مياه الشرب</p>
  <p>📚 المساهمة في نشر العلم النافع</p>
 </div>

 <div class="card">
  <h2>🔗 انشر الخير</h2>
  <p>ساهم في نشر هذا الموقع، فربما دعا لها أحدهم دعوة صادقة.</p>
  <button onclick="shareSite()">مشاركة الموقع</button>
 </div>
</section>

<footer>
 <h3>اللهم ارحمها رحمة تطمئن بها روحها</h3>
 واجعل كل حرف يُقرأ وكل دعاء يُرفع
 في ميزان حسناتها.
 <p>نسألكم الدعاء لها بالرحمة والمغفرة 🤍</p>
</footer>

<script>
let count=0;
function increment(){
 count++;
 document.getElementById('count').innerText=count;
}
function resetCount(){
 count=0;
 document.getElementById('count').innerText=count;
}
function copyDua(){
 const dua="اللهم ارحمها واغفر لها، وأنر قبرها، واجعل الجنة دارها ومستقرها.";
 navigator.clipboard.writeText(dua);
 alert("تم نسخ الدعاء");
}
function shareSite(){
 if(navigator.share){
  navigator.share({
   title:"صدقة جارية",
   text:"صدقة جارية على روح فقيدتنا الغالية، نسألكم الدعاء لها."
  });
 }else{
  navigator.clipboard.writeText(location.href);
  alert("تم نسخ رابط الموقع");
 }
}
</script>
</body>
</html>
# -sadaqa-jariah