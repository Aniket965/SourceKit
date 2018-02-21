# SourceKit
Swift Package Manager package for SourceKit

## For installation 

```swift
import PackageDescription

let package = Package(
    name: "MyPackage",
    products: [
        .executable(name: "MyPackage", targets: ["MyPackage"])
    ],
    dependencies: [
        .package(url: "https://github.com/Aniket965/SourceKit.git", from: "1.0.0"),
   ],
    targets: [
        .target(
            name: "MyPackage",
            dependencies: ["SourceKit"]
        )
    ]

```

```
$ swift build
```
## Usage 

```swift
import SourceKit
```
