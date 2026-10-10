
import turtle
import math
import random

# Screen setup
screen = turtle.Screen()
screen.setup(800, 850)
screen.bgcolor("#050514")
screen.title("Glowing Lily for You")
screen.tracer(0)

pen = turtle.Turtle()
pen.hideturtle()
pen.speed(0)

# Convert local petal coordinates to screen coordinates
def transform(x, y, angle, cx, cy):
    a = math.radians(angle)
    return (
        cx + x * math.cos(a) - y * math.sin(a),
        cy + x * math.sin(a) + y * math.cos(a)
    )

# Draw a pointed lily petal
def draw_petal(angle, color, length=190, width=48):
    cx, cy = 0, 100
    points = []

    # Left edge, from base to tip
    for i in range(101):
        t = i / 100
        x = -width * math.sin(math.pi * t)
        y = length * t
        points.append(transform(x, y, angle, cx, cy))

    # Right edge, from tip back to base
    for i in range(100, -1, -1):
        t = i / 100
        x = width * math.sin(math.pi * t)
        y = length * t
        points.append(transform(x, y, angle, cx, cy))

    pen.penup()
    pen.goto(points[0])
    pen.pendown()
    pen.color(color, color)
    pen.begin_fill()

    for point in points[1:]:
        pen.goto(point)

    pen.goto(points[0])
    pen.end_fill()

    # Bright outline
    pen.color("#ffd9f4" if "pink" in color else "#b9f4ff")
    pen.pensize(2)
    pen.penup()
    for point in points:
        pen.goto(point)
        pen.pendown()
    pen.penup()

# Draw six alternating pink and light-blue petals
petal_colors = [
    "#ff62c7", "#75dfff",
    "#ff8cda", "#80cfff",
    "#ff62c7", "#75dfff"
]

for i in range(6):
    draw_petal(i * 60, petal_colors[i])

# Petal veins
for angle in range(0, 360, 60):
    pen.penup()
    pen.goto(transform(0, 110, angle, 0, 100))
    pen.pendown()
    pen.color("#ffe5fa")
    pen.pensize(1)
    for i in range(1, 45):
        t = i / 45
        x = 8 * math.sin(math.pi * t)
        y = 115 * t
        pen.goto(transform(x, y, angle, 0, 100))
    pen.penup()

# Lily center
pen.goto(0, 100)
pen.dot(27, "#fff0a6")
pen.dot(13, "#ffb6ec")

# Stamen
for angle in [-55, -30, -10, 10, 30, 55]:
    pen.penup()
    pen.goto(0, 100)
    pen.setheading(90 + angle)
    pen.pendown()
    pen.color("#fff0a6")
    pen.pensize(3)
    pen.forward(48)
    pen.dot(9, "#ffdc76")
    pen.penup()

# Green stem
pen.goto(0, 95)
pen.setheading(270)
pen.pendown()
pen.color("#48ff85")
pen.pensize(8)
pen.forward(300)
pen.penup()

# Draw pointed green leaves
def draw_leaf(angle, length=125, width=32):
    cx, cy = 0, -100
    points = []

    for i in range(101):
        t = i / 100
        x = -width * math.sin(math.pi * t)
        y = length * t
        points.append(transform(x, y, angle, cx, cy))

    for i in range(100, -1, -1):
        t = i / 100
        x = width * math.sin(math.pi * t)
        y = length * t
        points.append(transform(x, y, angle, cx, cy))

    pen.penup()
    pen.goto(points[0])
    pen.pendown()
    pen.color("#55ff83", "#126b43")
    pen.begin_fill()
    for point in points[1:]:
        pen.goto(point)
    pen.goto(points[0])
    pen.end_fill()
    pen.penup()

    # Leaf vein
    pen.goto(transform(0, 0, angle, cx, cy))
    pen.pendown()
    pen.color("#8bffad")
    pen.pensize(2)
    pen.goto(transform(0, length, angle, cx, cy))
    pen.penup()

draw_leaf(48)
draw_leaf(132)

# Glowing sparkles around the lily
for _ in range(100):
    x = random.randint(-320, 320)
    y = random.randint(-180, 350)

    pen.penup()
    pen.goto(x, y)

    color = random.choice([
        "#ff71d5", "#8beaff",
        "#ffffff", "#b58aff"
    ])
    pen.dot(random.randint(2, 6), color)

# Small diamond-shaped sparkles
for x, y in [(-220, 170), (220, 220), (-180, -60),
             (190, -100), (130, 300), (-100, 300)]:
    pen.penup()
    pen.goto(x, y)
    pen.color("#ffffff")
    pen.dot(8, "#ffffff")
    pen.dot(4, "#8beaff")

# Message below the flower
pen.penup()
pen.goto(0, -355)
pen.color("#ff8cda")
pen.write(
    "I'M SORRY",
    align="center",
    font=("Arial", 27, "italic", "bold")
)

pen.goto(0, -395)
pen.color("#80dfff")
pen.write(
    "BFF NA ULIT US <3",
    align="center",
    font=("Arial", 15, "italic")
)

screen.update()
turtle.done()
