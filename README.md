Litepicker polyfills IE11
=========

This library also includes [ie11-custom-properties](https://github.com/nuxodin/ie11CustomProperties).

## Installation

**Installing a Litepicker module**

```bash
npm i litepicker-polyfills-ie11
```

**Non-module environments**

```html
<script src="https://cdn.jsdelivr.net/npm/litepicker-polyfills-ie11/dist/index.js"></script>
```

## Usage

If you’re using a bundler, e.g. webpack, you’ll need to import Litepicker.

```ts
// Include this library first
import 'litepicker-polyfills-ie11';
// then import Litepicker
import Litepicker from 'litepicker';
```

Now you can create Litepicker instance.
```html
<script>
var picker = new Litepicker({ 
  element: document.getElementById('litepicker'),
});
</script>
```
