# eslint-config-float

This package includes some opinionated configuration for [ESLint](https://eslint.org/).

## Installation

You can install and use the config in your project either by installing from [npm](https://npmjs.com/package/eslint-config-float) or local code.

### NPM

You can install the package using below commands:

```shell
npm install eslint-config-float --save-dev
# or
yarn add eslint-config-float --dev
```

### Local

If you have cloned the repository and want to use the package from local copy, run below command in the folder where you cloned this repository:

```shell
npm link
```

Then in your project folder, run below command:

```shell
npm link eslint-config-float
```

## Usage

In any of your project's `.eslintrc` files, extend from this package instead:

```json
{
    "extends": "float"
}
```

## License

See the [LICENSE](LICENSE) file.
