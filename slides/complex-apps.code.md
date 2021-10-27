HTML

```html
<form id="search">
  …
</form>
```

<br>

<v-click>

JS

```js
import { createApp } from 'https://unpkg.com/petite-vue?module'

createApp({
  results: [],

  async getResults (search) {
    …
  }
}).mount('#search')
```

</v-click>

<!--
To recap:

* HTML code as template for petite-vue
* More conventional JS setup like Vue
-->
