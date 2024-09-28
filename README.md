
Index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" 
content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" 
href="style.css">
<script src="register.js"></script>
</head>

<body align ="center", onload="generate()">
<div class="box">
<h2>Register</h2>
<label>Username</label>
<input type="text" id="name" name="name">
<br><br>
<label>Password</label>
<input type="password" id="password" name="Password">
<br><br>
<label>Email</label>
<input type="email" id="email" name="email">
<br><br>
<label>Phone</label>
<input type="number" id="phone" name="number">
<br><br>
<div class="gender">
<label>Gender</label>
<input type="radio" id="male" name="gender" value="male">
<label>Male</label>
<input type="radio" id="female" name="gender" value="female">
<label>Female</label>
<br><br>
</div> 
<div id="user-input" class="inline">
<input type="text" 
id="submit" 
placeholder="Captcha code" />
</div>

<div class="inline" onclick="generate()">
<i class="fas fa-sync"></i>
</div>

<div id="image" 
class="inline" 
selectable="False">
</div>
<input type="submit" 
id="btn" 
onclick="printmsg()" />

<p id="key"></p>
</div>
</body>
</html>

