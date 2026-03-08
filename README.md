<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>8 Март</title>

<style>
body{
  margin:0;
  text-align:center;
  font-family:sans-serif;
  background:#ffe6f0;
}

.page{
  padding:40px;
}

img{
  width:80%;
  max-width:400px;
  border-radius:20px;
}

button{
  margin-top:20px;
  padding:12px 25px;
  font-size:18px;
  background:#ff4d88;
  color:white;
  border:none;
  border-radius:10px;
}
</style>
</head>

<body>

<div id="first" class="page">
<h1>Сен учун 🌷</h1>

<img src="https://picsum.photos/400/300">

<br>

<button onclick="showSecond()">Бос ❤️</button>
</div>

<div id="second" class="page" style="display:none">

<h1>8-март майрамың менен! 🌹</h1>

<p>
Сен мен үчүн абдан кымбат адамсың.  
Сенин жылмайганың күндөрүмдү жарык кылат.  
Ар дайым бактылуу бол! 💖
</p>

<img src="https://picsum.photos/401/300">

</div>

<script>
function showSecond(){
document.getElementById("first").style.display="none";
document.getElementById("second").style.display="block";
}
</script>

</body>
</html>
