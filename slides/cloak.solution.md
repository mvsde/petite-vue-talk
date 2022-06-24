The solution is …

```html {1}
<ul v-cloak>
  <li v-for="item in items">
    {{ item }}
  </li>
</ul>
```

<br>

<v-click>

… paired with a bit of CSS:

```css
[v-cloak] {
  display: none !important;
}
```

</v-click>

<br>

<v-click>

`v-cloak` attribute will be removed when petite-vue is ready.

</v-click>

<!--
The solution:

* The `v-cloak` attribute
* Pair with a bit of JS
* Turns everything into progressive enhancement wonderland
-->
