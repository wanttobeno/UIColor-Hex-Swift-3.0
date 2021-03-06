
UIColor+Hex, now Swift.
[![Build Status](https://travis-ci.org/yeahdongcn/UIColor-Hex-Swift.svg?branch=Swift-3.0)](https://travis-ci.org/yeahdongcn/UIColor-Hex-Swift)
=================


Convenience method for creating autoreleased color using RGBA hex string.

#使用方法

1、拷贝UIColorExtension.swift到项目

2、

    var strokeColor = UIColor(rgba: "#ffcc00").CGColor // Solid color
    
    var fillColor = UIColor(rgba: "#ffcc00dd").CGColor // Color with alpha

    var backgroundColor = UIColor(rgba: "#FFF") // Supports shorthand 3 character representation

    var menuTextColor = UIColor(rgba: "#013E") // Supports shorthand 4 character representation (with alpha)

    var hexString = UIColor.redColor().hexString(false) // "#FF0000"

##Installation

###[CocoaPods](http://cocoapods.org)

Simply add the following lines to your `Podfile`:
```ruby
# required by CocoaPods 0.36.0.rc.1 for Swift Pods
use_frameworks! 

pod 'UIColor_Hex_Swift', '~> 2.1'
```

Then import it where you use it:
```
import UIColor_Hex_Swift
```

*(CocoaPods v0.36 or later required. See [this blog post](http://blog.cocoapods.org/Pod-Authors-Guide-to-CocoaPods-Frameworks/) for details.)*

###[Carthage](http://github.com/Carthage/Carthage)

Simply add the following line to your `Cartfile`:

```ruby
github "yeahdongcn/UIColor-Hex-Swift" >= 2.1
```
=================
See more in [RSBarcodes_Swift](https://github.com/yeahdongcn/RSBarcodes_Swift) and [objc version](https://github.com/yeahdongcn/RSBarcodes) 
