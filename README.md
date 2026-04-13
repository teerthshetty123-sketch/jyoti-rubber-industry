# Jyothi Rubber Industries — Official Website

Live business website for **Jyothi Rubber Industries**, a Mumbai-based manufacturer of automotive rubber components established in 1970.

🌐 **Live Site:** [https://&lt;your-username&gt;.github.io/jyothi-rubber-industries](https://your-username.github.io/jyothi-rubber-industries)

---

## About the Business

**Jyothi Rubber Industries**
R/9, Kasturi Industrial Estate, Goddev Phatak Road,
Mira Road East, Mumbai – 401105, Maharashtra, India

- **Owner:** R Shetty (Proprietor)
- **Phone / WhatsApp:** +91-9821351243
- **Office:** +91-8045201106
- **GST:** 27\*\*\*\*\*\*\*\*\*\*1Z7 (Verified)
- **Established:** 1970
- **IndiaMART:** [jyotirubberproductsmumbai](https://www.indiamart.com/jyotirubberproductsmumbai/)

---

## Products

| Product | Category | Price (indicative) |
|---|---|---|
| Automotive Rubber Engine Mounting | Auto Parts | ₹ 150 / piece |
| Automotive Strut Mount | Auto Parts | ₹ 250 / piece |
| Steering Rack Boot | Auto Parts | ₹ 80 / piece |
| Automotive Engine Mounts | Auto Parts | ₹ 120 / piece |
| Generator Engine Mounting | Auto Parts | ₹ 200 / piece |
| Rubber Molded Hose | Hoses | ₹ 100 / piece |
| Rubber Hose | Hoses | ₹ 90 / piece |
| Metal Bonded Rubber Bush | Bushes | ₹ 60 / piece |
| Rubber Bush / Bushing | Bushes | ₹ 40 / piece |
| Strut Kits | Auto Kits | ₹ 350 / set |
| Gunmetal Bushes | New Item | ₹ 50 / piece |

> Prices are indicative and exclude GST. Contact the business directly for confirmed bulk pricing.

---

## Tech Stack

- Pure **HTML5 + CSS3** — no frameworks, no dependencies, no build step
- Single-file site (`index.html`) — works offline and on any static host
- Mobile-responsive with CSS Grid and Flexbox
- Dark theme with amber/gold accent colour system using CSS custom properties

---

## Deployment — GitHub Pages (Step-by-Step)

### Option A: Automatic via GitHub Actions (recommended)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. The included workflow (`.github/workflows/deploy.yml`) will deploy automatically on every push to `main`

### Option B: Manual (branch-based)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, set branch to `main` and folder to `/ (root)`
4. Click **Save** — your site will be live at `https://<username>.github.io/<repo-name>`

### Option C: Custom Domain

1. Deploy via either option above
2. Go to **Settings → Pages → Custom domain**
3. Enter your domain (e.g. `www.jyothirubber.com`)
4. Add a `CNAME` record in your DNS pointing to `<username>.github.io`
5. Enable **Enforce HTTPS**

---

## Repository Structure

```
jyothi-rubber-industries/
├── index.html          ← Main website (single file, fully self-contained)
├── README.md           ← This file
├── LICENSE             ← MIT License
└── .github/
    └── workflows/
        └── deploy.yml  ← GitHub Actions auto-deploy workflow
```

---

## Making Updates

All content lives in `index.html`. To update:

1. Edit `index.html` locally or directly on GitHub
2. Commit and push to `main`
3. GitHub Actions will redeploy automatically within ~60 seconds

---

## License

MIT — see [LICENSE](LICENSE)
