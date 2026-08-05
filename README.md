# OctoSender

Windows XP-inspired static Discord webhook sender for GitHub Pages.

## Features

- Compact Windows XP-style application interface
- XP desktop background using the requested image reference
- Webhook URL, custom name, avatar URL and TTS
- Live message preview
- Single-message sending
- HTTP 429 rate-limit notice
- No backend or database

## GitHub Pages

Upload `index.html` to a repository, then enable GitHub Pages from the repository's Pages settings.

## Background

The stylesheet currently references the supplied ImgBB page:

`https://ibb.co/CpgfXDFs`

If that page does not work as a CSS background, replace it with the direct image URL provided by ImgBB.

## Note

The sender intentionally provides a single-send mode rather than a bulk spam loop. It handles Discord's rate-limit response instead of repeatedly retrying requests.
