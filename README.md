# ConsultingCorona

## Theme

This project uses a custom `dynamic-grid` theme, which aims to mitigate the missing layouting options in marp. The grid is activated by spanning a `<div>` block around the slide. This main block needs to classes, `dg` and either `dg-row` or `dg-col` in order to specify the main style.

### dg-row

A row has to be declared with a `div` block and CSS class `dg-row-elem`.  
Each row can have a different number of column elements. Each column then has to be declared with a `div` block and the CSS class `dg-col-elem`

### dg-col

Similar to [`dg-row`](#dg-row), use CSS class `dg-col-elem` here.  
Although one might think about putting row elements in columns, this is actually not the case. Just write your content in a column, putting a `dg-row-elem` inside actually breaks the layout