# 🐾 Paws-And-Walks-Pro

A mobile-first Progressive Web App for Paws-And-Walks-Pro, providing dog walking, pet sitting, and overnight pet care.

## Features

- Responsive mobile and desktop design
- Installable PWA experience
- Offline caching with a service worker
- Add-to-home-screen install prompt
- Dog walking, pet sitting, and overnight care sections
- Pricing information
- Mobile navigation
- Booking request form that opens the visitor's email client
- GitHub Pages compatible
- No Node.js, npm, or build step required

## GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

Your site will be available at:

`https://javanejones.github.io/Paws-And-Walks-Pro/`

GitHub Pages can take a few minutes to publish after the first deployment.

## Customize the booking email

The form currently uses `hello@paws-and-walks-pro.com` as the destination. Update the `mailto:` address in `app.js` to your preferred business email before launch.

## Files

- `index.html` - application UI
- `styles.css` - responsive design
- `app.js` - interactions, booking request, install prompt
- `manifest.json` - PWA metadata
- `service-worker.js` - offline support
- `icons/icon.svg` - application icon
