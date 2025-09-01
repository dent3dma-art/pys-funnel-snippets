# Print Your Smile — Funnel Snippets (ClickFunnels 2.0)

This repo holds **paste-ready HTML/JS blocks** and minimal CSS you can drop into **ClickFunnels 2.0**.

## Paste map (where code goes in ClickFunnels)
- **Components (sticky bar, modal, accordions):** add an **Elements → Custom JS/HTML** block and paste the file from `/snippets/...`.
- **Global helpers (UTM capture, small utilities):** **Settings → Tracking Code**
  - **Header** for helpers that must run early (e.g., UTM capture).
  - **Footer** for behaviors that can wait for the DOM.

## Structure
- `/snippets/` – individual component markup.
- `/styles/funnel.css` – global namespaced styles.

## Available snippets
| File | Purpose | ClickFunnels placement |
| --- | --- | --- |
| `snippets/couture-hero.html` | Hero section with heading, subhead, CTAs and trust row. | Elements → Custom JS/HTML |

To apply the styling, add `styles/funnel.css` to **Settings → Tracking Code → Header**.
