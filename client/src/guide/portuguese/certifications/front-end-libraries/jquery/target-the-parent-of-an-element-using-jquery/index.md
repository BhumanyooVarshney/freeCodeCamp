---
title: Target the Parent of an Element Using jQuery
localeTitle: Segmentar o pai de um elemento usando jQuery
---
## Segmentar o pai de um elemento usando jQuery

## Solução

```js
<script> 
  $(document).ready(function() { 
    $("#target1").parent().css("background-color", "red"); // Selects the parent of #target1 and changes its background-color to red 
  }); 
 </script> 

```