🏆 Milestone: Reporting & Tracking Issues Effectively
📊 Understanding Release Cycles & Version Control
🎯 Goal
Learn how QA fits into software release cycles and how version control (Git) impacts testing.

❓ Why is this important?
QA needs to know when and what to test during development. Understanding release cycles helps testers plan their work effectively, while knowing version control basics helps them track issues related to different branches or releases.

🔍 Research & Learn
**What are the typical stages in a software release cycle (development, testing, staging, production)?**
Typical stages in a software release cycle:
Development – Developers write new code or fix bugs.
Testing – QA tests new features, bug fixes, and regression areas.
Staging – A pre-production environment where the release is tested as close to real conditions as possible.
Production – The release goes live to all users. QA monitors for issues after deployment.
**How does QA work differ between a feature release and a hotfix?**
Feature release – QA tests new features, integration, regression, and performance. Testing is planned and can take more time.

Hotfix – QA focuses only on the urgent fix and critical areas affected by the change. Testing must be fast and precise to avoid delays.
**What is version control (Git), and how does it impact testing?**
Git is a system for tracking code changes and managing multiple versions. QA needs to know which branch or version is being tested to ensure bugs are tested in the correct environment. Testing the wrong branch can lead to false results.
**What are Git branches, and why do testers need to be aware of them?**
Branches allow developers to work on features or fixes separately. QA should know which branch is being tested to avoid confusion between versions and ensure the reported bugs match the correct code.
**How does QA handle rollbacks if a release causes major issues?**
If a release causes major issues, QA helps verify the rollback. They re-test the previous stable version to confirm that the app is working correctly and that no new issues were introduced during the rollback.

📝 Reflection
**How would you adjust your testing strategy for a major feature release vs. a small bug fix?**
For a major feature release, I would test extensively, including new functionality, integrations, and regression areas. For a small bug fix, I would focus only on the affected area and critical flows.
**If a developer says, “This bug only happens on an older branch,” how would you handle it?**
I would reproduce the bug on that branch, communicate with developers about the difference, and test any fixes in the correct branch before moving to production.
**Why is it important for testers to know which version of the app they are testing?**
Testing the correct version ensures that bugs are reported accurately, avoids confusion with old code, and helps developers fix the right issues.