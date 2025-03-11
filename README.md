# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Dashboard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Weather Dashboard</h1>
    <form id="weatherForm">
        <input type="text" id="cityName" placeholder="Enter city name" required>
        <button type="submit">Get Weather</button>
    </form>
    <div id="weatherInfo">
        <p id="temperature"></p>
        <p id="humidity"></p>
        <p id="description"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>
