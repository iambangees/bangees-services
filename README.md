# Bangees — Websites for Businesses

**The services page for Abubakar's freelance web design offer.**

A one-page, business-facing site that sells the packages from the freelance offer (`~/workspace/freelance-offer/FREELANCE_OFFER.md`): Launch ₦75,000, Business ₦180,000, Business Plus from ₦300,000, plus the ₦15,000/month Care Plan. It shows selected live work (Discaro, Show Picker, Name Atlas, Naira Lens), the 4-step process, honest FAQs, and WhatsApp-first contact.

## WhatsApp number

The page's WhatsApp buttons are wired from one config line at the top of the script in `site/index.html`:

```js
const WHATSAPP_NUMBER = "";
```

Set it to the number in international format, digits only (e.g. `2348012345678`), and every WhatsApp button opens a chat with a prefilled message (package buttons name the package). While it is empty, the buttons scroll to the contact section instead of opening a dead link — **set the number before sharing the page with prospects.**

## Run it

One static page (`site/index.html`), installable as a PWA, family pattern. Cross-origin links always go to the network; the service worker caches only this site's own files.

Part of the Bangees family of sites — see the footer on any of them.
