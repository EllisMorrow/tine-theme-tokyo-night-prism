<div align="center">

# Tokyo Night · Prism

**Blue lanterns drift across the day; indigo settles over the city at night. Let the last train carry each thought home.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-7aa2f7?labelColor=1a1b26)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-7aa2f7?labelColor=1a1b26)
[![License: Apache-2.0](https://img.shields.io/badge/license-Apache--2.0-7aa2f7?labelColor=1a1b26)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-tokyo-night-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-tokyo-night-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-tokyo-night-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Tokyo Night Day and Night share one Tine theme: cool blue-gray light and a deep indigo city after dark, with clear blue links and quiet green accents.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![Tokyo Night · Prism in Tine dark mode](docs/tokyo-night-dark.png)

### Light mode

![Tokyo Night · Prism in Tine light mode](docs/tokyo-night-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-tokyo-night-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#E1E2E7` | `#1A1B26` |
| Sidebar | `#D0D5E3` | `#16161E` |
| Body | `#3760BF` | `#C0CAF5` |
| Heading | `#3760BF` | `#C0CAF5` |
| Accent | `#2E7DE9` | `#7AA2F7` |
| Links | `#245EB0` | `#7AA2F7` |
| Tags | `#4D682F` | `#9ECE6A` |
| Mark background | `#EEE1C8` | `#41425A` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Tokyo Night Day / Night](https://github.com/folke/tokyonight.nvim) at `545d72cde6400835d895160ecb5853874fd5156d`, under Apache-2.0; see [LICENSE](LICENSE). The dark mode follows Tokyo Night Night, and the light mode uses the official upstream Day style. The original Codex reference is dark; Day is an upstream variant, not claimed as a Codex-native light preset. The source project is Apache-2.0, and its license and attribution are retained.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-tokyo-night-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.

