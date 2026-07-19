# Pitmaster Munse Cook Planner

A responsive barbecue planning application that works backward from a serving time to coordinate prep, fire, smoking, wrapping, glazing, resting, and serving across multiple proteins and cookers.

## Vercel deployment

This repository is configured for Vercel. Import the repository and Vercel will use:

- Build command: `npm run build:static`
- Output directory: `wpengine-dist`

Add the finished domain in the Vercel project settings after the first deployment.

## Google Analytics 4

Replace the placeholder in `public/ga4-config.js` with the GA4 Measurement ID before launch. The application records:

- Page views and visitors through GA4
- Cook plans generated
- Proteins selected or removed
- Protein weights changed
- Serving times changed
- Cooker counts and assignments changed
- Plans copied
- Plans printed

No cooking preferences or personal information are stored on a server. User settings remain in that visitor's browser.

## Local development

```bash
npm install
npm run build:static
```

The static production files are written to `wpengine-dist`.
