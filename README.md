# Yelitza Gil Nutritionist Website

Professional static website for a nutritionist in Colombia.

## Pages

- `index.html`: homepage
- `about.html`: professional presentation and portrait placeholder
- `services.html`: nutrition services
- `contact.html`: WhatsApp, Instagram, phone, and email

## Technology

- HTML
- CSS
- JavaScript
- No build system required

This keeps the site easy to edit and easy to publish with GitHub Pages, Netlify, Vercel, GoDaddy hosting, or similar static hosting.

## Update Contact Details

Edit `script.js`:

- `phoneDisplay`: visible phone number
- `whatsappNumber`: phone number in international format without `+`
- `whatsappMessage`: prefilled WhatsApp message in Spanish and English
- `instagramHandle`: Instagram username without `@`
- `email`: contact email

## Update Text

All Spanish and English text lives in the `translations` object inside `script.js`.

To add French later, add a `fr` object with the same keys as `es` and `en`, then add a `FR` button in each page header:

```html
<button type="button" data-lang="fr" aria-pressed="false">FR</button>
```

## Add Yelitza's Portrait

In `about.html`, replace the `.portrait-placeholder` block with:

```html
<img class="portrait-photo" src="assets/yelitza.jpg" alt="Yelitza Gil, nutricionista" />
```

Then create an `assets` folder and place the image there as `yelitza.jpg`.

## Public Photos

The current design uses remote food and nutrition photos from Unsplash URLs. For a final production site, you can keep remote URLs or download selected images into an `assets` folder for more control.
