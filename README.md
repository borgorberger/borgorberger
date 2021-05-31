nput.onButtonPressed(Button.A, function () {
    basic.showString("Hello!")
    images.createImage(`
        . . . . .
        . # . # .
        . . . . .
        . # . # .
        . # # # .
        `).scrollImage(1, 200)
    basic.showString("keep in mind that you can change the future:)")
})
input.onButtonPressed(Button.B, function () {
    basic.showString("how are you today?")
    images.createImage(`
        . # . # .
        . . # . .
        # . . . #
        . # # # .
        . . . . .
        `).scrollImage(1, 200)
})
