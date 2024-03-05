# Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## The challenge

Your challenge is to build out this card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout depending on their device's screen size

Want some support on the challenge? [Join our community](https://www.frontendmentor.io/community) and ask questions in the **#help** channel.

# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

(![Ma solution Desktop](<images/Stats previewD.PNG>))
(![Ma solution mobile](<images/Stats previewM.PNG>))

### Links

- Solution URL: [Add solution URL here](https://github.com/ClementServant/Stats-preview-challenge)
- Live Site URL: [Add live site URL here](https://clementservant.github.io/Stats-preview-challenge/)

## My process

### Built with

- Semantic HTML5 
- CSS custom properties
- Flexbox


### What I learned

Sur ce challenge, j'ai pu travailler sur l'utilisation de l'unité rem à la place de px. Que je n'avais pas utilisé auparavant, même dans ma formation actuelle développeur intégrateur web, je ne l'utilise pas.

```css
.text  {
    font-family: "Lexend Deca", sans-serif;
    font-size: 1.3rem;
    color: var(--main-paragraph);
    margin: 0;
    margin-top: 2.5rem;
    padding-right: 2rem;
}
```
J'ai aussi pu travailler sur l'utilisation et la  compréhension de vw et vh. J'utilisais principalement tout en " %", mais ce projet a pu me permettre de travailler et comprendre comment fonctionne l'utilisation de vh et vw.
```css
body{
    width: 100vw;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--main-background);
}
.card {
    width: 80vw;
    background: var(--card-background);
    border-radius: 10px;
    display: flex;
}
```

J'ai pu aussi travailler sur les reset CSS avec l'ajout d'une "font-sise" pour l'ensemble de la page et sur les variables dans le " : rot" mais aussi comprendre comment fonctionne le README.md comment écrire à l'intérieur, l'utilisation...
````css
:root {
    /** Primary color **/
    --main-background: hsl(233, 47%, 7%);
    --card-background: hsl(244, 38%, 16%);
    --accent: hsl(277, 64%, 61%);
    /** Neutral Color **/
    --main-heading-stats: hsl(0, 0%, 100%);
    --main-paragraph: hsla(0, 0%, 100%, 0.75);
    --stat-headings: hsla(0, 0%, 100%, 0.6);
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-size: 15px;
}
````
### Continued development

Travailler sur des challenges Frontend Mentor me permet de pouvoir travailler des choses que je ne me permets pas en formation par manque de temps étant en formation chez openclassrooms je ne peux pas me permettre de perdre du temps à travailler certaines choses alors que je peux les apprendre à côté de ma formation, sans perdre trop de temps et en réalisant des "projets", "challenges" en parallèle. Je pense que travailler en parallèle sur Frontend Mentor  peut me servir à mieux comprendre et travailler sur certaines choses dont j'ai du mal ou que je souhaite améliorer.

## Author

- Frontend Mentor - [@ClementServant](https://www.frontendmentor.io/profile/ClementServant)


