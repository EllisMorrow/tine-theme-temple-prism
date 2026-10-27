# Local check summary

- Theme: Temple · Prism 0.1.1
- Manifest SHA-256: `21028796a3213c7c2f352b981a8ec89738f3ea33aa59dc80364091f27d575fa0`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 9.53:1, title 9.53:1, link 4.76:1, tag 4.76:1, code 8.69:1, mark 9.37:1, chosen 9.36:1.
  - Dark: body 14.4:1, title 14.4:1, link 15.55:1, tag 15.55:1, code 12.97:1, mark 10.99:1, chosen 10.71:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
