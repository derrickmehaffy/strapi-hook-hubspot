# strapi-hook-hubspot

<a href="https://www.npmjs.org/package/strapi-hook-hubspot">
    <img src="https://img.shields.io/npm/v/strapi-hook-hubspot" alt="NPM Version" />
</a>
<a href="https://www.npmjs.org/package/strapi-hook-hubspot">
    <img src="https://img.shields.io/npm/dm/strapi-hook-hubspot.svg" alt="Monthly download on NPM" />
</a>

## This hook is a WIP and is not production ready!

This hook allows you to use [Hubspot](https://www.hubspot.com/) as a service in [Strapi](https://github.com/strapi/strapi) `strapi.services.hubspot`. Hubspot is a marketing CRM system used to maintain information about leads, send emails, create forms, and manage complex workflows for marketing automation.

**Supported Strapi versions:**

- v3.5.x (recommended)
- v3.x

_Older version may work with the beta version of this hook, but are not supported._

## Installation

```bash
# using yarn
yarn add strapi-hook-hubspot

# using npm
npm install strapi-hook-hubspot --save
```

## Usage

**WIP**

## Hook config

To activate and configure the hook, you need to create or update the file `./config/hook.js` in your strapi app. For more information please see the [Strapi hooks documentation](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/configurations.html#hooks). For information about environmental configs and alternative config locations, see the [Strapi environment documentation](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/configurations.html#environment).

```js
module.exports = {
  settings: {
    // ...
    hubspot: {
      enabled: true,
    },
  },
};
```

### Support

- [Strapi community on Slack](https://slack.strapi.io) for general chatting or questions
- [GitHub issues](https://github.com/derrickmehaffy/strapi-hook-hubspot/issues) for Bugs and Feature requests

### Resources

- [Strapi website](http://strapi.io/)
- [Strapi forum](https://forum.strapi.io/)
- [Strapi news on Twitter](https://twitter.com/strapijs)

### License

- Copyright (c) 2020-2021 Derrick Mehaffy & Strapi Solutions ([GPLv3 License](LICENSE)).
