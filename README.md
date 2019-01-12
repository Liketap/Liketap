<!DOCTYPE html>
  <lang html="Ru">
   <head>
    <meta charset="UTF-8">
     <title>Liketap</title>
      <link href="style.css" rel="stylesheet" type="text/css">
       </head>
      <body>
     <div id="menu">
    <h4 id="wrap"> Usual (от 100 руб.)</h4>  
   <h4 id="wrap2"> Prime ( от 1000 руб.)</h4>  
  </div>
 <div id="header">
  <h1 align="center" id="totle">Liketap</h1>
   </div>
    <div id="wrappercontent2">
     <img id="image2" src="images/Prime.png">
       <div id="description2"> <h4>
      <ul>
     <li>Многофункциональный сайт
    <li>Размещения рекламы
   <li>Оговоренные фичи
  <li>Общительная техподдержка (o´▽o)
 <li>Безопасная покупка
</ul>
 </h4></div>
  <div></div>
   </div>
    <div id="wrappercontent">
     <img id="image" src="images/Usual.png">
      <div id="description" ><h4>
       <ul>
      <li>Сайт для вашего сообщества
     <li>Собственный дизайн
    <li>Пиар группы (+150 пользователей)
   <li>Общительная техподдержка ʕ ᵔᴥᵔ ʔ
  <li>Безопасная покупка
 </ul>
</h4></div>
 </div>
  <footer>
   <div align="center" id="footer">2018-2019 © liketap.ru</div>
    <div id="footer2">Техподдержка:liketap@mail.ru</div>
     </footer>
      </body>
       </html>body{
	margin:0;
	background-color:#FFEBCD;
	overflow-x: hidden;
}
#header{
	background-color:#DEB887;
	height:65px;
	width:100%;
	border:2px solid #8B4513;
	position:absolute;
	margin:-15px 0px;
	color:#8B4513;
	font-size:15px;
}
#menu{
	position:fixed;
	 background-color:#DEB887;
	 height:40px;
	 width:100%;
	 margin:0px;
	 border:1px solid #8B4513;
}
footer{
	background-color:#DEB887;
	border:2px solid #8B4513;
	height:40px;
	width:100%;
	border-bottom:0px;
}
#wrappercontent{
	height:650px;
	width:610px;
	border:0px;
	border-bottom:0px;
	
}
#wrappercontent2{
    height:650px;
	width:610px;
	border:0px;
	border-bottom:0px;
	border-right:0px;
	float:right;	
}
#image{
	height:200px;
	width:380px;
	margin:130px 110px;
}
#image2{
	height:200px;
	width:380px;
	margin:130px 90px;
}
#wrap{
	margin:10px 240px;
	color:#8B4513;
}
#wrap2{
	margin:-27px 825px;
	color:#8B4513;
	width:200px;
}
#description{
	background-color:#DEB887;
	height:235px;
	width:320px;
	margin:-100px 160px;
	border:2px solid #8B4513;
	border-radius:20px;
	line-height:40px;
	color:#8B4513;
}
#description2{
	background-color:#DEB887;
	height:235px;
	width:300px;
	margin:-100px 135px;
	border:2px solid #8B4513;
	border-radius:20px;
	line-height:40px;
	color:#8B4513;
}
#footer{
	color: #342008;
	padding-top:20px;
}
#footer2{
   color: #342008;
   margin:-36px 506px;
}
