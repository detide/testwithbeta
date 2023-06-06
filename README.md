# TEST 

## 1 Unlugged test @unplugged
(This is how you insert link to  [words](https://youtu.be/qqBmvHD5bCw)).
![This is how you insert image with resizing properties]<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">

## 2 Showdialog test @showdialog
Can't find the difference between unlugged and showdialog yet <br>
If you want to display your tutorial step in a dialog and then have it skip to the next step automatically, use showdialog. This feature is typically used for introductory steps
![This is how you insert image with resizing properties]<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">

## 3 fullscreen test @fullscreen

secondary button ``||basic:show leds||``
primary button ``|input.onGesture:Shake|`` 
seems like primary button is purple?


## 4 show hint  @showhint

whats the diff between fullscreen and showhint?

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
})
```
~hint This content is hidden until the user clicks here.
  - :blank: Bullet 1
  - :mouse pointer: Bullet 2
hint~

## 5 boardname? show normal code

If you have a @boardname@ microbit connected, click ``|Download|`` to transfer your code and watch the hearts flash!

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
})
```

## Step 3: Add a sound effect

To add a sound effect to your project, follow these steps:

1. Drag and drop the "play sound" block from the "Sounds" category.
2. Choose the desired sound from the options.

~hint
> You can explore different sound options, such as "pop," "bell," or "fanfare."
> Experiment with different sounds to find the one you like best!
hint~

3. Connect the "play sound" block to a trigger, such as a button press or a certain event.
4. Test your project by running it on your target device.


```template
basic.forever(function() {})
let x = 0
```