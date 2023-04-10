# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

Desktop design screenshot
![Desktop design screenshot](./screenshots/desktop.design-screenshot.png)

Mobile design screenshot
![Mobile design screenshot](./screenshots/mobile.design-screenshot.png)


### Links

- Live Site URL: [GitHub Page](https://zmitchc.github.io/qr-code-component-main/)

## My process

First of all, in the [HTML file](./index.html) I set up a div with class named "container" to contain the qr code image and the two texts, which I separate using two paragraph since they have different style.

For the CSS, I alternate between inline code and the external [CSS page](./style.css).
For the body, after the color, I put `width: 100%`, so the page can fit no matter how large the screen size of the user is.
I set up the dimension of the container by myself trying to stay as similar as possible to the original design, and for the qrcode image as well. To leave some space between the qrcode and the container I put `padding: 10px`. Afer that, to get rounded corners I use `border-radius: 10px`.
After I finished, I set up the two paragraph style with font family, size, color and padding, centering them in the container.

That's all! :)


### Built with

- HTML5
- CSS

### What I learned

With this excersise, I learned how to perfectly center a div horizontally and vertically. I know there are others methods, maybe more accurate and I want to learn them!

About the position in CSS, I understood more how `relative` and `absolute` work!

### Continued development

I will definitely continue to work on the position of elements in the page.

### Useful resources

- [Center a DIV](https://stackoverflow.com/questions/356809/best-way-to-center-a-div-on-a-page-vertically-and-horizontally) - This helped me to understand how center a div horizontally and vertically

## Author

- GitHub - [zMitchC](https://github.com/zMitchC)
- Frontend Mentor - [@zMitchC](https://www.frontendmentor.io/profile/zMitchC)
