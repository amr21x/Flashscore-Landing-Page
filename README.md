# Flashscore Landing Page Project for Egypt FWD
A landing page for the famous live scores application Flashscore.

I designed this landing page completetly on my own and with my design choices for training purposes using HTML, CSS, and JavaScript.

## Deploy (Cloudflare)
The site is deployed as a Cloudflare Worker with static assets, served at `flashscore.amr21.dev` (see `wrangler.jsonc`).

```sh
npx wrangler login
npx wrangler deploy
```

The first deploy creates the Worker and the DNS record for the custom domain automatically.

© Copyright by Amr Yasser
