# Web Tools Artwork — XPlay listings

Artwork for the 1000 web-tool listings on XPlay, by MR SAQLAIN PRODUCTIONS.
Tools live at https://saqgamedev.github.io/web-tools/<slug>/

## Layout

- `logos/<slug>.png` — 512x512 logo. Category colour background, large white
  initial letter of the tool name, hub-category name in small text at the bottom.
- `features/<slug>.png` — 1024x500 feature banner. Same category colour, full
  tool name in large white bold text, the one-line problem underneath,
  "MR SAQLAIN PRODUCTIONS" at the bottom.
- `shots/<slug>.png` — 1280x800 real screenshots of the live tool page
  (headless Chrome, `https://saqgamedev.github.io/web-tools/<slug>/`).

## Raw URLs (loadable from Flutter web — release-asset URLs are CORS-blocked)

- Logo: `https://raw.githubusercontent.com/SaqGameDev/web-tools-artwork/main/logos/<slug>.png`
- Feature: `https://raw.githubusercontent.com/SaqGameDev/web-tools-artwork/main/features/<slug>.png`
- Screenshot: `https://raw.githubusercontent.com/SaqGameDev/web-tools-artwork/main/shots/<slug>.png`

## Category colours (one distinct colour per hub category)

| Cat | Category | Colour |
|----:|----------|--------|
| 1 | Money & finance | #16A34A |
| 2 | Business & invoicing | #2563EB |
| 3 | Real estate | #D97706 |
| 4 | Health & fitness | #DC2626 |
| 5 | Productivity & time | #7C3AED |
| 6 | Writing & documents | #0D9488 |
| 7 | Images & design | #EC4899 |
| 8 | Audio & video | #4F46E5 |
| 9 | Education & learning | #EAB308 |
| 10 | Home & household | #84CC16 |
| 11 | Travel | #0EA5E9 |
| 12 | Food & recipes | #F97316 |
| 13 | Parenting & family | #A855F7 |
| 14 | Legal & contracts | #64748B |
| 15 | Career & jobs | #06B6D4 |
| 16 | Marketing & social | #F43F5E |
| 17 | Developers & web | #111827 |
| 18 | Data & files | #92400E |
| 19 | Security & privacy | #1E3A8A |
| 20 | Everyday calculators & life tools | #7F1D1D |

## Pilot batch — tools 001–020 (2026-11-10)

invoice-maker, mortgage-calculator, rent-vs-buy-calculator, qr-code-generator,
secure-password-generator, resume-builder, unit-converter-pro,
meeting-time-planner, freelance-rate-calculator, budget-planner-50-30-20,
compound-interest-calculator, loan-payoff-planner, debt-snowball-planner,
credit-card-payoff-calculator, savings-goal-tracker, emergency-fund-calculator,
retirement-savings-planner, roth-vs-traditional-ira-comparator,
salary-after-tax-calculator, paycheck-budget-splitter.

Generator: `~/workspace/web-tools/artwork/generate_pilot_art.py` (Python + PIL).
