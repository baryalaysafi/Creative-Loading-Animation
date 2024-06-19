# Creative-Loading-Animation
<html lang="en">: Defines the root of the HTML document and sets the language to English.
<head>: Contains meta-information about the HTML document.
<meta charset="UTF-8" />: Sets the character encoding to UTF-8.
<meta http-equiv="X-UA-Compatible" content="IE=edge" />: Ensures compatibility with Internet Explorer, using the latest rendering engine.
<meta name="viewport" content="width=device-width, initial-scale=1.0" />: Ensures proper rendering and scaling on different devices by setting the viewport width to the device width.
<title>Loading Animation |Baryalay Safi</title>: Sets the title of the webpage, which appears in the browser tab.
<link rel="stylesheet" href="style.css" />: Links to an external CSS stylesheet named style.css for styling the page.
Body Content:
<body>: Contains the content that is displayed in the browser.
<section class="wrapper">: A section element with a class of wrapper, likely used for styling purposes.
<div class="loader">: A div element with a class of loader, which acts as a container for the loading animation.
<div class="loading one"></div>: A div element with classes loading and one, representing the first part of the loading animation.
<div class="loading two"></div>: A div element with classes loading and two, representing the second part of the loading animation.
<div class="loading three"></div>: A div element with classes loading and three, representing the third part of the loading animation.
<div class="loading four"></div>: A div element with classes loading and four, representing the fourth part of the loading animation.
Purpose:
This HTML document is designed to display a loading animation, which is visually represented by four animated div elements inside a loader container. The actual animation and styling are defined in an external CSS file (style.css).

This description provides an overview of the structure and purpose of your HTML code, explaining each part and its role in creating the loading animation.

=========================================================================================================
This CSS file styles the webpage elements and defines the animations for the loading animation. Here's a detailed breakdown of each section:

Global Styles:
* { margin: 0; padding: 0; box-sizing: border-box; }:
Resets the margin and padding for all elements to zero.
Sets box-sizing to border-box for all elements, which includes the padding and border in the element's total width and height.
Body Styles:
body { background: linear-gradient(0deg, rgba(34,62,195,1) 0%, rgba(253,45,245,1) 100%); }:
Applies a vertical linear gradient background to the body, starting from a blue color (rgba(34,62,195,1)) at the top to a pink color (rgba(253,45,245,1)) at the bottom.
Wrapper Styles:
.wrapper { display: flex; justify-content: center; align-items: center; min-height: 100vh; }:
Uses flexbox to center its contents both horizontally and vertically.
Ensures the wrapper takes up at least the full height of the viewport (100vh).
Loader Container Styles:
.wrapper .loader { display: flex; justify-content: space-evenly; padding: 0 20px; }:
Uses flexbox to arrange the loading elements evenly spaced.
Adds horizontal padding of 20px inside the loader container.
Loading Elements Styles:
.loader .loading { background: #fff; width: 30px; height: 30px; border-radius: 50px; margin: 0 10px; animation: load 0.8s ease infinite; }:
Sets a white background for each loading element.
Defines the size of each loading element as 30x30 pixels.
Makes each loading element circular with border-radius: 50px.
Adds a horizontal margin of 10px between the loading elements.
Applies an animation named load with a duration of 0.8 seconds, easing, and infinite repetition.
Individual Loading Element Delays:
.loader .loading.one { animation-delay: 0.3s; }:
Delays the start of the animation for the first loading element by 0.3 seconds.
.loader .loading.two { animation-delay: 0.4s; }:
Delays the start of the animation for the second loading element by 0.4 seconds.
.loader .loading.three { animation-delay: 0.5s; }:
Delays the start of the animation for the third loading element by 0.5 seconds.
Keyframes Animation:
@keyframes load { 0% { width: 30px; height: 30px; } 50% { width: 20px; height: 20px; } }:
Defines the load animation that changes the size of the loading elements.
At the start (0%), the elements have a size of 30x30 pixels.
At the midpoint (50%), the elements shrink to 20x20 pixels.
Summary:
This CSS file is designed to style a webpage with a visually appealing loading animation. It centers the loader in the viewport, styles the loading elements, and animates them to create a dynamic, eye-catching effect. The animation delays for each element create a staggered effect, enhancing the overall visual experience.
link: https://baryalaysafi.github.io/Creative-Loading-Animation/
