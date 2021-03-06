# Three Kings

A simple HTML page with CSS animation without Javscript coding (demo: http://jsfiddle.net/jg59cbxL/20/, inspired by http://jsfiddle.net/sok_/jg59cbxL/)

The figures "king", "crown", "coat", "star", "house" are composed with several basic shapes created by CSS.

A running version of this example can be started here https://muzijunyan.github.io/3kings/3kings.html.

## Basic Shapes

### 1. Triangle

A triangle created with CSS:

```css
#triangle {
  width: 0;
  border-top: 20px solid transparent;
  border-left: 20px solid orange;
  border-right: 20px solid transparent;
  border-bottom: 20px solid orange;
}
```

### 2. Circle

A circle created with CSS:

```css
#circle {
  border-radius: 50%;
  width: 250px;
  height: 250px;
  background: green;
}
```

The example goes here: <a href="https://muzijunyan.github.io/3kings/shapes/Circle.html" target="_blank">Circle</a> 

### 3. Pizza Pie

A pizza pie (could also be cake piece, coat and more):

```css
#pizza_pie {
  width: 0;
  border-left: 100px solid transparent;
  border-right: 100px solid transparent;
  border-bottom: 200px solid brown;
  border-bottom-left-radius: 100px;
  border-bottom-right-radius: 100px;
}
```
The example goes here: <a href="https://muzijunyan.github.io/3kings/shapes/Pie.html" target="_blank">Pie</a> 

### 4. Hexagram

A hexegram composed with 2 triangles as a star:

```css
#triangle1 {
  width: 0;
  border-left: 25px solid transparent;
  border-right: 25px solid transparent;
  border-bottom: 50px solid yellow;
  float: left;
}

#triangle2 {
  width: 0;
  border-left: 25px solid transparent;
  border-right: 25px solid transparent;
  border-top: 50px solid yellow;
  margin-top: 30px;
}
```

### 5. Rotated Triangle

A triangle with rotation as a star trail:

```css
#star_trail {
  width: 0px;
  border-top: 4px solid transparent;
  border-bottom: 4px solid transparent;
  border-left: 200px solid yellow;
  -webkit-transform: rotate(-7deg);
  transform: rotate(-7deg);
}
```
