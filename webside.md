# Webside på github

Denne guide forklarer, hvordan man opsætter en simpel hjemmeside med HTML og CSS, og hvordan man får den online via GitHub Pages.

##  1. Projektstruktur
For at browseren (og GitHub) kan forstå dit projekt, skal filerne ligge rigtigt:

* `index.html` (Din hovedfil - skal ligge i "roden" af mappen)
* `style.css` (Din styling)
* `billeder/` (Mappe til dine billedfiler)
    * `moon.jpeg`



##  2. Forbindelse mellem filerne
For at dine filer kan "tale sammen", skal du bruge korrekte stier:

### HTML til CSS
I din `<head>` sektion i `index.html` skal du linke til din CSS-fil:
```html
<link rel="stylesheet" href="style.css">

```

### HTML til Billeder

Når dit billede ligger i en undermappe, skal du fortælle stien til mappen først:

```html
<img src="billeder/moon.jpeg" alt="Beskrivelse af billede">

```

##  3. Aktivering af GitHub Pages (Gør siden live)

Når du har uploadet dine filer til GitHub, kan du gøre hjemmesiden tilgængelig for hele verden:

1. Gå til dit repository på GitHub.com.
2. Klik på ⚙️ **Settings** (Indstillinger).
3. Vælg **Pages** i menuen til venstre.
4. Under **Branch**, vælg `main` (eller `master`) og klik på **Save**.
5. Vent ca. 1-2 minutter. GitHub giver dig et link øverst på siden (f.eks. `https://brugernavn.github.io/projekt-navn/`).

## 4. Samarbejde via Fork & Pull Request

Hvis en anden vil foreslå ændringer til dit design:

1. **Fork:** De tager en kopi af dit web-projekt.
2. **Edit:** De ændrer f.eks. baggrundsfarven i `style.css`.
3. **Pull Request:** De sender ændringen til dig.
4. **Merge:** Du godkender ændringen, og din live-hjemmeside opdateres automatisk!
