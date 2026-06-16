GitHub Pages ZIP-pakke for PDF-faktura parser

Innhold:
- index.html      -> hovedsiden som GitHub Pages trenger
- .nojekyll       -> hindrer unødvendig Jekyll-behandling
- README.txt      -> denne filen

Publisering:
1. Pakk ut ZIP-filen.
2. Last opp ALLE filene til roten av GitHub-repoet ditt.
3. Gå til Settings -> Pages.
4. Velg Deploy from a branch.
5. Velg main og /(root).
6. Åpne GitHub Pages-URL-en din.

Valgfritt for ekstra robusthet:
Legg også disse filene i samme mappe som index.html:
- pdf.min.js
- pdf.worker.min.js

Hvis disse ikke finnes, prøver siden automatisk CDN.
