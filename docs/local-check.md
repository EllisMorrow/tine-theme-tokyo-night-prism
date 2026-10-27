# Local check summary

- Theme: Tokyo Night · Prism 0.1.1
- Manifest SHA-256: `ed410579498f4e4081dfb9774b944b0170c905a2948df0b30cbcb23ffa45b0e3`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 4.52:1, title 4.52:1, link 4.91:1, tag 4.87:1, code 4.52:1, mark 4.61:1, chosen 4.52:1.
  - Dark: body 10.59:1, title 10.59:1, link 6.79:1, tag 9.35:1, code 8.32:1, mark 4.88:1, chosen 8.32:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
