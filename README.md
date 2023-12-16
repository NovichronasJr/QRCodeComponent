# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### Links
- Live Site URL: [live site URL](https://novichronasjr.github.io/QRCodeComponent/)

## My process

i started with designing the 'card like' layout which can hold the barcode image and the heading and paragraph elements. The barcode should be above the bold sentence and the bold sentence should be above the pargraph as given in the challenge.
So i first clubbed them in to block level element div. Barcode image embedded in one div element and the paragaraphs and bold sentence embedded in another div element. I then applied css column flex property on main div holding the two div elements and applied gap between them. applied margin between bold text and paragraph text since they were in the same div and were close to each other giving a clustered look. Then by giving the suitable width and height to barcode image and suitable font and font weight to text, i completed the card design. Now i applied background colour to the body element and in this way completed the desktop layout.
Inorder to make it responsive i used css media with ma-width 375 px (the given phone size) and changed some of the properties like alignment of the card with the phone window. In this way i completed the challenge.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design using media


### What I learned

From this challenge i learned to use css flex and make designs in a simple way in almost no time. I also learned to use the css media property to make a responsive interface.


### Continued development

In future i am looking forward to make a dynamic website using Html, CSS and Javascript. Some begnner friendly backend projects as well.

### Useful resources

- [CSS3 Media Queiries](https://w3schools.com) - This site helped me with media tag syntax. I really liked their explanation and will use this site if i get stuck anywhere.


## Author

- Frontend Mentor - [@NovichronasJr](https://www.frontendmentor.io/profile/NovichronasJr)

