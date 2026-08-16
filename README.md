# SUVIKSAN CyberSOS — Exact React Conversion

This is the React/Vite conversion of the supplied HTML.

The original body markup, CSS, and JavaScript are preserved. The original JavaScript is executed in the **global browser scope** after React mounts the page. This keeps the original inline `onclick` handlers and global functions working.

Examples that are preserved:
- Language switcher
- SOS button
- Case/exhibit controls
- Cyber popup tabs
- FIR generator
- Landing popup
- Scroll progress / reveal interactions
- Hero interactions
- Any other original button handlers

## Run

```bash
npm install
npm run dev
```

## Video

If the original page uses the local awareness video, put the required MP4 asset in `public/` using the filename referenced by the original HTML.
