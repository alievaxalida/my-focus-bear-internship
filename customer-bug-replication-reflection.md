🏆 Milestone: Reporting & Tracking Issues Effectively
🔍 Replicating Bugs Reported by Customers
🎯 Goal
Learn how to investigate and reproduce customer-reported bugs and determine when additional logging or debugging tools are needed.

❓ Why is this important?
Customers report real-world issues, but these bugs can be hard to reproduce without additional details. QA must learn how to investigate, ask the right questions, and sometimes push for more logging or debugging tools to capture the problem.

🔍 Research & Learn
**What steps should QA take when a customer reports a bug that can’t be easily reproduced?**
*When a bug cannot be reproduced:*
Carefully read the customer report
Try to reproduce using the same steps
Test on the same device/OS version
Check logs and error messages
Ask for more information if needed
Review recent releases/changes
Check if similar issues were reported before
*Do not immediately mark it as “Cannot Reproduce”.*
**What information should QA request from customer support to help diagnose an issue?**
*QA should ask customer support for:*
Device model
OS version
App version
Browser (if web app)
Steps to reproduce
Screenshots or screen recording
Exact error message
Time/date of issue
User ID (if allowed)
*More details = easier reproduction.*
**How can logs, screenshots, and error messages help with bug reproduction?**
Logs:
Show hidden system errors
Show API failures
Show crash stack traces

Screenshots:
Show UI state
Show error messages
Show incorrect behavior

Error messages:
Help identify backend vs frontend issue
Show status codes (404, 500, 401)
*These details reduce guessing.*
**When should QA recommend adding more logging to capture hard-to-reproduce issues?**
*QA should suggest more logging when:*
The issue happens randomly
The issue happens only in production
There is no clear error message
Crashes happen without visible reason
User-specific data may be involved

*Useful logs:*
API request/response logs
Authentication logs
State changes
Crash stack traces
Feature flag information
**How do other teams handle "Cannot Reproduce" customer bugs effectively?**
Good teams:
Label as “Need More Info” instead of closing
Contact customer for more details
Monitor logs for similar patterns
Keep ticket open temporarily
Track frequency in analytics
*Closing too early may hide real problems.*

📝 Reflection
**If a customer reports a crash but you can’t reproduce it, what are your next steps?**
*My next steps:*
Ask for device + OS + app version
Ask for steps and screen recording
Check crash logs
Try on similar device
Check if recent update caused it
Check analytics for similar crashes
*If still not reproducible, mark as “Need More Info”.*
**When should you ask developers to add more logging, and what kind of logs would help?**
*I would ask when:*
Crash happens only in production
Only some users are affected
There is no clear error in logs
The issue depends on user data

*Helpful logs:*
Detailed error messages
API response details
User session info (non-sensitive)
Device/environment information
**What are some common patterns in bugs that only occur for some users but not others?**
Older OS versions
Slow internet connection
Corrupted local storage/cache
Different screen sizes
Feature flags enabled for some users
Timezone differences
Language/locale issues
Large user data sets
These bugs are usually environment-specific