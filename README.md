knowledge about D3 transitions and joins to create a linked scatter plot and animated box plot. __Boxplots__ (sometimes called box-and-whisker plots) show summary statistics about a quantitative attribute. Your box plot will be linked to the scatter plot via lasso interactions. That is, when a user lassos a selection of data points in the scatter plot, the box plot will be drawn (or updated) using D3-based animations.
It will include the following aspects:
* Create a page with a control panel to hold a set of required HTML controls and two visualization panels to hold your scatter plot and box plot.
* A user can select a dataset from a dropdown. We will give you two starting datasets, but we'll also grade using a third and fourth (hidden) dataset, so you'll need to code your logic in a way that dynamically supports loading and parsing datasets and their attributes.
* Draw the currently selected dataset and attributes in the scatter plot.
* When the user lassos a selection of points in the scatter plot, draw (or update) the box plot panel to show summary statistics about the selected points
