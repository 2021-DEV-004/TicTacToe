# Tic Tac Toe
## Swift 5 + UIKit

## How to run

- Clone the project
- Open with XCode (open tictactoe.xcodeproj)
- Be sure that you are on "tictactoe" target
- Choose on which device you want to run the application
- Click on the "Play" button


## How to run tests

You can run teset from the XCode test navigator.

To do it via command line, go on your project root with a terminal and launch 
```xcodebuild -project tictactoe.xcodeproj -scheme tictactoe -sdk iphonesimulator -destination 'platform=iOS Simulator,name=iPhone 12,OS=14.4’ test```

Be sure that the device name and OS is matching with one of your simulator