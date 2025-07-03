# A npm package of tailwind css for OrianSoft.

## Installation

```npm
npm i @orian/tailwind
```

# Or

```yarn
yarn add @orian/tailwind
```

## Import in app.css

```css
@import '@orian/tailwind/base.css';
```

## Configure in tailwind.config.js

```js
/** @type {import('tailwindcss').Config} */
import config from '@orian/tailwind/tailwind.config.js';
export default {
    ...config,
    content: ['./**/*.{js,blade.php,php}'],
};
```

## Configure in postcss.config.js

```js
import config from '@orian/tailwind/postcss.config.js';
export default config;
```

## Credits

-   [Comus Bala](https://github.com/comusbala96)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
