# Task matrix (description)

Frontend task  
Work with objects  
Technical conditions  
Use react + redux  
Input parameters  
Numbers M, N, X

Preparation  
Create a matrix M\*N (rows, columns).  
The intersection value is an object with a unique ID and the amount of Amount: int (3-digit random) find the sum for each row M and the average for each column N.

Table output  
Output the resulting data to a table with good UX. The main cells of the table display the Amount, previously automatically generated, on the right is the sum by rows M, at the bottom is the average by columns N.

Cell dynamics  
When you click on a cell, increase the Amount value by 1 and accordingly change the average of this column and the sum of this row; when you hover over a cell, highlight X cells whose Amount is closest to the Amount of the current cell.

When hovering over a cell of the sum by row, it is necessary to replace the cell value with the percentage of their contribution to the total sum and add a background: a column that will clearly show the percentage value. In fact, paint over part of the cell.

Row dynamics  
Give the ability to delete a row from the table, while the average values ​​for each column should change, give the ability to add a row, in fact, M+1. In this case, the row is filled in according to all the rules of the table.

## Scripts

- `dev`/`start` - start dev server and open browser
- `build` - build for production
- `preview` - locally preview production build
- `test` - launch test runner
