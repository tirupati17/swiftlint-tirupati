# Description
This repo contain config for SwiftLint which I use for iOS based projects.

# What is SwiftLint
SwiftLint. A tool to enforce Swift style and conventions.[Official Repo](https://github.com/realm/SwiftLint)


# Installation Instructions
1. Install swift-lint: [https://github.com/realm/SwiftLint/releases](https://github.com/realm/SwiftLint/releases)   

2. Add `.swiftlint.yml` to your xcode project folder
  - Example of swift-lint rule set: [https://github.com/realm/SwiftLint/blob/master/.swiftlint.yml](https://github.com/realm/SwiftLint/blob/master/.swiftlint.yml)

3. Add swift-lint script to your xcodeproject:

  - XCode 👉 Build phases
  - Click "plus-button" 👉 Add run script
  - Paste in the bellow:

```swift
if which swiftlint >/dev/null; then
  swiftlint
else
  echo "warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint"
fi
```

4. Build the project to see some swift-lint warnings

## Badge

Show off that you're using this config.

```
[![SwiftLint tirupati17](https://img.shields.io/badge/SwiftLint-tirupati17-brightgreen)](https://github.com/tirupati17/swiftlint-tirupati)  
```

[![SwiftLint tirupati17](https://img.shields.io/badge/SwiftLint-tirupati17-brightgreen)](https://github.com/tirupati17/swiftlint-tirupati)  

