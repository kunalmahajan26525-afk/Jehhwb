# Jehhwb<!DOCTYPE html>
<html>
<head>
<title>Wish Challenge</title>
</head>

<body style="text-align:center;font-family:sans-serif">

<h2>Submit Your Wish 🎯</h2>

<form id="wishForm">
<input type="text" placeholder="Your Name" required><br><br>

<input type="text" placeholder="Instagram ID"><br><br>

<textarea placeholder="Write your wish"></textarea><br><br>

<button type="button" onclick="generateScore()">Submit</button>
</form>

<h3 id="result"></h3>

<script>

function generateScore(){

let score = Math.floor(Math.random()*100)+1;

document.getElementById("result").innerHTML =
"Your Wish Score: " + score;

}

</script>

</body>
</html>
