🏆 Milestone: Advanced Testing Techniques
💥 Testing Error Handling & Edge Cases
🎯 Goal
Learn how to test Focus Bear’s error handling, boundary cases, and unexpected inputs to uncover hidden issues.

❓ Why is this important?
Users don’t always interact with software the way developers expect. Good QA testers think about unusual, extreme, and unexpected scenarios to find potential weaknesses in the app’s stability and usability.

🔍 Research & Learn
**What is boundary value analysis, and why is it useful for testing?**
Boundary value analysis means testing values at the minimum, maximum, and limits of input.
For example, if the password limit is 8–20 characters, test 7, 8, 20, and 21 characters.
It helps find errors at the edges of allowed values.
**What are common edge cases that testers should check in forms, authentication, and app flows?**
Empty fields
Very long text input
Special characters
Wrong password many times
Expired session
Clicking submit multiple times
Using back button during a process
**How should QA test network failures, offline mode, and slow connections?**
Turn off internet during an action
Simulate slow network in browser tools
Switch between online and offline mode
Check if the app shows a clear message and does not crash.
**What happens when an app encounters an unexpected input or invalid data?**
The app should not crash. It should show a clear error message and guide the user to fix the problem.
**How can error messages be tested to ensure they are helpful and user-friendly?**
Check if the message is clear and simple
Avoid technical words
Make sure it explains what to do next
Confirm it appears at the right time

📝 Reflection
**What edge cases could break Focus Bear’s onboarding flow?**
User closes app during onboarding
No internet connection
Skipping required steps
Entering invalid email
Very slow device
**If the app fails midway through a critical action, how should it behave?**
It should save progress if possible, show a clear error message, and allow the user to retry safely.
**How would you test for network instability and ensure Focus Bear handles it gracefully?**
I would simulate slow internet, disconnect during actions, and check if the app shows helpful messages and keeps data safe without crashing.