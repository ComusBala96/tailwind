# A npm package of tailwind css for OrianSoft.

## Installation

```npm
npm i @oriansoft/tailwind
```

## Or

```yarn
yarn add @oriansoft/tailwind
```

## Import in app.css

```css
@import '@oriansoft/tailwind/base.css';
```

## Configure in tailwind.config.js

```js
/** @type {import('tailwindcss').Config} */
import config from '@oriansoft/tailwind/tailwind.config.js';
export default {
    ...config,
    content: ['./**/*.{js,blade.php,php}'],
};
```

## Configure in postcss.config.js

```js
import config from '@oriansoft/tailwind/postcss.config.js';
export default config;
```

## Credits

-   [Comus Bala](https://github.com/comusbala96)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
