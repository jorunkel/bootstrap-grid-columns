# bootstrap-grid-columns
Makes bootstrap columns all the same height *for each* row!

Have you ever wanted to get the columns in your Bootstrap grid all the same height? Yes, there are solutions for that out there. But did you also want to do this on a per-row basis?

This plugin handles the case where you have a `<div class="row">...</div>` containing so many columns that they are wrapped in multiple rows. It adjusts the height of each column so that they are the same within their row.

## Features

* Easy to use (just add the class `grid-columns` to your row)
* Fully responsive
* Handles mixed column widths

## How to Use

1. Add `bootstrap-grid-columns.js` to your page

2. Add the class `grid-columns` to your rows:

```html
<div class="row grid-columns">
	<!-- define your rows here -->
</div>
```

## Demo Page

See [demo.html](http://htmlpreview.github.io/?https://github.com/jorunkel/bootstrap-grid-columns/blob/master/demo.html).
