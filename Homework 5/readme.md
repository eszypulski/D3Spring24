## Homework 5

After struggling immensely with Homework 4 (you can see that it's there but incomplete), I really enjoyed this assignment! It was fun to play around with the visualization. However, I still hit the gap between what I wanted to do and what I can do.

### What is this?
How to feed myself and my kid is a topic of interest 3-5 times a day. I wanted to visualize the recommended food groups. I know that the FDA has phased out the weirdly abstract and grainfull Food Pyramid, but I didn't realize they had replaced it with a metaphorical plate -- perfet for a circular visualization. I tweaked the visualization to look more like food on a plate, but didn't succeed in my goal of comparing what is recommended for a toddler and what is recommended for me. 

I got my data by using this tool: [FDA MyPlate Calculator](https://www.myplate.gov/myplate-plan).

### Screenshot of what I did
![a circle graph showing the recommended food intake for a toddler](Homework 5/screenshot.png)

### Screenshot of my attempt to have two visualizations
![a circle graph showing the recommended food intake for a toddler](Homework 5/screenshot_fail.png)

### Things I want to do...
-  Figure out how to have multiple visualizations within one SVG and move each one where I wish
- Figure out how to anchor/attach text to points that are relative to existing objects. I was basically cheating on this by manually defining the location of the center text. While I was impressed that my first guesses about where things should be, pixel-wise, were pretty accurate, it is not a smart way to do this, as editing the text or its attributes required me to scoot stuff around again. 
- Calculate the relative sizes of an adult's recommended calories vs. a toddler's. When I first played around with it, I was basing the radius on the total calories (800 for a toddler, 2200 for a breastfeeding adult, if you're curious), but in a "duh" moment, I just realized that I need to make the AREA of the circle reflect that for the sizes to be relative.
