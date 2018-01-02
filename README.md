# zenyatta
A lightweight Vue UI libray for mobile only

![](https://blzgdapipro-a.akamaihd.net/hero/zenyatta/hero-select-portrait.png)

The aim of this libray is to provide some useful functions on mobile platform but still reserves the extensibility as much as possible.

zenyatta provides some basic yet powerful components, you can simply use them or combine them with each other or with other components.

zenyatta is a "styleless" UI libray, it gives you maximum authority to make you components' style on you own.

# Get Started

## Install
```shell
npm install zenyatta
```

## In your project (module support needed)

```javascript
import "zenyatta"
```
or

```javascript
require("zenyatta")
```
## legacy project use `<script>`

```html
<!--vue needed-->
<script src="zenyatta/dist/zenyatta.min.js"></script>
```


# Useage

## scroller

```html
<zen-scroller :direction="'vertical'" :height="100px">
</zen-scroller>
```

```html
<zen-scroller>
</zen-scroller>
```

## swiper & slider

### pagination

## aside

## radio

## checkbox


# Demo

## aside + swiper + scroller + radio

## scroller & swiper works with [vue-lazyload-img](https://github.com/JALBAA/vue-lazyload-img)
