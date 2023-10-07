<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Creative Portfolio</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #f4d2d3; /* Pastel pink background color */
            color: #8bc4d7; /* Pastel blue text color */
            margin: 0;
            padding: 0;
        }
        
        .header {
            text-align: center;
            padding: 40px;
        }

        .typewriter-text {
            font-size: 24px;
            overflow: hidden; /* Hide text overflow */
            border-right: 2px solid #333; /* Typing cursor effect */
            white-space: nowrap; /* Keep text in one line */
            animation: typing 3s steps(40) 1s infinite alternate;
        }

        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }

        .portfolio-content {
            text-align: center;
            padding: 20px;
        }

        /* Add your portfolio content styles here */
    </style>
</head>
<body>
    <header class="header">
        <h1>Your Name</h1>
        <p class="typewriter-text">Creative Portfolio</p>
    </header>

    <div class="portfolio-content">
        <!-- Add your portfolio items and content here -->
        <h2>Portfolio Item 1</h2>
        <p>Description of your first portfolio item.</p>

        <h2>Portfolio Item 2</h2>
        <p>Description of your second portfolio item.</p>

        <!-- Add more items as needed -->
    </div>
</body>
</html>
