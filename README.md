# vue-lupus-paragrpah-pinterest
Vue pinterest paragraph component.



## Install

via npm:
`npm install https://github.com/drunomics/vue-lupus-paragraph-pinterest.git`


import it:

```
import { PgPinterest } from 'vue-lupus-paragraph-pinterest';

Vue.component('pg-text', PgPinterest);
```

## Options
You can pass options via props:

```
<pg-pinterest
  type="{{ type }}"
  data-pinterest-url="/pinterest/url"
>
```
- `data-pinterest-url` ( string )
  The pin's url.