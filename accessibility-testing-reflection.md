🏆 Milestone: Advanced Testing Techniques
🎨 How to Test Accessibility
🎯 Goal
Understand how to test for accessibility (a11y) and ensure Focus Bear is usable for people with disabilities.

❓ Why is this important?
A significant portion of Focus Bear’s users have ADHD and Autism, and many may also have dyslexia, visual impairments, or motor challenges. Accessibility testing ensures that the app is inclusive and easy to use for everyone.

🔍 Research & Learn
**What is WCAG (Web Content Accessibility Guidelines), and what are its key principles?**
WCAG (Web Content Accessibility Guidelines) are international rules for making websites accessible.
They are based on 4 main principles:
Perceivable – Users can see or hear content clearly.
Operable – Users can use the interface (keyboard, mouse, screen reader).
Understandable – Content is clear and simple.
Robust – The app works with assistive technologies.
**How do screen readers (e.g., NVDA, VoiceOver, TalkBack) work, and how can QA test with them?**
Screen readers read text aloud and describe buttons, links, and images.
Examples: NVDA (Windows), VoiceOver (Mac/iPhone), TalkBack (Android).

QA can test by:
Turning on a screen reader
Navigating without looking at the screen
Checking if labels and buttons are read correctly
**What are some common accessibility issues in apps and websites?**
Missing alt text for images
Low color contrast
Small font size
Buttons without clear labels
Not usable with keyboard
**How can you test keyboard navigation and focus management?**
Use only the Tab key to move through the app
Check if focus is visible (highlighted)
Ensure logical order of navigation
Make sure modals and popups trap focus correctly
**What tools can help automate basic accessibility checks?**
Lighthouse (Accessibility report)
Axe DevTools
WAVE browser extension

📝 Reflection
**How would you test if Focus Bear is usable with a screen reader?**
I would turn on a screen reader and navigate through onboarding, settings, and focus sessions. I would check if buttons, instructions, and error messages are read clearly.
**What accessibility barriers could affect someone with ADHD or Autism using the app?**
Too many distractions or animations
Complex navigation
Too much text at once
Unclear instructions
Sudden changes or popups
**If a developer says "this doesn't impact most users", how would you advocate for fixing an accessibility issue?**
I would explain that accessibility helps many users, including those with disabilities. It improves usability for everyone and supports inclusive design. Even small issues can create big barriers for some users.