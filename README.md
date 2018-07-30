# vue-lupus-paragraph-pinterest
Vue pinterest paragraph component.



## Install

via npm:
`npm install https://github.com/drunomics/vue-lupus-paragraph-pinterest.git`


import it:

```
import { PgPinterest } from 'vue-lupus-paragraph-pinterest';

Vue.component('pg-text', PgPinterest);
```


## Properties
You can pass the following props:

- `data-pinterest-url` ( string )
  The pin's url.

## Example
```
<pg-pinterest
  data-pinterest-url="/pinterest/url"
>
```