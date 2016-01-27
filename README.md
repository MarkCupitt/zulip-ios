The following steps may be needed to build and run Zulip iOS:

```
git submodule init
git submodule --recursive update
pod install

open Zulip.xcworkspace
```

you may need to disable bitcode in your project

http://stackoverflow.com/questions/31205133/how-to-enable-bitcode-in-xcode-7

if CocoaPods is not installed, you wil need to do so

``` sudo gem install cocoapods ```

before running

``` pod install ```
