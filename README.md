<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        .hidden-message {
            display: none;
            font-size: 2em;
            color: #ff4081;
        }
    </style>
</head>
<body>
    <img src="https://via.placeholder.com/300x200" alt="Click me" style="cursor: pointer;" onclick="showMessage()">
    <div class="hidden-message" id="message">Happy Birthday, PRIYA!</div>

    <script>
        function showMessage() {
            document.getElementById('message').style.display = 'block';
        }
    </script>
</body>
</html>
