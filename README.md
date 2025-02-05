<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INDI'S BIGGEST EVENT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>INDI'S BIGGEST EVENT</h1>
        <p class="subtitle">1st time in India! Join fast, ends on Mar/31st/2025.</p>
        
        <form id="signup-form">
            <input type="text" id="email" placeholder="Enter your email" required>
            <input type="text" id="mobile" placeholder="Enter your mobile number" required>
            <button type="submit">Get 3 Free Spins</button>
        </form>
    </div>

    <script>
        document.getElementById('signup-form').addEventListener('submit', function (e) {
            e.preventDefault();
            const email = document.getElementById('email').value;
            const mobile = document.getElementById('mobile').value;

            // Save user data (you'll need a backend for this)
            console.log('User signed up:', { email, mobile });

            // Redirect to spin wheel page
            window.location.href = 'spin.html';
        });
    </script>
</body>
</html>
