### @explicitHints true

# Turtle Logo - Lesson #2

## Turtle Logo - Lesson #2, with variables and sprites @unplugged
**Making the Turtle Move.**

In this lesson you will make your **Turtle Objects** move.
![move](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-lesson2-advanced/raw/main/assets/move_screenshot.png)

## Step 1
Code your solution below.

```ghost
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.moveDirection(TurtleDirection.Forward, 25)
myTurtle.say("Hello, World!")
```