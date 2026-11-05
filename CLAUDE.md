# CLAUDE.md

Repo: ict-vocabulaire

## Wat dit is
Een doorverwijzing. De module is opgegaan in TaalHulp (repo antonnoe/taalhulp-fr) op 24-10-2026, deze repo verwijst alleen nog door (README.md).

## Live adres
Niet in de repo vastgelegd. De doorverwijzing wijst naar https://taalhulp-fr.vercel.app/?domein=digitaal (index.html).

## Opbouw
- `index.html`: pagina "Verhuisd naar TaalHulp", noindex, stuurt na ongeveer 0,8 seconde door; in een frame wordt `embed=1` aan het doeladres toegevoegd
- `README.md` en `LICENSE`

## Techniek
Eén statische HTML-pagina met een meta-refresh en een klein inline script, lettertype Mulish via Google Fonts. Geen build, geen pakketten.

## Externe diensten en namen van omgevingsvariabelen
- TaalHulp op Vercel (doel van de doorverwijzing)
- Google Fonts (Mulish)
- Omgevingsvariabelen: geen

## Hoe het live gaat
Niet in de repo vastgelegd (geen vercel.json, CNAME of workflow).

## Regels en besluiten
- Deze repo verwijst alleen nog door naar TaalHulp, er komt hier geen inhoud meer bij (README.md)

## Laatst nagelopen
Laatst nagelopen: 5 november 2026
