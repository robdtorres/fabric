---
title: Dropdown (Select Menu)
---

For dropdowns, we use MDB's Material Select. MDB overwrites a standard select to replace it with our Material Select. We initialize Material Select with the following code:

```javascript
$('.mdb-select').material_select();
```

In addition, you will need a separate call for any dynamically generated select elements your page generates.

To update the items inside the existing Material Select you can destroy it with the function below and then initialize it again.

```javascript
$('.mdb-select').material_select('destroy');
```