frontend-nanodegree-mobile-portfolio
====================================

For web optimization of index.html, the following items were changed:

1. Pizzeria-small.jpg was used on the portfolio page instead of the large pic.  I used the compressed file that google recommended.

2. I commented out the google fonts

3. inlined style.css

4. moved print.css and js links to end of the html body


For 60 fps and quick pizza resize on the pizza site:

1. for changePizzaSizes, I followed Udacity's instructions in the Browser Rendering Optimization course.  I created a var randomPizzas to remove as much work from the for loop, then resized the pizzas using percentages in a switch(size).

2. On line 520, I created another variable to remove work from the for loop.

3. On line 544 I lowered the the pizza length to 50 since there's never more than 50 on the screen at a time.