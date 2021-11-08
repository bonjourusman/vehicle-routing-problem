# vehicle-routing-problem
Single Depot Vehicle Routing Problem

This notebook is based on the Clarke-Wright Savings Algorithm, which can be found <a href="https://web.mit.edu/urban_or_book/www/book/chapter6/6.4.12.html">here</a>.

The sole parameter required is the maximum number of visits per route, namely "max_visits".

In this notebook, 50 locations are generated randomly on an xy-plane, and the algorithm computes the route combinations that result in the greatest savings. The routes generated can be visualized at the end of the notebook.

Because of the flexible nature of this algorithm, additional parameters can also be added for greater complexity.
