🏆 Milestone: Reporting & Tracking Issues Effectively
🔍 Handling Hard-to-Reproduce Bugs
🎯 Goal
Learn techniques for investigating and documenting intermittent or hard-to-reproduce bugs.

❓ Why is this important?
Some bugs only happen under specific conditions (e.g., only after 10 minutes of use, on certain devices, or with unstable internet). Testers need strategies to capture enough information so developers can debug them effectively.

🔍 Research & Learn
**What are common causes of intermittent bugs in software?**
Common causes of intermittent bugs include race conditions, timing issues, unstable internet connections, memory leaks, background processes, device performance differences, corrupted cache or local storage, and environment-specific problems such as certain OS versions or feature flags. These bugs often depend on specific combinations of data, timing, or user behavior.

**What tools can help capture debug logs, network requests, and app crashes?**
Tools that help capture debug logs and crashes include browser DevTools (Console and Network tabs), mobile logs like Android Logcat and iOS device logs, crash reporting tools such as Firebase Crashlytics, and screen recording tools. Network monitoring tools can help detect failed API calls, slow responses, or timeouts. Performance monitoring tools can also help identify memory or CPU issues.

**What strategies can testers use to make flaky bugs more reproducible?**
To make flaky bugs more reproducible, testers can repeat the same steps multiple times, test under different network conditions (slow, offline, switching between Wi-Fi and mobile data), leave the app running for a longer period, test on low-battery mode, clear cache and test again, or use the same account and data as the affected user. It also helps to isolate variables by changing one condition at a time.

**How do teams handle "Cannot Reproduce" issues?**
Teams usually handle “Cannot Reproduce” issues by marking them as “Need More Info” instead of closing them immediately. They may request logs, environment details, or screen recordings from users. Some teams monitor analytics or crash reports to see if the issue appears again. If similar reports increase, the issue may be reopened and prioritized.

📝 Reflection
**How would you report a bug that only happens occasionally?**
If a bug happens only occasionally, I would clearly state that it is intermittent in the report. I would describe how often it occurs, under what conditions it happened, and how many times I tried to reproduce it. I would include logs, timestamps, device information, and screen recordings if possible. Even if it cannot be reproduced every time, detailed evidence helps developers investigate.

**If a developer marks a bug as "Not reproducible", what’s your next step?**
If a developer marks a bug as “Not reproducible,” my next step would be to review the steps again and confirm the environment details. I would share additional evidence such as logs or recordings and ask which environment they tested on. If needed, I would try to reproduce it on different devices or OS versions. The goal is to compare conditions and find differences.

**What tools or techniques can help capture extra details for unpredictable bugs?**
To capture extra details for unpredictable bugs, useful techniques include enabling detailed logging, using crash reporting tools, recording network traffic, keeping screen recording on during testing, testing with different user accounts, and checking analytics for patterns. Collecting as much context as possible increases the chance of identifying the root cause.