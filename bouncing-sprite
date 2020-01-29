let sprite = game.createSprite(2, 2)
input.onButtonPressed(Button.A, function () {
    sprite.turn(Direction.Right, 45)
})
input.onButtonPressed(Button.B, function () {
    sprite.set(LedSpriteProperty.X, Math.randomRange(0, 4))
    sprite.set(LedSpriteProperty.Y, Math.randomRange(0, 4))
})
basic.forever(function () {
    sprite.move(1)
    sprite.ifOnEdgeBounce()
})
