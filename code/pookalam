import turtle
from turtle import *
import math

bgcolor("white")
speed(1000)


#CIRCLE
def circ(len,clr):
    penup()
    home()
    goto(0, -(len+50))
    pendown()
    color(clr)
    begin_fill()
    circle(len)
    end_fill()

circ(300,"#3d0706")


#TRIANGULAR PATTERN
home()
goto(0, -50)
def triangles(len,clr):
    color(clr)
    for i in range(36):
        begin_fill()
        forward(len / math.tan(math.pi / 3.6))
        left(130)
        forward(len / math.sin(math.pi / 3.6))
        left(100)
        forward(len / math.sin(math.pi / 3.6))
        left(130)
        forward(len / math.tan(math.pi / 3.6))
        end_fill()
        left(10)
    left(5)


triangles(300,"#900C27")
triangles(271,"#f5700a")
triangles(246,"#fcd349")
triangles(223,"white")


#SQUARE PATTERN
def sqpatt(len,clr):
    penup()
    home()
    goto(0,-50)
    left(45)
    pendown()
    color(clr)
    for i in range(18):
        begin_fill()
        for i in range(4):
            forward(len * math.sqrt(2))
            left(90)
        end_fill()
        penup()
        left(20)
        pendown()
        
#HEXAGONAL PATTERN
def hexpatt(len, clr):
    turtle.penup()
    turtle.home()
    turtle.goto(0, -50)
    turtle.left(30) 
    turtle.pendown()
    turtle.color(clr)
    
    for i in range(18):  
        turtle.begin_fill()
        for _ in range(6):  
            turtle.forward(len)
            turtle.left(60)
        turtle.end_fill()
        
        turtle.penup()
        turtle.left(20)  
        turtle.pendown()


hexpatt(100,'#185519')
hexpatt(96,'white')
hexpatt(92,'#185519')
sqpatt(82,"#3d0706")
sqpatt(70,"#ba3035")
    
# DIAMOND PETALS
turtle.speed(0)
turtle.pensize(2)
colors = ['#fcd349','#f5700a']
distance = 70
turtle.hideturtle()


for j in range(8):
    turtle.color(colors[j % 2])  
    turtle.begin_fill()  
    turtle.left(45)
    for i in range(2):
        turtle.forward(distance)
        turtle.left(60)
        turtle.forward(distance)
        turtle.left(120)

    turtle.end_fill()

#DOT
turtle.penup()
turtle.goto(0,-50)
turtle.pendown()
turtle.color('maroon')
turtle.dot(15)  


#HAPPY ONAM
penup()
goto(-145,270)
pendown()
color("navy")
write("Happy Onam!",font=("Times New Roman",50, "italic"))

#SUBMITTED BY
sw,sh= turtle.window_width(), turtle.window_height()

turtle.penup()
turtle.goto(sw//2-40,-sh//2 + 50)  
turtle.pendown()
turtle.color("maroon")
turtle.write("- Pavithra Mohan",font=("Courier",20,"italic"),align="right")


turtle.penup()
turtle.goto(sw//2-40,-sh//2 + 20)
turtle.pendown()
turtle.write("S3 LB", font=("Courier", 20,"italic"),align="right")


turtle.Screen().exitonclick()
