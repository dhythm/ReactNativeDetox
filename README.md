# Getting started

```sh
npx react-native init ReactNativeDetox --template react-native-template-typescript
```

If you face with an error `Command PhaseScriptExecution failed with a nonzero exit code`, the link below may help.
https://github.com/getsentry/sentry-cordova/issues/102

# Set up Detox environment

https://wix.github.io/Detox/docs/introduction/getting-started/

Initialize environment

```sh
npx detox-cli init
# same as `detox init`
```

Build test

```sh
npx detox-cli build --configuration ios
```

Run test

```sh
npx detox-cli test --configuration ios
```
