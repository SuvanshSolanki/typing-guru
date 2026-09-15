# typing-guru
this is my first git repository
<br>
author-suvansh solanki
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typing Speed Test</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div class="container">

        <h1>⌨️ Typing Speed Test</h1>

        <p class="subtitle">
            Test your typing speed and accuracy
        </p>

        <!-- Statistics -->
        <div class="stats">

            <div class="box">
                <h3>Time</h3>
                <p id="time">60</p>
            </div>

            <div class="box">
                <h3>WPM</h3>
                <p id="wpm">0</p>
            </div>

            <div class="box">
                <h3>Accuracy</h3>
                <p id="accuracy">100%</p>
            </div>

            <div class="box">
                <h3>Errors</h3>
                <p id="errors">0</p>
            </div>

        </div>

        <!-- Text to type -->
        <div class="text-box" id="textDisplay">
            The quick brown fox jumps over the lazy dog. 
            Learning to type faster requires regular practice.
            Keep practicing every day and improve your typing speed.
        </div>

        <!-- Typing Input -->
        <textarea 
            id="typingInput"
            placeholder="Start typing here..."
            disabled>
        </textarea>

        <!-- Buttons -->
        <button id="startBtn">Start Test</button>
        <button id="restartBtn">Restart</button>

        <!-- Result -->
        <div id="result"></div>

    </div>

    <script src="script.js"></script>

</body>
</html>
