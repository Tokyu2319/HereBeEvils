# HerebeEvils
**HerebeEvils** is the name of the universe written by Tokyu.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smooth Caret Animation</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: 'Courier New', Courier, monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .typing-container {
            display: inline-flex;
            align-items: center;
            font-size: 2rem;
            font-weight: bold;
        }

        /* The Custom Caret */
        .caret {
            display: inline-block;
            width: 4px;
            height: 1.6em;
            background-color: #00ffcc;
            margin-left: 4px;
            /* Smooth fading animation */
            animation: blink 1s infinite alternate;
        }

        /* Keyframes for smooth smooth fading blink */
        @keyframes blink {
            0% {
                opacity: 1;
            }
            40% {
                opacity: 1;
            }
            60% {
                opacity: 0;
            }
            100% {
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <div class="typing-container">
        <span>Hello, World</span><span class="caret"></span>
    </div>

</body>
</html>
