# Campus-map-application-2.0
This is the updated version of application 1.0.
# Eduvos Campus Explorer (mobile web app / PWA)

Static, dependency-free app. Serve this folder over HTTPS (or run `python -m http.server 8000`)
and open `http://localhost:8000/app2.0.html`. Use "Add to Home Screen" to install.

Edit the `nodes` array at the top of `app2.0.js` to adjust positions, links, or names.
Each place needs `assets/<id>_low.webp` (~870px wide) and `assets/<id>_high.webp` (4096x2048)
panoramas. The supplied images include the map and branding, but not the place panoramas.

## Icons
Replace the images in `assets/` to use your own map and branding; keep the filenames unchanged.