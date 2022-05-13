# periodic_table_challenge
Recreating a periodic table layout

---

## Initial Thoughts <br>
I first thought to use ordered lists for the html, such that the numbers are already included. However, this came with formatting limitations; so I had to refactor the whole html into divs. <br>
I initially thought I would use a single grid for the whole table, but I decided to use 1 grid per row, and flex the rows. This would give me more freedom, even though I intend to have the rows spaced the same on every row. <br>

## Initial Psuedocode <br>
### html <br>
<pre>
div class="table"
  ol type="1"
    li class="table__element element--*color* *dots*" **H** /li
    li class="table__element *table__element--yellow* *five*" **He** /li
    li class="table__element *pink* *three*" **Li** /li
      etc...
/div
</pre>
### css <br>
<pre>
 .table {
  display: grid;
  grid-template-columns: repeat(18, 1fr);
  grid-template-rows: repeat(9, 1fr);

  &__element {
    display:flex;
     -center
    height + width;

  &__element--*color* {
  background-color: eg grey;
  }
 </pre>
  
  
