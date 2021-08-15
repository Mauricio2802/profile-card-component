# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

Mobile:

![mobile](https://user-images.githubusercontent.com/70554280/129464121-e1f3e345-4863-4f83-8dcb-8b5d5ee5816e.png)

Desktop:

![desktop](https://user-images.githubusercontent.com/70554280/129464125-587fe3b1-74b8-4c43-8940-8a80850e92cc.png)


### Links

- Solution URL: [Github repository](https://github.com/Mauricio2802/profile-card-component)
- Live Site URL: [Vercel Website](https://profile-card-component-nu-lemon.vercel.app/)

## My process

I alway start with this ⬇
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html {
  font-size: 62.5%;
  font-family: var(--primary-font-size);
}
:root {
  /* Primary */
  --dark-cyan: hsl(185, 75%, 39%);
  --very-dark-desaturated-blue: hsl(229, 23%, 23%);
  --dark-grayish-blue: hsl(227, 10%, 46%);
  /* Neutral */
  --dark-gray: hsl(0, 0%, 59%);
  /* Font-size */
  --primary-font-size: "Kumbh Sans", sans-serif;
}

```
Now, the process:

1. First I take out the default margin and padding and put box-sizing in the border-box because in this way you have complete control of your creation
2. Then, I put the default font size in 10px with font-size: 62.5%, and I put the principal font-family to my creation
3. Later, I create my color and font-size palette with: root {}
4. I recreate the layout without styles. It's easier when you have a guide design, and these Challenges help you with that: D
5. I put all the position styles (with flexbox and other stuff) because in this case is easier in this way.
6. I put the colors and font-sizes to all the layout.
7. I do the last touches and go with the background's (I think that I didn't put the background with the best way)
8. And finally, the media queries.
9. The project was finished and took me around 1.5 hours

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In the attribution section, I center this using calc(), that's a new one to my tools.
```css
.attribution {
  text-align: center;
  position: absolute;
  bottom: 10px;
  left: calc(50% - 182px);
  font-size: 1.4rem;
} 
}
```

I learned how to put many backgrounds in one site:
Is just putting a comma and work in that way.
```css
  background-image: url(../images/bg-pattern-top.svg),
    url(../images/bg-pattern-bottom.svg);
  background-position: -500px -450px, 150px 320px;
  background-repeat: no-repeat, no-repeat;
  background-size: cover, cover;
```

### Continued development

The project finished here, but I will go ahead with more challenges in Frontend Mentor.


### Useful resources

- [W3Schools](https://www.w3schools.com/) - This website was helpful to recap some specific things like "How to put many background in one site" :D

## Author

- Website - I don't have a website yet.
- Frontend Mentor - [@Mauricio2802](https://www.frontendmentor.io/profile/Mauricio2802)
- Twitter - [@maurice_cl42](https://www.twitter.com/maurice_cl42)
