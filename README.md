# Homepage-of-Netflix
<!DOCTYPE html>
<html>
<head>
	<title>Netflix Homepage</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">TV Shows</a></li>
				<li><a href="#">Movies</a></li>
				<li><a href="#">New & Popular</a></li>
				<li><a href="#">My List</a></li>
			</ul>
			<button>Sign In</button>
		</nav>
		<div class="hero">
			<h1>Unlimited movies, TV shows, and more.</h1>
			<p>Watch anywhere. Cancel anytime.</p>
			<button>Watch Free For 30 Days</button>
		</div>
	</header>
	<main>
		<section>
			<h2>TV Shows</h2>
			<div class="grid">
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="TV Show">
					<h3>TV Show Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="TV Show">
					<h3>TV Show Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="TV Show">
					<h3>TV Show Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="TV Show">
					<h3>TV Show Title</h3>
				</div>
			</div>
		</section>
		<section>
			<h2>Movies</h2>
			<div class="grid">
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="Movie">
					<h3>Movie Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="Movie">
					<h3>Movie Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="Movie">
					<h3>Movie Title</h3>
				</div>
				<div class="card">
					<img src="https://picsum.photos/200/300" alt="Movie">
					<h3>Movie Title</h3>
				</div>
			</div>
		</section>
	</main>
	<footer>
		<p>&copy; 2023 Netflix, Inc.</p>
	</footer>
</body>
</html>
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

body {
	font-family: Arial, sans-serif;
}

header {
	background-color: #141414;
	color: #fff;
	padding: 20px;
}

nav {
	display: flex;
	justify-content: space-between;
	align-items: center;
	margin-bottom: 20px;
}

nav ul {
	display: flex;
	list-style: none;
}

nav ul li {
	margin-right: 20px;
}

nav ul li a {
	color: #fff;
	text-decoration: none;
}

nav ul li a:hover {
	text-decoration: underline;
}

button {
	background-color: #e50914;
	color: #fff;
	border: none;
	padding: 10px 20px;
	border-radius: 5px;
	cursor: pointer;
}

.hero {
	max-width: 800px;
	margin: 0 auto;
	text-align: center;
}

.hero h1 {
	font-size: 3rem;
	margin-bottom: 20px;
}

.hero p {
	font-size: 1.5rem;
	margin-bottom: 20px;
}

main {
	max-width: 1200px;
	margin: 0 auto;
	padding: 20px;
}

section {
	margin-bottom: 40px;
}

section h2 {
	font-size: 2rem;
	margin-bottom: 20px;
}

.grid {
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
	grid-gap: 20px;
}

.card {
	background-color: #fff;
	box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
	border-radius: 5px;
	overflow: hidden;
}

.card img {
	width: 100%;
	height: 100%;
	object-fit: cover;
}

.card h3 {
	font-size: 1.2rem;
	padding: 10px;
}
