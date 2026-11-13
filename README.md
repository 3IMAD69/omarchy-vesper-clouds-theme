# Vesper Clouds

A warm-monochrome dark theme for [Omarchy](https://omarchy.org), built on the
[Vesper](https://github.com/raunofreiberg/vesper) palette and inspired by
[advtszn's macOS rice](https://github.com/advtszn/dotfiles).

![Vesper Clouds preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/3IMAD69/omarchy-vesper-clouds-theme
```

## Palette

| Role       | Color     |
| ---------- | --------- |
| Background | `#101010` |
| Foreground | `#dadada` |
| Accent     | `#ffc799` |
| Mint       | `#99ffe4` |
| Teal       | `#50b5aa` |
| Red        | `#ff8080` |
| Grey       | `#a0a0a0` |
| Dim        | `#505050` |

Window borders are grey on the focused window and dim on the rest, in place of
the usual accent-colored border.

## Wallpapers

Nine wallpapers ship with the theme. Cycle through them with Super + Ctrl + Space.

<table>
  <tr>
    <td><img alt="Silhouette above the clouds" src="https://github.com/user-attachments/assets/f87a0efd-3666-490b-8439-44988602d7a9" /></td>
    <td><img alt="Cave explorer under starlight" src="https://github.com/user-attachments/assets/4f2e75f8-a8ba-4b3b-94fb-d593bb586cb9" /></td>
  </tr>
  <tr>
    <td><img alt="Misty garden" src="https://github.com/user-attachments/assets/7b1bc753-b069-4f41-a012-db4c0e0bdd02" /></td>
    <td><img alt="Bonsai and prism" src="https://github.com/user-attachments/assets/8c36f2ff-bf61-48a0-8684-62578989c4aa" /></td>
  </tr>
  <tr>
    <td><img alt="Glowing helix garden" src="https://github.com/user-attachments/assets/42d49e13-0b02-4481-b36a-a1dae783cbb0" /></td>
    <td><img alt="Cosmic laptop" src="https://github.com/user-attachments/assets/f0ccc653-f6e8-45e6-b14e-999c0545bf36" /></td>
  </tr>
  <tr>
    <td><img alt="Prism glass flowers" src="https://github.com/user-attachments/assets/7748bbc7-b8bb-43f2-b03b-7a56e3b207ca" /></td>
    <td><img alt="Glass book garden" src="https://github.com/user-attachments/assets/4e80310a-687f-444a-b6c1-c4b4776671e8" /></td>
  </tr>
  <tr>
    <td><img alt="Light streaks" src="https://github.com/user-attachments/assets/55680647-584c-402c-a5fe-ff0f3296ce73" /></td>
    <td></td>
  </tr>
</table>

## Recommended

For the frosted-glass look in the preview, turn on glassy windows:

```bash
omarchy hyprland window transparency glassy
```

Or use Appearance > Windows > Window Opacity in the Omarchy menu.

VS Code, VSCodium and Cursor get the real Vesper editor colors automatically:
the theme ships Vesper's color theme as `vscode-theme.json`, which Omarchy
loads as its local theme, with no extension to install.

Neovim gets colors generated from the palette. For the real thing, install
[vesper.nvim](https://github.com/datsfilipe/vesper.nvim).

## Credits

- Palette and VS Code theme: [Vesper](https://github.com/raunofreiberg/vesper) by Rauno Freiberg,
  MIT licensed (see `LICENSE-vesper.txt`)
- Wallpapers: from Perplexity's PPLX wallpaper series, via
  [advtszn/dotfiles](https://github.com/advtszn/dotfiles). All rights belong to their owners.
