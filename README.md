# @burnmaniac/eslint-config-react-app

This package contains ESLint configuration for React projects.

## Usage

Install:

```sh
$ npm install --save-dev @burnmaniac/eslint-config-react-app
```

or with `yarn`

```sh
$ yarn add --dev @burnmaniac/eslint-config-react-app
```

Create a file named `.eslintrc` in the root folder of your project:

```json
{
    "extends": "@burnmaniac/eslint-config-react-app",
    "rules": {
        "valid-jsdoc": "warn",
        "require-jsdoc": "off"
    }
}
```

Learn more about [configuring ESLint](http://eslint.org/docs/user-guide/configuring) on the ESLint website.
