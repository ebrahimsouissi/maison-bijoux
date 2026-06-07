# maison-bijoux

A single-page fine-jewelry shop — multilingual (EN / FR / AR), WhatsApp ordering,
and a built-in admin panel. Backed by Supabase for product & settings storage.

## Files
- `index.html` — the entire site (HTML, CSS, and JS in one file).

## Admin
Open the site, click **Admin** in the footer, and log in (default password: `admin123`
— change it under **Settings**). From there you can add products, photos, set your
WhatsApp number, edit hero text per language, and back up / restore your shop.

## Hosting
The site talks to Supabase from the browser, so it must be served from a real URL
(e.g. GitHub Pages) rather than opened as a local file.
