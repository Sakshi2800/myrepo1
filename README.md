<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #333;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #ddd;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Simple Web App</h1>
    <button id="clickMe">Click Me!</button>
    <p id="message"></p>
    <script>
        document.getElementById('clickMe').addEventListener('click', function() {
            document.getElementById('message').textContent = 'Button was clicked!';
        });
    </script>
</body>
</html>
