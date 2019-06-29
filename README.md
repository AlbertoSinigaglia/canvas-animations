
# Canvas
Simple canvas projects, made in order to waste a lot of usefull time, but it comes out with some ''interesting'' animation, taking inspiration from ''the coding train'', but unfortunately
without P5.js, becouse i'm too lazy to include the script each time, so i decided to create them with basic Canvas, Js and lovely Maths.

All in all, it's fun, and that's enough for me

If you want to use, feel free to download, use, sell, destroy, improve, fall in love, sleep with it, or whatever you want, 
i don't know how licence works, so you can also abuse of it, i'll don't know what to do


PS: the code is not optimized in any way, at the same moment that it start working, i haven't worked on it anymore, sorry <3

## 10Print
Simple animation which spawns some slashes, changing randomically the direction ("\", "/"). You can change the number of the shashes by changing this line.
```javascript
var nSlash=70;
```

## AngleLine
Simple "mouse follower" drawing a line each n degrees, you can change by changing 360 with the number of line you want
```javascript
var dot= new Dot(360);
```
This is one of the first, so there is some bath Math inside, there is 4938749274 way better to do it.

## Asteroid
Simple Game like the old asteroid. You can move the SpaceShip with the mouse and shot with the spacebar.

## Breakout
Simple 80' breakout game, you can change number of row block by changing this line, with the number you want
```javascript
var nRowBriks=3;
```

## Circle & Circle2
Simple animation where some line spawn inside a circle, better Circle2

## CircleAnimation
Simple animation where balls near the mouse increase their radius; there are a lot of property that can be changed in the code if you want

## CircleLibyrinth
Simple animation which spawns peace of circle in a matrix; you can change the number of circle per line by changing this line with the number you want
```javascript
var nCircle=100;
```

## CircularMotion
Simple animation which spawns small circle around the mouse with random circular trajectories 

## Clock
Simple clock with AppleWatch's style

## CollisionDetection
Simple animation which spawns some ball with random speed, where the collision is managed by elastic shock formula

## EllipseCircle
Simple animation which spawns a ellipse which is rotating around the pointer

## FillCircle
Simple animation which spawns random circles which try to cover all the monitor

## FillCircleImage
Simple animation which spawns random circles in a photo trying to cover it with the color of the photo in that point

## FillCircleText
Simple animation which spawns small circle inside a text (top right textarea, you can have a new line with \n)

## Fireworks
Simple animation which spawns some fireworks from the bottom of the monitor

## FlappyBird
Simple implementation of the famous game (but with simple graphic elements)

## Follower
Simple animation which spawns a circle with follow the mouse, but smoothly


## Fourier Series && Fourier Series Representation
Simple animation which represent a Fourier series with circles, first one with circles inside other circles, second one drawing on screen the position of the last circle.  You can choose the number of circles by changing the number inside the "init" call
```javascript
var first= new Circle(canvas.height/4-100).init(10);
```
## FractalBinaryTree
Simple animation which represent a Fractal Binary Tree made by a L-system. You can choose "wood" color by changing 
```javascript
c.strokeStyle="brown";
```
and "leaves" color by changing
```javascript
c.strokeStyle="green";
```
The pseudo-code can be found here: https://en.wikipedia.org/wiki/L-system#Example_2:_Fractal_(binary)_tree 

See also this combination:
```javascript
if(reg[i]==="1")newReg+="11";
else if(reg[i]==="0")newReg+="1[[0[0]]]0[0]0";
var wSeg=10;
```
## GraphicFunction
Simple animation which draw a ellipse each frame ina  position determined by a function, wich can be modyfy by changing those lines
```javascript
var a = 3.085;
var b = -1.504;
var c = 0.111;
var d = -4.393;
var step = 0.0002;
```

## Gravity
Simple animation which spawns some balls with a mass, and emulating the gravity, which can be changed by modifying
```javascript
this.gravity=0.6;
this.friction=0.6;
```

## LabyrinthGenerator
Simple animation representing a possible labyrinth from the top left corner to the bottom right, pseudo-code taken from 
https://en.wikipedia.org/wiki/Maze_generation_algorithm

## LavaGlow
Simple animation which spawns some balls with random radius in a square, and used to mimic "lava lamp". You can change the size of the square from, taking in account that the algorithm used is O(n*n) where n = pizel of the square, each frame.
```javascript
canvas.width=500;
canvas.height=500;
```

## LineConnected
Simple animation which spawns some ponts outside the canvas, and connecting if they're close to someone less than a given distance, which can be changed by changing
```javascript
var tollerance = 90;
```
## Lissajous
Simple animation which spawns some points in the intersection of the circles on top and on the left. You can change the number of circles by changing
```javascript
var nSquare = 10;
```
See more on https://it.wikipedia.org/wiki/Figura_di_Lissajous

## Paint
Sorry, i've MacBook, and i need a simple paint some times... so i created this, vary useless maybe, but usefull for me :-)

## Particles
Simple animation which spawns some balls where you click on the screen. Commenting the uncommented lines of those, and uncomment commented lines, inside Particle, you will get a more "peacefull" result
```javascript
// this.r=r;
// this.g=g;
// this.b=b;
this.r=Math.floor(Math.random()*255);
this.g=Math.floor(Math.random()*255);
this.b=Math.floor(Math.random()*255);
```

## Phyllotaxis
Simple animation which spawns some points in order to create a Phyllotaxy. You can change the angle in order to get different results
```javascript
//one of those
var angle=n*137.7;
var angle=n*137.5;
var angle=n*137.3;
```

## RayCasting2D && RayCasting2DWithAngle
Simple animation representing a raycasting 2D on the canvas, with random segments. 
The first one generate rays in every direction, the second one only in a specific "view", which change by moving mouse.

## RayCasting3D && RayCastingWithStructure
Simple animation representig the 2D casting in a 3D view, based on the distance. The second one is the best one, has a 2D minimap on the top right corner, and you can move inside the space with the keyboard arrow.

Unfortunately, i wasn't able to take out the fisheye effect...

## Rose
Simple animation which spawns some points in the canvas in order to generate roses. The result depends on the value of the following 2 varables
```javascript
var n=3;
var d=8;
```
Everything can be found inside https://en.wikipedia.org/wiki/Rose_(mathematics)

## Snake && SnakePacmanEffect
No description needed, the only thing i can say is that you can modify the speed by changing this line. The second one has only the Pacman effect on the side.
```javascript
setTimeout(animate,200);
```

## SpiderWeb && SpiderWeb2
Simple animation which spawns some random points on the screen, and connect with the pointer if is close enougth. This distance can be changed by modifying
```javascript
var tollerance = 300;
```

## Starship
Simple animation which spawns some random points in the center of the screen, in order to create Star Trek starship effect, and the speed change based on the distance of the mouse from the left side of the canvas

## SpiderWeb && SpiderWeb2
Simple animation which represent times table: you can change the number of points used on the circle by changing the first value of this line (take in account that every frame has to generate that number of line, so a big number can cause lag)
```javascript
var tt = new TimesTable(200, Math.min(canvas.height-100, canvas.width-100)/2);
```

## WalkingHexagon
Simple animation which spawns a Hexagon and makes it walk. Working with every 2D polygon. The number of vertices can be changed by changing this line with the number you prefer
```javascript
this.points=generatePoints(6);
```