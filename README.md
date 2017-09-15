# Senseless.js

A comprehensive desensifying library for web development

## Word replace

Replace almost all the words with some other word. [Live example](https://www.mousereeve.com/resume).

```html
<div data-replace-word="flask" id="tobeflask">
    <h1>Oh Brave New Words</h1>
    <p>
        That have <strong>such</strong> other words in them.
    </p>
</div>
<div class="replace" data-replace-id="tobeflask">toggle</div>

<script src="static/js/lib/jquery-3.2.1.min.js"></script>
<script src="static/js/lib/wordreplace.js"></script>
```

To have the text start out in the toggled state, use the `data-start-replaced` attribute on the toggle element:

```html
<div class="replace" data-start-replaced="true" data-replace-id="tobeflask">toggle</div>
```
