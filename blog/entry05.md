# Entry 5
##### 4/19/24

Today, I dedicated my time to studying CSS Grid, a fantastic tool for effortlessly creating complex layouts. I began by establishing a fundamental grid structure using CSS:

--------------------
.grid-container {
  display: grid;
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr 1fr;
--------------------

This snippet of code sets up a container with three columns of the same size. To position items in particular spots, I made use of features such as "grid-column-start" and "grid-column-end":

--------------------
.grid-item {
  grid-column-start: 1;
  grid-column-end: 3;
}
--------------------

This causes an item to span across the initial two columns. I gained valuable insights into grid features from the website: https://css-tricks.com/snippets/css/complete-guide-grid/

I also explored the process of arranging sections within a grid using "grid-template-areas", which simplifies layout management:
--------------------
.grid-layout {
  display: grid;
  grid-template-areas:
    "header header header"
    "nav content sidebar"
    "footer footer footer";
}
--------------------
--------------------
.header {
  grid-area: header;
}
--------------------
When you utilize set grid areas, it becomes easier to structure the layout in a clear manner. I gained a better grasp of this concept with the help of thorough explanations and illustrations from: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout

I used these methods to enhance a section of the project, making it adaptable with CSS Grid.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
