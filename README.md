# Hemsida-mall (HTML5 + CSS3)

Denna mall innehåller:
- `index.html` - startsida med meny, header (hero), body (sektioner) och footer.
- `css/styles.css` - all styling.
- `assets/background.svg` - inbyggd bakgrund om du inte har laddat upp en egen.
- Tips: byt ut `assets/background.jpg` mot din uppladdade bild för att använda önskat bakgrundsbild.

## Publicera på GitHub Pages (snabbguide)
1. Skapa ett nytt repo på GitHub (t.ex. `mitt-hemsida`).
2. Kopiera filerna från denna mapp till repo: root ska innehålla `index.html`.
3. Kör lokalt:
   ```
   git init
   git add .
   git commit -m "Första version"
   git branch -M main
   git remote add origin git@github.com:<ditt-anvandarnamn>/<repo>.git
   git push -u origin main
   ```
4. Gå till repo -> Settings -> Pages och välj branch `main` / root. Spara.
5. Vänta ett par minuter och din sida är live på `https://<ditt-anvandarnamn>.github.io/<repo>/`

## Byta bakgrund till din uppladdade bild
1. Placera din bild i `assets/` och döp den till `background.jpg`.
2. Commita och pusha till GitHub.
3. CSS prioriterar `background.jpg`; om den finns används den istället för SVG-fallback.

Lycka till!