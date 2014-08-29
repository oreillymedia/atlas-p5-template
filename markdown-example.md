# Here's an example in Markdown

This chapter was written in [Markdown](http://daringfireball.net/projects/markdown/).  In your editor, type the following:

<pre data-executable="true" data-code-language="p5js" id="mycode">
function setup() {
  createCanvas(640, 480);
}

function draw() {
  if (mouseIsPressed) {
    fill(0);
  } else {
    fill(255);
  }
  ellipse(mouseX, mouseY, 80, 80);
}
</pre>

This program creates a window that is 640 pixels wide and 480 pixels high, and then starts drawing white circles at the position of the mouse. When a mouse button is pressed, the circle color changes to black. We’ll explain more about the elements of this program in detail later. For now, run the code, move the mouse, and click to experience it.