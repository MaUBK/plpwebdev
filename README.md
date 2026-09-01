# Budget Tracker — Week 2 Assignment

This repository contains the Week 2 upgrade to the Budget Tracker project. Files included:

- `index.html` — main page with the expense form, expense table, embedded video, and collapsible help.
- `style.css` — styles for layout, the expenses table, form states, and interactive effects.

What I built and why:

- Expense Table: Replaced the "No expenses yet" placeholder with a semantic HTML table using `<table>`, `<thead>`, and `<tbody>`. It contains 5 sample rows for demo purposes.
- Form Upgrade: Wrapped inputs inside a `<form id="expense-form">`. Added a `<select id="expense-category">` with 5 options (Food, Transport, Rent, Entertainment, Other). Each input has a clear `id` for future JavaScript integration.
- Multimedia: Added a small logo image near the main heading and embedded a YouTube video via `<iframe>`.
- Interactive Element: Added a collapsible `details`/`summary` section explaining how to use the tracker.
- CSS Selectors & Effects: Implemented advanced selectors and visible styles: a descendant selector (`#your-expenses td`), a direct child selector (`.card > h2`), position pseudo-class (`tr:nth-child(even)`), negation pseudo-class (`input:not([type="submit"])`), and focus state (`input:focus`). Also added row hover effects and `cursor: pointer` for the button.

