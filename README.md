# Brian – instrukcja opieki (strona)

Statyczna strona (jeden plik `index.html`, CSS w środku) z instrukcją opieki nad Brianem.

- Treść: edytuj `index.html`. Brakujące dane oznaczone `<span class="todo">[do uzupełnienia]</span>` (żółte podświetlenie) – zastąp je zwykłym tekstem.
- Planowane rzeczy oznacz `<span class="badge">planowane</span>`.
- Zmień datę w stopce (`id="updated"`).

## Hosting / redeploy
Repo: https://github.com/ddknapik/brian-hq (GitHub Pages z gałęzi `main`, katalog `/`).

Zdjęcia: oryginały w `/workspace/brian-site-inputs/` (NIE commitować – mają EXIF/GPS). Wersje web w `img/` (900×1200, bez metadanych), generowane skryptem Pillow (exif_transpose → thumbnail 1200 → zapis JPEG q80 bez EXIF).

```bash
cd /workspace/brian-site
git add -A && git commit -m "Aktualizacja" && git push
```
Pages przebudowuje się automatycznie (~1 min). Adres: https://ddknapik.github.io/brian-hq/
