Until JS has loaded, this HTML …

```html
<ul>
  <li v-for="item in items">
    {{ item }}
  </li>
</ul>
```

<br>

<v-click>

… will look like this:

* {​{ item }}

</v-click>

<br>

<v-click>

A flash of “un-compiled” content. ~~FOUC~~ FOU**C**C? 🤔

</v-click>

<!--
The problem:

* While JS is loading the HTML looks … suboptimal
* Let’s call it a “flash of un-compiled content”
-->
