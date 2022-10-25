# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/screenshot.png)

### Links

- Solution URL: https://github.com/Faris-Thibani/Three-Column-Preview
- Live Site URL: https://faris-thibani.github.io/Three-Column-Preview/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to use utilites to style components instead of creating containers.

I also learnt to avoid the div and use semantic tags.

```html
<section class="card-container bgOrange flex">
        <img src="images/icon-sedans.svg" class="icon" alt="" aria-hidden="true">
        <h1 class="headings">Sedans</h1>
        <p class="paragraphs"> Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in
          the city
          or on your next road trip.</p>
        <button class="btn orange">Learn More</button>
    </section>
```
```css
.orange{
    color:var(--brightOrange)
}
.cyan{
    color:var(--darkCyan)
}
.darkCyan{
    color: var(--veryDarkCyan)
}
.bgOrange{
    background-color: var(--brightOrange);
    border-radius: 1em 1em 0 0;
}
.bgCyan{
    background-color: var(--darkCyan);
}
.bgVeryCyan{
    background-color: var(--veryDarkCyan);
    border-radius: 0 0 1em 1em;
}
```

### Continued development

I would like to continue developing HTML Profeciency and gain knowledge in accessisability and testing. 

### Useful resources

- [Example resource 1]https://testingaccessibility.com/ - This is an amazing course for anyone interested in learning HTML accessibility & testing.

## Author

- Frontend Mentor - [@Faris-Thibani](https://www.frontendmentor.io/profile/Faris-Thibani)



## Acknowledgments

Thanks for the Frontend mentor community for providing this project and a special thanks to Alex Marshal & James for providing useful insights and tips on improvig the code and fixing some CSS bugs. 

If you would like to learn more, please visit the live website and also you can find other solutions to challenges posted here on github.

As always see you next time!
