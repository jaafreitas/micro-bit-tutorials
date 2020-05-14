# Micro LED

This tutorial was built following this video:
https://www.youtube.com/watch?v=XsM8hp7eysA

## Toogle an LED

Drag the code to toggle and LED.

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

## Randomize x

Drag the code to pick a random ``x`` index between ``0`` and ``4``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), 0)
})
```

## Randomize y

Drag the code to pick a random ``y`` index between ``0`` and ``4``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```
