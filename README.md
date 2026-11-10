# GitHub theme for Pi Pocket

GitHub's look for [Pi Pocket](https://github.com/TannerMidd/pi-pocket), ported from the
[GitHub Theme for VS Code](https://github.com/primer/github-vscode-theme) (MIT, © GitHub, Inc.).

The theme is the `github/` folder: GitHub Dark Default in `colors.toml`, GitHub Light Default in `colors-light.toml`
as its light half, and the look — flat surfaces on 1px lines, 6px corners, the Primer blue accent, the green primary
button, GitHub's syntax palette, GitHub's font stacks, and GitHub's reading width — in `theme.css`.

## Install

Owner: Menu → Extensions → Discover, set the index to `MasFana/OMP`, refresh, install **GitHub**. Installation
applies nothing: choose **GitHub** in Appearance → Theme, as each person does in their own browser. The pair and each
half alone show under Colors too.

By hand: copy `github/` into `~/.pi-pocket/themes/`.

## What it changes

Tokens only, plus three parts: a turn drawn as GitHub's bordered comment (`prompt`), a secondary button's hairline
(`.button`), and the open session's grey fill (`session-button`). `colors.toml` and `colors-light.toml` carry the
palettes, so Appearance's Colors can put GitHub's look over other colors; the accent and the status colors follow them,
while GitHub's neutrals, syntax colors, and primary-button green stay pinned, as they are on GitHub itself.

`themeApi` 1, `minPocket` 0.14.0: no token newer than the first release with themes.

## Not ported

The extension's other variants — Dark Dimmed, Dark and Light High Contrast, Dark and Light Colorblind, and the classic
Light and Dark — are palettes, not layouts. Each becomes a colors-only theme folder (`<id>/colors.toml`, no
`theme.json`) that Appearance lists under Colors next to this theme; add one when it is wanted.

## License

MIT. See [LICENSE](LICENSE); the palette and syntax colors come from `primer/github-vscode-theme`.