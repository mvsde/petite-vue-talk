Add the petite-vue script with `init` …

```html
<script src="https://unpkg.com/petite-vue" defer init></script>
```

<br>

<v-click>

… create a petite-vue “region” with `v-scope` …

```html
<div v-scope="{ count: 0 }">
  …
</div>
```

</v-click>

<br>

<v-click>

… then do Vue things:

```html {2,3}
<div v-scope="{ count: 0 }">
  {{ count }}
  <button @click="count++">Increment</button>
</div>
```

</v-click>

<!--
* Add `init` attribute to auto-load petite-vue
* `v-scope` regions are self-contained apps
* Everything else goes inside the region
* This goes a long way, but what about … ?
-->
