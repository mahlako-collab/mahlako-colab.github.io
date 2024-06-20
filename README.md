
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            display: flex;
            align-items: center;
            background-color: #f8f8f8;
            padding: 10px 20px;
        }
        .profile-picture {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 20px;
        }
        .nav-menu {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        .nav-menu li {
            margin: 0 10px;
        }
        .nav-menu a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .banner {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 50px 0;
        }
    </style>
</head>
<body>

    <header class="header">
        <img src="profile-picture.jpg" alt="Profile Picture" class="profile-picture">
        <nav>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
            </ul>
        </nav>
    </header>

    <div class="banner">
        <h1>Welcome to My Website</h1>
        <p>This is a banner section.</p>
    </div>

</body>
</html>
