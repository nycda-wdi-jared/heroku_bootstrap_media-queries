autoscale: true
footer: © New York Code + Design Academy 2016
slidenumbers: true

#[fit] Grid<br>Systems

---

# What is a grid system?
### (as it relates to design)

A framework of intersecting lines meant to be used as a skeleton to arrange different graphic elements

![](resources/grid-system-one.png)

![inline](resources/grid-system-two.png)

---

# What is a grid system?
### (as it relates to CSS + web design)

- Rather than arbitrarily deciding how large content blocks on a web page should be, have them conform to a set width

- Going further, instead of a set width for each block, decide on a width unit and make certain blocks x number of that unit wide

- Makes for more symmetrical designs and easier to maintain, more easily responsive code

---

# Existing grid system options

[Bootstrap](http://getbootstrap.com)

[Zurb Foundation](http://foundation.zurb.com)

[Unsemantic](http://unsemantic.com)

[Responsive Grid System](http://www.responsivegridsystem.com)

---

# Using Bootstrap's grid system

- Bootstrap is a full-featured front end CSS framework

- It is written in LESS, a higher-level version of CSS that gets compiled down to CSS

- To use Bootstrap, you include their library in the `<head>` section of your webpage

- Different features of the library are accessed using class names like `.row` for your elements

---

# Using Bootstrap's Grid System
## according to the official docs at [getboostrap.com/css](getboostrap.com/css)


- Rows must be placed within a .container (fixed-width) or .container-fluid (full-width) for proper alignment and padding.

- Use rows to create horizontal groups of columns.

- Content should be placed within columns, and only columns may be immediate children of rows.

---

# Using Bootstrap's Grid System
## according to the official docs at [getboostrap.com/css](getboostrap.com/css)

- Predefined grid classes like `.row` and `.col-xs-4` are available for quickly making grid layouts. 

- Columns create gutters (gaps between column content) via padding. That padding is offset in rows for the first and last column via negative margin on `.rows`

- Grid columns are created by specifying the number of twelve available columns you wish to span. For example, three equal columns would use three `.col-xs-4`

---

# Using Bootstrap's Grid System
### some sample code


````html
<div class="row">
  <div class="col-md-8">.col-md-8</div>
  <div class="col-md-4">.col-md-4</div>
</div>
<div class="row">
  <div class="col-md-4">.col-md-4</div>
  <div class="col-md-4">.col-md-4</div>
  <div class="col-md-4">.col-md-4</div>
</div>
````
---

# Exercise

Create the webpage mocked up in the file bootstrap.png using Bootstrap's fluid grid system

---

# Creating your own grid system

- You could also create your own grid system

- For inspiration, take a look at one of the major frameworks' code!

[https://github.com/twbs/bootstrap](https://github.com/twbs/bootstrap)

[https://github.com/nathansmith/unsemantic](https://github.com/nathansmith/unsemantic)
