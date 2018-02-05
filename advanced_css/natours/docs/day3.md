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

#### Day 3


##### Code Refactoring: rem
🍈 `px` needs to be changed constantly for its fixed size properties, this can be tedious later to change for multiplatform displays. So we can use the properties of `rem` to make our life easier.

🍉 recap: `rem` are always measured relative to the document’s **root** `font-size`;

The refactoring process was to set the `html` selector with a `font-size` of `10px`, and change the rest of `px` into `rem`.

```html
html {
    /* rem base value */
    font-size: 10px;
}
```

However, to set a fixed size `font-size` remove the possibilities of end-users experience if they want to change font-size in chrome dev-tool. Instead, a better practice is to give a `percentages` size relative to the browser's default `font-size`: 16px. In this scenario, 10px/16px = `62.5%` :

```html
html {
    /* rem base value */
    font-size: 62.5%;
}
```
---

##### BEM

`BEM` or `Block, Element, Modifier methodology` is a popular naming convention for classes in HTML and CSS, for example:

```css
/* Block component */
.btn {}

/* Element that depends upon the block */
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {}
.btn--big {}

```



##### Why BEM

🍉 If we want to make a new style of a component, we can easily see which modifiers and children already exist. We might even realize we don't need to write any CSS in the first place because there is a pre-existing modifier that does what we need.

🍊 If we are reading the markup instead of CSS, we should be able to quickly get an idea of which element depends on another (in the previous example we can see that .btn__price depends on .btn, even if we don't know what that does just yet.)

🍋 Designers and developers can consistently name components for easier communication between team members. In other words, BEM gives everyone on a project a declarative syntax that they can share so that they're on the same page.

## License

🌱 MIT 🌱

---

> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) &nbsp;&middot;&nbsp;
> ![github](http://yuzhoujr.com/emoji/github.svg)  [@yuzhoujr](https://github.com/yuzhoujr) &nbsp;&middot;&nbsp;
> ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg)  [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
