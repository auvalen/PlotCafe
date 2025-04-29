<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlotCafé | Login</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body class="login-page">

    <div class="form-container">
        <h1>PlotCafé Login</h1>
        <form action="php/login.php" method="POST">
            <input type="email" name="email" placeholder="Email" required>
            <input type="password" name="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>

        <div class="google-signup">
            <p>or</p>
            <button class="google-btn">Login with Google</button>
        </div>

        <p class="redirect">Don't have an account? <a href="signup.html">Sign up here</a></p>
    </div>

</body>
</html>