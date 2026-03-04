🏆 Milestone: Core Manual QA Skills
⏳ Deciding how long to spend on testing an issue
🎯 Goal
Learn how to determine the appropriate amount of time to spend testing an issue based on its complexity, impact, and risk.

❓ Why is this important?
Time management is a crucial skill in manual QA. Some issues require deep investigation, while others need quick validation. Knowing when to stop testing helps balance thoroughness with efficiency, ensuring Focus Bear is tested effectively without wasting time on low-priority tasks.

🔍 Research & Learn

**What factors influence how long you should test an issue? (Complexity, risk, priority, deadlines)**
The amount of time you spend testing an issue depends on several factors. The most important ones are severity, user impact, complexity of the feature, technical risk, and release deadlines. A critical issue that blocks users or affects security requires deeper investigation. A small visual issue may only need quick validation. If a release is close, testing time must be focused on high-risk areas. If the feature is complex or recently changed, it usually needs more testing time.

**What techniques can help prioritise testing efforts? (Risk-based testing, exploratory timeboxing)**
Risk-based testing is one technique that helps prioritize effort. This means focusing first on areas that could cause the biggest damage if they fail. Another useful technique is timeboxing in exploratory testing. For example, you decide to spend 20–30 minutes exploring a feature deeply, then stop and evaluate results. This prevents spending unlimited time on one area. Prioritizing core functionality before edge cases also helps manage time effectively.

**What is "good enough" testing, and how do you know when to stop?**
“Good enough” testing means reaching a reasonable level of confidence that the feature works correctly based on risk and context. It does not mean perfect or bug-free. You know it is time to stop when critical paths are tested, major risks are covered, no new serious issues are being found, and deadlines require moving forward. Testing should reduce risk to an acceptable level, not eliminate all possible risk.

**How do experienced QA testers balance depth vs. speed in real-world projects?**
Experienced QA testers balance depth and speed by adjusting their approach depending on the situation. For high-risk areas, they test deeply and explore edge cases. For low-risk areas, they validate quickly and move on. They also reuse past knowledge, focus on recent changes, and avoid retesting stable areas unnecessarily.

📝 Reflection

**How would you approach testing a small UI bug vs. a critical login issue?**
If I were testing a small UI bug, I would verify that the issue exists, check it on relevant devices or browsers, confirm whether it affects usability, and ensure no related layout problems exist. I would not spend excessive time unless it impacts important flows. For a critical login issue, I would test different user accounts, incorrect credentials, network conditions, different devices, session handling, and security aspects. I would also check related flows like password reset and account lockout.

**If you had limited time, how would you decide what to test first?**
If I had limited time, I would test core user flows first, especially features that generate revenue or block access, such as login, onboarding, and main functionality. Then I would test areas that recently changed. Low-impact visual issues would be tested last.

**What risks come with over-testing or under-testing an issue?**
Over-testing can waste time, delay releases, and reduce productivity by focusing too much on minor issues. Under-testing can allow serious bugs to reach production, damage user trust, and create more work later. The key is balancing risk, impact, and available time to test effectively and efficiently.