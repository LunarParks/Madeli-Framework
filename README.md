# Madeli-Framework
High performant, lightweight, robust and simple **Material Design Framework** designed to be used on Cordova/PhoneGap SPAs (Single Page Applications).

This project aims to help new HTML5/JavaScript developers (such as students) when building SPAs.

# Get Started

To see `Madeli Framework` in action jump to our [Live Demo] (app.html).

In order to use the Framework you'll need to download `madeli.css` and `madeli.js`. Include them on your `head` tag and `script` tag respectively. Once you've done that, you can start inserting `Madeli` components to build your app.

**Important:** If you decide to add a new .css and/or .js file, please add them after the ones provided by the Framework to avoid overriding them.

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

### Text Inputs

### Floating Action Button (FAB)

### Dialog

### Transparent Mask

### Dark Mask
