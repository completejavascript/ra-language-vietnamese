# Vietnamese Messages for React-Admin

Vietnamese messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install @completejavascript/ra-language-vietnamese
```

## Usage

```jsx
import { Admin } from "react-admin";
import vietnamesMessages from "@completejavascript/ra-language-vietnamese";
import polyglotI18nProvider from "ra-i18n-polyglot";

const messages = {
  vi: vietnamesMessages,
};
const i18nProvider = polyglotI18nProvider((locale) => messages[locale]);

<Admin locale="vi" i18nProvider={i18nProvider}>
  ...
</Admin>;
```

## License

This translation is licensed under the MIT License.
