# GitHub themes for Pi Pocket

GitHub's looks for [Pi Pocket](https://github.com/TannerMidd/pi-pocket), ported from the
[GitHub Theme for VS Code](https://github.com/primer/github-vscode-theme) (MIT, © GitHub, Inc.). All nine VS Code themes
are here, as five theme folders:

| Folder | Themes | Colors |
|---|---|---|
| `github/` | GitHub (the default pair) | GitHub Dark Default, GitHub Light Default |
| `github-dimmed/` | GitHub Dark Dimmed | GitHub Dark Dimmed |
| `github-high-contrast/` | GitHub High Contrast | GitHub Dark High Contrast, GitHub Light High Contrast |
| `github-colorblind/` | GitHub Colorblind | GitHub Dark Colorblind, GitHub Light Colorblind |
| `github-classic/` | GitHub Classic | GitHub's first themes for VS Code: GitHub Dark, GitHub Light |

Each folder is one theme: `theme.json`, `theme.css` (GitHub's greys, corners, font stacks, syntax palette, reading
width, and its comment-shaped turns), and `colors.toml` — with `colors-light.toml` beside it when the theme brings a
light half. A theme with a pair shows in Appearance → Colors three ways: the pair, which follows the system, and each
half alone.

## Install

Owner: Menu → Extensions → Discover, set the index to `MasFana/OMP`, refresh, install the ones you want. Installation
applies nothing: choose one in **Appearance → Theme**, as each person does in their own browser.

By hand: copy the folders you want into `~/.pi-pocket/themes/`.

## What they change

Tokens only, plus three parts: a turn drawn as GitHub's bordered comment (`prompt`), a secondary button's hairline
(`.button`), and the open session's grey fill (`session-button`). The accent and the status colors follow Appearance's
Colors, so another palette keeps the layout and the type; each theme's own greys, syntax colors, and primary-button
green stay pinned, as they are on GitHub itself.

`themeApi` 1, `minPocket` 0.14.0: no token newer than the first release with themes.

Quiet text is at 4.5:1 or more on every ground. Where GitHub's own muted grey is dimmer than that (Dark Dimmed's
`#768390` on `#22272e`, for one), `--muted` and `--faint` are mixed from the theme's text color instead; each
`theme.css` names the value and its measured ratio.

## License

MIT. See [LICENSE](LICENSE); the palette and syntax colors come from `primer/github-vscode-theme`.