# Flashing Heart

## Introduction unlugged 1 @unplugged

Learn how to use the LEDs and make a flashing heart! 
(Want to learn how lights work? [Watch this video](https://youtu.be/qqBmvHD5bCw)).
![Heart shape in the LEDs]<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">

## 2 showdialog test @showdialog
test test If you want to display your tutorial step in a dialog and then have it skip to the next step automatically, use showdialog. This feature is typically used for introductory steps

## fullscreen test @fullscreen

secondary button ``||basic:show leds||``
primary button ``|basic:forever|`` 

test for template
```template
let x = 0
```


## show hint?  @showhint

Let's get real bright. We're going to make all the lights flash on your board!

## fullscreen test 2 @fullscreen

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
## Step 4

If you have a @boardname@ connected, click ``|Download|`` to transfer your code and watch the hearts flash!

```template
basic.forever(function() {})
```

## It's time to code! @showhint

Let's get real bright. We're going to make all the lights flash on your board!

![Flash lights](/static/tutorials/lights-flashing.gif)


