# DREAM Charter Schools — Splash Prototype

A standalone splash page built for aiEDU's collaboration with [DREAM Charter Schools](https://wearedream.org/).

Published at: **https://prototype.aiedu.org/dream-charter-schools**

## Stack

- Single static `index.html` (no build step)
- Embedded CSS + vanilla JS (count-up stats, scroll reveal, sticky nav, marquee)
- Google Fonts: Archivo / Archivo Black / Inter

## Local preview

Open `index.html` directly, or:

```bash
npx serve .
```

## Deploy

```bash
vercel deploy --prod --yes --scope akotrans-projects
```

The Vercel project is `dream-prototype` under the `akotrans-projects` scope.
The router at https://prototype.aiedu.org rewrites `/dream-charter-schools/*` to this origin.
