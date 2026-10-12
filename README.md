# uLatte

A personal take on [Catppuccin Latte](https://github.com/catppuccin/zed) for
[Zed](https://zed.dev), with a unified background for a seamless interface.

The editor, panels, title bar, and status bar share the same background color,
giving the workspace a consistent look while keeping Latte's pastel palette.
Currently available in light mode.

<!-- Add a screenshot of the theme in Zed at assets/preview.png, then uncomment:
![uLatte theme in Zed](assets/preview.png)
-->

## Installation

### Local theme (macOS and Linux)

Download this repository, then run the following commands from its root:

```sh
mkdir -p ~/.config/zed/themes
cp themes/ulatte.json ~/.config/zed/themes/ulatte.json
```

On Windows, copy `themes/ulatte.json` into
`%USERPROFILE%\AppData\Roaming\Zed\themes\` instead.

Restart Zed, open the command palette, run `theme selector: toggle`, and select
**uLatte**.

### Development extension

1. Download or clone this repository.
2. Open the command palette in Zed and run `zed: install dev extension`.
3. Select the repository root (the directory containing `extension.toml`).
4. Run `theme selector: toggle` and select **uLatte**.

The GitHub repository can be installed using either method above. Publication
in the Zed extension catalog is a separate step.

## Credits and license

Based on [Catppuccin for Zed](https://github.com/catppuccin/zed), specifically
the Latte variant. uLatte is an independent customization and is not an
official Catppuccin theme.

Distributed under the [MIT License](LICENSE), with the original Catppuccin
copyright notice preserved.
