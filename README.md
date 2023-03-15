<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>
	<h1>VRenovations</h1>
	<s1>repairs made easy<s1>
	</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			font-size: 16px;
			margin: 0;
			padding: 0;
		}
		
		header {
			background-color: #333;
			color: #fff;
			padding: 20px;
			text-align: center;
		}
		
		h1 {
			font-size: 36px;
			margin: 0;
		}
		
		main {
			padding: 20px;
			max-width: 800px;
			margin: auto;
		}
		
		section {
			margin-bottom: 20px;
		}
		
		h2 {
			font-size: 24px;
			margin-bottom: 10px;
		}
		
		form {
			border: 1px solid #ccc;
			padding: 20px;
			max-width: 600px;
			margin: auto;
		}
		
		label {
			display: block;
			margin-bottom: 10px;
		}
		
		input[type="text"],
		input[type="email"],
		input[type="tel"],
		textarea {
			width: 100%;
			padding: 10px;
			border: 1px solid #ccc;
			border-radius: 4px;
			margin-bottom: 20px;
			box-sizing: border-box;
			font-size: 16px;
		}
		
		input[type="submit"] {
			background-color: #333;
			color: #fff;
			border: none;
			padding: 10px 20px;
			border-radius: 4px;
			cursor: pointer;
			font-size: 16px;
		}
		
		input[type="submit"]:hover {
			background-color: #555;
		}
		
		ul {
			list-style-type: none;
			padding: 0;
			margin: 0;
		}
		
		li {
			margin-bottom: 10px;
			padding: 10px;
			background-color: #f9f9f9;
			border: 1px solid #ccc;
			border-radius: 4px;
		}
		
		img {
			max-width: 100%;
			height: auto;
			margin-bottom: 10px;
		}
	</style>
</head>
<body>
	<header>
		<h1>Handyman Services</h1>
	</header>
	
	<main>
		<section>
			<h2>Our Services</h2>
			<ul>
				<li>Painting</li>
				<li>Flooring</li>
				<li>Assembly</li>
				<li>And more...</li>
			</ul>
		</section>
		
		<section>
			<h2>Contact Us</h2>
			<form action="#" method="post">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required>
				
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required>
				
				<label for="phone">Phone:</label>
				<input type="tel" id="phone" name="phone" required>
				
				<label for="location">
Location:</label>
<input type="text" id="location" name="location" required>
			<label for="message">Message:</label>
			<textarea id="message" name="message" required></textarea>
			
			<input type="submit" value="Submit">
		</form>
	</section>
	
	<section>
		<h2>Our Work</h2>
		<img src="img1.jpg" alt="Example of our work">
		<img src="img2.jpg" alt="Example of our work">
		<img src="img3.jpg" alt="Example of our work">
	</section>
	
	<section>
		<h2>Pricing</h2>
		<p>Our prices vary based on the specific job and any additional factors. Please contact us for a quote.</p>
	</section>
	
	<section>
		<h2>Payment Options</h2>
		<ul>
			<li>Cash</li>
			<li>E-transfer</li>
			<li>Cheque</li>
			<li><a href="https://www.paypal.com/">PayPal</a></li>
			<li><a href="https://stripe.com/">Stripe</a></li>
		</ul>
	</section>
	
	<section>
		<h2>Customer Reviews</h2>
		<ul>
			<li>"Great service and attention to detail. Highly recommend!" - John D.</li>
			<li>"Very professional and efficient. Will definitely use again." - Sarah L.</li>
			<li>"Excellent work, very pleased with the results." - Michael T.</li>
		</ul>
	</section>
</main>
</body>
</html>
