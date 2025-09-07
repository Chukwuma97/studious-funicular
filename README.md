<!DOCTYPE html>
<html lang="eng">
	<head>
		<!-- CO710 Statement of Authorship
			I Chukwuma Okonkwo, 000944711 certify that this material is
			my original work!. No other person's work has been used
			without due acknowledgement. I have not made my work available
			to anyone else -->
			
		<title>Sandy and Leslie's apartment</title>
		<link href="apartment_layout.css" rel="stylesheet" type="text/css">
		<link href="printstyles.css" rel="stylesheet">
		<link href="mobile.css" rel="stylesheet" type="text/css">
	</head>
	<body>
		<header>
			<h1>Sandy and Leslie's Apartment</h1>
			<h5>Click a room for a detailed view</h5>
			<img src="apartmentfloorplan.jpg" alt="apartment" usemap="#apartment">
			<map name="apartment">
				<area shape="rect" coords="50,50,170,120" alt="bedroom" href="bedroom.html" title="Bedroom1">
				<area shape="poly" coords="200,50,300,130" alt="bedroom" href="bedroom.html" title="Bedroom2">
				<area shape="circle" coords="400,100,50" alt="dining room" href="diningroom.html" title="Dining Room">
				<area shape="rect" coords="400,200,550,400" alt="living room" href="livingroom.html" title="Living Room">
				<area shape="rect" coords="260,210,380,330" alt="kitchen" href="kitchen.html" title="Kitchen">
			</map>
		</header>
		<nav>
			<a href="apartment.html">Apartment</a>
			<span>|</span>
			<a href="bedroom.html">Bedroom 1</a>
			<span>|</span>
			<a href="bedroom.html">Bedroom 2</a>
			<span>|</span>
			<a href="diningroom.html">Dining Room</a>
			<span>|</span>
			<a href="kitchen.html">Kitchen</a>
			<span>|</span>
			<a href="livingroom.html">Living Room</a>
		</nav>
		<div id="grid">
			<div class="welcome">
				<h2>Welcome Message</h2>
				<audio src="apartment.mp3" controls>
				</audio>
					<p>Transcript: Hello. Welcome to our apartment. You'll really enjoy living here. The rooms are spacious and the apartment building amenities are fantastic. We look forward to hearing from you!</p>
				
				<h2>Survey</h2>
				<form>
					<legend>How did you find out about this apartment? Check any that apply:</legend>
					<div>
						<input type="checkbox" name="web" value="Web Search" id="ws">
						<label for="ws">Web Search</label>
						<input type="checkbox" name="friend" value="Friend" id="f">
						<label for="f">Friend</label>
						<input type="checkbox" name="newspaper" value="Newspaper" id="np">
						<label for="np">Newspaper</label>
					</div>
					<div>
						<section>
							<input type="submit" value="SUBMIT" class="btn">
							<input type="reset" value="RESET FORM" class="btn">
						</section>
					</div>
				</form>
			</div>

			<div class="services">
				<h2>Apartment services:</h2>
				<table>
					<thead>
						<tr class="gray">
							<th>Service</th>
							<th>Day/Hours</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<td>Gym</td>
							<td rowspan="2" colspan="3">Monday-Friday 6am - 10pm<br>Saturday 8am - 8pm<br>Sunday 8am - 5pm</td>
						</tr>
						<tr>
							<td>Pool</td>
						</tr>
						<tr>
							<td>Laundry</td>
							<td>24/7</td>
						</tr>
						<tr class="green">
							<td colspan="4">Please do not allow people you do not know to use<br> these facilities</td>
						</tr>
					</tbody>
				</table>
			</div>
			
			<div class="map">
				<h2>Location</h2>
				<img src="location.png" alt="map">
			</div>
		</div>
		
		<h2>Gallery</h2>
			<div id="gallery">
				<div class="caption">
					<h3>Balcony</h3>
					<img src="thumbnails/balcony_sm.jpg" alt="balcony">
				</div>
				<div class="caption">
					<h3>Bathroom</h3>
					<img src="thumbnails/bathroom_sm.jpg" alt="bathroom">
				</div>
				<div class="caption">
					<h3>Bedroom</h3>
					<img src="thumbnails/bedroom_sm.jpg" alt="bedroom">
				</div>
				<div class="caption">
					<h3>Dining Room</h3>
					<img src="thumbnails/diningroom_sm.jpg" alt="dining room">
				</div>
				<div class="caption">
					<h3>Kitchen</h3>
					<img src="thumbnails/kitchen_sm.jpg" alt="kitchen">
				</div>
				<div class="caption">
					<h3>Living Room</h3>
					<img src="thumbnails/livingroom_sm.jpg" alt="living room">
				</div>
			</div>
		
		<footer>
			<p>For more information contact: <a href="mailto:SandyAndLeslie@example.com">SandyAndLeslie@example.com</a> or <a href="tel:(905)555-1234">(905) 555-1234</a></p>
			<p>&copy; Sandy and Leslie 2022</p>
		</footer>
	</body>	
</html>
