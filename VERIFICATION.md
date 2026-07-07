[← Back to comparison](README.md)

# Data Verification Log — 2026-07-07

The original figures in this repo were extracted from Pageloot's own comparison articles (mostly stamped "April 2026"). On **2026-07-07** each tool's **headline data — cheapest paid price + G2 / Trustpilot / Product Hunt / Capterra scores — was independently spot-checked against live sources.** This log records what confirmed, what changed, and what couldn't be verified.

## How to read the confidence tags

- ✅ **Verified** — read directly from a live page (vendor pricing page, or a review platform that rendered), or confirmed via the platform's own page title / rating asset.
- 🟡 **Corroborated** — the review page itself is bot-blocked, but multiple consistent snippets from the live platform domain agree (and, where possible, pagination math supports the count).
- ⚠️ **Unverified** — page blocked *and* sources conflict or are absent; the original Pageloot-sourced figure is retained but should not be trusted without a manual check.

> **Important caveat:** **G2 and Trustpilot hard-block automated access** (HTTP 403 / CAPTCHA / Cloudflare). Most review scores below are therefore 🟡 corroborated from search snippets and page titles, not read off the rendered page. Vendor **pricing pages** and **Product Hunt / Capterra** mostly rendered fine (✅). Review counts on high-volume tools drift upward daily as new reviews accrue.

## Headline takeaways

- **Three "implausibly high" Trustpilot counts turned out to be real**, not extraction errors: QR.io (~13k), QRFY (~11.1k), QRCG/QR Code Generator Pro (~9.2k). All validated and now slightly *higher* than the April figures.
- **Genuine corrections found:** QR Tiger's Trustpilot score (4.8 → **4.5**), Uniqode's Capterra (4.6/~30 → **4.0/1**) and entry price ($9 → **$5**/mo), QR.io's price ($35 → **$39.99**/mo), Me-QR's ad-free price ($15 → **$9.99**/mo). QR Code Generator Pro has rebranded to **"QRCG by Bitly."**
- **Could not verify (bot-blocked, retained as-reported):** Bitly's G2 & Trustpilot, Uniqode's Trustpilot, Me-QR's G2, QRCode Monkey's G2 & Trustpilot.

---

## Per-tool reconciliation

Legend: **old** = Pageloot-sourced (≈April 2026) · **live** = checked 2026-07-07.

### Pageloot
Owner-provided (G2 4.8/13, Trustpilot 4.0/3); not part of this third-party live check. See [pageloot.md](competitors/pageloot.md).

