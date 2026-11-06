# SothoPulse

Website for **SothoPulse**, a photography and web design studio in Johannesburg, South Africa.

Live site: https://sothopulse.netlify.app

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `photography.html` | Projects – photography and video |
| `websites.html` | Projects – websites |
| `services.html` | Services |
| `contact.html` | Contact and enquiry form |
| `thanks.html` | Shown after an enquiry is sent |
| `404.html` | Page not found |

Media lives in `media/` (photos, films, client logos), `video/` (hero background) and `img/`.

## Deploying on Netlify

1. In Netlify, choose **Add new site → Import an existing project** and pick this repository.
2. Leave the build command empty and set the publish directory to `/` (the repository root).
3. Every push to `main` then goes live automatically.

### Contact form

The enquiry form uses Netlify Forms. In **Site configuration → Forms**, turn on form detection, redeploy once,
and add an email notification so new enquiries arrive in your inbox.

### Search

After launch, add the site to Google Search Console and submit `/sitemap.xml`.
