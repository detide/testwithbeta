# TEST 


### ~button /#tutorial:/github:detide/testwithbeta/README
Try this tutorial!

### ~

## 1 Unlugged test @unplugged
(This is how you insert link to  [words](https://youtu.be/qqBmvHD5bCw)). <br>
![This is how you insert image with resizing properties]<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">

## 2 fullscreen test @fullscreen

secondary button ``||basic:show leds||``<br>
primary button ``|input:Shake|``  ``||input:Shake||`` <br>
hi `1` to `3` and store it in the variable named ``hand``.<br>
seems like primary button is purple?

## 3 Showdialog test @showdialog
Can't find the difference between unlugged and showdialog yet <br>
If you want to display your tutorial step in a dialog and then have it skip to the next step automatically, use showdialog. 
This feature is typically used for introductory steps<br>
![This is how you insert image with resizing properties]<br>
<img src="https://raw.githubusercontent.com/detide/testwithbeta/master/githubpic/https___for.edu.sg_1wildlife.png" width="300">

## 4 show hint  @showhint

### ~hint

#### Hint Title
heyheyheyh
### ~

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
yeap

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


```template
basic.forever(function() {})
let x = 0
```
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

# Flashing Heart

## Introduction @unplugged

Learn how to use the LEDs and make a flashing heart! 
(Want to learn how lights work? [Watch this video](https://youtu.be/qqBmvHD5bCw)).


![Heart shape in the LEDs](/static/mb/projects/flashing-heart/sim.gif)

## Step 1 @fullscreen

Place the ``||basic:show leds||`` block in the ``||basic:forever||`` block and draw a heart.

![An animation that shows how to drag a block and paint a heart](/static/mb/projects/flashing-heart/showleds.gif)

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