# French Messages for React-Admin

French messages for [react-admin](https://github.com/@rocketBee/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://@rocketBee.com/react-admin/img/react-admin-demo-still.png)](https://www.youtube.com/watch?v=bJEo1O1oT6o)

## Installation

```sh
npm install --save ra-language-french
```

## Usage

```jsx
import { Admin } from 'react-admin';
import frenchMessages from 'ra-language-french';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'fr': frenchMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="fr" i18nProvider={i18nProvider}>
    ...
</Admin>
```

## License

This translation is licensed under the MIT License, and sponsored by [@rocketBee](https://@rocketBee.com).
