<h3 style="text-align:center;font-weight: 300;" align="center">
  <img src="../img/logo-green-2x.png" width="150px">
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat-square">
  <img src="https://img.shields.io/badge/downloads-0k-yellow.svg?style=flat-square">
  <img src="https://img.shields.io/badge/build-passing-yellow.svg?style=flat-square">
</p>


> Natours: Let's make some CSS, I mean... Legit looking CSS 🔥



## Progress

#### Day 4 | Sass Crash Course


##### What is Sass?
🍈 `Sass` is a CSS preprocessor, an extension of CSS that adds power and elegance to the basic language.

`Sass Source Code` -> `Sass compiler` -> `Compiled CSS code`

---

##### Variables

🍇 Variables can store colors, font stacks, or any CSS value. Sass uses the `$` symbol to declare a variable. Here's an example:


```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```
🍈 When the Sass is processed, it outputs normal CSS with our variable values placed in the CSS. This can be handy working with brand colors and keeping them consistent throughout the site.

```css
/* css output of the above scss code */
body {
  font: 100% Helvetica, sans-serif;
  color: #333;
}
```

---
##### Nesting

🍊 Sass allows nesting feature that is similar to the visual hierarchy of HTML. Be aware that overly nested rules result in over-qualified CSS and is considered a bad practice.


```scss
nav {
  ul {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  li { display: inline-block; }

  a {
    display: block;
    padding: 6px 12px;
    text-decoration: none;
  }
}
```

🍋 `ul`, `li`, and a selectors are nested inside the `nav` selector. This is a great way to organize your CSS and make it more readable. CSS output:

```css
nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

nav li {
  display: inline-block;
}

nav a {
  display: block;
  padding: 6px 12px;
  text-decoration: none;
}
```
---

 🍌 🍍 🍎 🍏 🍐 🍑 🍒 🍓 🥝 🍅 🥥





## License

🌱 MIT 🌱

---





> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) &nbsp;&middot;&nbsp;
> ![github](http://yuzhoujr.com/emoji/github.svg)  [@yuzhoujr](https://github.com/yuzhoujr) &nbsp;&middot;&nbsp;
> ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg)  [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
