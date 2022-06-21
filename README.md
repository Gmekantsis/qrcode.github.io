# Frontend mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)

## Overview

### Screenshot

![](https://cdn.glitch.global/6d9f6ebc-9b7c-463b-85b8-f353c7c6f6cf/QR%20screen.png?v=1655796378956)

### Links

- Solution URL: [Add solution URL here](https://glitch.com/edit/#!/gmekantsis-qr-code-component)
- Live Site URL: [Add live site URL here](https://gmekantsis-qr-code-component.glitch.me)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

```html
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="card">
      <img
        src="https://cdn.glitch.global/6d9f6ebc-9b7c-463b-85b8-f353c7c6f6cf/qr.png?v=1655379299801"
      />

      <p class="text">
        Improve your front-end <br />
        skills by building projects
      </p>
      <p class="bottomtext">
        Scan the QR code to visit Frontend <br />
        Mentor and take your coding skills to<br />
        the next level
      </p>
    </div>
  </body>
</html>

```

```css
body {
  background-color: #d5e1ef;
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card {
  width: 320px;
  height: 497px;
  background-color: white;
  border-radius: 20px;
}
img {
  width: 288px;
  height: 288px;
  margin-left: 16px;
  margin-right: 16px;
  margin-top: 16px;
  border-radius: 10px;
}

.text {
  width: 288px;
  height: 56px;
  text-align: center;
  font-family: "Outfit", sans-serif;
  font-weight: 700;
  font-size: 22px;
  margin-left: 16px;
  margin-right: 16px;
}

.bottomtext {
  width: 256px;
  height: 57px;
  text-align: center;
  font-family: "Outfit", sans-serif;
  font-weight: 400;
  font-size: 15px;
  margin-left: 32px;
  margin-right: 32px;
}


```

## Author

- Website - [gmekantsis-qr-code-component](https://gmekantsis-qr-code-component.glitch.me)
- Bootcam student - [@Giorgi Mekantsishvili](https://gmekantsis-qr-code-component.glitch.me)
