# sunrise

Creating a sunrise animation using HTML, CSS, and JavaScript in one file is definitely possible. Below is a simple example of a sunrise animation where the sun rises from the horizon:
Save the code below in an HTML file (e.g., sunrise.html) and open it in your web browser to see the sunrise animation:


In this example, we use the HTML canvas element to draw a sunrise animation. The drawSky function creates a blue gradient to represent the sky, and the drawGround function creates a green rectangle to represent the ground. The drawSun function draws the sun at the bottom of the canvas.
The sunrise animation starts with the sun at the bottom and gradually moves it up to the center of the canvas using the animateSunrise function. The animation is achieved by repeatedly clearing the canvas, redrawing the sky, ground, and the sun at different positions using the requestAnimationFrame function.
Please note that this is a simple animation to demonstrate the concept. For more complex and realistic sunrise animations, you may consider using advanced graphics libraries like Three.js or WebGL.
