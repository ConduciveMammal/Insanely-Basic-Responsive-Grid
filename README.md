# Insanely Basic Responsive Grid

---

IBRG is a pretty standard responsive grid, aimed to keeping the file size and class names down.

Based from Bootstrap 4, it utilises a flex-based grid with percentage widths and em media queries.

Classes are based on how many columns you want, if you want two columns, use `<div class="col-2"></div>`.

This is literally just the beginning so it's pretty bare right now.

It also includes [Meyer Reset.css](http://meyerweb.com/eric/tools/css/reset/) to reset browser-default margins, paddings etc.

## How to Use

Like Bootstrap, this grid uses containers and rows to align floats and sections.

A column must be contained within a row, and a row must be contained in either a container or a container-fluid.

### Sample

```html
<div class="container">
	<div class="row">
    	<div class="col-2">
        	First of two columns
        </div>
        <div class="col-2">
        	Second of two columns
        </div>
    </div>
</div>
```
The `.layout` class is irrelevant to the grid or any of the layout, it's simply there to use for inital development for some column height and background colour.

Columns don't yet break down on mobile, this on the "to-do" list.
