# Do-you-like-me-
index.html
<!DOCTYPE html>
<html>
<head>
  <title>Question</title>
</head>
<body style="text-align:center; font-family:Arial; margin-top:100px;">

<h2 id="question">Do you like me?</h2>

<button onclick="yes()">Yes</button>
<button onclick="no()">No</button>

<script>
function no() {
  document.getElementById("question").innerText = "Ek baar aur soch lo 😌";
}

function yes() {
  document.getElementById("question").innerText = "Mujhe pata hi tha 😍";
}
</script>

</body>
</html>
