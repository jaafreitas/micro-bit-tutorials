# Micro LED

Este tutorial foi construído de acordo com este vídeo:
https://www.youtube.com/watch?v=XsM8hp7eysA

## Toogle an LED

Arraste este código e pisque o LED.

```blocks
basic.forever(function () {
    led.toggle(0, 0)
})
```

## Randomize x

Arraste este código para sortear um número aleatório entre ``0`` e ``4`` para ``x``.
Drag the code to pick a random ``x`` index between ``0`` and ``4``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), 0)
})
```

## Randomize y

Arraste este código para sortear um número aleatório entre ``0`` e ``4`` para ``y``.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```
