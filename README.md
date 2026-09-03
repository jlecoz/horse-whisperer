# Gaëlle HAMELIN — site vitrine

Layout-first static page based on the brand mockup and `Socle_de_marque_Gaelle_Hamelin`.

## Structure

- `index.html` — page sections (Bootstrap columns + custom CSS)
- `css/styles.css` — brand tokens, 8px spacing scale, component styles
- `content/` — source copy (`Socle_de_marque_Gaelle_Hamelin.docx`, extracted `brand-copy.txt`)
- `assets/design-reference.jpg` — visual reference mockup

## Update content

1. Edit the section copy directly in `index.html` (hero, services, about, CTA).
2. Or refresh from the brand doc: replace `content/Socle_de_marque_Gaelle_Hamelin.docx` and re-extract text.
3. Swap image URLs for local files in `assets/` when final photos are ready:
   - Hero: tall crop, soft organic top edge (`.hero-photo`)
   - Particuliers: wavy top (`.service-photo--wave`)
   - Entreprises: pill crop (`.service-photo--pill`)
   - Approche: circular (`.philosophy-photo`)

## Brand tokens

In `css/styles.css` `:root`:

- Olive `#4a5235` / dark `#2f3422`
- Terracotta `#c07a4a`
- Tan `#b08968`
- Cream bg `#f7f3ec`

Fonts: Cormorant Garamond (serif), Great Vibes (script), DM Sans (UI/body).

## Preview

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```
