 <!DOCTYPE html>
<html>
<head>
<title>Registration</title>
</head>
<body style="background-color: bisque; text-align: center;">

<h1>AIUB COURSE REGISTRATION</h1>
 <form>
Full Name: 
<input type="text" id="name"><br><br>
Email:
 <input type="text" id="email"><br><br>

Password:
 <input type="password" id="password"><br><br>
Confirm Password:
 <input type="password" id="confirm_password"><br><br>

<input type="button" value="Register" onclick="reg()"><br><br>

 
</form>

<div id="error"></div>
  <div id="output"></div>

<script>
function reg() 
{
    var name = document.getElementById("name").value;
    var email = document.getElementById("email").value;
    var password = document.getElementById("password").value; 
    var confirm_password = document.getElementById("confirm_password").value;

    var errorDiv = document.getElementById("error");
      var outputDiv = document.getElementById("output");
 
     
      errorDiv.innerHTML = "";
      outputDiv.innerHTML = "";

      if (name === "" || email=== "" || password === "" || confirm_password === "") {
        errorDiv.innerHTML = "Please fill in all fields.";
        return false;
      }

      if (password !== confirm_password) {
        errorDiv.innerHTML = "Password not matched";
        return false;}

        if(){}


       outputDiv.innerHTML = `
        <strong>Registration Complete!</strong><br><br>
        Name: ${name}<br>
        Email: ${email}<br>
        Password: ${password}<br>
        Confirm Password: ${confirm_password}
           
    `;

    return false;
}



</script>

</body>
</html>