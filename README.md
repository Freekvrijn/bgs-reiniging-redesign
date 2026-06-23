# BGS-Reiniging — redesign (voorbeeld)

Moderne herontwerp-voorstel voor [bgs-reiniging.nl](https://bgs-reiniging.nl) — specialist
in bestrating reinigen en blijvend onkruidvrij invoegen. Statische voorbeeldsite om als
preview naar de klant te sturen.

> Dit is **versie 1** (fris & clean, merkgroen). Er is ook een **versie 2** met een warmere,
> ambachtelijke uitstraling in een aparte map (`bgs-reiniging-redesign-v2`), zodat de klant
> kan kiezen.

## Bekijken
Open `index.html` in je browser, of start een lokale server:
```bash
cd bgs-reiniging-redesign && python3 -m http.server 8000
# open http://localhost:8000
```

## Designkeuzes
| Onderdeel | Keuze |
|---|---|
| Sfeer | Fris & clean, vertrouwd |
| Kleuren | Merkgroen — emerald `#1A9768`, donkergroen `#0B3D24`, mintwit, helderwit |
| Typografie | Modern & helder (Hanken Grotesk) |
| Focus | Offerteaanvragen + vertrouwen (voor/na + reviews) |

Alle kleuren staan als CSS-variabelen bovenin `assets/css/styles.css`.

## Pagina's
- `index.html` — hero, diensten, voor/na-slider, waarom BGS, reviews, werkgebied, CTA
- `diensten.html` — reinigen / onkruidvrij invoegen / impregneren + tarieven
- `resultaten.html` — gerealiseerde opdrachten (voor/na-sliders + galerij)
- `over.html` — Richard van Breugel, werkwijze, sinds 2017
- `beoordelingen.html` — echte klantbeoordelingen
- `contact.html` — offerteformulier (demo) + gegevens + kaart

## Inhoud
Alle teksten, foto's, het logo en de beoordelingen komen **1:1 van de huidige site**.
Het interactieve **voor/na-schuifje** gebruikt hun echte voor- en na-foto's.

## Vervolg (na akkoord)
1. **Werkend offerteformulier** (verzending per e-mail, met optie om foto's mee te sturen).
2. SEO & eventuele analytics overzetten.
3. Beeldoptimalisatie (WebP, juiste formaten).
4. Cookie-/privacybanner + privacybeleid.

## Techniek
Pure HTML/CSS/JS, geen build-stap. Extern: Google Font (Hanken Grotesk) en een
OpenStreetMap-embed.
