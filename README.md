# Property and Technology hub

The front door for the Property and Technology brand: one static page that links out to the Origins newsletter, the Founders & Friends job board, Syndeo, and what is coming next.

- Live at https://property-and-technology-hub.eh2homes.workers.dev
- `public/index.html` is the whole site. Markup, styles, and copy live in that one file.
- `public/assets/` holds the logo and icons.
- `wrangler.jsonc` tells Cloudflare to publish only the `public/` folder. There is no build step.
- Every push to `main` republishes the site.

Every outbound link and hard-coded number is listed in the comment at the top of `<body>` in `public/index.html`.
