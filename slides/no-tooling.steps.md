Load Vue …

```html
<script src="https://unpkg.com/vue@3"></script>
```

<br>

<v-click>

… add a bit of markup …

```html
<div id="todo">
  …
</div>
```

</v-click>

<br>

<v-click>

… and off we go!

```js
const { createApp } = Vue

createApp({
  data () {
    …
  }
}).mount('#todo')
```

</v-click>
