frontend-nanodegree-mobile-portfolio
====================================

Welcome to my web optimization project made possible through Udacity.

This repository contains two web pages that were optimized.

1) index.html

	To review the finished product, please click on index.html.

	You can also right click to open the file in a text editor to see the HTML code.

	For optimization, the following code was changed:

		1. Pizzeria-small.jpg was used on the portfolio page instead of the large pic.  I used the compressed file that google recommended.

		2. I commented out the google fonts

		3. inlined style.css

		4. moved print.css and js links to end of the html body

2) pizza.html

	To review the finished product, visit the views folder and click on pizza.html

	To review the code changes, visit js/main.js.

	For optimization, the following code was changed in main.js:

		1. for changePizzaSizes, I followed Udacity's instructions in the Browser Rendering Optimization course.  I created a var randomPizzas to remove as much work from the for loop, then resized the pizzas using percentages in a switch(size).

		2. On line 520, I created another variable to remove work from the for loop.

		3. On line 544 I lowered the the pizza length to 50 since there's never more than 50 on the screen at a time.