# IDFlipBook v1.19 FINAL

Adobe InDesign script that exports an InDesign document as an interactive HTML flipbook.

## Final v1.19 updates

- Replaced the macOS system color picker with a safe built-in **RGB + HEX color picker** inside InDesign.
  - It no longer closes the main exporter dialog.
  - The chosen color is applied back to the Custom Background HEX field.
- Replaced the All Pages toolbar symbol with a clean **2 × 2 four-rectangle icon**.
- Keeps the working v1.18 viewer behavior and layout.

## Main features

- PNG or JPEG page export
- 96 / 150 / 300 / 600 / 900 ppi presets
- Smooth StPageFlip page turning
- Single first and last cover behavior
- Two-page inside spreads
- Zoom controls
- Fullscreen
- Page-number jump
- All-pages thumbnail browser
- Custom HTML viewer background colors + HEX input
- Optional PDF button
- Optional highlighter + Clear
- PDF opens in a new browser tab
- HTML footer: `adprocreatives © 2026. All rights reserved.`

## Installation

1. Open Adobe InDesign.
2. Go to **Window > Utilities > Scripts**.
3. Right-click **User** and choose **Reveal in Finder** / **Reveal in Explorer**.
4. Copy `IDFlipBook_v1.19.jsx` into the Scripts Panel folder.
5. Open an InDesign document.
6. Double-click `IDFlipBook_v1.19.jsx`.

No CEP folder, terminal command, or plugin installation is required.

## Important

The generated HTML viewer currently loads **StPageFlip 2.0.7 from jsDelivr**, so internet access is required when opening the exported flipbook.

Created By **Basheer Parammal** • © 2026 **adprocreatives**. All rights reserved.
