<!DOCTYPE html>
<html lang="en">
<head>

<title> VGS </title>
<script>
window.onload = function() {

var canvas = document.getElementById("paper"),
c = canvas.getContent("2d");

c.fillStyle = "black";
c.fillRect(0,0, canvas.width, canvas.height);

c.fillStyle="red";
c.fillRect(20,20,50);


  };
</script>
<style>
</style>
</head>
<body>
<canvas id="paper" width="500" height="500">
</canvas>
</body>
</html>

