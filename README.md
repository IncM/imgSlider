A simple jquery plugin for creating image comparison sliders. See live demo at http://kavyasukumar.com/apps/imgSlider/

##Getting started

Download the code from [here](http://github.com/kavyasukumar/imgSlider/tree/master/distr)

Unzip and include the files on your page
```html 
   <link rel="stylesheet" type="text/css" href="imgslider-2.0.1--min.css">

	<script type="text/javascript" src="imgslider-2.0.1-min.js"></script>
```
HTML decoration for your images goes like this
```html
<div class="slider">

 <div class="slider responsive">

  <div class="left image">

    <img src="before.jpg"/>

  </div>

  <div class="right image">

    <img src="after.jpg"/>

  </div>

</div>

</div>
```
Include the following near the end of the page.
```html
<script type="text/javascript">

  $('.slider').slider();

</script>
```
### Initialization options

The following are the initialization options and their default values
```json
initialPosition: .5

showInstruction: true

instructiontext: "Click and Drag"
```
You can override the values during initialization by passing in the options like this
```html
 <script type="text/javascript">

  $('.slider').slider({ instructionText:"New instructions here" });

</script>
```

###Dependencies
* Jquery
