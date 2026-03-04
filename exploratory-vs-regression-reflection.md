🏆 Milestone: Core Manual QA Skills
🔀 Exploratory Testing vs. Regression Testing
🎯 Goal
Understand the differences between exploratory testing and regression testing, and when to use each approach.

❓ Why is this important?
Both exploratory testing and regression testing play a crucial role in manual QA:

Exploratory testing helps find unexpected issues by thinking like a user rather than following a predefined script.
Regression testing ensures that previously working features still function correctly after changes.
A good QA tester knows when to explore freely vs. when to follow structured test cases to maintain stability.

🔍 Research & Learn

**What is exploratory testing, and how does it differ from scripted testing?**
Exploratory testing is a testing approach where the tester actively explores the application without following a strict predefined test script. The tester learns, designs, and executes tests at the same time. It focuses on curiosity, risk areas, edge cases, and real user behavior. Scripted testing, on the other hand, follows predefined test cases with specific steps and expected results. Scripted testing is structured and repeatable, while exploratory testing is flexible and creative.

**What is regression testing, and why is it important in software development?**
Regression testing is the process of re-testing previously working features after changes, such as new features, bug fixes, or updates. Its goal is to ensure that existing functionality still works correctly and that new changes did not break something else. Regression testing is important because even small code changes can unintentionally affect other parts of the system.

**When should exploratory testing be used instead of regression testing (or vice versa)?**
Exploratory testing should be used when testing new features, unclear requirements, complex workflows, high-risk areas, or when time is limited and quick feedback is needed. Regression testing should be used before releases, after bug fixes, and after major changes to ensure stability. Both approaches are important and should complement each other rather than replace each other.

**How can exploratory testing reveal bugs that scripted tests might miss?**
Exploratory testing can reveal bugs that scripted tests might miss because it encourages testers to think beyond predefined paths. Testers may try unusual inputs, interrupt processes, switch between screens quickly, test with unstable internet, or behave like a real distracted user. Scripted tests only check what is written in them, while exploratory testing can uncover unexpected behaviors.

📝 Reflection

**Why is exploratory testing particularly useful for an app like Focus Bear?**
Exploratory testing is particularly useful for an app like Focus Bear because it focuses on user experience, behavior patterns, and edge cases. Since Focus Bear is used by people with ADHD and other focus-related challenges, usability, clarity, and flow are very important. Exploratory testing can help identify confusing steps, distractions, or unexpected interruptions that structured tests might not catch.

**What risks come with relying too much on exploratory testing vs. only doing regression testing?**
If a team relies too much on exploratory testing, there is a risk of missing consistent regression coverage, forgetting important scenarios, or having inconsistent results between testers. If a team only does regression testing, they may miss new edge cases, usability issues, or unexpected interactions between features. A balanced approach is the safest strategy.

**How would you document and report issues found during an exploratory testing session?**
To document issues found during exploratory testing, I would clearly describe the context of the session, what feature was being explored, what actions were performed, and what unexpected behavior occurred. I would include steps to reproduce if possible, expected and actual results, environment details, and attach screenshots or logs. Even though the session was exploratory, the bug report should still be structured and clear so developers can reproduce the issue.