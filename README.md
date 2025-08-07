
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Weather Dashboard</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Weather Dashboard</h1>
        <form id="weather-form">
            <input type="text" id="city-input" placeholder="Enter a city name..." required>
            <button type="submit">Get Weather</button>
        </form>
        <div id="weather-result" class="weather-card"></div>
    </div>
    <footer>
        <p>&copy; 2025 Weather Dashboard Example</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
