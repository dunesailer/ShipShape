ShipShape
========

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/dunesailer/ShipShape/blob/main/LICENSE)
[![Platform](https://img.shields.io/badge/in-swift5.3-orange.svg)](https://github.com/apple/swift)
[![build](https://github.com/dunesailer/ShipShape/workflows/build/badge.svg)](https://github.com/dunesailer/ShipShape/actions?query=workflow%3Abuild)

Dunesailer Research's ShipShape package provides utilities and data structures that assist in generating the shapes of ships, for use in projects developed in the Swift programming language. Though the functionality provided is driven by the specific needs of Dunesailer Research itself, we believe there is value to the broader programmming public contained therein, so we are pleased to make these available in a free and open source format.


## Using the Package

The ShipShape package is a standard Swift package, and can easily be added to your project using Xcode. Simply select the *Swift Packages* tab of your project root, click the + button to add a dependency, search for "ShipShape", and add it. Please note that you will need to have Xcode connected to GitHub for this to work.

To include ShipShape in another Swift Package Manager package, add it to the `dependencies` attribute defined in your `Package.swift` file. You can select the version using the `from` parameter. For example:
```
dependencies: [
    .package(url: "https://github.com/dunesailer/ShipShape.git", from: "0.1.0")
]
```


## About Us

Dunesailer Research's mission is to build and advance technology that allows software to be creative in all realms.

Dunesailer is the brainchild and solo endeavor of B.T. Franklin, a software engineer and researcher located in Phoenix, Arizona, USA.
