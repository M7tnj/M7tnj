<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacker Style Text with GIF</title>
    <style>
        body {
            background-color: black; /* Dark background for hacker aesthetic */
            color: #00FFFF; /* Text color */
            font-family: 'Courier New', monospace; /* Monospace font */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* Full viewport height */
            margin: 0; /* Remove default margin */
        }

        .hacker-text {
            font-size: 24px; /* Font size */
            text-shadow: 0 0 5px #00FFFF, 0 0 10px #00FFFF, 0 0 15px #00FFFF; /* Glowing effect */
            animation: flicker 1.5s infinite alternate; /* Flicker animation */
        }

        @keyframes flicker {
            0% { opacity: 1; }
            50% { opacity: 0.7; }
            100% { opacity: 1; }
        }

        .gif-container {
            transition: transform 0.3s; /* Smooth transition for hover effect */
        }

        .gif-container:hover {
            transform: scale(1.1); /* Scale up on hover */
        }
    </style>
</head>
<body>
    <div style="display: flex; align-items: center;">
        <div class="gif-container" style="margin-right: 20px;">
            <img src="https://orig00.deviantart.net/1954/f/2013/245/3/5/clash_of_geometry__animated__by_plutonia_v41-d6kpuve.png" 
                 alt="Descriptive Text for the GIF" 
                 style="width: 80px; height: auto;" />
        </div>
        <h1 class="hacker-text">
            <img src="https://readme-typing-svg.herokuapp.com?font=Source+Code+Pro&size=24&duration=1500&color=00FFFF&center=true&vCenter=true&width=435&lines=Hey..+I'm+Mostafa;This+is..;..my+Github..;" alt="Typing SVG"/>
        </h1>
    </div>
</body>
</html>
