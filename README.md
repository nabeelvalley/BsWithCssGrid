# BsWithCssGrid
Implementation of the Bootstrap Grid System Using CSS Grid instead of Flexbox

Available on this [CodePen](https://codepen.io/nabeelvalley/pen/xapreX?editors=1100)

# Usage
## Column Spans
Pretty much the same as with a regular bootstrap grid, with the exception of the overall grid being wrapped in a container with `class="grid"`
```html
<div class="grid">
  <div class="col-1">Span 1 Column</div>
  <div class="col-1 col-lg-2">1 Column on Smaller Devices, 2 on Larger</div>
  ...
</div>
```
