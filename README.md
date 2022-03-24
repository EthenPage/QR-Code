# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 
Date: 24 March 2022

## Table of contents

- [Overview](#overview)
  - [Finished Product](#finished-product)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Date](#date)


## Overview

### Finished Product

- Desktop Version: [Screenshot](./finished/desktop-version.jpg)
- Mobile Version: [Screenshot](./finished/mobile-version.jpg)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/qr-code-component-challenge-Hy9q22YMq)
- Live on GitHub: [Live](https://ethenpage.github.io/QR-Code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

- Vertical alignment of an item.

To make a box vertically center alignment, the following code is useful. 

```html
<body>
  <div class="content">
    <main>
      <div class="container">
        .................
        .................
      </div>
    </main>
    <footer>
      ..................
    </footer>
  </div>
<body>

```
```css
body{
    position: relative;
    height: 100vh;
}

.content{
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 100%;
}
```
Another Solution: using flex. In this case only child involves, not parent.
Thanks to [Ciceron](https://www.frontendmentor.io/profile/MarcusTuliusCiceron)

```css
body{
    /* position: relative;
    min-height: 100vh; */
}

.content{
    /* position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 100%; */
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
```



## Author

- Website - [Mirza Monirul Alam](https://github.com/EthenPage/QR-Code)
- Frontend Mentor - [@EthenPage](https://www.frontendmentor.io/profile/EthenPage)

## Date

- 24 March 2022.