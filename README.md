# CSS Grid Utility 
A simple CSS Grid utility library built with SCSS. Creates 3 columns by deafult for . Follows bootstrap media query breakpoints and it mobile first. This does not add any presentational CSS, just CSS grid template columns with grid-gap.

Just include the CSS or SCSS file into you project and Start using it. 

---

## Let create simple CSS grid that create 3 columns.
```html
<div class="grids col-3">
  <div>Content</div>
  <div>Content</div>
  <div>Content</div>
</div>
```

### How about CSS grids that is 1 column in mobile, 2 in tablet and 3 in destkop
```html
<div class="grids col-1 sm-2 lg-3">
  <div>Content</div>
  <div>Content</div>
  <div>Content</div>
</div>
```

As this is my version of adoptation from bootstrap breakpoint. A copy-paste of same, take a look

| | Extra small <576px | Small ≥576px | Medium ≥768px | Large ≥992px | Extra large ≥1200px |
|-|-|-|-|-|-|
| Class prefix | .col- | .sm- | .md- | .lg- | .xl- |
| # of Columns | 3 |
| Grid Gap | 2rem |

If you like this utility library, Feel free to use it in your project. Happy to recieve feedback and contributions ofcourse :)
