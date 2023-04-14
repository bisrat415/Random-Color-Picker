# Random-Color-Picker

This is a simple React application that generates a random RGB color and sets it as the background color of the page whenever the user clicks a button.

## How to Use

To use this application, simply open the index.html file in your web browser. The application should start running immediately.

When the page loads, you will see a heading displaying the current color. There is also a button labeled "Refresh". Clicking this button will generate a new random color and update the background color and heading text accordingly.


## Technical Details

The Random component is the main component of this application. It has a state containing the current color and a method to randomly generate a new color. The Button component is a child of Random, which triggers a new color generation when clicked.

When the component mounts or updates, the applyColor() function is called, which formats the color and sets it as the background color of the document.body. Additionally, the isLight() function is used to determine if the text should be white or black based on the current color.

The rendered HTML code includes a div with an id of app, which is where the React application is mounted. There is also a link to an external stylesheet and two script tags, one for the React library and another for the compiled React component.

## Screenshot

<img src="images/page.png" width="300" />

## Contributing

This is a simple example application meant for learning purposes, so contributions are not expected. However, if you find a bug or would like to suggest an improvement, please feel free to create an issue or a pull request on GitHub.

## Badge

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
