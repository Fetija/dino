<!DOCTYPE html>
<html>
<head>
	<title>Dino Gej</title>
</head>
<style>
	#jumpscare {position: absolute; top: 0px; left: 0px; width: 100%; height: 100%; cursor: pointer; visibility: hidden;}
</style>
<body>
	<input type="button" onclick="jumpscare()" value="click me">
	<img id="jumpscare" src="./assets/jumpscare.jpg">
	<audio id="scream" src="./assets/jumpscareAudio2.mp3"/>
	<script>
	function jumpscare() {
	var jumpscare = document.getElementById("jumpscare");
	jumpscare.style.visibility="visible"
	var audio = document.getElementById("scream");
	audio.play();
     }
 </script>
</body>



</html>
