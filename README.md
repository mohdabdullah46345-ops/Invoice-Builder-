# 🧾 Invoice Builder

A free, browser-based invoice generator for freelancers and small businesses. Fill in your details, add line items, apply tax and discounts, and download a clean, print-ready PDF — no sign-up, no software, 100% in your browser.

**Live site:** https://mohdabdullah46345-ops.github.io/Invoice-Builder-/

---

## ✨ Features

- Live invoice preview as you type
- Company logo upload
- Multi-currency support (INR, USD, EUR, GBP, JPY, AUD)
- Line items with quantity and price
- Tax and percentage/flat discount
- One-click PDF download and Print
- Auto-save drafts to your browser (local storage)
- Fully responsive (works on mobile)
- Privacy-friendly — your data never leaves your device

## 📄 Pages

| Page | Description |
|------|-------------|
| `index.html` | Invoice generator + landing page |
| `guides.html` | Hub of invoicing guides |
| `guides/*.html` | Original articles on invoicing |
| `about.html` | About the project |
| `contact.html` | Contact form (mailto) |
| `privacy-policy.html` | Privacy Policy (AdSense ready) |
| `terms.html` | Terms of Service |
| `disclaimer.html` | Disclaimer |
| `404.html` | Custom not-found page |

## 🚀 Deploy on GitHub Pages

1. Go to your repository on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder, then **Save**.
4. Wait a minute, then visit: `https://mohdabdullah46345-ops.github.io/Invoice-Builder-/`

## 🔍 Google Search Console

1. Open [Google Search Console](https://search.google.com/search-console) and add a **URL prefix** property with your live URL.
2. Choose the **HTML tag** verification method and copy the code.
3. Paste it into the `google-site-verification` meta tag in `index.html`.
4. Submit your sitemap: `sitemap.xml`.

## 💰 Google AdSense

1. Sign up at [Google AdSense](https://www.google.com/adsense) with your live site URL.
2. After approval you will get a **Publisher ID** (`ca-pub-XXXXXXXXXXXXXXXX`).
3. Replace the placeholder Publisher ID in `index.html` (AdSense script + ad slots).
4. Replace `pub-0000000000000000` in `ads.txt` with your real Publisher ID.

> **Note:** AdSense requires real, original content and the legal pages (Privacy Policy, Terms, Contact) — all of which are already included in this project.

## 🛠 Tech

Plain HTML, CSS and vanilla JavaScript. PDF export uses [jsPDF](https://github.com/parallax/jsPDF) and [html2canvas](https://github.com/niklasvh/html2canvas) loaded from a CDN. No build step required.

## 👤 Author

Built and maintained by **Abdullah** — mohdabdullah46345@gmail.com

## 📜 License

Released under the [MIT License](LICENSE).
