# Emcee Jihan · SenadaRasa

A responsive one-page portfolio and booking website for **Emcee Jihan**, positioned around a calm, structured and emotionally aware hosting style.

## Live site

After GitHub Pages is enabled, the site will be available at:

`https://shukritobi.github.io/Emcee-Jihan-SenadaRasa/`

## Features

- Mobile-first responsive layout
- Malay-first conversion copy
- Wedding, corporate, school and community service sections
- Training certificate and experience highlights
- FAQ accordion
- Booking form that prepares a complete WhatsApp enquiry
- SEO metadata, Open Graph image and Schema.org markup
- GitHub Pages deployment workflow
- No framework or build step required

## Set the WhatsApp number

Open `index.html` and update the `data-whatsapp-number` attribute on the `<body>` element.

```html
<body data-whatsapp-number="60123456789">
```

Use the Malaysian international format without `+`, spaces or dashes.

When the number is blank, the form opens WhatsApp's share flow and copies the enquiry text to the visitor's clipboard.

## Replace content and media

- Main portrait: `assets/emcee-jihan.svg`
- Certificate artwork: `assets/sutra-jiwa-certificate.svg`
- Social preview: `assets/og-image.svg`
- Social links: search for `beacons.ai`, `threads.com`, `instagram.com` and `tiktok.com` in `index.html`

## Local preview

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

The included workflow publishes the repository to GitHub Pages whenever `main` is updated.

In GitHub:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions**.
3. Push or rerun the `Deploy static site to Pages` workflow.

## Next production updates

- Confirm and insert Jihan's direct WhatsApp number
- Replace the current screenshot-derived portrait with an original high-resolution image
- Add authentic event photos and vertical video clips
- Add verified client testimonials
- Confirm language options, rates, travel policy and package inclusions
- Connect a custom domain such as `emceejihan.my`
