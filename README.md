# Simple Font Awesome 5 Checkboxes

If you are already using Font Awesome 5 in your project,
it's should be simple to use the icons for your checkboxes and radio buttons.

Download the `facheck.min.css` stylesheet,
or the `facheck-bulma.min.css` stylesheet if you're using the
[Bulma framework](https://bulma.io/),
or grab the stylesheets from
[npm](https://www.npmjs.com/package/@cityssm/simple-fa5-checkbox).

```bash
npm install @cityssm/simple-fa5-checkbox
```

## Usage

```html
<p class="facheck">
  <input id="checkbox1" type="checkbox" checked />
  <label for="checkbox1">Checkbox in regular style</label>
</p>

<p class="facheck facheck-fas">
  <input id="checkbox2" type="checkbox" checked />
  <label for="checkbox2">Checkbox in solid style</label>
</p>

<p class="facheck facheck-fas-checked">
  <input id="checkbox3" type="checkbox" checked />
  <label for="checkbox3">Checkbox in solid style when checked</label>
</p>

<p class="facheck facheck-fas facheck-far-checked">
  <input id="checkbox4" type="checkbox" checked />
  <label for="checkbox4">Checkbox in regular style when checked</label>
</p>
```

[See more examples](https://cityssm.github.io/simple-fa5-checkbox/)
including radio buttons, inline radio buttons, and Bulma styles.
