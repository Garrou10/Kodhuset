# Kodhuset AB - Umbraco & Sass

Detta är ett webbprojekt byggt med Umbraco CMS och stylat med Sass.

## Hur man startar webbplatsen
1. Öppna terminalen i Visual Studio Code.
2. Skriv kommandot `dotnet run` och tryck Enter.
3. Öppna webbläsaren och gå till `https://localhost:44354`.

## Hur man bygger CSS (Sass)
Sass-koden ligger i mappen `/Styles`. För att bygga om koden till vanlig CSS som webbplatsen kan läsa, gör så här:
1. Öppna terminalen.
2. Kör kommandot `npm run bygg`.
Den färdiga CSS-filen sparas då automatiskt i `wwwroot/css/site.css`.