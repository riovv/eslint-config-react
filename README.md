# eslint-config-patrio
A set of opinionated ESLint (http://eslint.org) rules by me for React projects.

## Usage:
1. `npm install --save-dev eslint-config-patrio babel-eslint eslint-plugin-react`
2. Create a file named `.eslintrc` in your project:
```js
{
  "extends": "react"
  // Your overrides...
}
```

## Why does it complain about bla-blu-blä, what does it all mean?
Read about all the rules here: http://eslint.org/docs/rules/  
React plugin rules: https://github.com/yannickcr/eslint-plugin-react#list-of-supported-rules

## Changelog
#### 1.0.2
jsx-quotes: The react/jsx-quotes rule is deprecated. Using the jsx-quotes rule instead.
#### 1.0.1
no-unused-vars: Ignore React as unused variable. Because you need to import React for JSX (it will reference that variable) without you specifically referencing it.
