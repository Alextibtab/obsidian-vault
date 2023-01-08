# Topic / Title: Mouse Interaction

2023-01-08
21:26


# Notes
`mouseX` and `mouseY` are two predefined variables that can be used to obtain the users exact mouse position. The coordinates are from the top left corner so if the user moves there mouse down the `mouseY` value would increase.

`mousePressed()` and `mouseReleased()` are functions that can be defined in the main sketch to handle whenever the user presses and releases the mouse button when this happens whatever code is written in these functions will be executed.

```javascript
void setup() { 
	// setup code
} 
void draw() {
	// draw loop 
} 
void mousePressed() { 
	// mouse-button has been pressed down 
} 
void mouseReleased() { 
	// mouse-button has been released 
}
```

If instead you want to query whether the mouse is being pressed inside the draw loop there is also the boolean variable `mouseIsPressed` which will equal `true` if the mouse is currently pressed.
# Keywords/Questions
`mouseX`
`mouseY`
`mouseIsPressed`
`m`

# Summary

Related: [[essentials course]]
Tags: #generativeProgramming #timrodenbroeker 