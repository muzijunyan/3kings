# Three Kings

A simple HTML page with CSS animation without Javscript coding (demo: http://jsfiddle.net/jg59cbxL/20/, inspired by http://jsfiddle.net/sok_/jg59cbxL/)

The figures "king", "crown", "coat", "star", "house" are composed with several basic shapes created by CSS.

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
  width: 50px;
  height: 50px;
  background: green;
}
```

### 3. Pizza Pie

A pizza pie (could also be cake piece, coat and more):

```css
#pizza_pie {
  width: 0;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  border-bottom: 100px solid brown;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
}
```

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
