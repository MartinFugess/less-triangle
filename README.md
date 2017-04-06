# advanced less triangle

#### less mixins for create css triangles

#### Using (fully custom):
```css
element {
    ...
    .arrow(15px, 0, 15px, 26px, transparent, transparent, transparent, #000);
    ...
}
```

#### or (equilateral):
```css
element {
    ...
    .equ-right-arrow(30px, #000);
    ...
}
```

#### or (isosceles):
```css
element {
    ...
    .iso-right-arrow(30px, 30px, #000);
    ...
}
```

#### or (scalene):
```css
element {
    ...
    .sca-right-arrow(30px, 15px, 15px, #000);
    ...
}
```

#### all options
```css
arrow(@width1: 10px, @width2: 0, @width3: 10px, @width4: 20px, @color1: transparent, @color2: transparent, @color3: transparent, @color4: #000)
```
```css
equ-top-arrow(@size: 20px, @color: #000)
```
```css
equ-right-arrow(@size: 20px, @color: #000)
```
```css
equ-bottom-arrow(@size: 20px, @color: #000)
```
```css
equ-left-arrow(@size: 20px, @color: #000)
```
```css
iso-top-arrow(@width: 30px, @height: 20px, @color: #000)
```
```css
iso-top-right-arrow(@size: 30px, @color: #000)
```
```css
iso-right-arrow(@width: 20px, @height: 30px, @color: #000)
```
```css
iso-bottom-right-arrow(@size: 30px, @color: #000)
```
```css
iso-bottom-arrow(@width: 30px, @height: 20px, @color: #000)
```
```css
iso-bottom-left-arrow(@size: 30px, @color: #000)
```
```css
iso-left-arrow(@width: 20px, @height: 30px, @color: #000)
```
```css
iso-top-left-arrow(@size: 30px, @color: #000)
```
```css
sca-top-arrow(@height: 20px, @left: 15px, @right: 15px, @color: #000)
```
```css
sca-top-right-arrow(@width: 30px, @height: 30px, @color: #000)
```
```css
sca-right-arrow(@width: 20px, @top: 15px, @bottom: 15px, @color: #000)
```
```css
sca-bottom-right-arrow(@width: 30px, @height: 30px, @color: #000)
```
```css
sca-bottom-arrow(@height: 20px, @left: 15px, @right: 15px, @color: #000)
```
```css
sca-bottom-left-arrow(@width: 30px, @height: 30px, @color: #000)
```
```css
sca-left-arrow(@width: 20px, @top: 15px, @bottom: 15px, @color: #000)
```
```css
sca-top-left-arrow(@width: 30px, @height: 30px, @color: #000)
```


**Author**
Martin Fugess

**License**
The MIT License (MIT)
