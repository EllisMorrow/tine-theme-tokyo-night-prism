# Adaptation notes

The Codex reference is Tokyo Night in dark mode. This package uses its official Night variant and pairs the official upstream Day style for Tine light mode; Day is not described as a Codex-native light preset. The source is release v4.14.1 at the pinned commit, under Apache-2.0. The package preserves the license and identifies the changed role mapping.

## Sources

- Night palette: https://github.com/folke/tokyonight.nvim/blob/545d72cde6400835d895160ecb5853874fd5156d/lua/tokyonight/colors/night.lua
- shared palette: https://github.com/folke/tokyonight.nvim/blob/545d72cde6400835d895160ecb5853874fd5156d/lua/tokyonight/colors/storm.lua
- Day palette: https://github.com/folke/tokyonight.nvim/blob/545d72cde6400835d895160ecb5853874fd5156d/extras/alacritty/tokyonight_day.toml
- license: https://github.com/folke/tokyonight.nvim/blob/545d72cde6400835d895160ecb5853874fd5156d/LICENSE

## Mapping decisions

- Dark canvas, foreground, blue, green and yellow use official Night palette values (#1A1B26, #C0CAF5, #7AA2F7, #9ECE6A, #E0AF68).
- Light mode uses the Day palette's #E1E2E7 canvas, #3760BF foreground and official blue/green families. Light link and tag roles are deepened to #245EB0 and #4D682F; secondary text uses #4E619D.
- The light inline-code and chosen-block backgrounds use the canvas color to preserve text contrast. Tiered surfaces, selection and marks are Tine adaptations. Storm and Moon are not included.
- This local adaptation modifies original color role presentation. No Codex code, logo or bundled assets are included.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
