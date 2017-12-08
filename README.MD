<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>无标题文档</title>
<script>
function tt(){
	var x;
var d=new Date().getDay(); 
switch (d) 
{ 
  case 0:x="今天是星期日"; 
  break; 
  case 1:x="今天是星期一"; 
  break; 
  case 2:x="今天是星期二"; 
  break; 
  case 3:x="今天是星期三"; 
  break; 
  case 4:x="今天是星期四"; 
  break; 
  case 5:x="今天是星期5"; 
  break; 
  case 6:x="今天是星期6"; 
  break; 
}
document.getElementById("div1").innerHTML=x;
}
</script>
</head>

<body>
<div id="div1"></div>
<input id="btn1" type="button" value="123" onClick="tt()">
</body>
</html>
