Processing Assign 1 
Learning to Draw


Create a comment at the beginning of your program that includes the following:
File Name
Purpose or goal of the program (1 sentence) 
Programmer’s name

Marking
80% - drawing the scene with the requirements below
10% - proper indenting is maintained 
10% - proper commenting is included (end of function comments)

Your goal is to draw one of the following things/scenes.  
a house on a street
an old school ipod
a car or truck or submarine
a snowman
a robot or MineCraft Creeper
For a tougher challenge, try a colourful Canadian Flag
any other scene that you can think of

Create a String variable to hold your name and an int variable to hold the year.
Use a text line to print these two variables near the bottom left of your screen (as if you are signing your art)

Your drawing must include:
a background colour
At least 10 shapes, including all of the following:
Lines
rectangles
Ellipses
Optional shapes: triangles, quad, arc
some shapes must be filled, using multiple colours 
You could also use random(255) to affect your color codes.
multiple stroke thicknesses. Example:  strokeWeight(5);

Tips
Need to center a rectangle? 
Start with: 	rectMode(CENTER);
Then specify the center points instead of the corner: rect(center, center, size, size)
If you want to go back to normal rectangle mode:	rectMode(CORNER);

noFill()  & noStroke()	can be useful.

Need help with colour?  Try https://processing.org/tutorials/  There is a tutorial on shapes and a separate one dealing with colours.

Want to do a curved line? They are surprisingly tricky.  https://processing.org/tutorials/curves/ 

Done early?  Try animating your picture.  Can you make your snowman wave by moving your mouse? Or add a bird that flies across your screen.


New Addition: If you already know how to add images to a Processing file, figure out how to include a picture as a background.  For example, you could have a winter scene picture behind your snowman.  To do this you do NOT use the background( ) code, you just put the right sized image at 0,0.  Example: image(snowscene.jpg, 0, 0, 400, 600);
