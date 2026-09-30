# AI Studio — Android-friendly

This is a lightweight Progressive Web App (PWA).

## Setup

1. Create an account/key with Pollinations.
2. Host this folder on any HTTPS static host (GitHub Pages, Cloudflare Pages, Netlify, etc.).
3. Open the URL in Chrome on Android.
4. Open Settings and paste your own API key.
5. Use **⋮ → Add to Home screen / Install app**.

The app calls Pollinations' current OpenAI-compatible chat endpoint and image endpoint.

Important:
- This is not literally unlimited cloud generation. Cloud providers can impose quotas, pricing, or content rules.
- For effectively unlimited generation, run an image model locally on hardware you control. Modern phones generally aren't a practical replacement for a GPU PC for large image models.
- The app is intended for lawful use. It does not provide a mechanism for bypassing a provider's safety restrictions.
