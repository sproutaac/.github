# Sprout AAC brand assets

The **three-leaf sprout** is the official Sprout AAC logo. It's used for the app, the website ([sproutaac.org](https://sproutaac.org)), and the [LinkedIn page](https://www.linkedin.com/company/sproutaac/). Use these files rather than redrawing it.

<p align="center"><img src="sprout-mark.png" width="96" alt="Sprout AAC logo"></p>

| File | What it's for |
| --- | --- |
| `sprout-mark.png` | The mark on a **transparent** background (192×252). Works on light and dark backgrounds. Use this for READMEs, docs, and the website header. |
| `sprout-mark-on-white-400.png` | Square, on white (400×400). For profile pictures and avatars (LinkedIn, GitHub org, Discord). |
| `sprout-logo-lockup-original.png` | The original lockup (960×320) the mark is cut from. It has a solid white background and a **white wordmark**, so the wordmark only shows up on dark backgrounds. Kept as the source; don't use it directly. |
| `social/og-image-1200x630.png` | Link-preview image for sproutaac.org (same as the site's `og-image.png`). |
| `social/linkedin-page-cover-1128x191.png` | LinkedIn company page cover. |
| `social/linkedin-profile-banner-1584x396.png` | LinkedIn personal profile banner (content kept clear of the profile photo). |

## Colours

These match the website's CSS tokens.

| Token | Hex |
| --- | --- |
| `--forest` | `#0F5C2E` |
| `--green` | `#1A8C45` |
| `--mid` | `#3DC46A` |
| `--fresh` | `#A8F0C0` |

## Known gaps

- **No vector or high-resolution master yet.** The largest version of the mark is about 250px tall, which is fine for the web and READMEs but too small for app-store icons (1024×1024) or print. Before the app ships, it needs an SVG or high-res master.
- The app's iOS, Android and macOS icons are still Flutter's default placeholder. Replace them with the mark once the master exists.
