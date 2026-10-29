# Disco new UI feedback: documentation rules

The design being reviewed is `design-src/Disco Plugin Re Design v2.html`. Feedback on it goes in `feedback-v2/` as Markdown files, with screenshots in `screenshots-v2/`.

`feedback/` and `screenshots/` hold notes 01–57 on the first design. Leave them as they are. The rules below apply to both.

**v2 notes describe v2 only.** Don't compare with the previous design (no "before / after", "was", "used to"). Every screenshot in a v2 note is taken from the v2 design and saved in `screenshots-v2/`.

## Rules for every feedback file

1. **Every issue has a "Steps" line** showing how to reach it in the UI, as a path with arrows, e.g.
   `**Steps:** Campaigns → Discounts → Buy more, save more → Products → Only these`
   - Put it directly under the issue heading (or under the file title when the whole file is one issue).
   - Start from the top navigation and name each tab, step, button or dropdown option clicked, in order.
   - For a new discount, start with `Campaigns → Discounts → New discount → <template>`.
   - **Follow the steps yourself.** Reproduce the issue in the design by clicking through exactly the path in the Steps line, and take the screenshot at the end of that path. The Steps line must match what the screenshot shows, including the options picked (e.g. `→ at % off`).
   - Every document follows this, including mockups (their Steps line ends with `(proposed)`) and sections added later to an existing file.
2. **Every issue has a marked screenshot.** Red boxes with numbered labels, and the issue text refers to them as "(marker N)".
   - **Mockups of a proposed design** are drawn on top of the prototype, with **green** boxes and "Proposed: …" labels, saved as `mock-*.png` in the screenshots folder.
3. **Only write what the user asks for.** Explain or review in chat first; add to a file only when the user says so.
4. **Each file has an issue and a suggestion.**
5. **When a rule here changes, update the existing files to follow it.**
