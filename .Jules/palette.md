## 2024-05-22 - Duplicate IDs and Invisible Links
**Learning:** Duplicate IDs (like `id="name"`) can silently break accessibility and form functionality, even if the page looks fine. Icon-only links (social media) are completely invisible to screen readers without `aria-label`.
**Action:** Always scan for duplicate IDs (`grep`) and verify that every interactive element has an accessible name, especially in footers where they are often forgotten.
