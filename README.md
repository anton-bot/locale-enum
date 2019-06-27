#i18 Locale Enum

A Typescript enum containing all locales, such as `en-US` or `zh-Hant-HK`.

Install:

`npm i --save locale-enum`

Use:

```js
const Locale = require('locale-enum');
console.log(Locale.en_US); // "en-US"
```

Import using `import`:

```js
import { Locale } from 'locale-enum';
```

Note: the enum keys are with underscores, while string values contain dashes.
