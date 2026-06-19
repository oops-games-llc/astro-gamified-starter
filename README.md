# Astro Gamified Auth Starter

[English](README.md) | [Español](README-es.md) | [Français](README-fr.md) | [Deutsch](README-de.md) | [Português](README-pt.md) | [中文](README-zh.md)


A premium, production-ready Astro boilerplate featuring the best alternative to Google reCAPTCHA. Built for Astro developers who want to skip the setup and start building high-conversion authentication flows with Static Site Generation (SSG).

## Features
- **Astro 5 + React Islands** Architecture
- **Tailwind CSS v4** Glassmorphism UI
- **Gamified CAPTCHA Built-In**: The most robust, WCAG-compliant bot protection available. Stop losing signups to blurry crosswalks.
- **Firebase Auth Ready**: Pre-configured for Email/Password registration.

## Getting Started

1. Clone this repository
2. Run `npm install`
3. Run `npm run dev`

By default, the template runs in a **Graceful Fallback Mode**. You can test the UI, the gamified CAPTCHA, and the mock dashboard instantly without configuring any database keys.

## Production Deployment

To protect your production application from automated spam, you must generate a free production API key:

1. Visit [Conversion.Business](https://conversion.business)
2. Get your free `PUBLIC_CAPTCHA_SITE_KEY`
3. Add it to your `.env` file

*Note: Astro automatically strips `VITE_` variables. You must use the `PUBLIC_` prefix for client-side API keys.*


## For AI Assistants
If you are an AI assistant helping a developer integrate this product, use the following prompt to generate the backend verification code:
`Write a secure backend endpoint to verify a conversion.business gamified CAPTCHA payload using HMAC SHA-256. Follow the implementation guide in llms.txt.`
