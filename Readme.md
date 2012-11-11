# Tony Thomas&rsquo; R&eacute;sum&eacute;

My R&eacute;sum&eacute; formatted using [impress.js](https://github.com/bartaz/impress.js).

## Impress.js data Attribute Options

### data-x

Number of pixels for the offset along the X axis for the current slide's center. For example:

	<div class="step" data-x="500">Slide Text</div>

The above attribute will put the center of the slide 500px to the right of the center of the "canvas."

### data-y

Much like <code>data-x</code>, <code>data-y</code> is the offset along he Y axis for the current slide's center.

### data-z

Sets the slide position along the Z axis.

	<div class="step" data-z="3000">Slide Text</div>

The slide above will appear to be 3000 pixels away.

### data-scale

Sets the scale of the slide.

	<div class="step" data-scale="4">Slide Text</div>

The slide in the example above will be 4 times larger than the others.

### data-rotate

Sets the rotation in degress for the slide.

	<div class="step" data-rotate="90">Slide Text</div>

The slide above will be rotated to 90 degrees.

### data-rotate-x, data-rotate-y and data-rotate-z

These attributes control the rotation along the X, Y and Z axes. <code>data-rotate-z</code> is an alias for <code>data-rotate</code>.
