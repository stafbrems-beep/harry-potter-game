<!DOCTYPE html>
<html>
<head>
  <title>Wizard Adventure</title>
</head>
<body style="background:black; color:lime; font-family:monospace;">

<h1>🧙 Wizard Adventure</h1>
<p id="story">Je wordt wakker in een mysterieuze toverschool...</p>

<button onclick="choice1()">Ga naar links</button>
<button onclick="choice2()">Ga naar rechts</button>

<script>
function choice1() {
  document.getElementById("story").innerHTML =
  "Je vindt een magische staf! Je bent sterker geworden.";
}

function choice2() {
  document.getElementById("story").innerHTML =
  "Je loopt een donkere kamer binnen... een monster verschijnt!";
}
</script>

</body>
</html>
