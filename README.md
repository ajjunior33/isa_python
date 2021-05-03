# Exercício 01

```python
import turtle
t = turtle.Turtle()

t.forward(100)
t.left(120)
t.forward(100)
t.left(120)
t.forward(100)

```

# Exercício 02
```python
import turtle

a = int(input("Informe um valor: "))
t = turtle.Turtle()

t.forward(a)
t.left(120)
t.forward(a)
t.left(120)
t.forward(a)

```

# Exercício 03
```python
import turtle
t = turtle.Turtle()


colors = [
    '#1abc9c',
    '#f1c40f',
    '#f39c12',
    '#d35400',
    '#3498db',
    '#2980b9',
    '#e74c3c',
    '#8e44ad'
];
# Reset line
t.penup()
t.left(180)
t.forward(230)
t.right(180)
t.pendown()

for i in xrange(8):
	t.forward(100)
	t.color(colors[i])
  
  
```