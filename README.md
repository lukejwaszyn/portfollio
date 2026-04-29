# Luke Waszyn II — Portfolio Site

## To view locally
Just double-click `portfolio.html`. It'll open in your browser. No build step, no server needed.

## To deploy (when ready)
**Option 1 — GitHub Pages (free, keeps a permanent record):**
1. Create a new public GitHub repo (e.g. `portfolio` or `lukejwaszyn.github.io`)
2. Upload this entire folder to the repo root
3. Settings → Pages → Source: `main` branch, `/ (root)` → Save
4. Site goes live at `https://lukejwaszyn.github.io/portfolio/` in a few minutes

**Option 2 — Netlify (free, instant deploy, custom domain easy):**
1. Go to https://app.netlify.com/drop
2. Drag this entire folder onto the drop zone
3. Get a live URL immediately (e.g. `fluffy-waffle-9823.netlify.app`)
4. You can rename it in site settings and hook up a custom domain later

## File structure
```
portfolio.html                        ← the whole site
assets/
├── Waszyn_Resume.pdf                 ← downloaded via hero & footer buttons
├── about/
│   └── headshot.jpg
├── lunarecycle/
│   └── concept-sketches.jpg          ← team sketches
├── ground-station/
│   ├── hmi-screenshot.png            ← 3D mission ops HMI
│   └── rtl-sdr-v4.jpg
├── rtl-sdr/
│   ├── fm-dipole.jpg                 ← FM dipole antenna
│   └── rtl-sdr-v4.jpg                ← also referenced from the ground station project
└── tone-control/
    └── pcb.jpg                       ← EE 210 PCB
```

## Still outstanding (add later)
These are placeholders or omissions you may want to fill in over time:
- **Best decoded NOAA image** — once you get a clean capture, drop it at `assets/ground-station/decoded-noaa.jpg` and add an `<img>` tag in the ground station section
- **VHF dipole photo for ground station** — currently the ground station only shows the RTL-SDR since the FM dipole was attributed to the RTL-SDR project
- **LunaRecycle CAD renders** or team photos, once available
- **Updated resume** (fix "Millenium" → "Millennium" typo; update "6 subsystem" → "7-subsystem"; your choice on whether to mention Co-Lead SE vs. Systems Engineering with Julian)

## Editing the site
The whole site is a single HTML file. All CSS is in a `<style>` block at the top, all JavaScript in a `<script>` block at the bottom. Search for `<!-- COMMENT -->` markers to find sections fast (e.g. `<!-- FEATURED #1: LunaRecycle` or `<!-- EXPERIENCE -->`).

For minor tweaks, open `portfolio.html` in any text editor — TextEdit works on macOS but VS Code is nicer.
