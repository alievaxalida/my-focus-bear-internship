🏆 Milestone: Advanced Testing Techniques
🔍 Understanding Logs & Debugging Tools for QA
🎯 Goal
Learn how to capture and analyze logs, network requests, and errors to help diagnose issues.

❓ Why is this important?
Some bugs can’t be reproduced easily just by interacting with the app. Examining logs and debugging tools can reveal hidden errors, helping QA testers report issues more effectively and provide useful details for developers.

🔍 Research & Learn
**What are logs, and how do they help with debugging?**
Logs are records of events that happen inside the app. They show errors, warnings, and system messages. Logs help QA and developers understand what went wrong.
**How can you capture logs from a web app (browser DevTools)?**
Using Browser DevTools:
Open DevTools (F12)
Check the Console tab for errors
Check the Network tab for failed requests
Save screenshots or export logs if needed
**How can you capture logs from a mobile app (Android/iOS debugging tools)?**
*For Android:*
Use Logcat in Android Studio
*For iOS:*
Use Xcode console logs
These tools show crashes, errors, and system messages.
**What are some common error messages and log patterns testers should recognize?**
404 (Not Found) , 500 (Server Error) , Network timeout , Undefined or null errors , Authentication failed.
**How do network requests in browser DevTools help diagnose API failures?**
In DevTools Network tab:
Check request status codes
Review request payload
Review response data
Look for failed or slow requests

📝 Reflection
**If Focus Bear crashes on a user’s device but not on yours, how would you use logs to investigate?**
I would ask the user for logs, device details, and steps to reproduce. I would review console logs and network logs to identify errors.
**What are some useful log messages that should be included when reporting a bug?**
Error message
Status code
Time of issue
Steps to reproduce
Device and browser information
**If an API call returns an unexpected response, what steps would you take to analyze the issue?**
I would check the status code, compare the response with expected data, review request parameters, and share findings with developers.