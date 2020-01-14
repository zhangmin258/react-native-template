# React Native UIW Template

[![](https://img.shields.io/github/issues/uiwjs/react-native-template.svg?style=flat-square)](https://github.com/uiwjs/react-native-template/issues)
[![](https://img.shields.io/github/forks/uiwjs/react-native-template.svg?style=flat-square)](https://github.com/uiwjs/react-native-template/network)
[![](https://img.shields.io/github/stars/uiwjs/react-native-template.svg?style=flat-square)](https://github.com/uiwjs/react-native-template/stargazers)
[![](https://img.shields.io/github/release/uiwjs/react-native-template?style=flat-square)](https://github.com/uiwjs/react-baidu-map/releases)
[![](https://img.shields.io/npm/v/@uiw/react-native-template.svg?color=success&style=flat-square)](https://www.npmjs.com/package/@uiw/react-native-template)

React Native template for [@uiw/react-native](https://github.com/uiwjs/react-native-uiw). 

## Features

- Elegant usage directly within the [React Native CLI](https://github.com/react-native-community/cli)
- Consistent with the default React Native template
- Minimal additional dependencies

## Installation and Usage

⚠️ This template only works with the new CLI. This template is intended for React Native versions `>= 0.61`. It has not been tested with previous versions. 

**Note on the legacy CLI**

⚠️ There seems to be quite some confusion about the legacy CLI. This template only works with the new CLI. Make sure you have uninstalled the legacy `react-native-cli` first (`npm uninstall -g react-native-cli`), for the below command to work. 

```bash
npm uninstall -g react-native-cli
```

Further information can be found here: https://github.com/react-native-community/cli#about

**`react-native@0.61.0` or higher**

```sh
npx react-native init MyApp --template @uiw/react-native-template
# npx react-native init MyApp --template @uiw/react-native-template@v1.0.0
```

**If you wish to not use `npx`**

you can also install the new CLI globally (`npm i -g @react-native-community/cli` or `yarn global add @react-native-community/cli`).

```bash
react-native init MyApp --template @uiw/react-native-template
```

```bash
# This will initialize new project using template from TEMPLATE_NAME package
npx react-native init ProjectName --template ${TEMPLATE_NAME}

# This will initialize new project using init command from react-native@VERSION but will use TEMPLATE_NAME custom template
npx react-native@${VERSION} init ProjectName --template ${TEMPLATE_NAME}
```

## Features

This template includes the following:

- React Native 0.60 support (now with Hooks! 🙌).
- Easy to use and understand folder structure to get you up and running as fast as possible.
- [@uiw/react-native](https://github.com/uiwjs/react-native-uiw) component framework and themes.
- [React Navigation](https://reactnavigation.org/)
- Redux support (with [@rematch](https://github.com/rematch/rematch) example)
- ESLint, and Prettier configured out-of-the-box

## Contributing

Contributions are very welcome. Please check out the [contributing document](CONTRIBUTING.md).

## License

This project is [MIT](LICENSE) licensed.
