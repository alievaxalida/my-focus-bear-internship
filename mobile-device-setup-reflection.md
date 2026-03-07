📱 Set up a real mobile device for testing
🎯 Goal
Ensure you can test Focus Bear on a real Android or iOS device.

❓ Why is this important?
Testing on real devices provides more accurate results for performance, touch interactions, and real-world scenarios compared to emulators.

🔍 Research & Learn

**How do you enable developer mode on Android and iOS?**
To test on a real device, you first need to enable developer mode. On Android, you can do this by going to Settings, opening “About Phone,” and tapping the “Build Number” several times until developer mode is enabled. After that, a “Developer Options” menu appears in the settings where you can enable USB debugging. On iOS, developer mode is enabled by connecting the device to a Mac with Xcode installed and turning on Developer Mode in the device settings when prompted.

**What tools can you use to inspect and debug apps on a real device?**
There are several tools that help inspect and debug apps on real devices. For Android, Android Studio and ADB (Android Debug Bridge) are commonly used to monitor logs and debug applications. For iOS, Xcode provides debugging tools and device logs. Browser developer tools can also be used when testing mobile web apps by connecting the phone to a computer and enabling remote debugging.

**How do you capture logs from an Android/iOS device while testing?**
To capture logs during testing, Android testers can use Logcat through Android Studio or the ADB command line to view system and application logs. On iOS, logs can be viewed through Xcode’s device console or the macOS Console app when the device is connected. These logs help developers understand what happened before a crash or error.

**What are common challenges when testing on physical devices, and how do you work around them?**
Testing on physical devices can have challenges such as different screen sizes, OS versions, battery conditions, network changes, and device performance differences. Testers often work around these challenges by testing on multiple devices when possible, simulating different network conditions, clearing cache or reinstalling the app, and documenting the exact device model and OS version used during testing.

📝 Reflection

**What issues might only appear on a real device but not on an emulator?**
Some issues only appear on real devices, such as problems with touch gestures, performance slowdowns, camera or sensor interactions, push notifications, background app behavior, battery usage, and real network connectivity. Emulators sometimes cannot fully simulate these hardware and performance conditions.

**How would you report a bug that only happens on a specific device model?**
If a bug happens only on a specific device model, I would clearly report the device model, OS version, app version, and environment used during testing. I would also include the steps to reproduce the issue and attach screenshots, screen recordings, or logs. Mentioning that the issue was tested on other devices where it did not occur is also helpful for developers.

**If an app crashes on a physical device, what steps would you take to gather useful debugging information?**
If an app crashes on a physical device, I would try to reproduce the crash again while capturing logs. I would record the screen if possible, note the exact steps before the crash, and collect system logs from Logcat (Android) or Xcode/device console (iOS). I would also include device information, OS version, and app version in the bug report so developers can investigate the issue more effectively.