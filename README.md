# Brian – ściąga dla opiekuna

Statyczna strona: jeden plik `index.html` (CSS + JS w środku, bez zdjęć, pixel-art rysowany w SVG przez JS).
Live: https://ddknapik.github.io/brian-hq/ (GitHub Pages, gałąź `main`, katalog `/`, repo `ddknapik/brian-hq`).

## Edycja
- Treść sekcji: HTML w `index.html` (`#plan`, `#jedzenie`, `#wyprawka`, `#komendy`).
- Karta „Co teraz?”: tablica `B` w skrypcie (start w minutach od północy, czas Europe/Warsaw), `MEALS`, `POOS`, `STEP_OF` (który punkt planu podświetlić).
- Pixel Brian: `BODY`, `LEG`, `POS` (4 klatki chodu); ikony: `ICONS`; kolory: `PAL`.

## Redeploy
```bash
cd /workspace/brian-site
git add -A && git commit -m "Aktualizacja" && git push
```
Pages przebudowuje się w ~1 min. Nie wrzucaj zdjęć (EXIF/GPS).
