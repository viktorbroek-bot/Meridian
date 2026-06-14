# Meridian — Landing Pages

This repository hosts landing pages for Meridian.

## What's in here

Each landing page lives in its own folder. The folder name becomes the URL.

```
meridian-site/
├── index.html                              → meridian.[yourdomain].com/
├── 3-facials-worth-booking-after-35/
│   └── index.html                          → meridian.[yourdomain].com/3-facials-worth-booking-after-35/
├── README.md
├── LICENSE
└── .gitignore
```

## Adding a new landing page

1. Create a new folder. Name it whatever you want the URL to be (use hyphens, no spaces, lowercase).
2. Put the page's HTML file inside that folder.
3. Rename the HTML file to `index.html`.
4. Commit and push. Cloudflare Pages will deploy it automatically within ~1 minute.

Example: to add a page at `meridian.[yourdomain].com/glow-summer-special/`, create:

```
glow-summer-special/
└── index.html
```

## Hosting

This repo is deployed via Cloudflare Pages, connected to GitHub. Any push to the `main` branch automatically redeploys the site.

## License

All content is proprietary. See LICENSE.
