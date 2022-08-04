# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

 <h2>Mobile Version</h2>

![](https://i.postimg.cc/rpDL9Sj1/mobile.png)
![](https://i.postimg.cc/qMqQqjvx/mobile-1.png)
![](https://i.postimg.cc/SKhW6rk5/mobile-2.png)
![](https://i.postimg.cc/3NVGdjtt/mobile-3.png)

<h2>Desktop Version</h2>

![](https://i.postimg.cc/YqSLQCZ1/mobile-4.png)
![](https://i.postimg.cc/nhDz1jkQ/mobile-5.png)
![](https://i.postimg.cc/cJMxJ6fq/mobile-9.png)
![](https://i.postimg.cc/hGV1NGSX/mobile-8.png)

### Links

- Live Site URL: [live site URL](https://huddlelandingpage-1b4a4.web.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

During the process, I have learned about the variable manage. I mean, the sections between header and footer have waves, while I was coding, according the section I changed the value of the variable.  

Example:

```html
--hero__main--
<div class="wave"></div>
```

```css
.wave {
  ...
  backgroud: url(--wave1); 
}
```
```html
--section__white--
<div class="wave"></div>
```

```css
.section--white{
  --wave1:url(/assets/img/bg-section-top-mobile-2.svg);
  /*The variables has changed the value for another svg.*/
}
```

## Autor
- Frontend Mentor - [@ricardozu](https://www.frontendmentor.io/profile/ricardozu)
- Twitter - [@ricardozu4](https://www.twitter.com/ricardozu4)

