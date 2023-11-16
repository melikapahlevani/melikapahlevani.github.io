---
layout: posts
title: turtle works
---
<img src="C:\git\personal_website_template\assets\images\2023-11-11 (4).png"> 
<p>import turtle <br>

def flower(): <br>
    turtle.circle(5,steps=6) <br>
    
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
</p>