# password
password authentication module
<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="password.css">
</head>
<body>
<div class="main">
<b>Password:</b><br>
<input type="password" id="password" autofocus class="passlength" onkeyup="match();length();CheckPasswordStrength(this.value);" />    <span id="password_strength"></span><br>
<b>Retype password:</b><br> 
<input type="password" id="repass"  onkeyup="match();length();"/> <br>
<input type="checkbox" name="checkbox" value="login" checked>Keep me log in<br>
<input type="text" placeholder="Username"/>
<label id="lbl_check"> </label><br>
<label id="lbl_length"> </label><br>
<label id="lbl_strength"> </label>

<script type="text/javascript" src="interaction.js"/>
</script>
</div>
</body>
</html>
