# darcula_chrome

A port of my all time favorite coding theme, JetBrains Darcula ported to Google Chrome.

Totally Claude Generated, but looks pretty good to me!

It recolors the browser frame, tabs, toolbar, omnibox, and new-tab page with the
classic Darcula palette:

| Element            | Color       | RGB             |
| ------------------ | ----------- | --------------- |
| Editor background  | `#2B2B2B`   | 43, 43, 43      |
| Panel / toolbar    | `#3C3F41`   | 60, 63, 65      |
| Foreground text    | `#A9B7C6`   | 169, 183, 198   |
| Keyword orange     | `#CC7832`   | 204, 120, 50    |
| Number blue        | `#6897BB`   | 104, 151, 187   |
| String green       | `#6A8759`   | 106, 135, 89    |

## Install (load unpacked)

Chrome does not let you install a theme from a raw folder by double-clicking, so
load it as an unpacked extension:

1. Open `chrome://extensions` in Chrome.
2. Toggle **Developer mode** on (top-right).
3. Click **Load unpacked** and select this `darcula_chrome` folder.
4. The Darcula theme is applied immediately.

To remove it, go to `chrome://extensions`, find **Darcula**, and click **Remove**
(or `Reset to default` under Appearance in Chrome settings).

## Files

- `manifest.json` — theme definition (colors, tints, properties).
- `images/icon128.png` — extension icon.
- `images/ntp_background.png` — solid `#2B2B2B` tile for the new-tab page.
