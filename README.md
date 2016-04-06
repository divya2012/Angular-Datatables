# Angular-Datatables

Angular module that provides a datatable directive along with datatable options helpers.

The required dependencies are:
  AngularJS (tested with version 1.3.0+)
  jQuery (tested with version 1.11.0+)
  Datatables (tested with version 1.10+)

Installation

   Include the CSS, JS file in your index.html file:
   
   <script src="jquery.min.js"></script>
   <script src="jquery.dataTables.min.js"></script>
   <script src="angular.min.js"></script>
   <script src="angular-datatables.min.js"></script>
   <link rel="stylesheet" href="angular-datatables.css">

Declare dependencies on your module app like this:

angular.module('myModule', ['datatables']);
