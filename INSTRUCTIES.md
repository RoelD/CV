# Instructies - Material Design 3 Expressive versie

Deze zip bevat een volledige design-update van je GitHub Pages CV-site.

## Wat is aangepast

- De volledige layout is opnieuw opgebouwd richting Material Design 3 Expressive.
- De pagina heeft nu een grote expressive hero met profielfoto, blobs/orbs en duidelijke call-to-actions.
- Contactgegevens staan als duidelijke Material-achtige tegels direct bovenaan.
- Werkervaring is herschreven als visuele timeline.
- Oudere werkervaring staat in een uitklapbaar `<details>`-blok, zodat de pagina rustiger en moderner leest.
- Skills en certificaten zijn vormgegeven als chips/tonal buttons.
- De CSS gebruikt design tokens voor kleur, spacing, radius, shadows en typografie.
- De site gebruikt geen externe fonts, icon-libraries, Bootstrap of JavaScript. Dat helpt voor snelheid en GitHub Pages-betrouwbaarheid.
- `style.min.css` is opnieuw gegenereerd en wordt in de layout geladen.
- Theme color en webmanifest zijn aangepast aan de nieuwe stijl.

## Bestanden overschrijven

Upload de inhoud van de map `CV_verbeterd` over je huidige repository heen.

Belangrijk: je bestaande profielfoto moet blijven staan op:

```text
assets/images/Profile/foto2.webp
```

Die afbeelding zit niet in deze zip, omdat hij in je oorspronkelijke repository al aanwezig was. De code verwijst er wel naar.

## Controleren na upload

1. Open `https://roeld.github.io/CV/`.
2. Controleer of je profielfoto zichtbaar is.
3. Controleer of de CV-PDF-download werkt.
4. Controleer of de favicon zichtbaar is in het browsertabblad.
5. Run eventueel PageSpeed Insights opnieuw.

## PDF-pad aanpassen

Als je CV-PDF anders heet, pas dan in `_config.yml` aan:

```yml
cv_pdf_url: "/assets/certificates/CV_Roel_Deckers.pdf"
```


## Laatste update
- Hoofdkleur gewijzigd naar een Material Design 3 Expressive roodpalet.
- Nieuw avatar-icoon gemaakt op basis van de profielfoto en toegepast als favicon, app icon en navbar-icoon.
- theme-color, manifest-kleuren en iconbestanden bijgewerkt.

- Avatar-icoon vierkant gemaakt en zwarte hoekachtergrond verwijderd.
- Paarse resttinten verwijderd uit Over mij en ervaring-secties.

- Interesses-kaart rood gemaakt in plaats van paars/blauw.
- Statusregels “Beschikbaar voor contact” en “Open to contact” verwijderd.
- Donkere modus toegevoegd via globale navigatie-toggle met volledige CSS-varianten.
