# Minimal Gatsby E-commerce (Stripe + Netlify Functions)

## Overview
This is a minimal starter site to integrate Stripe Checkout with Netlify Functions.
It includes:
- Client: Gatsby + React components (MiniCart, OrderSummary)
- Serverless: Netlify functions `create-checkout-session` and `webhook`

## Environment variables (set on Netlify)
- GATSBY_STRIPE_PUBLIC_KEY - Stripe publishable key
- STRIPE_SECRET_KEY - Stripe secret key
- STRIPE_WEBHOOK_SECRET - Stripe webhook secret
- URL - your site URL (e.g. https://your-site.netlify.app)

## Deploy
1. Push this repo to GitHub.
2. Link site on Netlify, set build command `gatsby build` and publish directory `public`.
3. Add environment variables on Netlify.
4. Install dependencies and deploy.

