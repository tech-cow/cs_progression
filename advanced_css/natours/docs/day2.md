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

#### Day 2

🍇 🍈 🍉 🍊 🍋 🍌 🍍 🍎 🍏 🍐 🍑 🍒 🍓 🥝 🍅

🍉 `specificity` in action:

```css
#nav div.pull-right a.button {
    background-color: orangered;
}

#nav a.button:hover {
    background-color: yellow;
}
```

Ideally, When hovering around this button, background-color should turn into yellow. However since its specificity is lower than before, the color won't change, to fix, we will need a selector with even higher specificity:

```css
#nav div.pull-right a.button {
    background-color: orangered;
}

#nav div.pull-right a.button:hover {
    background-color: yellow;
}
```
---

🍈 `background-color: purple !important;` : !important property gives priority to cascade specificity. Use carefully due to its conflicting nature against scalability.


```html
  <nav id="nav">
      <div class="pull-right">
          <a class="button button-danger" href="link.html"> Don't click me! </a>
      </div>
  </nav>
```

```css
body {
    padding: 50px;
}

.button {
    font-size: 20px;
    color: white;
    background-color: blue;
}

a {
    background-color: purple;
}

/* Highest specificity */
#nav div.pull-right a.button{
    background-color: orangered;
}

/* When hover, should turn the screen yellow */
#nav a.button:hover {
    background-color: yellow;
}

```


## Daily End Product:
![Day1](../progress/day1.png)


## License

🌱 MIT 🌱

---

> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) &nbsp;&middot;&nbsp;
> ![github](http://yuzhoujr.com/emoji/github.svg)  [@yuzhoujr](https://github.com/yuzhoujr) &nbsp;&middot;&nbsp;
> ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg)  [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
