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

## Overview

### Screenshot

![](./images/qrcode.gif)

### Links

- Live Site URL: [https://qr-code-component-project-three.vercel.app/](https://qr-code-component-project-three.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- JavaScript Plugin - For Styles

### What I learned

I learned that using library plugins can help make a project faster and fix problems.</br>
In order to avoid overlapping with the background of my project, I had to change its background. However, I was unable to do this through the plugin code. The opacity property helped me and the result was the same as you see.

```html
    <script src="https://cdn.jsdelivr.net/npm/bubbly-bg@1.0.0/dist/bubbly-bg.js"></script>
    <script>bubbly();</script>
```
```css
#QR-bg{
    width: 100%;
    height: 100vh;
    opacity: 0.5;
}
```

### Continued development

I'd like to devote more time to resolving issues and mastering the fundamentals of JavaScript and the React framework.

### useful resources

- [Bubbles creation by HTML5 and CSS3](https://www.aparat.com/v/MQ3eF)
- [Some JavaScript plugins](https://roocket.ir/articles/javascript-plugins)
- [bubbly-bg/Generator](https://tipsy.github.io/bubbly-bg/generator)

## Author

- Frontend Mentor - [@zhrehsani](https://www.frontendmentor.io/profile/zhrehsani)
- Linkedin - [chegodev](https://www.linkedin.com/in/chegodev/)
