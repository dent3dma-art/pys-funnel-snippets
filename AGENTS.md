Goals
- Produce paste-ready HTML+JS snippets for ClickFunnels 2.0 “Custom JS/HTML”.
- Minimal, namespaced CSS (.pys-*). No external CDNs.

Deliverables
1) File in /snippets with HTML + inline <script> if needed.
2) Any CSS in /styles/funnel.css (namespaced).
3) utils.js helpers if needed.
4) README update with EXACT ClickFunnels placement:
   - Component markup → Elements > Custom JS/HTML
   - Global helpers → Settings > Tracking Code (Header or Footer)

Validation
- Temporary HTML harness to demo behavior.
- If UTM capture requested, simulate ?utm_source=ig and show persistence in localStorage.
- Provide clear diffs.

Constraints
- Vanilla JS. Accessible (aria / focus). Keep CSS small.
