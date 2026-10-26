# WoW Forever – Android-nedräkning

Det här är en liten installerbar webbapp (PWA) med WoW-fantasytema och live-nedräkning till **5 november 2026 kl. 00:00 svensk tid**.

## Viktigt
Det här blir en appgenväg på hemskärmen, inte en inbyggd Android-widget som ligger direkt på startskärmen med uppdaterande siffror. Androids vanliga hemskärmswidgetar kräver en native app eller en widget-app som KWGT. PWA:n öppnas i eget appfönster och uppdaterar nedräkningen varje sekund när den är öppen.

## Publicera gratis med GitHub Pages
1. Öppna https://github.com/ och skapa/logga in på ett konto.
2. Skapa ett nytt repository, exempelvis `wow-forever-countdown`.
3. Ladda upp `index.html`, `manifest.json` och `sw.js` från den här mappen till repositoryts rot.
4. I repositoryt: **Settings → Pages**.
5. Under **Build and deployment**, välj **Deploy from a branch**, välj `main` och `/ (root)`, tryck **Save**.
6. Vänta tills GitHub visar din publicerade adress, normalt `https://DITT-KONTO.github.io/wow-forever-countdown/`.
7. Öppna adressen på Android i **Chrome**.
8. Tryck på Chrome-menyn **⋮ → Installera app** eller **Lägg till på startskärmen** (texten kan variera).
9. Bekräfta. Ikonen WoW Forever finns nu på hemskärmen.

## Ändra datum
Nedräkningen använder `2026-11-05T00:00:00+01:00` i `index.html`, alltså svensk normaltid (CET). Om Blizzard ändrar releasetiden ändrar du datumsträngen där och publicerar filen på nytt.

## Källa till releasetid
Blizzard anger global lansering 4 november 2026 kl. 15:00 Pacific Standard Time. Det motsvarar 23:00 UTC och 00:00 CET den 5 november i Sverige.
Officiell nyhet: https://worldofwarcraft.blizzard.com/en-gb/news/24302093

Bakgrund: background.png används nu som helskärmsbakgrund. Ladda upp även denna fil till samma GitHub Pages-mapp som de andra filerna.
