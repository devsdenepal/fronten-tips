# Basic CSS Tips
## Centering Element
> If the width is set the element can be centered by giving `auto` **left and right margin**

```
.center-block {
  margin-left: auto;
  margin-right: auto;
}
```

## Traditional Layouting
### HTML
```
<div class="container">
    <div class="col">First</div>
    <div class="col">Second</div>
    <div class="col">Third</div>
    <div class="col">Fourth</div>
    <div class="col">Fifth</div>
    <div class="col">Sixth</div>
</div>
```
### CSS
```
.container { 
  margin: 50px; 
  padding: 0; 
  font-size: 0;
}

.col { 
  display: inline-block; 
  border: 2px solid black; 
  width: 33.33%; 
  box-sizing: border-box; 
  margin: 0 auto; 
  height: 100px; 
  background-color: lightblue;
  font-size: 16px;
  vertical-align: middle;
}
````
*THERE ARE CHALLENGWS*
