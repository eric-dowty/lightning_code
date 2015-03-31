********************************
* SIMPLE BOOTSTRAP GRID LAYOUT *
********************************

======
SETUP:
======

1. To get Bootstrap download the source files at "http://getbootstrap.com/getting-started/"

2. In the download folder will need to copy the following file "css/bootstrap.min.css"

3. Create a new directory for your project with the following structure
  
  - directory
    -- public
      --- css

4. Paste the "bootstrap.min.css" into the css folder of your directory

=========================
USING THE BOOTSTRAP GRID:
=========================

Note: Reference the columns.html file for examples of the explanations below.

1. Columns in bootstrap are made up of 12 units. A row made up of a single column spanning the entire page will be 12 units, while a row of 3 evenly spaced columns will be made up of 4 units each.

2. These are made up of divisions with a class of column width sizes (e.g. <div class="col-md-12">)

3. Each row must be encapsulated in a row class (e.g. <div class="row">)

4. Each row should be encapsulated in a container class (e.g. <div class="container">). It will work without the container, but formatting can suffer.

5. The container class is made up of "container" and "container-fluid". Using "container-fluid" will resize the columns dynamically as the viewport is expanded/contracted. The "container" will wait until the window reaches a specified breakpoint to resize the columns.

6. Column sizes include: 
    xs - extra small devices <768px (phones) 
    sm - small devices >768px (tablets)
    md - medium devices >992px (laptops)
    lg - large devices >1200px (large screens)

5. Below is an example of a row made up of 2 evenly spaced medium sized columns:

<div class="container-fluid">
  <div class="row">
    <div class="col-md-6">some info</div>
    <div class="col-md-6">some info</div>
  </div>
</div>

6. Run the example code from your terminal: open columns.html

==============
DOCUMENTATION:
==============

For more information on how to use the grid system see the Bootstrap documentation at: "http://getbootstrap.com/css/#grid"

