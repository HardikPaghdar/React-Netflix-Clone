# Netflix-Style Video Browsing Demo

A Next.js 13 and React demo for a Netflix-style video browsing experience. The project is intended for learning and demonstration, not as a production streaming service.

## Documented features

- Authentication flow
- Video category browsing
- Like/dislike interactions
- Favorites page
- Horizontally scrollable video lists
- Incremental Static Regeneration (ISR) demonstration

## Requirements

- Node.js and npm
- Any provider credentials and environment variables required by the current authentication/API configuration

## Run locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Scripts

- `npm run dev` — development server
- `npm run build` — production build
- `npm start` — serve the production build
- `npm run lint` — run the configured lint command

## Screenshots

Check `public/static/readme/` for the screenshots included with this project.

## Scope and security

Before deployment, verify authentication callbacks, authorization, provider API access, rate limits, and environment configuration. Never commit private keys or production credentials. Review the age of the Next.js and related dependencies before using this project as a foundation for new work.
