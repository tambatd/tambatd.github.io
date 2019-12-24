---
title: Processing Art!
tags: [Processing.py, Python]
style: border
color: primary
description: How to program in Processing.py and some example projects!.
---

Source: [Me]

In this mini tutorial I'll teach you the basics of Processing.py!

## What is Processing?

Processing is a open source programable sketchbook. Languages supported currently are Python and JS. Here is some example code in Python:

```html
def setup():
    background(0)
    size(1000,1000)
    frameRate(60)
    main()

def main():
    draw()

def draw():
    x1 = 0
    y1 = 0
    for i in range(1000):
        if x1 < 2500:
            for x in range(100):
                noStroke()
                fill(random(255), random(255), random(255))
                rect(x1,y1,5,5)
                x1 += 50
        if x1 >= 2500:
            y1 += 20
            x1 = 0

    #saveFrame("gif-####.png")
```
