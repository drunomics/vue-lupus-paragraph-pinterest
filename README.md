# vue-lupus-paragraph-pinterest
Vue pinterest paragraph component.



## Install

via npm:
`npm install https://github.com/drunomics/vue-lupus-paragraph-pinterest.git`


import it:

```
import PgPinterest from 'vue-lupus-paragraph-pinterest';

Vue.component('pg-pinterest', PgPinterest);
```


## Properties
You can pass the following props:

- `src` ( string )
  The pin's url.

## Slots
You can use the following slots

- `title` ( default )
  A title.

## Example
```
<pg-pinterest src="#the-pinterest-post-link">
  <h3 slot="title">The title value</h3>
</pg-pinterest>
```
