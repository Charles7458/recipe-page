# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Author](#author)



## Overview

### Links

- Live Site URL: (https://charles7458.github.io/recipe-page-solution)


### Built with

- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to select specific elements using pseudo-elemnts in css. Also I learnt how to change the color and size of list markers.
To change the marker size, I reduced the font-size of li elements and put the wordings of the li in a span and gave them separate sizes.

css code I'm proud of:
```css

.prep-time li::marker {
    color: hsl(332, 51%, 32%);
    height: 2px;
}

.nutrients table:first-child {
    color: hsl(32,10%,34%);
}

.nutrients table td:last-child {
    font-weight: bold; 
    color: hsl(14,45%,36%);
}
.nutrients table td:not(.last) {
    border-bottom: 1px solid hsla(32, 10%, 34%, 0.2);
}
```

### Continued development

Now I'm a little confident in my basic html and css knowldege, so I'm going to learn frameworks like Bootstrap and tailwind.

## Author

- Frontend Mentor - [@Charles7458](https://www.frontendmentor.io/profile/Charles7458)