### QR Tiger
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | Regular $7/mo (only monthly tier) | $7/mo, confirmed only monthly-billable plan | ✅ | [pricing](https://www.qrcode-tiger.com/payment), [help](https://qrtiger.helpscoutdocs.com/article/88-plans-and-pricing) |
| G2 | 4.8/5 (145) | 4.8/5 (~148) | 🟡 | [g2.com](https://www.g2.com/products/qr-tiger/reviews) |
| Trustpilot | 4.8/5 (158) | **4.5/5 (160)** ← corrected | ✅ | [trustpilot](https://www.trustpilot.com/review/www.qrcode-tiger.com) (star asset = 4.5) |
| Product Hunt | — (award only) | No reviews / no numeric score | ✅ | [producthunt](https://www.producthunt.com/products/qrtiger) |

### Uniqode (formerly Beaconstac)
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | Essential $9/mo (annual only) | **Starter $5/mo, annual only** (ladder renamed) | 🟡 | [pricing](https://www.uniqode.com/pricing) (JS-rendered) |
| G2 | 4.8/5 (507) | 4.8/5 (507) | 🟡 | [g2.com](https://www.g2.com/sellers/uniqode) |
| Trustpilot | 3.7/5 (19) | ~4.0–4.4 (~24) — snippets conflict | ⚠️ | [trustpilot](https://www.trustpilot.com/review/www.uniqode.com) |
| Capterra | 4.6/5 (~30) | **4.0/5 (1 review)** ← corrected | ✅ | [capterra](https://www.capterra.com/p/234622/Uniqode/) (rendered) |

### QR Code Generator Pro → now "QRCG by Bitly"
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Name | QR Code Generator Pro | **rebranded "QRCG by Bitly"** | ✅ | [trustpilot title](https://www.trustpilot.com/review/www.qr-code-generator.com) |
| Cheapest plan | $120/yr (~$10/mo) | ~$5/mo Starter reported (annual) — page JS-only | ⚠️ | [pricing](https://www.qr-code-generator.com/pricing/) |
| Trustpilot | 1.5/5 (~9,194) | 1.5/5 (~9,200+) — count validated | 🟡 | [trustpilot](https://www.trustpilot.com/review/www.qr-code-generator.com) |
| G2 | 3.4/5 (54) | ~3.3–3.4 (~54–59) | 🟡 | [g2.com](https://www.g2.com/products/qr-code-generator-pro/reviews) |
| Capterra | 2.4/5 (82) | 2.4/5 (82) — exact | ✅ | [capterra](https://www.capterra.com/p/177261/QR-Code-Generator-Pro/reviews/) (rendered) |

### Bitly
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | Core $10/mo (annual only) | $10/mo ($120/yr); free = 2 QR/mo | ✅ | [pricing](https://bitly.com/pages/pricing) (rendered) |
| G2 | 4.5/5 (916) | score ~4.5; count ~915–974 (conflicting) | ⚠️ | [g2.com](https://www.g2.com/products/bitly/reviews) |
| Trustpilot | 2.3/5 (694) | snippets conflict (2.3 vs 1.5) | ⚠️ | [trustpilot](https://www.trustpilot.com/review/bitly.com) |

### QR.io
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | $35/mo | **$39.99/mo** ← raised | ✅ | [pricing](https://qr.io/pricing) (rendered) |
| Trustpilot | 4.3/5 (12,778) | 4.3/5 (~13,000, still climbing) — validated | 🟡 | [trustpilot](https://www.trustpilot.com/review/qr.io) |
| G2 | 4.5/5 (462) | 4.5/5 (~461) | 🟡 | [g2.com](https://www.g2.com/products/qr-io/reviews) |
| Product Hunt | 1.1/5 (25) | 1.1/5 (26) | ✅ | [producthunt](https://www.producthunt.com/products/qr-io/reviews) (rendered) |

### QRFY
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | ~€20/mo annual; no monthly | same (quarterly ~€41/mo min; no monthly) | 🟡 | [pricing](https://qrfy.com/pricing) (JS-rendered) |
| Trustpilot | 3.9/5 (10,808) | 3.9/5 (~11,100) — validated, grew | 🟡 | [trustpilot](https://www.trustpilot.com/review/qrfy.com) |
| G2 | 4.6/5 (221) | 4.6/5 (221) — exact | 🟡 | [g2.com](https://www.g2.com/products/qrfy/reviews) |
| Product Hunt | 1.3/5 (12) | 1.3/5 (12) — exact | ✅ | [producthunt](https://www.producthunt.com/products/qrfy/reviews) (rendered) |

### Me-QR
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Ad-free price | $15/mo | **Premium $9.99/mo or $69/yr**; Lite $5/mo (1 ad-free code) ← corrected | ✅ | [pricing](https://me-qr.com/page/instructions/types-of-me-qr-paid-subscriptions) |
| Trustpilot | 3.8/5 (567) | 3.8/5 (573) | 🟡 | [trustpilot](https://www.trustpilot.com/review/me-qr.com) |
| G2 | 4.3/5 (2) | could not confirm (no rated card surfaced) | ⚠️ | [g2.com](https://www.g2.com/products/me-qr/reviews) |

### QRCode Monkey
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Status | Free/static only; routes to QRCGP | confirmed | ✅ | [qrcode-monkey.com](https://www.qrcode-monkey.com/) (rendered) |
| Trustpilot | 1.8/5 (41) | snippets 1.8/41 vs 2.1/43 — unresolved | ⚠️ | [trustpilot](https://www.trustpilot.com/review/www.qrcode-monkey.com) |
| G2 | no score | a profile may now exist (~4.8/25) — unconfirmed | ⚠️ | [g2.com](https://www.g2.com/products/qr-monkey/reviews) |

### Flowcode
| Field | Old | Live 2026-07-07 | Status | Source |
|---|---|---|---|---|
| Cheapest plan | Pro Plus $25/mo (annual); free 2 codes/500 scans | confirmed | ✅ | [pricing](https://www.flowcode.com/pricing) (rendered) |
| G2 | 4.6/5 (85) | 4.6/5 (85) — exact | 🟡 | [g2.com](https://www.g2.com/products/flowcode/reviews) |
| Trustpilot | 3.6/5 (36) | count ~38; score not re-confirmable | ⚠️ | [trustpilot](https://www.trustpilot.com/review/www.flowcode.com) |

---

*Method: live checks via web search + direct page fetch on 2026-07-07. Review-platform pages that block automated access were corroborated from live-domain search snippets and page titles rather than rendered pages; those are tagged 🟡 or ⚠️ accordingly. Figures were only changed in the comparison when confidence was ✅ or strong 🟡.*
