electronics-site/
│
├── index.html
├── products.html
├── details.html
├── about.html
├── contact.html
├── style.css
├── images/
├── videos/
└── audio/
body{
font-family:Times New Roman;
margin:0;
background:#f5f5f5;
}

header{
background:black;
color:white;
padding:15px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
}

.container{
padding:20px;
}

img{
width:300px;
border-radius:10px;
}

footer{
background:black;
color:white;
text-align:center;
padding:10px;
}
<!DOCTYPE html>
<html>
<head>
<title>ElectroHub Home</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>ElectroHub</h1>
<nav>
<a href="index.html">Home</a>
<a href="products.html">Products</a>
<a href="details.html">Details</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<h2>Welcome to ElectroHub</h2>

<video width="400" controls>
<source src="videos/intro.mp4" type="video/mp4">
</video>

<p>Your trusted electronics shop.</p>
</div>

<footer>©2026 ElectroHub</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Products</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>Products</h1>
<nav>
<a href="index.html">Home</a>
<a href="products.html">Products</a>
<a href="details.html">Details</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<h2>Laptop</h2>
<img src="images/laptop.jpg">

<h2>Smartphone</h2>
<img src="images/phone.jpg">
</div>

<footer>©2026 ElectroHub</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Product Details</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>Product Details</h1>
<nav>
<a href="index.html">Home</a>
<a href="products.html">Products</a>
<a href="details.html">Details</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<h2>Smartphone X</h2>
<p>High performance device.</p>

<audio controls>
<source src="audio/review.mp3" type="audio/mpeg">
</audio>

</div>

<footer>©2026 ElectroHub</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>About</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>About Us</h1>
<nav>
<a href="index.html">Home</a>
<a href="products.html">Products</a>
<a href="details.html">Details</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<p>ElectroHub sells quality electronics across Ghana.</p>
</div>

<footer>©2026 ElectroHub</footer>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Contact</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
<h1>Contact Us</h1>
<nav>
<a href="index.html">Home</a>
<a href="products.html">Products</a>
<a href="details.html">Details</a>
<a href="about.html">About</a>
<a href="contact.html">Contact</a>
</nav>
</header>

<div class="container">
<form>
<input type="text" placeholder="Name"><br><br>
<input type="email" placeholder="Email"><br><br>
<textarea placeholder="Message"></textarea><br><br>
<button>Send</button>
</form>
</div>

<footer>©2026 ElectroHub</footer>
</body>
</html>
