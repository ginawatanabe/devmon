# Devmon

You’re in charge of creating the starter layout for the newest edition of Devmon - Fire Flexbox. Players will be choosing their first Devmon for the game. Use your HTML, CSS, and Flexbox skills to craft the layout for this page.  

![Devball](https://github.com/ginawatanabe/devmon/blob/master/images/alldevballs.png)

## Objective

Use **Flexbox** properties to style **HTML Elements** and **JavaScript Logic** and **Events** to change inner HTML on click of an image, manipulate image size, change the source of an image, create a button, and play sounds when the button and image are clicked.

## Prerequisites

To complete this project, students should have the following:
* Basic understanding of HTML structures and attributes.
* Basic understanding of Flexbox.
* Basic understanding of JavaScript and DOM.

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:
* Set up your project file structure through the command line.
* Create an `HTML` structure with a `CSS` stylesheet to mimic the layout in the `images` folder.  
* Load 3 Devball images to your page in their respective boxes.

### Part II

To complete Part II, fulfill the following requirements:
* Create a file called `app.js` and change the text displayed in the `text container`, play the Devmon's battle cry, and enlarge the image when clicking on the image of a Devball.
  * Select the HTML element with the current text of "Placeholder" and give it an `id` of `text container`.
  * Select the Devball images.
  * Create an `onclick` Event Handler for each Devmon image.
    * Change the `inner HTML` of the `text container` to display a unique description of each Devmon on click.
    * Play the sound of the Devmon's cry on click.
    * Make the Devmon image larger than the rest on click.  

### Part III

To complete Part III, fulfill the following requirements:
* In the `app.js` create the logic to play a sound and change the enlarged image of the Devball to an actual Devmon when clicking on the button.
  * Create an `onclick` Event Handler for the button element.
    * Play the sound file `theme.wav` located in the `sound` folder when clicking the button.  
    * Change the source of the enlarged image to that of a Devmon when clicking the button.

### Stretch Goals

* Pretty up your page.
* Add a CSS animation upon hovering over a Devball image.
* Use a `case switch` statement in your JavaScript logic.

## Resources
* [Devmon Layout]()
* [Devmon Images]()
* [Devmon Sounds]()

* [InnerHTML Property](https://www.w3schools.com/jsref/prop_html_innerhtml.asp)
* [JavaScript Events](https://www.w3schools.com/js/js_htmldom_events.asp)
