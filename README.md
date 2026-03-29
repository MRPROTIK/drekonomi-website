# Drekonomi AB — Premium Website

> Bilingual premium website for **Drekonomi AB**, a high-end bookkeeping and financial advisory company based in Sollentuna, Stockholm, Sweden.

---

## 🌐 Live Demo

**GitHub Repository:**
👉 https://github.com/MRPROTIK/drekonomi-website

**Live Site (GitHub Pages):**
👉 https://mrprotik.github.io/drekonomi-website/

> ⏳ After uploading files and enabling Pages, allow ~60 seconds for the site to go live.

---

## 📁 File Structure

```
drekonomi-website/
├── index.html       ← Complete website (all 6 pages, single file)
├── hero.jpg         ← Homepage hero background (office desk + Stockholm view)
├── services.jpg     ← Services page header image
├── portrait.jpg     ← About Us portrait image
├── contact.jpg      ← Contact & Blog page header image
├── pricing.jpg      ← Pricing page background
└── README.md        ← This file
```

> ⚠️ All 6 files must be in the **same folder / root of the repo** for images to load correctly.

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### 1. Go to your repository
```
https://github.com/MRPROTIK/drekonomi-website
```

### 2. Upload all 6 files
- Click **Add file → Upload files**
- Drag and drop all 6 files:
  - `index.html`
  - `hero.jpg`
  - `services.jpg`
  - `portrait.jpg`
  - `contact.jpg`
  - `pricing.jpg`
- Scroll down and click **Commit changes**

### 3. Upload README.md
- Click **Add file → Upload files** again
- Upload `README.md`
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to **Settings** (top menu of the repo)
- Click **Pages** in the left sidebar
- Under **Source**, select **Deploy from a branch**
- Branch: `main` &nbsp;/&nbsp; Folder: `/ (root)`
- Click **Save**

### 5. Your live site is at:
```
https://mrprotik.github.io/drekonomi-website/
```

---

## 🎨 Design System

| Token | Value | Usage |
|---|---|---|
| `--ivory` | `#FAF8F4` | Main background |
| `--ivory2` | `#F3F0EA` | Section alternates |
| `--ivory3` | `#EDE9E0` | Borders, dividers |
| `--gold` | `#B8952A` | Primary accent |
| `--gold2` | `#D4AF37` | Gold on dark backgrounds |
| `--ink` | `#1C1A17` | Primary text / dark sections |
| `--serif` | Playfair Display | Headings, hero text |
| `--sans` | Jost | Body, nav, labels |

---

## 📄 Pages

| Page | Swedish | English | Key Feature |
|---|---|---|---|
| Home | Hem | Home | Full-screen hero, testimonials, steps |
| Services | Tjänster | Services | All 8 services with detailed descriptions |
| Pricing | Priser | Pricing | 3 packages, featured card highlighted |
| About | Om oss | About | Portrait split, values, trust signals |
| Blog | Blogg | Blog | 5 article cards with featured post |
| Contact | Kontakt | Contact | Form + company info, dark panel |

---

## 🌍 Bilingual Toggle

The site supports **Swedish (SV)** and **English (EN)** with a toggle in:
- Top navigation (desktop)
- Mobile drawer menu
- Footer

All text elements use `data-sv` / `data-en` attributes. Switching language is instant with no page reload.

---

## 📱 Mobile Optimisation

- Fluid typography using `clamp()` — scales between mobile and desktop
- Hamburger menu → full-screen drawer on screens ≤ 960px
- All CSS grids collapse gracefully to single column
- `100svh` hero height (respects mobile browser chrome)
- `autocomplete` on all form fields for mobile keyboards
- Tap targets sized for touch (minimum 44×44px)
- `passive` scroll event listeners for smooth performance

---

## 🔍 SEO Features

- **Page title** optimised with Swedish keywords
- **Meta description** with location + service keywords
- **Meta keywords** covering: bokföring Stockholm, redovisningskonsult Sollentuna, K10-blankett, årsredovisning, lönehantering
- **Open Graph** tags for social sharing
- **Geo meta tags** — `geo.region: SE-AB`, `geo.placename: Sollentuna Stockholm`
- **JSON-LD structured data** — `AccountingService` schema for Google rich results
- **Semantic HTML** — `<main>`, `<article>`, `<section>`, `<nav>`, `<footer>`
- **ARIA attributes** — `aria-label`, `aria-hidden`, `aria-expanded`, `role`
- **Canonical URL** tag (update to live domain before launch)

---

## 🛠️ Customisation

### Update company details
Search and replace in `index.html`:

| Find | Replace with |
|---|---|
| `+46 76 042 51 55` | Your phone number |
| `info@drekonomi.se` | Your email address |
| `Sollentuna, Stockholm` | Your address |
| `https://drekonomi.se` | Your live domain |

### Update canonical URL (important for SEO)
Find this line in `<head>` and update before going live:
```html
<link rel="canonical" href="https://drekonomi.se/">
```

### Change the gold accent colour
In the `:root` CSS block, change:
```css
--gold: #B8952A;
--gold2: #D4AF37;
```

---

## 📦 Tech Stack

- Pure **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies
- **Google Fonts**: Playfair Display + Jost (loaded via CDN)
- No build process required — open `index.html` directly in any browser
- Compatible with all modern browsers (Chrome, Firefox, Safari, Edge)

---

## 📋 Services Included

1. Årsredovisning / Annual Report
2. Bokslut & Finansiella rapporter / Financial Statements
3. Inkomstdeklaration / Income Tax Declaration
4. Lönehantering & Löneberedning / Payroll Management
5. Löpande bokföring / Ongoing Bookkeeping
6. Rapportering till Skatteverket / VAT & Official Reporting
7. Finansiell rådgivning & CFO-stöd / Financial Advice & Part-time CFO
8. K10-blankett / K10 Form (Gränsbelopp & Utdelning)

---

## 💰 Pricing Packages

| Package | Price | Target |
|---|---|---|
| Startup-paket | från 1 500 kr/mån | New companies, up to 50 transactions/month |
| Small Business-paket | från 2 199 kr/mån | Growing companies, includes K10 + annual report |
| Medium-paket | från 3 799 kr/mån | Established companies, full CFO support |

*All prices exclude VAT (moms). Fixed price after needs analysis.*

---

## 📞 Contact

**Drekonomi AB**
Sollentuna, Stockholm, Sweden
📱 +46 76 042 51 55
📧 info@drekonomi.se

---

*Built with quiet luxury — ivory palette, Playfair Display typography, and gold accents.*
