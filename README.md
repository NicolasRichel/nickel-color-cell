[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/NicolasRichel/nickel-color-cell)

# \<nickel-color-cell\>

A dynamical color cell that is customizable and parametrized.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="nickel-color-cell.html"/>
    <script>
      const levels = [0,3,6,9,12,15,18,21,24];
      const i=0;
      (() => {
        setInterval(() => {
          document.querySelector('nickel-color-cell').set('level', levels[i++]);
        }, 1200);
      })();
    </script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<nickel-color-cell
  min-color="[128,128,0]"
  max-color="[0,0,225]"
  nb-colors="25">
</nickel-color-cell>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

GNU General Public License version 3.0.
