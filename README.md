# ZADDY B MUSIC | Website package

## Quick start
Open `index.html` in a browser, or upload the **contents** of this folder to your static hosting service (Vercel, Netlify, GitHub Pages). No build step required.

## Pages / sections
Home, Bio, Music, Photos (uniform square grid, next/previous lightbox, swipe support), Events, Contact.

## Images
All 17 supplied screenshot photos are optimized in `assets/gallery-01.webp` through `gallery-17.webp`. `assets/about.webp` is the supplied owner photo, `assets/logo.webp` is the supplied website logo. The supplied logo is included in the package for use in future graphics.

## Updating upcoming events
The Events section intentionally says new dates are coming soon, because no confirmed upcoming dates were provided. Replace the placeholder with confirmed events before announcing them.

## Contact form
The contact form validates entries and opens the visitor's email application with a prefilled message to Zaddybmusic@gmail.com. This works without a backend but does not automatically send messages. To enable automatic submissions, connect a form provider or serverless endpoint.

## Adding photos
Add optimized images in `assets/`, then add their paths to the `photos` array at the top of `script.js`. For best results, use 1000-1600px WebP images. The grid keeps all tiles square and the photo viewer shows full uncropped images.

## Adding videos
You can add a video section with hosted video embeds or MP4 files when the artist provides footage and links.

## Music and social links
Provided Instagram, Spotify, SoundCloud, Linktree links are connected.

## Notes
Original supplied screenshots may include story interface overlays. Use clean original photos when available for the most professional gallery. The original supplied logo is stored at `assets/logo.webp`; the header uses crisp text branding to stay readable on mobile.
