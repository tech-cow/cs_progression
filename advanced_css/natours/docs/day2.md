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

🍈 `clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%)`: clips away corner by input exact coordinate of x and y planet.

```css
.header {
    /* 95% of the viewport height 也就是页面高度的95% */
    height: 95vh;
    /* 颜色转变gradient, 0.8是Transparency */
    background-image: linear-gradient(
        to right bottom,
        rgba(126, 213, 111 ,0.8),
        rgba(40, 180, 131 ,0.8)),
        url(../img/hero.jpg);
    /* Fit element in the box */
    background-size: cover;
    background-position: top;
    position: relative;
    /* 让页面切掉右下角， polygon定义四周的点 Clockwise */
    clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%)
}
```


Daily End Product:
![Day1](./progress/day1.png)


## License

🌱 MIT 🌱

---

> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) &nbsp;&middot;&nbsp;
> ![github](http://yuzhoujr.com/emoji/github.svg)  [@yuzhoujr](https://github.com/yuzhoujr) &nbsp;&middot;&nbsp;
> ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg)  [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
