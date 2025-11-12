# Může čmelák létat? 🐝

Jednoduchá webová kalkulačka vyvracející slavný mýtus, že čmelák podle zákonů aerodynamiky létat nemůže. Pomocí fyzikálních výpočtů vztlaku a váhy si můžete ověřit, jestli zadané parametry umožňují čmelákovi vzlétnout.

## 🌐 Demo

[Spustit kalkulačku](https://tvoje-url.github.io/cmelak-calculator/) <!-- TODO: Doplň finální URL -->

## 📦 Použití

### Stažení a spuštění lokálně

1. **Klonuj repozitář:**
   ```bash
   git clone https://github.com/tvoje-jmeno/cmelak-calculator.git
   cd cmelak-calculator
   ```

2. **Otevři `index.html` v prohlížeči**
   - Dvojklik na soubor, nebo
   - Spusť lokální server: `python -m http.server 8000`

### Fork a vlastní hosting

1. **Fork** tohoto repozitáře
2. **GitHub Pages**: Settings → Pages → zapni pro main branch
3. **Vlastní doména** (volitelné): Nastav CNAME v DNS a přidej custom domain v GitHub Pages


## 📁 Struktura projektu

```
├── index.html      # Kompletní webová aplikace
├── bumblebee.jpg   # Obrázek čmeláka
└── README.md       # Tento soubor
```

## 🔧 Jak to funguje

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

## 📄 Licence

MIT License - volně použitelné pro jakékoli účely.

## 👨‍💻 Autor

Vytvořil [FOXEM AUTOMATIONS](https://foxem.cz)

---

Máš nápad na vylepšení? Pull requesty jsou vítány! 🐝
