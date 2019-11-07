#TypeScript Locale Enum

A TypeScript enum containing all locales, such as `en-US` or `zh-Hant-HK`. Uses
mixed-case strings for locales (`en-US`, not `en-us`). Contains 495 locales.

### Install: ###

`npm i --save locale-enum`

### Use: ###

```js
const Locale = require('locale-enum');
console.log(Locale.en_US); // "en-US"
```

Import using `import`:

```js
import { Locale } from 'locale-enum';
console.log(Locale.fr_FR); // "fr-FR"
```

### How about JavaScript? ###

You can use this in JavaScript too, this is especially handy if your IDE
supports code completion.

```js
const { Locale } = require('locale-enum');
console.log(Locale.pt_BR); // "pt-BR"
```

Note: the enum keys use underscores, while string values use dashes.

Pull requests and comments are welcome at the GitHub repo.
