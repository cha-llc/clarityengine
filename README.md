# 🟢 Clarity Engine — AI Brand Decision Tool

**"Rebrand or Refresh? Get the answer."**

Clarity Engine is a fully automated $37 brand decision tool. Answer 12 questions, get a clear verdict — Full Rebrand, Brand Refresh, or Stay the Course — with a confidence score and sequenced action plan.

## What It Does
- Delivers one of 3 verdicts: Full Rebrand / Brand Refresh / Stay the Course
- Provides a confidence score (0–100%)
- Breaks down the key factors driving the recommendation
- Generates a sequenced action plan specific to your verdict
- 100% automated — no human involvement after setup

## Tech Stack
- Pure HTML/CSS/JS — single file, zero dependencies
- Stripe Payment Links for checkout ($37 one-time)
- Gmail/Systeme.io for automated report delivery
- Supabase (optional) for customer records

## Setup
1. Open `index.html`
2. Replace the Stripe comment with your Payment Link:
   ```js
   window.location.href = 'https://buy.stripe.com/YOUR_LINK';
   ```
3. Deploy to Netlify Drop, Vercel, or any static host
4. Connect Stripe webhook → Gmail for report delivery

## Pricing
- **$37 one-time** per decision report
- Target: business owners actively considering a rebrand

## License
© 2026 C.H.A. LLC — All rights reserved
