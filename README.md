# The Gentlemen's Beer Shop

Website and brand assets for **The Gentlemen's Beer Shop**, Komárno, Slovakia.

Live site → [GitHub Pages URL after deploy]

---

## Structure

```
GentlemensBeerShop/
├── index.html          ← Main website (single-page)
├── brand-kit.html      ← Brand identity reference guide
├── Assets/
│   ├── 01_Logos/               Logo files (PNG + production PDFs)
│   ├── 02_Photography/
│   │   ├── Product_Photography/ DSC series — cans, bottles, pours
│   │   └── Branded_Glassware/   Branded glass & atmosphere shots
│   ├── 03_Social_Media/         Facebook & email graphics
│   ├── 04_Seasonal_Campaigns/   Christmas & public holiday artwork
│   ├── 05_Menus/                Menu design files
│   ├── 06_Print_Production/     Print-ready PDFs (excluded from repo — see .gitignore)
│   └── 08_ArtWork/              Illustration assets
```

## Local development

No build step required. Open `index.html` directly in a browser, or serve locally:

```bash
# Python 3
python3 -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`

## Deploy to GitHub Pages

1. Push to GitHub (see setup commands below)
2. Go to repo **Settings → Pages**
3. Set source: **Deploy from branch → main → / (root)**
4. GitHub Pages URL: `https://<your-username>.github.io/GentlemensBeerShop/`

## Contact / Brand

- **Address:** Mederčská 732/15, 945 01 Komárno, Slovensko
- **Email:** gentlemensbeer@gmail.com
- **Phone:** +421 915 390 227
- **Facebook:** [facebook.com/gentlemensbeer](https://www.facebook.com/gentlemensbeer/)
- **Instagram:** [@gentlemensbeershop](https://www.instagram.com/gentlemensbeershop/)
