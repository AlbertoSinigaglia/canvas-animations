
# Canvas
Simple canvas projects, made in order to waste a lot of usefull time, but it comes out with some ''interesting'' animation, taking inspiration from ''the coding train'', but unfortunately
without P5.js, becouse i'm too lazy to include the script each time, so i decided to create them with basic Canvas, Js and lovely Maths.

All in all, it's fun, and that's enough for me

If you want to use, feel free to download, use, sell, destroy, improve, fall in love, sleep with it, or whatever you want, 
i don't know how licence works, so you can also abuse of it, i'll don't know what to do


PS: the code is not optimized in any way, at the same moment that it start working, i haven't worked on it anymore, sorry <3

## Projects "simple" description

### AngleLine
Simple "mouse follower" drawing a line each n degrees, you can change by changing 360 with the number of line you want
```javascript
var dot= new Dot(360);
```
This is one of the first, so there is some bath Math inside, there is 4938749274 way better to do it.

### Breakout
Simple 80' breakout game, you can change number of row block by changing this line, with the number you want
```javascript
var nRowBriks=3;
```

### Circle & Circle2
Simple animation where some line spawn inside a circle, better Circle2

### CircleAnimation
Simple animation where balls near the mouse increase their radius; there are a lot of property that can be changed in the code if you want

### CircleLibyrinth
Simple animation spawning peace of circle in a matrix; you can change the number of circle per line by changing this line with the number you want
```javascript
var nCircle=100;
```

### CircularMotion
Simple animation spawning small circle around the mouse with random circular trajectories 

### Clock
Simple clock with AppleWatch's style

### CollisionDetection
Simple animation spawning some ball with random speed, where the collision is managed by elastic shock formula

### EllipseCircle
Simple animation spawning a ellipse which is rotating around the pointer

### FillCircle
Simple animation spawning random circles which try to cover all the monitor

### FillCircleImage
Simple animation spawning random circles in a photo trying to cover it with the color of the photo in that point

### FillCircleText
Simple animation spawning small circle inside a text (top right textarea, you can have a new line with \n)

### Fireworks
Simple animation spawning some fireworks from the bottom of the monitor

### FlappyBird
Simple implementation of the famous game (but with simple graphic elements)

### Follower
Simple animation spawning a circle with follow the mouse, but smoothly

### GraphicFunction
Simple animation whitch draw a ellipse each frame ina  position determined by a function, wich can be modyfy by changing those lines
```javascript
var a = 3.085;
var b = -1.504;
var c = 0.111;
var d = -4.393;
var step = 0.0002;
```

### GRavity
Simple animation spawning some balls with a mass, and emulating the gravity, whitch can be changed by modifying
```javascript
this.gravity=0.6;
this.friction=0.6;
```