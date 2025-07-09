<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="800" height="800" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(100,0);
ctx.lineTo(100,800);

ctx.moveTo(200,0);
ctx.lineTo(200,800);

ctx.moveTo(300,0);
ctx.lineTo(300,800);

ctx.moveTo(400,0);
ctx.lineTo(400,800);

ctx.moveTo(500,0);
ctx.lineTo(500,800);

ctx.moveTo(600,0);
ctx.lineTo(600,800);

ctx.moveTo(700,0);
ctx.lineTo(700,800);


ctx.moveTo(0,100);
ctx.lineTo(800,100);

ctx.moveTo(0,200);
ctx.lineTo(800,200);

ctx.moveTo(0,300);
ctx.lineTo(800,300);

ctx.moveTo(0,400);
ctx.lineTo(800,400);

ctx.moveTo(0,500);
ctx.lineTo(800,500);

ctx.moveTo(0,600);
ctx.lineTo(800,600);

ctx.moveTo(0,700);
ctx.lineTo(800,700);

ctx.stroke();
</script>

</body>
</html>
