# email-assets

Hosted images and static pages used by ZenMode OS and Build 365 emails and marketing. Everything here is served over GitHub Pages so email clients can load the images by URL.

## What's inside

| Path | What it is |
|---|---|
| `build365/` | Assets for the Build 365 marketing site and live demo |
| `clueso-reply/` | Images for the Clueso reply email |
| `index.html` | The published marketing page |
| `*.png`, `*.gif` | Standalone email images (ZenMode OS clip, product shots, animated demos) |
| `.nojekyll` | Tells GitHub Pages to serve files as they are |

## Using an asset

Reference a file by its Pages URL in an email template:

```html
<img src="https://justkamal07.github.io/email-assets/image_1.png" alt="" width="600">
```

Keep images small (under 1 MB) and always set alt text and an explicit width so emails render well when images are blocked.

## Related

- [Build365-site](https://github.com/justkamal07/Build365-site): the Build 365 website
- [zenmode-os-brand-style](https://github.com/justkamal07/zenmode-os-brand-style): ZenMode OS brand style guide

---

Made by [Kamalraaj Senthilkumar](https://www.justkamalthings.com/).
