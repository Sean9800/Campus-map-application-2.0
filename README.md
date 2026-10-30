# Campus-map-application-2.0
This is the updated version of application 1.0
# Eduvos Campus Explorer (mobile web app / PWA)

Static, dependency-free app. Serve this folder over HTTPS (or `python3 -m http.server`) and open on a phone;
use "Add to Home Screen" to install. Edit the `nodes` array at the top of `app.js` to adjust positions/links/names.
To add a place: add a node, put `assets/<id>_low.webp` (~870px) and `assets/<id>_high.webp` (4096x2048) in assets.


## Icons
Branded icons (any + maskable), favicons and `og-image.jpg` are in `assets/`. Regenerate with your own artwork by replacing those files (keep the names).