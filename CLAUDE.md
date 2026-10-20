# Disco new UI feedback: documentation rules

Feedback on the Disco admin redesign (`design-src/design.html`) is written as Markdown files in `feedback/`, with screenshots in `screenshots/`.

## Rules for every feedback file

1. **Every issue has a "Steps" line** showing how to reach it in the UI, as a path with arrows, e.g.
   `**Steps:** Campaigns → Discounts → Buy more, save more → Products → Only these`
   - Put it directly under the issue heading (or under the file title when the whole file is one issue).
   - Start from the top navigation and name each tab, step, button or dropdown option clicked, in order.
   - For a new discount, start with `Campaigns → Discounts → New discount → <template>`.
2. **Every issue has a marked screenshot.** Red boxes with numbered labels, and the issue text refers to them as "(marker N)".
   - **Mockups of a proposed design** are drawn on top of the prototype, with **green** boxes and "Proposed: …" labels, saved as `screenshots/mock-*.png`.
3. **Only write what the user asks for.** Explain or review in chat first; add to a file only when the user says so.
4. **Each file has an issue and a suggestion.**
5. **When a rule here changes, update the existing files to follow it.**
