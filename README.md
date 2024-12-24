# Login
Login
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Student Login</title>
    <style>
        body {
            font-family: sans-serif;
            background-image: url('1.png'); /* Replace with your image */
            background-size: cover;
            background-position: center;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            position: relative; /* For overlay */
        }
        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.3); /* Overlay for better readability */
        }

        .login-container {
            background-color: rgba(255, 255, 255, 0.9); /* Slightly transparent white */
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
            width: 350px;
            z-index: 1; /* Ensure it's above the overlay */
        }
        .login-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #333;
        }

        .login-form input {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
         .login-form button {
            background-color: #007bff;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        .login-form button:hover {
            background-color: #0056b3;
        }

        .login-form a {
            display: block;
            text-align: center;
            margin-top: 10px;
            color: #007bff;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Student Login</h2>
        <form class="login-form">
            <input type="text" placeholder="Matric Number" required>
            <input type="password" placeholder="Password" required>
            <button type="submit" ><a href="https://abdulramat.github.io/saadu-zungur-university-bauchi/">Login</button>
            <a href="https://abdulramat.github.io/saadu-zungur-university-bauchi/">Forgot Password?</a>
        </form>
    </div>
</body>
</html>
