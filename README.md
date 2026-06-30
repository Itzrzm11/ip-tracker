# IP Address Tracker

## Table of content:
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [How to setup the project](#how-to-setup-the-project)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## My process

### Built with

- HTML5
- CSS3
- JavaScript
- Leaflet.js (for the map)
- IP Geolocation API (for fetching IP address details)

### What I learned

This project is great at understanding how to execute basic CSS features like flexbox, responsive layout using media queries for both desktop and mobile and all sizes in between as shown below-

```css
@media (max-width: 920px) {
    .info-field {
        font-size: .9rem;
    }
}

@media (max-width: 770px) {
    #ip-input {
        width: min(380px, 70%);
    }

    .info {
        width: 85vw;
    }
}

@media (max-width: 600px) {
    .top {
        height: 35vh;
        padding: .7rem;
    }

    .title {
        font-size: 1.5rem;
    }

    .info {
        width: 75vw;
        flex-direction: column;
        text-align: center;
        gap: 1.1rem;
        top: 12%;
    }

    .box {
        width: 100%;
        border: none;
    }
}
```




