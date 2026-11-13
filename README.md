# Property and Technology hub

The front door for the Property and Technology brand: one static page that links out to the Origins newsletter, the Founders & Friends job board, Syndeo, and what is coming next.

- `index.html` is the whole site. Markup, styles, and copy live in that one file.
- `assets/` holds the logo and icons.
- There is no build step. Cloudflare Pages can serve the repo root as is.

Every outbound link and hard-coded number is listed in the comment at the top of `<body>` in `index.html`.
