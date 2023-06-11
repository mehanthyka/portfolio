AIM:

To create a portfolio using HTML and CSS

ALGORITHM:

1.Set up the basic structure of your HTML document.

2.Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3.Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4.Add a header section to display your name or the title of your portfolio.

5.Add images or media to enhance your portfolio. You can use the  tag to display images and embed videos or other media using appropriate HTML tags.

6.Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7.Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

CODE:
HTML CSS CODE:
```
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content=
		"width=device-width, initial-scale=1.0">
	<title>HTML Project</title>
</head>

<body>
	<!--Header(start)-->

	   
	

	<table id="header" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="grey">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td>
							

						</td>

						<td>
							<font face="Comic sans MS" size="6">
								<b>Portfolio</b>
							</font>
						</td>

						<td width="40%">
                           
							
						</td>

						<td>
							<a href="#home" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Home
								</font>
							</a>
						</td>

						<td>
							|
						</td>

						<td>
							<a href="#about" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									About
								</font>
							</a>
						</td>

						<td>
							|
						</td>

						<td>
							<a href="#projects" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Projects
								</font>
							</a>
						</td>

						<td>
							|
						</td>

						<td>
							<a href="#achievements" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Achievements
								</font>
							</a>
						</td>

						<td>
							|
						</td>

						<td>
							<a href="#contact" style="text-decoration:none">
								<font face="Verdana" size="5" color=black>
									Contact
								</font>
							</a>
						</td>
					</tr>
				</table>
			</td>
		</tr>
	</table>
	<!--Header(end)-->

	<!--Home(start)-->
	<table id="home" border="1" width="100%"
		cellpadding="20" cellspacing="0" bgcolor="black">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td align="center" valign="middle">
							<h3>
								<font face="Times New Roman"
									size="6" color="#ffffff">
									
								</font>
							</h3>

							<h2>
								<font face="Verdana" size="6"
									color="#4CAF50">
									<!-- Freelance Programmer -->
								</font>
							</h2>
						</td>
					</tr>
				</table>
			</td>
		</tr>
	</table>
	<!--Home(end)-->


	<!--About(start)-->
	<table id="about" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="skyblue">
								About Me
							</font>
							<hr color="#0000FF" width="90">
						</td>
					</tr>

					<tr>
						<td width="10%" height="10%">
							<img src="Screenshot 2023-03-20 184717.png" width="200" height="200">
						</td>

						<td width="60%">
							<font face="Verdana" size="4"
								color="white">
								Thanks for your interest, here
								is a quick story of me and this
								website.
								<hr color="black">
								Mehanthyka A Student from  Saveetha Engineering College.
								I am interested in solving programs in different ways.
								<hr color="black">

								I do my work mainly in C-Language,
								C++ and JAVA. C++ and Data Structure
								& Algorithm are my stronger section.
							
								<hr color="black">

								This website is basically one of my
								Web Development project which is
								built using HTML only.
								Here one can also find ideas for
								projects in different languages.

								Thanks again for reading this,
								because of people like you, it
								exists and prospers!
								<hr color="black">
					
							</font>
						</td>
					</tr>
				</table>
				<hr color="black">
				<hr color="black">
				<hr color="black">
			</td>
		</tr>
	</table>
	<!--About(end)-->


	<!--Projects(start)-->
	<table id="projects" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#c2c0c3">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="black">
								Projects
							</font>
							<hr color="black" width="90">
						</td>
					</tr>

					<tr>
						<td height="10">
							<font face="Times New Roman"
								size="5" color="black">
								<ul>
									<li>
										Cyber sercurity
										<a href="#" style="text-decoration:none">
											 ➲
										</a>
									</li>

									<li>
										<hr color="#c2c0c3">
										Microsoft Bot
										<a href="#" style="text-decoration:none"
											color="#c2c0c3">
											 ➲
										</a>
									</li>

									
					</tr>
				</table>
			</td>
		</tr>
	</table>
	<!--Projects(end)-->

	<!--Achievement(start)-->
	<table id="achievements" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center" valign="middle">
							<font face="Verdana" size="7" color="skyblue">
								Achievements
								<hr color="#0000FF" width="100">
							</font>
						</td>
					</tr>

					<tr>
						<td>
							<font face="Verdana" size="4" color="white">
								<ul>
									<li>
										<b>Intern at Connect Infosytsem</b>
										<ul>
											<li>
												January,2023 - March,2023.
											</li>
											<li>
												Write technical articles
												on programming related topics.
											</li>
										</ul>
									</li>

									<li>
										<hr color="black">
										<hr color="black">
										<hr color="black">
										<b>Workshop</b>
										<ul>
											<li>
												March,2023.
											</li>
											<li>
												Attended Workshop in Microsoft Bot.
											</li>
										</ul>
									</li>

									<li>
										<hr color="black">
										<hr color="black">
										<hr color="black">
										<b>Paper Presentation.</b>
										<ul>
											<li>
												October,2020.
											</li>
											<li>
												Presented paper in topic of Cyber security
											</li>
											<hr color="black">
											<hr color="black">
											<hr color="black">
											<hr color="black">
											<hr color="black">
										</ul>
									</li>

								</ul>

							</font>
						</td>
					</tr>
				</table>
			</td>
		</tr>
	</table>
	<!--Achievement(end)-->


	<!--Contact(start)-->
	<table id="contact" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#c2c0c3">
		<tr>
			<td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="black">
								Contact
							</font>
							<hr color="black" width="90">
						</td>
					</tr>

					<tr>
						<td align="center" valign="top">
							<table border="0" width="50%" cellpadding="15"
								cellspacing="0" align="center" bgcolor="black">
								<tr>
									<td width="30%">
										<hr color="black">
										<font face="Verdana" size="4"
											color="#ffffff">
											Name
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="text" size="40">
										</font>
									</td>
								</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Email
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="email" size="40">
										</font>
									</td>
								</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Number
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="number" size="12">
										</font>
									</td>
								</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="#ffffff">
											Message
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<textarea rows="5"
												cols="37">
											</textarea>
										</font>
									</td>
								</tr>
								<tr>
									<td width="30%">
										
									</td>
									<td width="70%">
										<button type="Submit">
											<font face="Verdana"
												size="4" color="black">
												<b>Submit</b>
											</font>
										</button>
										<hr color="black">
										<hr color="black">
									</td>
								</tr>
							</table>
						</td>

					</tr>
					<tr>
						<td colspan="2">		
						</td>
					</tr>
				</table>
			</td>
		</tr>
	</table>
	<!--Contact(end)-->
</body>
</html>
```
OUTPUT:

![_C__Users_mehan_OneDrive_Documents_html_portfolio html (2)](https://github.com/mehanthyka/portfolio/assets/127507580/b44336a6-0ea2-4dac-a952-bd3718b8f1a9)

RESULT:

Thus, a Portfolio is created using HTML and CSS.
