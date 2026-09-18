# Usage history responsive layout

Review screenshots for `fix/mobile-usage-table` (1a1b6c4c).
Rendered from the actual usage component, its Alpine behavior and admin styles
in an isolated preview. All model names, dates and usage numbers are synthetic;
no live server data, credentials, account identifiers or browser chrome appear.

- Before / after phone viewport: 390 × 844 CSS pixels.
- Tablet viewport: 768 × 1000.
- Desktop viewport: 1440 × 1000.
- Tablet and desktop captures show the usage component bounds.

The screenshot branch is separate from the code PR.

Additional full-viewport desktop evidence (no cropping):
- `desktop-1024.png`: 1024 × 768, dark theme.
- `desktop-1440.png`: 1440 × 900, dark theme.
- `desktop-1920.png`: 1920 × 1080, light theme.

At each size all seven columns fit without horizontal scrolling, the page has
no horizontal overflow, and the two sample rows are at most 65 CSS pixels tall.
