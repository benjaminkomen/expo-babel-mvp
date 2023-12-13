# Expo Babel MVP

This is a minimal reproducible example of a bug in Expo's babel configuration.

## Steps to reproduce

- `yarn install`
- `yarn start`
- Open the app in the Expo app on your Simulator, Emulator or phone
- You should see a red screen with an error saying that `babel-plugin-module-resolver` is not installed
- Installing the plugin with `yarn add --dev babel-plugin-module-resolver` and restarting the app will make it work

