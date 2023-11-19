---
layout: posts
title: turtle works
---
 
* ![alt text](../assets/images/2023-11-11%20(4).png "tree")



* ![alt text](../assets/images/2023-11-11%20(6).png "star") 


TREE
import turtle <br>

def flower(): <br>
    turtle.circle(5,steps=6) <br>
    <br>
def Tree(d,r,n): <br>
    if d < 10 or r < 10 : <br>
        return <br>
    turtle.pencolor("brown") <br>
    turtle.pensize(n) <br>
    turtle.forward(d) <br>
    turtle.left(r) <br>
    Tree(d*0.75 , r, n*0.4) <br>
    turtle.right(2*r) <br>
    Tree(d*0.75 ,r , n*0.4) <br>
    turtle.left(r) <br>
    turtle.backward(d) <br>
    turtle.pencolor("purple") <br>
    flower() <br>
turtle.tracer(0) <br>
turtle.penup <br>
turtle.bgcolor("pink") <br>
turtle.left(90) <br>
turtle.backward(200) <br>
turtle.pendown <br>
turtle.speed(0) <br>
turtle.pencolor("brown") <br>
Tree(120,30,35) <br>
turtle.update() <br>
turtle.mainloop() <br>
  STAR <br>
 import turtle <br>
def T(d):<br>
   if d < 5 :<br>
      return<br>
   for _ in range(5):<br>
     turtle.forward(d)<br>
     T(d/3)<br>
     turtle.right(180 - 180/5)<br>


def moon(b):<br>
   turtle.begin_fill()<br>
   turtle.fillcolor("darkgoldenrod")<br>
   turtle.circle(b)<br>
   turtle.end_fill()<br>


turtle.tracer(0)<br>
turtle.pensize(5)<br>
turtle.bgcolor("darkslategray")<br>
turtle.pencolor("darkgoldenrod")<br>
T(200)<br>
turtle.penup()<br>
turtle.backward(300)<br>
turtle.pendown()<br>
T(200)<br>
turtle.penup()<br>
turtle.backward(300)<br>
turtle.pendown()<br>
T(200)<br>
turtle.penup()<br>
turtle.left(90)<br>
turtle.forward(200)<br>
turtle.pendown()<br>
moon(100)<br>
turtle.right(90)<br>
turtle.penup<br>
turtle.update()<br>
turtle.mainloop()<br>


 

