# Royal Estate

A responsive, dependency-free real estate experience built with semantic HTML, CSS and vanilla JavaScript.

## Run locally

Open `index.html` in a modern browser, or serve this folder from a local static server (for example, `python -m http.server 8000`) and visit `http://localhost:8000`.

## Included

- Home, properties, property detail, buy, rent, sell, agents, about, services, journal and contact views.
- Client-side search over the included sample properties: transaction type, location, price range, type, bedrooms, bathrooms and minimum area.
- Sorting by recommended order, price or size; resettable filters; property detail galleries; and favorite properties saved in browser local storage.
- Responsive navigation, validated appointment and inquiry forms, newsletter form, direct email and WhatsApp inquiry links, keyboard-operable controls and SEO metadata.

## Integrations and content

Property listings are illustrative frontend data in `app.js`; connect a property-management system or API to publish live inventory. Contact and appointment forms validate in the browser and open a prefilled email to the displayed address; appointment times are requests only and require confirmation. Newsletter signup provides an on-page confirmation only. Connect an email/CRM and newsletter provider before accepting submissions as a business workflow. Replace sample contact details, social profiles and illustrative listings before launch. Property photographs are served from Unsplash and require an internet connection.

## Images and performance

Photography is loaded from Unsplash's image CDN in responsive-width derivatives; below-the-fold images use native lazy loading. Google Fonts are optional; local system fallbacks are configured.
