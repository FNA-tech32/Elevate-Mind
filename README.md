# Elevate Mind

Voice-first AI fitness coach. You speak your goals in plain English. Elevate Mind builds your profile, coaches each session, and walks you through every exercise with video and form cues.

## Contact

| | |
| --- | --- |
| **Email** | [hello@elevatemind.com](mailto:hello@elevatemind.com) |
| **Phone** | [+1 (628) 555-0174](tel:+16285550174) |
| **Studio** | 180 Market Street, Suite 400, San Francisco, CA 94105 |

Those details are in the navigation Contact link, the contact section, and the footer.

## What the site includes

The marketing site is a single page:

- **Navigation** — Elevate Mind name, a Contact link, and a button that scrolls to early access
- **Hero** — “Voice coach. Video guidance. Every session.” plus a phone mockup of a coaching reply and an exercise card
- **Badge bar** — Voice-first, AI-powered, Injury-aware, Built for real training
- **How it works** — Speak your goals, meet your profile, train every day
- **See it in action** — voice onboarding, smart profile, and daily coaching, each with a phone mockup
- **Features** — voice onboarding, injury-aware planning, adaptive coaching, exercise cards, and session memory
- **Early access** — email form that posts to Formspree
- **Contact** — email, phone, and studio address
- **Footer** — brand name, email, phone, and copyright

The early-access form still uses the placeholder endpoint `https://formspree.io/f/YOUR_FORM_ID`. Replace `YOUR_FORM_ID` in `app/page.tsx` with a real Formspree form id before collecting signups.

## Run it locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Project structure

```text
app/
  page.tsx      Marketing page
  layout.tsx    Root layout and page title
  globals.css   Base styles and Tailwind
CONTEXT.md      Product notes for later app work
```

## Stack

Next.js 16, React 19, TypeScript, and Tailwind CSS v4. Headings use Geist Mono. Body text uses Geist Sans.
