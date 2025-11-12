# Může čmelák létat? 🐝

Jednoduchá webová kalkulačka pro výpočet, zda může čmelák létat na základě fyzikálních parametrů.

## Obsah projektu

- `index.html` - kompletní web (HTML + CSS + JavaScript)
- `bumblebee.jpg` - obrázek čmeláka
- `README.md` - tento soubor

## Jak nahodit na GitHub Pages (zdarma hosting)

### 1. Vytvoř GitHub repozitář

1. Jdi na [github.com](https://github.com) a přihlaš se
2. Klikni na "New repository"
3. Pojmenuj ho např. `cmelak-calculator`
4. Nastav ho jako **Public**
5. Klikni "Create repository"

### 2. Nahraj soubory

Máš dvě možnosti:

**A) Přes webové rozhraní (jednodušší):**
1. V repozitáři klikni "uploading an existing file"
2. Přetáhni oba soubory (`index.html` a `bumblebee.jpg`)
3. Klikni "Commit changes"

**B) Přes Git (pokud máš nainstalovaný):**
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TVOJE_JMENO/cmelak-calculator.git
git push -u origin main
```

### 3. Zapni GitHub Pages

1. V repozitáři jdi do **Settings**
2. V levém menu klikni na **Pages**
3. V sekci "Source" vyber **main** branch
4. Klikni **Save**
5. Za chvíli (1-2 min) ti GitHub ukáže URL: `https://tvoje-jmeno.github.io/cmelak-calculator/`

### 4. Vlastní doména (volitelné)

1. Kup doménu (např. na Wedos.cz nebo Cloudflare)
2. V DNS nastavení domény přidej:
   - **A záznam** → IP: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - **CNAME záznam** → `www` → `tvoje-jmeno.github.io`
3. V GitHub Settings → Pages → Custom domain zadej svou doménu
4. Zaškrtni "Enforce HTTPS"

## Jak to funguje

Kalkulačka počítá podle vzorců:

- **Vztlak**: L = 0.5 × ρ × v² × CL × A
  - ρ = hustota vzduchu (kg/m³)
  - v = rychlost (m/s)
  - CL = koeficient vztlaku
  - A = plocha křídel (m²)

- **Váha**: W = m × g
  - m = hmotnost (kg)
  - g = 9.81 m/s²

Pokud Vztlak > Váha → čmelák může létat! ✅

## Credits

- Foto čmeláka: [Michelle Reeves](https://www.pexels.com/cs-cz/foto/leto-zahrada-zavod-rostlina-2662156/)
- Powered by [FOXEM AUTOMATIONS](https://foxem.cz)

## Technologie

- Vanilla HTML/CSS/JavaScript
- Žádné závislosti, žádný build process
- Responsive design
- Žádná analytika, žádné cookies

## Licence

Free to use. Have fun! 🐝
