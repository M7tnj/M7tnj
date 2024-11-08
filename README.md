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
            white-space: nowrap; /* Prevent line breaks */
        }

        @keyframes flicker {
            0% { opacity: 1; }
            50% { opacity: 0.7; }
            100% { opacity: 1; }
        }

        .gif-container {
            transition: transform ⬤
