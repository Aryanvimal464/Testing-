# Testing-
QA Software Testing Project | Manual Testing, Test Case Design, Bug Reporting, Selenium, Python &amp; Pytest Automation
QA practice log: finding & fixing 16 bugs across two apps 🐛
As part of sharpening my testing skills, I worked through two intentionally buggy web apps — a task manager and a shopping cart app — and ran a full QA cycle on each: exploratory testing, documenting bugs, root-causing them, and verifying fixes.
A few bugs that stood out:
📋 Task Manager
• Delete button removed the wrong task once a search filter was applied (classic index-vs-ID bug)
• "Tasks remaining" counter was showing completed tasks instead of pending ones
• "Clear completed" wiped the entire list, not just completed items
🛒 Shopping Cart
• Coupon code could be applied repeatedly, stacking the discount each time
• Tax was calculated on the pre-discount subtotal instead of the post-discount amount
• "Clear cart" only cleared the UI — the underlying data stayed intact
The biggest lesson: most of these weren't obvious from a glance at the UI. They only surfaced through deliberate, methodical testing — changing state, combining actions (like search + delete), and checking the numbers by hand instead of trusting the screen.
