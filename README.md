# ClearVision v7 overrides (Vencord)

This repo hosts **only** my personal overrides (variables + extra CSS) and imports the upstream ClearVision v7 CSS.

## Use with Vencord (online theme)
1. Open Vencord settings → **Themes**
2. Add this file’s **RAW** GitHub URL as an online theme:
   - `https://raw.githubusercontent.com/Cucklord420/Discord-Theme/main/theme.css`

## Use with Vencord (local theme)
1. Download `theme.css`
2. Put it here:
   - `%appdata%\vencord\themes`
3. Enable it in Vencord → Themes

## Notes
- If Discord updates classnames, the watermark-hiding selector may stop working.
- The four background images remain hotlinked from Imgur. Their availability and redistribution rights are recorded below; no image files are bundled.

## External dependency record (checked 2026-11-22)

- ClearVision's `main.css` and `vencord.css` imports are pinned to deployment commit [`f4dababa725309de554ad1aa46291003406a3d1e`](https://github.com/ClearVision/ClearVision-v7/commit/f4dababa725309de554ad1aa46291003406a3d1e) on the upstream `gh-pages` branch. Its deployment message identifies source commit [`d36064149577a541b5e66de0b471c5c29128996b`](https://github.com/ClearVision/ClearVision-v7/commit/d36064149577a541b5e66de0b471c5c29128996b). On the check date, both pinned files matched the currently served ClearVision URLs byte-for-byte: `main.css` SHA-256 `4dcc81f02543bfb9d65466d1b8ecd7165ded7c9cd4d5802f058a35b9030ada0f`; `vencord.css` SHA-256 `128da4bc86a2cf8e6ffc4af61700ae4a0008e87f87e1e3d124787ad125e39437`. ClearVision's source license is [Apache-2.0](https://github.com/ClearVision/ClearVision-v7/blob/d36064149577a541b5e66de0b471c5c29128996b/LICENSE). The CSS remains an external import, not a local cache, so loading it still requires network access to GitHub Raw; there is no guaranteed offline ClearVision fallback.
- The four Imgur references were checked with HTTP `HEAD`; each returned `200 image/jpeg`: [app wallpaper](https://i.imgur.com/XSOBwhH.jpg), [user popout](https://i.imgur.com/Vba2eQh.jpg), [user modal](https://i.imgur.com/gGlA6Od.jpg), and [home icon](https://i.imgur.com/mg6Y8LT.jpg). No image was downloaded or bundled, and redistribution rights were not verified. The images remain live dependencies; if Imgur is unavailable, the corresponding image may be missing. No offline replacement is provided.
- The ClearVision CSS bytes are unchanged from the live version observed on the check date; only their URLs are pinned. Actual Vencord loading, visual contrast, overlays, settings scrolling, and offline appearance still need a client smoke test; parser validation does not establish those behaviors.

## License

New original contributions use [AGPL v3](LICENSE), subject to [LICENSE-SCOPE.md](LICENSE-SCOPE.md). The pre-existing `theme.css` remains under the Unlicense; imported ClearVision styles keep Apache-2.0. Previously granted permissions are preserved.
