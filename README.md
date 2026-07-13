# FOR-MY-LOVE-OF-MY-LIFE
Hehe something special is cooking lol
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>For My Love ❤️</title>
<style>
body{margin:0;font-family:Arial,sans-serif;background:linear-gradient(135deg,#ff9ecf,#ffd6e8);display:flex;align-items:center;justify-content:center;min-height:100vh;overflow:hidden}
.card{background:#fff;padding:30px;border-radius:20px;max-width:700px;box-shadow:0 10px 30px rgba(0,0,0,.2);text-align:center;animation:fade 1s}
h1{color:#e91e63}button{padding:12px 22px;border:none;border-radius:25px;background:#e91e63;color:#fff;font-size:16px;cursor:pointer}
#letter{display:none;margin-top:20px;line-height:1.7}
.heart{position:fixed;color:#ff3b7a;animation:float 8s linear infinite}
@keyframes float{from{transform:translateY(100vh)}to{transform:translateY(-120vh)}}
@keyframes fade{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}
</style>
</head>
<body>
<div class="card">
<h1>Happy 2 Months ❤️</h1>
<p>Click below for a surprise.</p>
<button onclick="showLetter()">Open My Letter</button>
<div id="letter">
<p>Soo miss shy my official jaanuuuu... time kaise nikal gaya pata hi nahi chala. Sirf 2 months bolne me chhote lagte hain, but in 2 months mujhe meri duniya mil gayi. Har smile, har baat aur har memory mere liye special hai. Thank you for being a part of my life. I hope we create many more beautiful memories together. ❤️</p>
<h2>I Love You Forever ♾️</h2>
</div>
</div>
<script>
function showLetter(){document.getElementById('letter').style.display='block';}
setInterval(()=>{
 let h=document.createElement('div');
 h.className='heart';
 h.innerHTML='❤';
 h.style.left=Math.random()*100+'vw';
 h.style.fontSize=(16+Math.random()*24)+'px';
 document.body.appendChild(h);
 setTimeout(()=>h.remove(),8000);
},300);
</script>
</body>
</html>
