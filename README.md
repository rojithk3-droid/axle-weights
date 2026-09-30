# Axle Weights

Dispatch Pro **Axle Weights** prototype — a single self-contained page (`index.html`, no build step).

**Live:** https://rojithk3-droid.github.io/axle-weights/

- **List page** — asset status table (trucks / trailers), fleet donut, needs-attention list.
- **Asset page** (`#/asset/DTL88`) — live 3D truck/trailer with per-axle weight bars and limit markers, axle table, weight history chart, re-weigh sequence, CSV / PNG export.
- **Settings page** (`#/settings`) — per-axle max weight and alert duration, basic and additional notification recipients.

Built on the Dispatch Pro shadcn/ui-at-80% design system. Three.js and Lucide load from jsDelivr; the 3D truck is generated in code (no model files). Settings persist in `localStorage` (`dp-axle-cfg`). All fleet data is demo data.

Open `index.html` directly, or serve the folder with any static server.
