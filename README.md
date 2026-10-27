# The Bulod — website/PWA prototype

## Preview
Open `index.html` in a modern browser. For full PWA installation and offline caching, serve the folder over HTTPS or localhost (service workers do not run from ordinary `file://` URLs).

## Included
- Responsive Home, News, Feature, Literary, Sports, and Cartoons sections
- Publication logo and blue/yellow branding
- Sample placeholder stories and captions
- Editor CMS to add, edit, and delete articles/cartoons
- JSON export/import backup
- PWA manifest and service worker starter

## Important limitations
This is a front-end prototype. CMS changes are stored in the current browser only using localStorage. There is no authentication, shared database, server-side publishing, or secure multi-user editorial workflow. Anyone with access to the browser can edit content. Before public deployment, connect a secure backend/CMS, add authenticated roles and backups, host images securely, and obtain school approval. Replace placeholder content and use only verified stories and authorized photos.

External Google Fonts and sample Unsplash photos need internet access. Replace image URLs with school-approved images when ready.
