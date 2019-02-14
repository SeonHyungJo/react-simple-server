# simple-react-server

Create very very Simple react repo to making library

**NOT USE WEBPACK-DEV-SERVER CONFIG VERSION**

## :zap: Start Server

```
  npm run dev
```


## :zap: Setting List

- .editorconfig
- eslint
- eslint-prettier
- webpack.config.js
- vscode / settings.json
- React, ReactDom

## .editorconfig

Create `.editorconfig` file and setting this.

```js
root = true

[*]

charset = utf-8
end_of_line = lf
insert_final_newline = true
indent_style = space
indent_size = 2
trim_trailing_whitespace = true
```

If you cooperate with other people. It is requied.

## eslint

As you know, `eslint` is pluggable linting utility for JavaScript and JSX

I use `eslint --init`

```
  npx eslint --init

  Use a popular style guide // choose
  Standard // choose
  JSON // choose
  Yes // choose
  // And Download Dependencies and Create eslint file
```

> npx is a very cool way to run Node code, and provides many useful features

We should use React, ReacDom, React-Hook

Add eslint-plugin-react

```js
{
    "extends": ["standard", "plugin:react/recommended"],
    "plugins": [
        "react-hooks"
    ],
    "rules": {
        "react-hooks/rules-of-hooks": "error"
    }
}
```


Create `.eslintignore` file

```
node_modules
public

*.config.js
```

## vscode / settings.json

```js
{
    "eslint.autoFixOnSave": true,
    "prettier.eslintIntegration": true
}
```

## React, ReactDom

```
  npm i react react-dom
```
