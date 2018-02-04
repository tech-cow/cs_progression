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

#### Day 1

🍉 `Viewport Height | vh`:  which will take percentages of vertical length.

🍇 `background-image: linear-gradient`: blend pictures and background color, last args in rgba indicates transparency

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

🍑 `transform: translate(-50%, -50%);` :this 50% are relative to its own block, not its parent's block

```css
.text-box {
    position: absolute;
    /* relative to the parent position */
    top: 40%;
    left: 50%;
    /* 这里translate会把整体往parent的50%起始点，往左边移动50%自身box的长度
    已达到到达中间的位置 */
    transform: translate(-50%, -50%);
    text-align: center;
}
```

🍍 `@keyframes moveInLeft` : starting position has to be negative if the end result is shifting from left. In order for ``@keyfrmes` to work, needs to add this animation in its relative box: `.heading-primary-main`


```css
.heading-primary-main {
    /* 因为span element本身定义的是inline，这里我们需要字体为上下，所以要用block */
    display: block;
    margin-bottom: 10px;
    font-size: 60px;
    font-weight: 400;
    letter-spacing: 35px;
    /* Animation */
    animation-name: moveInLeft;
    animation-duration: 1s;
    animation-timing-function: ease-out;
}

@keyframes moveInLeft {
    0% {
        opacity: 0;
        transform: translateX(-100px);
    }

    80%{
      transform: translateX(10px);
    }

    100%{
        opacity: 1;
        transform: translate(0);
    }
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
