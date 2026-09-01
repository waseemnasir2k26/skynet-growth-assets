# skynet-growth-assets

Public CDN-backed assets for the SkynetLabs GitHub-growth content pack (September 2026).

Served via **jsDelivr**, not `raw.githubusercontent.com`. That distinction matters:
raw GitHub serves media as `application/octet-stream`, which social schedulers reject
(a video posted from a raw URL fails silently). jsDelivr serves the correct MIME type.

```
https://cdn.jsdelivr.net/gh/waseemnasir2k26/skynet-growth-assets@main/cards/<file>.png
https://cdn.jsdelivr.net/gh/waseemnasir2k26/skynet-growth-assets@main/pins/<file>.png
https://cdn.jsdelivr.net/gh/waseemnasir2k26/skynet-growth-assets@main/video/<file>.mp4
```

| Folder   | Contents                          | Size        |
| -------- | --------------------------------- | ----------- |
| `cards/` | 29 social cards, 1080x1350        | LI/FB/IG    |
| `pins/`  | 12 Pinterest pins, 1000x1500      | Pinterest   |
| `video/` | 6 vertical shorts, 1080x1920      | YT/TikTok   |

jsDelivr caps a single file at 20 MB. Every asset here is well under that.

Built by SkynetLabs — https://skynetjoe.com
