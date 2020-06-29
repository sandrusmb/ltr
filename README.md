## Install dependencies

This project is developed with React using npm to manage dependencies. To install them, execute

```
npm install
```

## Start the project

Once the dependencies are installed, you can start the project by executing

```
npm start
```

## Project in production

To run the code in production mode I have created the docs folder by running npm run docs. This way the website will be available in `/ docs / public /` so you simply have to open the file index.html in the browser or [https://sandrusmb.github.io/ltr/](https://sandrusmb.github.io/ltr/)

## Structure

```
src
 ├─ images
 |  └─ b-cr-img1.png
 |  └─ b-cr-img2.png
 |  └─ ...
 ├─ scss
 |  ├─ core
 |  |    └─ _mixins.scss
 |  |    └─ _reset.scss
 |  |    └─ _variables.scss
 |  ├─ layout
 |  |    └─ header.scss
 |  |    └─ page.scss
 |  |    └─ footer.scss
 |  └─ main.scss
 └─ html
 |  └─ partials
 |  |   └─ header.html
 |  |   └─ main.html
 |  |   └─ footer.html
 |  └─ index.html
```

## Decisions

I created a responsive website design to be used on mobile (horizontally), iPad and computer. I have used HTML5, CSS3, Sass, SCSS and Git to carry out the project and the first thing I did was the code from left to right direction.

To make the code easier, I have divided the elements of the web and created partials of HTML and SCSS, so I have separated the header, the central part of the web (that is a main section and an aside) and the footer.

I have also created a mixins file with the styles of those elements that are most repeated on the web, such as the buttons or the navigation bar, a reset file with the basics styles of the body and a variables file with the colors and fonts.

I added some animations to the buttons, the navigation bar and the gallery of icons to make more dynamic the user experience.

Thanks!
