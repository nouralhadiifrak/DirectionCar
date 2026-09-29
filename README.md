# Direction Car

Website for Direction Car, a car rental agency in Casablanca. It is a single file, `index.html`, with no build step. Open it in a browser or host it on any static host (Netlify, GitHub Pages, Vercel, etc.).

## Features
- Home, Fleet (7 cars with filters and colour picker), Rental conditions, Reservation, Location/Contact
- The logo is embedded inside `index.html`, so the page works as a single file (`images/logo.png` is a copy)
- English / Français / العربية (Arabic switches the page to right-to-left)
- Reservation form sends the booking to WhatsApp **0661864810**
- WhatsApp, Instagram and Google Maps buttons (floating on desktop, a bottom bar on mobile)

## Editing
Everything is at the top of the `<script>` in `index.html`:
- `CONFIG.instagram`: Instagram page URL
- `CARS`: prices, types, descriptions, options, available colours
- Car photos are studio renders with no background, all shown at the same angle, from the imagin.studio CDN.
  To use your own photos, add transparent PNGs to `images/` and set `photo: "images/xxx.png"` on the car.
