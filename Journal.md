# This is the journal for Comp Sci

1. What **did** we do?
1. What *did* you learn?
1. What question do I have?

Kano's code for the dice,

```.py
def setup():
    size (600,600)
    
def draw():
    x=0
    
def mouseClicked():
    background(255)
    stroke(0)
    rect(100,100, 400, 400, 10)
    stroke(255,0,0)
    strokeWeight(10)

    
    
    n=random(0,3.1)
    print(n)
    if 0<=n<0.5:
        circle(300,300,50)
    if 0.5<=n<1.0:
        circle(200,200,50)
        circle(400,400,50)
    if 1.0<=n<1.5:
        circle(200,200,50)
        circle(400,400,50)
        circle(300,300,50)
    if 1.5<=n<2.0:
        circle(200,200,50)
        circle(400,200,50)
        circle(200,400,50)
        circle(400,400,50)
    if 2.0<=n<2.5:
        circle(200,200,50)
        circle(400,200,50)
        circle(200,400,50)
        circle(400,400,50)
        circle(300,300,50)
    if 2.5<=n<3.1:
        circle(200,200,50)
        circle(400,200,50)
        circle(200,400,50)
        circle(400,400,50)
        circle(200,300,50)
        circle(400,300,50)

```
