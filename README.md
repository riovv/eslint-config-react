# eslint-config-react
A set of opinionated ESLint (http://eslint.org) rules (all rules included) tailored for React projects

## Usage:
1. `npm install --save-dev eslint-config-react babel-eslint eslint-plugin-react`
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
#### 1.0.5
react/sort-comp: Order custom component* (lifecycle) methods before other custom methods.
#### 1.0.4
prefer-const: Disabled since it's very annoying when you have variables that will be changeable later on. const is a very nice concept that should be used for stuff that are actually constants.
#### 1.0.3
Name change. This is a config for React projects.
#### 1.0.2
jsx-quotes: The react/jsx-quotes rule is deprecated. Using the jsx-quotes rule instead.
#### 1.0.1
no-unused-vars: Ignore React as unused variable. Because you need to import React for JSX (it will reference that variable) without you specifically referencing it.
