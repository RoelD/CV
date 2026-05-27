# Online CV - Roel Deckers

Deze repository bevat de statische GitHub Pages-website voor het online CV van Roel Deckers.

## Inhoud

- `index.html` - Nederlandse CV-pagina
- `indexEng.html` - Engelse CV-pagina
- `_layouts/default.html` - gedeelde HTML-layout
- `assets/css/style.css` - leesbare Material Design 3 Expressive geïnspireerde stylesheet
- `assets/css/style.min.css` - geminificeerde stylesheet voor productie
- `assets/faviconlogo.png` en `assets/icons/` - favicon en app-icon bestanden
- `site.webmanifest` - web app manifest
- `robots.txt` - zoekmachine-instructies

## Designrichting

Het ontwerp is herschreven richting Material Design 3 Expressive: kleurrijker, persoonlijker en app-achtiger, met grotere vormen, zachte surfaces, expressive cards, chips, duidelijke states en een responsive layout zonder externe CSS- of JavaScript-frameworks.

## Publicatie

GitHub Pages bouwt de site automatisch vanuit de repository. Controleer na upload of de PDF-route in `_config.yml` klopt:

```yml
cv_pdf_url: "/assets/certificates/CV_Roel_Deckers.pdf"
```

Als de PDF anders heet, pas alleen deze waarde aan.
