# title
## Step 1

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)```

## **Step 2** - Drag a second **showLeds**  into the first **showLeds**
Click on the  ``||basic.basic||`` folder  to select the ``||basic.showLeds||``. 
Then, drag a ``||basic.showLeds||`` place it into ``||basic.showLeds||``
Continue your animation
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)```

## **Step 3** - Drag a third **showLeds** into the second **showLeds**
 Drag  ``||basic.showLeds||`` place it into ``||basic.showLeds||``
 Continue your animation
```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)```

## **Step 4** - Drag a fourth  **showLeds** place it into the third **showLeds**
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
Continue your animation

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)```

## **Step 5** - Drag a fifth **showLeds** place it into the fourth **showLeds**.
Drag a ``||basic.showLeds||`` into ``||basic.showLeds||``
Continue your animation

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)```

## **Step 6** - Drag a ** basic forever loop** from the basic folder.
Click on the ``||basic.basic||`` folder and drag a ``||basic.forever||``
Continue your animation

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function ()```

## **Step 7** - Drag a basic **show Number** from the **basic folder** and place it into the **basic forever loop**.
Drag a ``||basic.showNumber||`` and place it into ``||basic.forever||`` loop
Finish your animation

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function () {
    basic.showNumber()
})```

## Step 8 - Drag temperature from the Input folder and place it into the forever loop.
Under the **toolbox** Click on the ``||input.input||`` folder and drag a ``||input.temperature||``  and place it into ``||basic.showNumber||``

```blocks
basic.showLeds(`
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    # # # # #
    `)
basic.showLeds(`
    . # # # #
    . # . . .
    . # # # #
    . # . . .
    . # # # #
    `)
basic.showLeds(`
    . # # # .
    . # . . .
    . # # # .
    . # . . .
    . # # # .
    `)
basic.showLeds(`
    . # # . .
    . # . . .
    . # # . .
    . # . . .
    . # # . .
    `)
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.forever(function () {
    basic.showNumber(input.temperature())
})```

## Step 9 - Run the Program
To run the program you will click on thermometer to display the temperature. 
You can lower or raise the temperature.
