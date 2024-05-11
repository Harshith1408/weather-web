used html and css for the main frame and beautification of the webpage and javascript for the action to be performed and used google API for the live weather updates
<!DOCTYPE html>

<head>
	<link rel="stylesheet" href="m2.css">
	<link rel="stylesheet" href=
"https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
	<link rel="stylesheet" href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
	<link rel="stylesheet" href=
"https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap">
	<title>GFG App</title>
</head>

<body>
	<div class="container">
		<div class="weather-card">
			

			<h1 style="color: blue;">
			
				Weather App
			</h1>
			<input type="text" id="city-input"
				placeholder="Enter city name">
			<button id="city-input-btn"
					onclick="weatherFn($('#city-input').val())">
					Get Weather
			</button>
			<div id="weather-info"
				class="animate__animated animate__fadeIn">
				<h3 id="city-name"></h3>
				<p id="date"></p>
				<p id="temperature"></p>
				<p id="description"></p>
				<p id="wind-speed"></p>
			</div>
		</div>
	</div>
	<script src=
"https://code.jquery.com/jquery-3.6.0.min.js">
	</script>
	<script src=
"https://momentjs.com/downloads/moment.min.js">
	</script>
	<script src="m3.js"></script>
</body>

</html>
