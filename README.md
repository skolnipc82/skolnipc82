0 až 10

let gg = 0
for (let index = 0; index < 10; index++) {
    basic.showNumber(gg)
    gg += 1
}
basic.forever(function () {
	
})

lichá čísla 0 až 10

let gg = 0
basic.forever(function () {
    gg = 9
    while (gg > 0) {
        basic.showNumber(gg)
        gg += -2
    }
})

screnař zobraz několik ikon po sobě a nakonec zhasni displej


for (let index = 0; index < 4; index++) {
    basic.showIcon(IconNames.Happy)
    basic.pause(1000)
    basic.showIcon(IconNames.Sad)
    basic.pause(1000)
    basic.showIcon(IconNames.Scissors)
    basic.pause(1000)
    basic.clearScreen()
}

rosvit nebo přepni F


led.toggle(0, 0)
led.toggle(0, 1)
led.toggle(0, 2)
led.toggle(0, 3)
led.toggle(1, 0)
led.toggle(2, 0)
led.toggle(1, 2)
led.toggle(2, 2)
led.toggle(0, 4)
basic.forever(function () {
    led.plot(0, 0)
    led.plot(0, 1)
    led.plot(0, 2)
    led.plot(0, 3)
    led.plot(1, 0)
    led.plot(2, 0)
    led.plot(1, 2)
    led.plot(2, 2)
    led.plot(0, 4)
})



při stisknutí a 1+ a při b -1

input.onButtonPressed(Button.A, function () {
    gg += 1
    basic.showNumber(gg)
})
input.onButtonPressed(Button.B, function () {
    gg += -1
    basic.showNumber(gg)
})
let gg = 0
gg = 0
basic.showNumber(gg)


kompas

input.calibrateCompass()
basic.forever(function () {
    basic.showNumber(input.compassHeading())
})

rubikova kostka

input.onGesture(Gesture.Shake, function () {
    basic.showNumber(randint(0, 6))
})
basic.forever(function () {
	
})


