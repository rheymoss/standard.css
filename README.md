# standard.css v 0.0

It's all that simple! This is the very first of Standard CSS and it comes without any JS yet. 
Might be updated on every month, year, or even decade.


### Prerequisities

The first of all, you might need a computer, food, some coffee, and a girl to keep you survive while learning this CSS.


### Html, Body
html and body has no margin-top.
.bgblack means background set to black
.bgred means background set to red
.see means height is set to 180px
.seem means height is set to 367px
.see-the-sky means height is set to 750px

Sometimes it will help you to see or "debug" your element.

```
<body class="bgblack see-the-sky"></body>
```

### Columns & width
.c{number}cent
You'll find the class with name started with 'c{number}cent', means it has the width of element on percent.
Let say .c50cent, means your element has 50% size of it's container, but it's actually not full of 50%, because it's just 49%, allows you to create another padding/margin of the element. And if you want a real 50% of width, then you need to put full-c{number}cent. Of course those are not set as important, so your class/id can override it.

.full means the width of element is 100%

```
<div class="full-c70cent">
<div class="c70cent"></div>
```

### Alligning and Floating
.lt means float : left.
.rt means float : right.
.ct means float : none, but margin:auto

If you need to know what exactly is happening when you put it on your element -> its getting your element to the left or right, or center. Somehow .ct can't work as you expected, it needs you to put a width in it.

```
<div class="full "></div>
```

.text-left, .text-right, .text-center 
It's alligning your text or image to left, right, or center


```
Give examples
```

* Hat tip to anyone who's code was used
* Inspiration
* etc
