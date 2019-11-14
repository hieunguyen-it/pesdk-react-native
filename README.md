<p align="center">
  <a href="https://www.photoeditorsdk.com/?utm_campaign=Projects&utm_source=Github&utm_medium=PESDK&utm_content=React-Native">
    <img src="http://static.photoeditorsdk.com/logo.png" alt="PhotoEditor SDK Logo"/>
  </a>
</p>
<p align="center">
  <a href="https://npmjs.org/package/react-native-photoeditorsdk">
    <img src="https://img.shields.io/npm/v/react-native-photoeditorsdk.svg" alt="NPM version">
  </a>
  <a href="http://twitter.com/PhotoEditorSDK">
    <img src="https://img.shields.io/badge/twitter-@PhotoEditorSDK-blue.svg?style=flat" alt="Twitter">
  </a>
</p>

# React Native module for PhotoEditor SDK

## Getting started

Install the module with [autolinking](https://github.com/react-native-community/cli/blob/master/docs/autolinking.md) as follows:

```sh
# install
yarn add react-native-photoeditorsdk
cd ios && pod install && cd .. # CocoaPods on iOS needs this extra step
# run
yarn react-native run-ios
```

Import the module in your `App.js`:

```js
import {PESDK, Configuration} from 'react-native-photoeditorsdk';
```

Unlock PhotoEditor SDK with a license file:

```js
PESDK.unlockWithLicense(require('./pesdk_license'));
```

Open the editor with an image:

```js
PESDK.openEditor(require('./image.jpg'));
```

Please see the [code documentation](./index.d.ts) for more details and additional [customization and configuration options](./configuration.ts).

## Example

Please see our [example project](https://github.com/imgly/pesdk-react-native-demo) which demonstrates how to use the React Native module for PhotoEditor SDK.

## License Terms

Make sure you have a [commercial license](https://account.photoeditorsdk.com/pricing?utm_campaign=Projects&utm_source=Github&utm_medium=PESDK&utm_content=React-Native) for PhotoEditor SDK before releasing your app.
A commercial license is required for any app or service that has any form of monetization: This includes free apps with in-app purchases or ad supported applications. Please contact us if you want to purchase the commercial license.

## Support and License

Use our [service desk](http://support.photoeditorsdk.com) for bug reports or support requests. To request a commercial license, please use the [license request form](https://account.photoeditorsdk.com/pricing?utm_campaign=Projects&utm_source=Github&utm_medium=PESDK&utm_content=React-Native) on our website.
