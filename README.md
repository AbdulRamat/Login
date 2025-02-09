<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SA'ADU ZUNGUR University BAUCHI Student Login</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-image: url('1.png'); /* Using 1.png as the background image */
            background-size: cover;
            background-position: center;
            position: relative;
            color: white;
        }

        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.6); /* Dark overlay */
        }

        .login-container {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 40px;
            border-radius: 10px;
            z-index: 1;
            width: 350px;
            text-align: center;
            backdrop-filter: blur(5px);
            -webkit-backdrop-filter: blur(5px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .login-container h2 {
            margin-bottom: 30px;
            color: white;
        }

        .login-form input {
            width: calc(100% - 20px);
            padding: 12px;
            margin-bottom: 20px;
            border: none;
            border-bottom: 2px solid rgba(255, 255, 255, 0.5);
            background: transparent;
            color: white;
            box-sizing: border-box;
        }

        .login-form button {
            background-color: rgba(255, 255, 255, 0.8);
            color: #333;
            border: none;
            padding: 12px 20px;
            margin-top: 15px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s;
        }

        .login-form button:hover {
            background-color: rgba(255, 255, 255, 0.95);
        }

        .login-form a {
            color: white;
            display: block;
            margin-top: 15px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>SAZUB Student Login</h2>
        <form class="login-form" id="loginForm">
            <input type="text" id="matricNumber" placeholder="Matric Number" required>
            <input type="password" id="password" placeholder="Password" required>
            <button type="submit">Login</button>
            <a href="#">Forgot Password?</a>
        </form>
    </div>

    <script>
        const loginForm = document.getElementById('loginForm');

        loginForm.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent the default form submission

            const matricNumber = document.getElementById('matricNumber').value;
            const password = document.getElementById('password').value;

            if (matricNumber === "MTHU/23/0913" && password === "123456789") {
                window.location.href = "https://abdulramat.github.io/saadu-zungur-university-bauchi/";
            } else {
                alert("Incorrect Matric Number or Password.");
            }
        });
    </script>
</body>
</html>
