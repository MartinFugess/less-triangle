# advanced less triangle

#### less mixins for create css triangles

####Using (fully custom):
```less
element {
    ...
    .arrow(15px, 0, 15px, 26px, transparent, transparent, transparent, #000);
    ...
}
```

####or (equilateral):
```less
element {
    ...
    .equ-right-arrow(30px, #000);
    ...
}
```

####or (isosceles):
```less
element {
    ...
    .iso-right-arrow(30px, 30px, #000);
    ...
}
```

####or (scalene):
```less
element {
    ...
    .sca-right-arrow(30px, 15px, 15px, #000);
    ...
}
```

####all options
```less
.arrow(@width1: 10px, @width2: 0, @width3: 10px, @width4: 20px, @color1: transparent, @color2: transparent, @color3: transparent, @color4: #000)
```
```less
.equ-top-arrow(@size: 20px, @color: #000)
```
```less
.equ-right-arrow(@size: 20px, @color: #000)
```
```less
.equ-bottom-arrow(@size: 20px, @color: #000)
```
```less
.equ-left-arrow(@size: 20px, @color: #000)
```
```less
.iso-top-arrow(@width: 30px, @height: 20px, @color: #000)
```
```less
.iso-top-right-arrow(@size: 30px, @color: #000)
```
```less
.iso-right-arrow(@width: 20px, @height: 30px, @color: #000)
```
```less
.iso-bottom-right-arrow(@size: 30px, @color: #000)
```
```less
.iso-bottom-arrow(@width: 30px, @height: 20px, @color: #000)
```
```less
.iso-bottom-left-arrow(@size: 30px, @color: #000)
```
```less
.iso-left-arrow(@width: 20px, @height: 30px, @color: #000)
```
```less
.iso-top-left-arrow(@size: 30px, @color: #000)
```
```less
.sca-top-arrow(@height: 20px, @left: 15px, @right: 15px, @color: #000)
```
```less
.sca-top-right-arrow(@width: 30px, @height: 30px, @color: #000)
```
```less
.sca-right-arrow(@width: 20px, @top: 15px, @bottom: 15px, @color: #000)
```
```less
.sca-bottom-right-arrow(@width: 30px, @height: 30px, @color: #000)
```
```less
.sca-bottom-arrow(@height: 20px, @left: 15px, @right: 15px, @color: #000)
```
```less
.sca-bottom-left-arrow(@width: 30px, @height: 30px, @color: #000)
```
```less
.sca-left-arrow(@width: 20px, @top: 15px, @bottom: 15px, @color: #000)
```
```less
.sca-top-left-arrow(@width: 30px, @height: 30px, @color: #000)
```


**Author**
Martin Fugess

**License**
The MIT License (MIT)
