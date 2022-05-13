# periodic_table_challenge
Recreating a periodic table layout

---

## Psuedocode <br>
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
  
  
