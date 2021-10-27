Insert a _slightly risky_ script…

```html
<script defer src="https://unpkg.com/vue/dist/vue.js"></script>
```

<br>

<v-click>

… a bit of markup …

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
new Vue({
  el: '#todo',
  data: { … },
  methods: { … }
)}
```

</v-click>

<!--
* Didn’t even specify a version for Vue 🤦🏻
-->
