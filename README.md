<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlotCafé | Signup</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body class="signup-page">

    <div class="form-container">
        <h1>PlotCafé Signup</h1>
        <form action="php/signup.php" method="POST">
            <input type="text" name="username" placeholder="Username" required>
            <input type="email" name="email" placeholder="Email" required>
            <input type="password" name="password" placeholder="Password" required>
            <input type="text" name="discord" placeholder="Discord Username (optional)">
            <input type="url" name="patreon" placeholder="Patreon Link (optional)">
            <button type="submit">Sign Up</button>
        </form>

        <div class="google-signup">
            <p>or</p>
            <button class="google-btn">Sign up with Google</button>
        </div>

        <p class="redirect">Already have an account? <a href="login.html">Login here</a></p>
    </div>

</body>
</html>