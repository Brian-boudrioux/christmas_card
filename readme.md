## Let's go creating your first Christmas card

## Create interactivity
- 1/ First, we will focus on how to change the text :
    - Get the p tag with the id #card-text and store the element on a variable in your script *js*
    - Get the textarea tag wirth the id #user-text and store the element on a second variable in your script *js*
    - on the textarea (*html*), add on `oninput` attribute that call a `updateText()` function
    - on the js, create a function `updateText()`
        Inside, just match the value of the p element to the textarea value

- 2/ Second, we will change the color of the text
  - Add an onClick attribute, that call a function `changeColor(#color#)` with the color as arguments on each `div`
  - On the `JS`, create a function `changeColor` that receive a *color* as argument.
  - On this function, apply the `style.color` to the p element, with the value of the received argument

- 3/ For the background image, we will apply an event listener..
  - Get the image with the background with its `id` and store it on a variable
  - Get all the 3 images with the id of an parent div (Add the div and the id if needed) with a query selector all
  - Then, use the `.forEach()` method on the array of element to add an eventListener to each of them.
  - This eventlistener (On the click), will change the *src* attribute of the backeground element with the src of the element you clicked on

