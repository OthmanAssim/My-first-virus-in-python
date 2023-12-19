# My-first-virus-in-python
This is the code of my first virus in pyhon



# code:

import turtle
a = turtle.Turtle()
a.color('white')
a.speed(0)
a.hideturtle()

s=turtle.Screen()
s.bgcolor('black')
for x in range (500):
    a.forward(x)
    a.left(x-1)
turtle.done()

