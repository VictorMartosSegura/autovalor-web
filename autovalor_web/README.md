# AutoValor Landing Page

Web de presentació i descàrrega de l'app AutoValor.

## Estructura

```
autovalor_web/
├── index.html          ← pàgina principal
├── styles.css          ← tots els estils
├── README.md           ← aquest fitxer
└── downloads/
    └── AutoValor.apk   ← posa aquí la teva APK
```

## Com afegir la APK

1. Genera la APK (debug o release) tal com s'explica a la documentació del projecte
2. Copia-la a la carpeta `downloads/` amb el nom `AutoValor.apk`
3. El botó de descàrrega ja funciona automàticament

## Desplegament a Vercel

1. Crea un compte a https://vercel.com si no en tens
2. Puja la carpeta `autovalor_web/` al teu repositori de GitHub (o crea un repo nou)
3. A Vercel: New Project → Import → selecciona el repo
4. Framework Preset: **Other** (és HTML estàtic, sense framework)
5. Deploy

Alternativament pots arrossegar la carpeta directament a https://vercel.com/new (drag & drop).

## Notes

- La carpeta `downloads/` ha d'existir al repo perquè Vercel la serveixi
- Si la APK pesa molt (>100MB), considera allotjar-la a GitHub Releases i canviar l'URL del botó
