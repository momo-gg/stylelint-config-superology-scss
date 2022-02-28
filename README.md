# stylelint-config-superology-scss

Shared Stylelint & Prettier config for SCSS based projects at Superology.

![@superology/eslint-config-vue](https://svgshare.com/i/dvq.svg "Stylelint SCSS config by Superology")

Extends [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended) and [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss).

Turns on additional rules to enforce common conventions found in the specifications and in a handful of CSS styleguides, including: [The Idiomatic CSS Principles](https://github.com/necolas/idiomatic-css),
[Google's CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#CSS_Formatting_Rules), [Airbnb's Styleguide](https://github.com/airbnb/css#css), and [@mdo's Code Guide](https://codeguide.co/#css).

It favours flexibility over strictness for things like multi-line lists and single-line rulesets.

To see the rules that this config uses, please read the [config itself](./index.js).

## Usage

### Install the configuration

```bash
npm install stylelint-config-superology-scss --save-dev
```

Also make sure you have peer dependencies installed:

```bash
npm install stylelint prettier --save-dev
```

### Add to Stylelint configuration

```json
{
  "extends": "stylelint-config-superology-scss"
}
```

_Using `.stylelintrc` file_

or

```js
module.exports = {
  extends: "stylelint-config-superology-scss",
};
```

_if using `.stylelintrc.js` file_

## Suggestions?

Create a discussion on [GitHub](/discussions) or [learn how to make a contribution](https://github.com/firstcontributions/first-contributions).
