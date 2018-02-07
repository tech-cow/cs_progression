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
#### Day X | Sass Refactoring

<!-- 🍍 🍎 🍏 🍐 🍑 🍒 🍓 🥝 🍅 🥥 -->

##### Sass Refactoring

`Sass` allows a `parent` selector to include `child` selector if prefix are the same, using the properties along with `BAM` naming convention, the code becomes **art**......

Example:

🍈 `before`

![sass-before](../docs/img/sass-before.png)

🍊 `after`

![sass-after](../docs/img/sass-after.png)

---
##### Sass 7-1 Pattern

🍌 `7-1 Refactoring` : To make a front-end project easier to scale, having a structured design is important. This project follows the Sass 7-1 pattern as listed below:

![sass-rules](../docs/img/sassrules.png)

Our main.scss now have a brand-new look:
```scss
@import "abstracts/functions";
@import "abstracts/mixins";
@import "abstracts/variables";

@import "base/animations";
@import "base/base";
@import "base/typography";
@import "base/utilities";

@import "components/button";

@import "layout/header";

@import "pages/home";

```

---

## License

🌱 MIT 🌱

---
> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) &nbsp;&middot;&nbsp;
> ![github](http://yuzhoujr.com/emoji/github.svg)  [@yuzhoujr](https://github.com/yuzhoujr) &nbsp;&middot;&nbsp;
> ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg)  [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
