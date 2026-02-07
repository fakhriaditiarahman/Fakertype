## 2024-05-22 - Duplicate IDs and Missing Labels in Static Templates
**Learning:** Static HTML templates often reuse IDs like `name` or `email` across different forms (e.g., generator vs. contact), causing accessibility violations and potential JS conflicts. They also frequently rely on placeholders instead of labels.
**Action:** Always scan for duplicate IDs (`grep -r "id=\"name\""`) and missing `aria-label` or `for` attributes in form inputs when auditing static sites.
