# Topic / Title: Setup and Draw

2023-01-07
03:39


# Notes
The foundation of any Processing or P5.js sketch is based on two functions: `setup()` and `draw()`. In short, `setup()` defines the project-details whereas `draw()` defines what happens over time

```javascript
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}
```
The above javascript code is the default code provided when creating a new sketch in P5.js

#### Setup
first inside the setup function the `createCanvas()` function takes two parameters which will represent the width and height of the sketch. 

#### Draw
Once the `setup()` function has been called by the computer then the `draw()` loop will run any code inside this function will repeatedly be executed until the program is stopped.

Currently, all the `draw()` function is doing is setting the background colour using the `background()` function which takes either a singular value which will then be used for the RGB components of the colour or you could pass in three parameters to customise each RGB value
```javascript
background(50, 100, 150);
```

# Keywords/Questions

# Summary

{related}
{tags}