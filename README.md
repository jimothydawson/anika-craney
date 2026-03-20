# Anika Craney Site

Astro site for Anika Craney, including a Tonga whale-swim expressions-of-interest flow powered by Netlify Forms.

- collects `name` and `email`
- sends a Netlify form notification email to Anika
- reveals the discount code and resort link only after successful submission

## Local Setup

1. Install dependencies:

```sh
npm install
```

2. Start local development:

```sh
npm run dev
```

## Netlify Form Setup

1. Deploy the site to Netlify.
2. Make sure form detection is enabled in Netlify.
3. In Netlify, add an email notification for the `tonga-whales-eoi` form.
4. Set the hidden `resortUrl` and `discountCode` field values in [src/pages/index.astro](/Users/jamesdawson/github-jimothy/lumara/src/pages/index.astro) to the real resort URL and code.

## Commands

- `npm run dev` starts the local dev server
- `npm run build` builds the production site
- `npm run preview` previews the production build locally
