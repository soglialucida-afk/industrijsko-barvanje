# AGIS — prašno barvanje, d.o.o.

Statična spletna stran. Brez frameworkov, brez build koraka.

## Struktura
```
AGIS-site/
├── index.html      # vse vgrajeno (HTML + CSS + JS)
├── img/            # fotografije (placeholder zaenkrat prazno)
├── docs/           # PDF specifikacije
├── netlify.toml    # deploy + headers
└── README.md
```

## Razvoj
Odpri `index.html` v brskalniku. Brez orodjarne.

## Deploy
Netlify, drag-and-drop ali Git. `netlify.toml` že nastavljen.

## TODO pred produkcijo
- [ ] Zamenjaj placeholder slike v `/img/` (glej oznake v HTML — `IMG_PENDING`)
- [ ] Dodaj favicon (`/img/favicon.ico`, `/img/favicon-32.png`, `/img/apple-touch-icon.png`)
- [ ] Vstavi pravi GA4 measurement ID (`G-XXXXXXXXXX`)
- [ ] Potrdi korporativni accent — trenutno `#c0392b` (oksidno rdeča)
- [ ] Naloži `/docs/agis-tehnicna-specifikacija.pdf`
- [ ] Preveri Netlify Forms — `data-netlify="true"` in `enctype="multipart/form-data"` že nastavljen
- [ ] Cookie consent — trenutno minimal placeholder, po potrebi zamenjaj z Cookiebot/Iubenda
- [ ] og:image — generiraj 1200×630 reprezentacijo (priporočeno: fotografija proizvodnje + logotip)
- [ ] Zamenjaj koordinate Google Maps embeda, če lokacija ni točna
