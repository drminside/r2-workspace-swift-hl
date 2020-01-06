# r2-workspace-swift
A workspace for on-boarding developers

This workspace is one of the ways you can get started with the R2 Swift Projects. It is not the only way and you can pick to setup your development environment in the way that best fits your needs.

This is one of the 4 Github branches in this workspace:

### int/testapp
You pick this branch if are an integrator and all you need is to quickly get started with the R2 Testapp. 

### Prerequisite
- install/update [Carthage](https://github.com/Carthage/Carthage)
- install/update [Carting](https://github.com/artemnovichkov/Carting) 
- Xcode 10.x
- Swift 4.2

### Setup your workspace

1. git clone --recurse-submodules -b dev/highlights https://github.com/drminside/r2-workspace-swift-hl.git r2-workspace-swift
2. run **carthage update --platform ios** on r2-testapp-swift
3. run **carting update** on r2-testapp-swift
4. open **r2-workspace-swift.xcworkspace**
5. run target **r2-testapp-swift (carthage)**

**Cartfile should look like this:**

```
github "readium/r2-shared-swift" == ?.?.?
github "readium/r2-streamer-swift" == ?.?.?
github "readium/r2-navigator-swift" == ?.?.?
github "readium/readium-opds-swift" == ?.?.?
github "weichsel/ZIPFoundation" == 0.9.8
github "onevcat/Kingfisher" == 4.10.1
github "jdg/MBProgressHUD"
github "stephencelis/SQLite.swift" == 0.11.5
github "tadija/AEXML" == 4.3.3
github "swisspol/GCDWebServer" == 3.5.2
github "krzyzanowskim/CryptoSwift" == 0.15.0
github "cezheng/Fuzi" == 2.2.1
github "dexman/Minizip"
```
- [weichsel/ZIPFoundation](https://github.com/weichsel/ZIPFoundation) used in [ReadiumLCP](https://github.com/readium/r2-lcp-swift)
- [onevcat/Kingfisher](https://github.com/onevcat/Kingfisher) used in [R2 Testapp](https://github.com/readium/r2-testapp-swift)
- [jdg/MBProgressHUD](https://github.com/jdg/MBProgressHUD) used in [R2 Testapp](https://github.com/readium/r2-testapp-swift)
- [stephencelis/SQLite.swift](https://github.com/stephencelis/SQLite.swift) used in [R2 Testapp](https://github.com/readium/r2-testapp-swift), [ReadiumLCP](https://github.com/readium/r2-lcp-swift)
- [tadija/AEXML](https://github.com/tadija/AEXML) used in [R2Streamer](https://github.com/readium/r2-streamer-swift)
- [swisspol/GCDWebServer](https://github.com/swisspol/GCDWebServer) used in [R2Streamer](https://github.com/readium/r2-streamer-swift)
- [krzyzanowskim/CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) used in [ReadiumLCP](https://github.com/readium/r2-lcp-swift), [R2Streamer](/readium/r2-streamer-swift)
- [cezheng/Fuzi](https://github.com/cezheng/Fuzi) used in [ReadiumOPDS](https://github.com/readium/r2-opds-swift), [R2Streamer](https://github.com/readium/r2-streamer-swift)
- [dexman/Minizip](https://github.com/dexman/Minizip) used in [R2Streamer](https://github.com/readium/r2-streamer-swift)

