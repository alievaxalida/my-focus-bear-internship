🏆 Milestone: Advanced Testing Techniques
⚡ Testing Performance & Responsiveness
🎯 Goal
Learn how to identify performance issues and ensure Focus Bear responds quickly under different conditions.

❓ Why is this important?
Even if an app functions correctly, poor performance (slow loading, laggy interactions, crashes under load) can ruin the user experience. QA needs to test speed, responsiveness, and performance bottlenecks.

🔍 Research & Learn
**What are the key factors that impact app performance (CPU, memory, network, database queries, etc.)?**
CPU – If CPU is overloaded, the app becomes slow.
Memory (RAM) – Low memory can cause freezing or crashes.
Network speed – Slow internet makes loading slow.
Database queries – Slow queries delay data loading.
Large images or files – Increase loading time.
**How can QA testers measure app speed and responsiveness?**
QA can check: Page loading time, response time after clicking a button, time to log in or sync data, app behavior during scrolling or switching screens.
**What tools can be used for basic performance testing (e.g., Chrome DevTools, Lighthouse, mobile profiling tools)?**
Chrome DevTools – Check load time, network speed, CPU usage
Lighthouse – Get performance score and suggestions
Mobile profiling tools – Monitor memory and CPU usage on mobile
**What common performance issues appear in web apps vs. mobile apps?**
**Web apps:**
Slow page load
Large JavaScript files
Too many network requests
**Mobile apps:**
High battery usage
Memory leaks
App freezing or crashing
**How can QA test app behavior under high load or low resources (low RAM, slow CPU, unstable network)?**
Use browser tools to simulate slow internet
Test on older devices
Limit CPU or RAM (using dev tools)
Open many apps at the same time to simulate low memory

📝 Reflection
**How would you test Focus Bear’s performance on an older device or a slow internet connection?**
I would use a low-end device, reduce network speed in DevTools, and test core features like login, focus sessions, and syncing.
**If a user reports that the app feels slow, what steps would you take to investigate?**
I would try to reproduce the issue, check loading time, monitor CPU/memory usage, and review logs for errors.
**What performance optimizations could help Focus Bear run smoothly on low-end devices?**
Reduce animations
Optimize images and files
Improve database queries
Reduce background processes