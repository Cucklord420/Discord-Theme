# ClearVision v7 overrides (Vencord)

This repo hosts **only** my personal overrides (variables + extra CSS) and imports the upstream ClearVision v7 CSS.

## Use with Vencord (online theme)
1. Open Vencord settings → **Themes**
2. Add this file’s **RAW** GitHub URL as an online theme:
   - `https://raw.githubusercontent.com/<YOUR_GH_USER>/<REPO>/main/theme.css`

## Use with Vencord (local theme)
1. Download `theme.css`
2. Put it here:
   - `%appdata%\vencord\themes`
3. Enable it in Vencord → Themes

## Notes
- If Discord updates classnames, the watermark-hiding selector may stop working.
- Background images are currently hotlinked (Imgur). If you want them pinned, add them to an `assets/` folder and update URLs.

## License

New original contributions use [AGPL v3](LICENSE), subject to [LICENSE-SCOPE.md](LICENSE-SCOPE.md). The pre-existing `theme.css` remains under the Unlicense; imported ClearVision styles keep Apache-2.0. Previously granted permissions are preserved.
