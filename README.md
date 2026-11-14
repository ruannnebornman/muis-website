# muis-website

Landing page for [muis](https://github.com/ruannnebornman/muis), the terminal
that ships with Veldmuis.

Static HTML and CSS — no build step, no framework.

## Local preview

```sh
python3 -m http.server 8080
```

Open <http://127.0.0.1:8080/>.

## Deploy

Cloudflare Pages builds directly from this repository:

- Build command: none
- Output directory: `/`
- Custom domain: `muis.veldmuislinux.org`

`_headers` adds the security headers Cloudflare applies to every response.

## Editing

- `index.html` — page content and links
- `styles.css` — theme variables and layout
- `assets/muis.png` — app icon
- `assets/screenshot.png` — current muis window, captured from the real app

Keep the download button pointed at
`https://github.com/ruannnebornman/muis/releases/latest` so it never needs a
version bump.
