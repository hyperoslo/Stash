# Keychain

[![CI Status](http://img.shields.io/travis/hyperoslo/Keychain.svg?style=flat)](https://travis-ci.org/hyperoslo/Keychain)
[![Version](https://img.shields.io/cocoapods/v/Keychain.svg?style=flat)](http://cocoadocs.org/docsets/Keychain)
[![License](https://img.shields.io/cocoapods/l/Keychain.svg?style=flat)](http://cocoadocs.org/docsets/Keychain)
[![Platform](https://img.shields.io/cocoapods/p/Keychain.svg?style=flat)](http://cocoadocs.org/docsets/Keychain)

A keychain wrapper that is so easy to use that your cat could use it.

## Usage

```swift
// Save and/or update a password
Keychain.setPassword(password, forAccount: account)

// Get a password
Keychain.password(forAccount:account)

// Delete a password
Keychain.deletePassword(forAccount: account)
```

## Installation

**Keychain** is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Keychain'
```

## Author

Hyper Interaktiv AS, ios@hyper.no

## License

**Keychain** is available under the MIT license. See the LICENSE file for more info.
