<!DOCTYPE html>
<html>
<head>
<title>Calculator</title>
</head>
<body>
<h2>Simple Calculator</h2>
<input id="num1" type="number">
<input id="num2" type="number">
<br><br>
<button onclick="add()">Add</button>
<p id="result"></p>

<script>
function add() {
let a = Number(document.getElementById("num1").value);
let b = Number(document.getElementById("num2").value);
document.getElementById("result").innerText = a + b;
}
</script>
</body>
</html>
