# gridder
Probably the best grid system with features like multi-column, no-responsive, no-spacing, offsets and many more.


We have built our own grid system to make the work even more easier, Now it's possible to make the responsive website even more easier. What's special about this grid system is you don't even need to write even a single media query. And that's what we always wanted. When you are hurry to complete the website on time this is the good to go grid system.

## Basic Markup
```html
<html lang="en">
   <head>
	  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
	  <title> Gridder </title>
	  <link rel="stylesheet" href="http://aoonidsgn.com/css/gridder.css" />
   </head>
   <body>
      <div class="section clearfix">
        <div class="row">
          <div class="grid2 first">.grid2 .first</div>
          <div class="grid2 last">.grid2 .last</div>
        </div>
      </div>
   </body>
</html>
```

You can see an example of the Gridder [here on Our Website](http://aoonidsgn.com/blog/the-best-grid-system/example-gridder.html)

We also wrote a small blog post on this grid system. which will help you to understand in depth. [click here to read the blog post](http://aoonidsgn.com/blog/the-best-grid-system/)

More examples can be found in the [example
section](#examples).

## Examples
### Nested Grid
```html
<div class="row clearfix">
	<div class="grid2 first">
		<div class="row">
			<div class="grid3 first">.grid3</div>
			<div class="grid3">.grid3</div>
			<div class="grid3 last">.grid3</div>
		</div>
		<div class="row">
			<div class="grid1">.grid1</div>
		</div>
		<div class="row">
			<div class="grid4">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</div>
			<div class="grid4">.grid4</div>
			<div class="grid4">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</div>
			<div class="grid4">.grid4</div>
		</div>
		<div class="row">
			<div class="grid2">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</div>
			<div class="grid2">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</div>
		</div>
	</div>
	<div class="grid2 last bgpad0">
		column 2
	</div>
</div>
```


### No-Responsive  

Use (`.noresponsive`) class to avoid responsive media querries.

```html
<div class="row noresponsive">
    <div class="grid6">.grid6</div>
    <div class="grid6">.grid6</div>
    <div class="grid6">.grid6</div>
    <div class="grid6">.grid6</div>
    <div class="grid6">.grid6</div>
    <div class="grid6">.grid6</div>
</div>
```

### No-Spacing

Use (`.nospacing`) class to avoid spaces between the columns.

```html
<div class="row nospacing">
	<div class="grid5">.grid5</div>
	<div class="grid5">.grid5</div>
	<div class="grid5">.grid5</div>
	<div class="grid5">.grid5</div>
	<div class="grid5">.grid5</div>
</div>
```

### No-Responsive & No-Spacing

Use the combination of both (`.noresponsive`) and (`.nospacing`) class to avoid spacing and responsive both at once.

```html
<div class="row noresponsive nospacing">
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
	<div class="grid7">.grid7</div>
</div>
```

### Offsets

Offset are the most commonly available so we included them in our gridder, add (`.offset-grid9`) after `.offset-` use the grid column class to leave that much space before that column.

```html
<div class="row">
	<div class="grid8 offset-grid9">.offset-grid9</div>
	<div class="grid8 offset-grid12">.offset-grid12</div>
	<div class="grid8 offset-grid7">.offset-grid7</div>
	<div class="grid8 offset-grid7">.offset-grid7</div>
</div>
```

### Multi-Column
We have some special classes to divide the row into different columns, we divided the complete width into 12 parts, 
use `.grid2-12` to occupy 2 columns out of 12. below given some of the example which will help you to understand easily.

```html
<div class="row">
	<div class="grid2-12">.grid2-12</div>
	<div class="grid4-12">.grid4-12</div>
	<div class="grid1-12">.grid1-12</div>
	<div class="grid5-12">.grid5-12</div>
</div>

<div class="row">
	<div class="grid3-12">.grid3-12</div>
	<div class="grid2-12">.grid2-12</div>
	<div class="grid5-12">.grid5-12</div>
	<div class="grid2-12">.grid2-12</div>
</div>
```

### Percentage-grid

The word itself says that these are the percentage grids. use (`.grid90p`) to make 90% width column. we have percentages ranging from 10% to 90%.

```html
<div class="row">
	<div class="grid90p">.grid90p</div>
	<div class="grid80p">.grid80p</div>
	<div class="grid70p">.grid70p</div>
</div>
```
