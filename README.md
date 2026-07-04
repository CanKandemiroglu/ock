# ⚡ PromptForge — A Ready-to-Launch Digital Product Business

A complete, deploy-ready online business selling **AI prompt packs** — one of the top-selling digital product categories of 2026 (100% margin, no inventory, instant delivery).

**What's in this repo:**

| File | What it is |
|---|---|
| `index.html` | The full storefront: landing page, free AI Prompt Generator tool, product cards, email capture, FAQ. Zero build step. |
| `products/starter-pack-free.md` | 🎁 Free lead magnet — 10 prompts (given away for email signups) |
| `products/marketing-machine-50-prompts.md` | 🚀 The $19 product — 50 marketing prompts |
| `products/ai-business-os.md` | 👑 The $39 flagship — 55 prompts + 5 workflows (bundled with Marketing Machine) |

The products are **real and finished** — written, organized, and sellable as-is.

---

## 🚀 Launch Checklist (~30 minutes to first sale capability)

### 1. Put the site live (5 min, free)
Easiest: **GitHub Pages**
1. Repo → Settings → Pages → Source: `Deploy from a branch` → select your branch, `/ (root)` → Save.
2. Site is live at `https://<username>.github.io/ock/` within a minute.

(Alternatives: drag the folder into Netlify, or `vercel deploy` — both free.)

### 2. Connect payments (10 min, free)
1. Create a free [Gumroad](https://gumroad.com) account (or Lemon Squeezy / Payhip).
2. Create two products and upload the files (export the `.md` files to PDF first for a premium feel — paste into Google Docs → Download as PDF):
   - **Marketing Machine** — $19 — upload `marketing-machine-50-prompts.pdf`
   - **AI Business OS** — $39 — upload BOTH `ai-business-os.pdf` and `marketing-machine-50-prompts.pdf` (it's bundled)
3. Copy each product's Gumroad link.
4. In `index.html`, find the two `<!-- LAUNCH: replace href -->` comments and replace `#buy-setup` with your Gumroad links.

Gumroad handles checkout, delivery, receipts, VAT and refunds. You get paid from sale #1.

### 3. Connect email capture (10 min, free)
1. Create a free [Formspree](https://formspree.io) form (or Buttondown/MailerLite for real automation).
2. Replace `YOUR_FORM_ID` in the form `action` in `index.html`.
3. When someone signs up, send them `starter-pack-free.md` (as PDF). With Buttondown/MailerLite you can automate this delivery.

### 4. First traffic (day 1 — all free)
Ranked by effort-to-result for this exact product:
1. **Reddit/communities**: genuinely answer questions in r/smallbusiness, r/Entrepreneur, r/ChatGPT — share 1–2 free prompts in the answer, link the free pack (not the paid one) in your profile.
2. **Twitter/X + LinkedIn**: post one prompt from the free pack daily as value content. "Steal this prompt" posts perform well. Link the site.
3. **Product Hunt / betalist**: launch the free Prompt Generator tool (tools get upvotes more than products).
4. **TikTok/Reels/Shorts**: 30-sec screen recordings — "watch ChatGPT write my whole week of posts with one prompt" → free pack in bio.
5. **SEO (compounding)**: the generator page targets "AI prompt generator" searches; add blog posts later with prompts for specific niches ("ChatGPT prompts for real estate agents" etc.).

### 5. The proven upsell path
Free pack (email) → nurture with 1 valuable email/week → $19 pack → $39 flagship. Typical digital-product funnel converts 1–3% of email subscribers per campaign.

---

## 💰 Honest revenue math

No website makes money "instantly" — money arrives when the first visitor buys. This model is the *shortest legitimate path*: products already exist, checkout works from day one, margin is ~100%.

| Daily visitors | Est. sales/mo (1.5% conv, $24 avg) | Monthly revenue |
|---|---|---|
| 30 | ~13 | ~$320 |
| 100 | ~45 | ~$1,080 |
| 300 | ~135 | ~$3,240 |

Levers, in order: traffic → email list size → new packs for new niches (repeatable: duplicate a pack for "realtors", "coaches", "Etsy sellers" — niche packs outsell generic ones).

## 🧭 Why this idea (research summary)

- AI prompt packs, Notion templates and AI guides top Gumroad's 2025–2026 best-seller charts; AI-guide searches doubled YoY.
- Marketing prompts are the **#1 selling text-prompt subcategory**; $9–$39 is the proven price band; focused packs from solo creators do $2k–$10k/mo.
- Micro-tools (like the free generator here) are the proven traffic magnet for these sites.
- Digital services/products are the fastest path to cash flow: no inventory, <$100 startup cost, revenue possible in weeks.

## 🛠 Customizing

- All styling is CSS variables at the top of `index.html` (`--accent`, `--bg`...) — rebrand in minutes.
- The Prompt Generator templates live in the `TEMPLATES` object in `index.html` — add niches to target new keywords.
- Rename the brand throughout if "PromptForge" is taken in your market.
