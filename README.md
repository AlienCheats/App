
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gradient Background</title>
    <style>
        body {
            background: linear-gradient(to bottom, #000000, #003366);
            margin: 0;
            height: 100vh;
            font-family: 'Arial', sans-serif;
            color: white;
        }
        nav {
            background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent dark background */
            padding: 15px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* Add shadow for depth */
            position: sticky;
            top: 0;
            width: 100%;
            z-index: 1000;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
            text-transform: uppercase;
            letter-spacing: 1px;
            padding: 10px 20px;
            border: 2px solid #888; /* Grey contour for button-like effect */
            border-radius: 5px;
            transition: all 0.3s ease;
            background-color: transparent;
        }
        nav a:hover {
            background-color: #003366; /* Dark blue background on hover */
            color: #ffcc00; /* Gold color for the text when hovered */
            border-color: #ffcc00; /* Gold border on hover */
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Home</a>
        <a href="#dns">DNS</a>
        <a href="#direct-installs">Direct Installs</a>
        <a href="#certificate">Certificate</a>
        <a href="#help">Help</a>
    </nav>

</body>
</html>
