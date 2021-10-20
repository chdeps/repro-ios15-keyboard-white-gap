# Reproduction of ios 15 issue opening keyboard

This project is a small React applications reproducing an ios 15 bug. When opening the keyboard and closing the keyboard on the input, you end up with a white gap in between the address bar and the content of the page.

Changing the font size of the input from `16px` to any other value ie. `14px` triggers a different behavior when toggling the keyboard.

It was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
