<html>
<head>
<style>
h1{
	text-align: center;
}
body{
	background-color: black;
	color: white;
}


h2{
	color: white;
	text-align: center;
}

p{
	font-family: verdana;
	font-size: 20px;
	text-align: center;
	
}

a{
	color:white;
	
}
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
ul { display:table; margin:0 auto;}
ol { display:table; margin:0 auto;}
</style>
<title>自我介紹</title>
</head>
<body>
<h1>自我<span style="background-color:orange; color:black">介紹</span></h1>
<h2>個人資訊</h2>
	<img src="cat.jpg" width="200" height="150">
  <ul style="list-style-type:circle">
    <li >名字:黃道均</li> 
    <li>學號:108062320</li> 
    <li>科系:資工</li> 
    <li>班級:梅班</li> 
  </ul>
<h2>本學期修的科目</h2>
	<ol>
		<li width="230"; auto> 微積分B(一)</li>
		<li>普通物理(一)</li>
		<li>離散數學</li>
		<li>計算機程式設計(一)</li>
		<li>資訊系統及應用導論</li>
		<li>大學中文</li>
		<li>社會學導論</li>
		<li>大一體育</li>
	</ol>
<h2>聯絡資訊</h2>
	<p>E-mail:gene891005@gmail.com</p>
	<p>Instagram:<a href="https://www.instagram.com/gene891005/?hl=zh-tw">@gene891005</a></p>

<script language="JavaScript">
function ShowTime(){
　document.getElementById('showbox').innerHTML = new Date();
　setTimeout('ShowTime()',1000);
}
</script>
<body onload="ShowTime()">
<div onclick="ChangeColor('white')" style="background-color: black;color: white; border:3px double; width:150px;height:200px;float:right;">
<div id="showbox"></div>
</body>
</html>
