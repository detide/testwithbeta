# Flashing Heart

## Introduction @unplugged

Learn how to use the LEDs and make a flashing heart! 
(Want to learn how lights work? [Watch this video](https://youtu.be/qqBmvHD5bCw)).
![Agent building a tower](https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png)

![Heart shape in the LEDs](https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png|width=80px)
<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">
## Step 1 @fullscreen

Place the ``||basic:show leds||`` block in the ``||basic:forever||`` block and draw a heart.


## Step 2

Place another ``||basic:show leds||`` block. You can leave it blank and draw what you want.

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .`);
})
```

## Step 3

Look at the virtual @boardname@, you should see the heart and your drawing blink on the screen.

## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and watch the hearts flash!

```template
basic.forever(function() {})
```

# Flash-a-rama

## It's time to code! @showhint

Let's get real bright. We're going to make all the lights flash on your board!

![Flash lights](/static/tutorials/lights-flashing.gif)

## Step 1: Make a new variable @showdialog

