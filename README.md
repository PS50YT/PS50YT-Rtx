<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Horizontal Navigation Bar</title>
    <style>
        /* Style for the navigation bar */
        .navbar {
            display: flex; /* Makes the items align horizontally */
            background-color: #333; /* Background color of the navbar */
            overflow: hidden; /* Ensures no overflow */
        }

        /* Style for navigation links */
        .navbar a {
            flex: 1; /* Ensures equal spacing for items */
            color: white; /* Text color */
            text-align: center; /* Center text */
            padding: 14px 20px; /* Padding for links */
            text-decoration: none; /* Remove underline */
        }

        /* Hover effect */
        .navbar a:hover {
            background-color: #575757; /* Change background on hover */
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </div>
</body>
</html>
