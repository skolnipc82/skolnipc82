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
