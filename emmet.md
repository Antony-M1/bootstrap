# Summary
In this documentation. we are going to see lots of tips and tricks to use the emmet. in the effective way.

### ID
if I want to create an element with a specific `ID` you can use the **#**
```
#my-id
```
output
```
<div id="my-id"></div>
```

### Class
If I want to create an element with a specific `Class`. Use the **.**(dot)

example
```
.row
```
output
```
<div class="row"></div>
```

### How to use different element?
You can see it always create an element of `div` but I want to create in the `p`, `h1`, `span`...etc. how to do that

if you want to use a <p> element with a class of "col", you can do:
```
p.col
```
output
```
<p class="col"></p>
```

### Nested Components.
For example I want to create a nested of elements for the we can use this **>**

example
```
.container>.row>.col*3
```
output
```
<div class="container">
  <div class="row">
    <div class="col"></div>
    <div class="col"></div>
    <div class="col"></div>
  </div>
</div>
```

### InnerHTML
if you want to set the innerHTML you can use this **{}**

example
```
.row>.col*{Col}
```
output
```
<div class="row">
  <div class="col">Col</div>
  <div class="col">Col</div>
  <div class="col">Col</div>
</div>
```
### Dynamic Numbering
I want to create 3 div elements with class `col1`, `col2`, `col3` to dynamically create use this

example
```
p.col$*3{$}
```
output
```
<p class="col1">1</p>
<p class="col2">2</p>
<p class="col3">3</p>
```
