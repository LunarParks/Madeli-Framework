# Madeli-Framework
High performant, lightweight, robust and simple **Material Design Framework** designed to be used on Cordova/PhoneGap SPAs (Single Page Applications).

This project aims to help new HTML5/JavaScript developers (such as students) when building SPAs.

# Get Started

To see `Madeli Framework` in action jump to our live demo.

In order to use the Framework you'll need to download two files and include them in your page, those are: `madeli.css` and `madeli.js`.

A basic app made with `Madeli Framework` has the following structure

```html
<!DOCTYPE html>

<html>

	<head>
		<title>Madeli App</title>
		<link rel="stylesheet" type="text/css" href="madeli.css">
	</head>

	<body>

		<!-- SPLASH SCREEN -->
		<section class="madeli-splashscreen">
			<img class="madeli-splashscreen-image" src="assets/images/splashscreen.png"></img>
		</section>

		<!-- APP SCREEN #1 -->
		<section class="madeli-appscreen"></section>

		<!-- APP SCREEN #2 -->
		<section class="madeli-appscreen"></section>

		<!-- APP SCREEN #3 -->
		<section class="madeli-appscreen"></section>

	</body>

	<script type="application/javascript" src="madeli.js"></script>

</html>
```

# Components

### Splash Screen

To use a Splash Screen on your application add this HTML code right after your `body` tag.

```html
<section class="madeli-splashscreen">
	<img class="madeli-splashscreen-image" src="assets/images/splashscreen.png"></img>
</section>
```

Then create an image called `splashscreen.png` and save it under `assets/images/` or use a custom location.

### App Screen

### Toolbar

### Navigation Drawer

### Cards

Cards can be generated by using the following HTML code. You can safely remove indivual parts of the card i.e remove the Card Title.

```html
<div class="madeli-card">
  <p class="madeli-card-title">Card Title</p>
  <p class="madeli-card-text">Some random text...</p>
  <div class="madeli-card-actionbar">
    <p class="madeli-card-action">BUTTON 1</p>
    <p class="madeli-card-action">BUTTON 2</p>
    <p class="madeli-card-action">BUTTON 3</p>
  </div>
</div>
```

### Floating Action Button (FAB)

### Dialog

### Transparent Mask

### Dark Mask
