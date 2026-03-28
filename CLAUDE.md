# CLAUDE.md - huntOS V2

## Projekt
Premium hjemmeside for huntOS jagtstol. Rebuild fra scratch.
Deploy: GitHub Pages via niberdk/huntos-website-v2

## Produkt
- **Navn:** huntOS jagtstol
- **Pris:** 3.500 kr. inkl. moms
- **Vægt:** 6,5 kg
- **Features:** 360° rotation, stabilt anlæg, transportabel (rygsæk)
- **Produceret:** Danmark, patentanmeldt
- **Skaber:** Oskar Schulz, jæger i 40+ år
- **Firma:** huntOS ApS, Langhus 19, 6200 Aabenraa, CVR: 44566133
- **Kontakt:** oskar@huntos.dk, +45 92 92 12 07
- **Webshop:** https://huntos.dk/vare/huntos-stol/

## Design Vision
Cinematisk, premium, dyrt. Stolen i fokus. Store billeder, generøs whitespace.
Tænk Oura Ring / Apple i kvalitetsniveau, men med mørk grøn natur-palette.
IKKE mørkt deprimerende. Mørk og indbydende. Premium outdoor.

## Målgruppe
55-årige danske jægere. Store fingre, kolde hænder. Min 48px touch targets.
Billeder og video overbeviser mere end animationer og tekst.

## Sider
| Fil | Side |
|---|---|
| index.html | Forside (hero, features, brugsrejse, showcase, video, Oscar-citat, CTA) |
| produktet.html | Produktet (karrusel assembly, specs, komponenter, FAQ) |
| om-oscar.html | Om Oskar (historie, motivation, produktion) |
| kontakt.html | Kontakt (form, info, kort) |

Alle deler: styles.css, main.js, nav, footer.

## Farvepalette
| Token | Hex | Brug |
|---|---|---|
| bg-base | #0a0f0a | Primær baggrund |
| bg-elevated | #111811 | Sektioner, cards |
| accent | #6b8f5b | Militærgrøn accent |
| text-primary | #f5f0e8 | Cream tekst |
| brass | #b8976a | Pris-highlight, vigtige tal |

## Typografi
- Playfair Display (headings): tight tracking, vægt 700
- DM Sans (body): weight 400/500, line-height 1.7
- Vægt-ekstremer: 300/400 vs 700. IKKE 400 vs 600.

## Animation
- GSAP + ScrollTrigger til ALLE animationer
- Kun transform + opacity. ALDRIG transition-all
- VARIÉR: stagger, parallax, scale, split text. IKKE kun fade-in-up
- Page load: staggered reveals (0.1s delay)

## Bekræftede "MEGA FEDT" elementer
- "Fra rygsæk til præcist skud" 4-step brugsrejse med action-fotos
- Showcase rows (stor billede + tekst: skydestilling, rygsæk)
- 3 nøglekomponenter (teleskopstang, klips, anlægsbøjle)
- Video sektion
- Oscar-citat over markbillede

## ALDRIG
- Generisk 3-kolonne icon+title+text card grid
- Identiske sektioner med samme padding/struktur
- Inter, Roboto, Open Sans, system fonts
- Emojis
- ae, oe, aa (ALTID æ, ø, å)
- Hvide baggrunde direkte mod dark theme

## Billeder
Se images/ mappen. Organiseret i:
- hero/ (dramatiske vildmark-billeder)
- action/ (Oscar i brug, setup-sekvens)
- product/ (stolen alene)
- detail/ (teleskopstang, klips, anlægsbøjle)
- oscar/ (Oscar bærer stolen)
- video-demo.mp4 (stolen i brug)
