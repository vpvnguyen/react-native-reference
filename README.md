# react-native-reference

# Setup React-Native-Cli
Source: https://facebook.github.io/react-native/docs/getting-started

```
brew install yarn
brew install node
brew install watchman
brew tap AdoptOpenJDK/openjdk
brew cask install adoptopenjdk8
npm install -g react-native-cli
sudo gem install cocoapods
```
> All above must be resolved for react-native to work.

# Creating a new App
- react-native init PROJECT_NAME
- cd into PROJECT_NAME
- react-native run-ios

> If iPhone X emulator is not detected, force simulator with `--simulator "iPhone 11 Pro"` flag or edit npm scripts in `package.json`. 

> ``` "ios": "react-native run-ios --simulator 'iPhone 11 Pro'" ```

> Source: https://github.com/react-native-community/cli/issues/418

