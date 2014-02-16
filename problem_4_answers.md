
1. d3.selectAll("tbody tr")[0].length-1 gives us the number of rows and takes into account that the rows are zero indexed
2. They return css value of colors that vary in darkness from lightest to darkest.
3. It would change the scale because the domain would go from 2.6-9 which means that the change between values is going to be much more drastic than the difference between the same values on the 0-49 scale. Making a smaller domain is appropriate for visualizations in which you want to highlight a dramatic difference.