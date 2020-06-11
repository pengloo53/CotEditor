# CotEditor

CotEditor is a lightweight plain-text editor for macOS.

- **Requirement**: macOS 10.12.2 Sierra or later
- **Web Site**: <https://coteditor.com>
- **Mac App Store**: <https://itunes.apple.com/app/coteditor/id1024640650?ls=1>

<img src="screenshot@2x.png" width="750"/>

## Source Code

[![Build Status](https://travis-ci.org/coteditor/CotEditor.svg?branch=develop)](https://travis-ci.org/coteditor/CotEditor)
[![GitHub release](https://img.shields.io/github/release/coteditor/CotEditor.svg)](https://github.com/coteditor/CotEditor/releases/latest)

CotEditor is a pure document-based Cocoa application written in Swift.

### Development Environment

- macOS 10.14 Mojave
- Xcode 10.1
- Swift 4.2
- Sandbox enabled

## How to Build

1. `git submodule update --init`
2. Update frameworks (you can skip this process if you only wanna build).
   1. `carthage update --platform macOS`
   2. Build Sparkle's XPCs by running "Sparkle XPCs" scheme in CotEditor.xcworkspace
3. Open CotEditor.xcworkspace in Xcode.
4. Build.

## License

© 2005-2009 nakamuxu,
© 2011, 2014 usami-k,
© 2013-2019 1024jp.

The source code is licensed under the terms of the **Apache License, Version 2.0**. The image resources are licensed under the terms of the [**Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License**](https://creativecommons.org/licenses/by-nc-nd/4.0/). See [LICENSE](LICENSE) for details.
