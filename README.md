#art-gallery-byte-bandits__login-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <script>function showPopup(){
      alert("Thankyou for loggin in! :)");
    }</script>
    <h1 class="lucy">Eunoia</h1>
    <h3 class="luca">BEAUTIFUL THINKING, A WELL MIND</h3>
    
    <link href="form.css" rel="stylesheet">
</head>
<body>
    <div class="login-container">
        <h1>
            <a href="mainpage.html">Login</a>
        </h1>
        <form id="login-form" onsubmit="validateForm(event)">
          <label for="username">Username:</label>
          <input type="text" id="username" name="username" placeholder="Enter User Name" required>
          
          <label for="password">Password:</label>
          <input type="password" id="password" name="password" placeholder="Enter Password" required>
    
          <input type="submit" value="Login" onclick="showPopup()">
        </form>
        <p id="error-message"></p>
      </div>
    
      <script src="cse326proj.js"></script>
</body>
</html>
