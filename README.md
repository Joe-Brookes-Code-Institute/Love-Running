<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up - Love Running</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Honk&family=Arial&family=Verdana&family=Courier+New&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #77df8d;
            margin: 0;
            padding: 0;
        }
        h1 {
            font-family: 'Honk', cursive;
            font-size: 3em;
            color: #86c48b;
            margin: 0;
            padding: 20px 0;
            background-color: #055f23;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3);
        }
        .navbar {
            background-color: #4CAF50;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 50px;
        }
        .navbar a {
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 16px;
        }
        .navbar a:hover {
            background-color: #3e8e41;
        }
        form {
            background-color: white;
            max-width: 400px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input[type="text"], input[type="email"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Sign Up for Love Running</h1>
    
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="gallery.html">Gallery</a>
        <a href="signup.html">Sign Up</a>
    </div>

    <form action="#" method="post">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="password" name="password" placeholder="Choose a Password" required>
        <input type="submit" value="Sign Up">
    </form>
</body>
</html>
