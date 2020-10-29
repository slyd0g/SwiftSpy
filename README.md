# SwiftSpy
macOS keylogger, clipboard monitor, and screenshotter written in Swift

# Usage
```                 
SwiftSpy by @slyd0g
Usage:
-h || -help        | Print help menu
-keylog            | Logs all keystrokes to stdout using IOHIDManager* APIs, requires 'Input Monitoring' permissions
-clipboard         | Monitors for changes to the system clipboard and logs to stdout
-allkeys           | Runs both the keylog and clipboard modules, requires 'Input Monitoring' permissions
-screenshot /tmp   | Takes a screenshot of the user's screen and saves to the /tmp, requires 'Screen Recording` permissions
-screenshot /tmp 5 | Takes a screenshot every 5 seconds and saves to /tmp, requires 'Screen Recording` permissions
```

# References
- https://github.com/SkrewEverything/Swift-Keylogger
- https://stackoverflow.com/questions/7190852/using-iohidmanager-to-get-modifier-key-events
- https://stackoverflow.com/questions/30380400/how-to-tap-hook-keyboard-events-in-osx-and-record-which-keyboard-fires-each-even
- https://stackoverflow.com/questions/8676135/osx-hid-filter-for-secondary-keyboard
- https://developer.apple.com/library/archive/documentation/DeviceDrivers/Conceptual/HID/new_api_10_5/tn2187.html
- https://stackoverflow.com/questions/48070396/how-to-get-list-of-hid-devices-in-a-swift-cocoa-application
- https://stackoverflow.com/questions/39691106/programmatically-screenshot-swift-3-macos/40864231#40864231