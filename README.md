# Lissajous Curve

Just a little HTML5 canvas representation of the Lissajous curve.

Inspired by Matt Parker's [Youtube Video](https://www.youtube.com/watch?v=4CbPksEl51Q)

You can edit the colours and speeds of the circles:

```js
var circles = [
    { speed: 2, r: 255, g: 0, b: 0 },
    { speed: 1.2, r: 255, g: 200, b: 200 },
    { speed: 1.6, r: 0, g: 0, b: 255 },
    { speed: 1.3, r: 0, g: 255, b: 0 },
    { speed: 1, r: 255, g: 255, b: 0 }
]
```

The speeds are just factors, speed: 2 will be twice the rotational speed as speed: 1. Colours are averaged together at the cross-over points.
