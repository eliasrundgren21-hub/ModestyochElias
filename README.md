# Modesty & Elias — bröllopshemsida

En statisk hemsida för GitHub Pages. Ingen installation eller byggprocess behövs.

## Publicera

1. Packa upp ZIP-filen på din dator.
2. Skapa ett repository på GitHub, exempelvis `brollop`.
3. Ladda upp de uppackade filerna direkt i repositoryts rot. `index.html` och `inbjudningskort-original.jpg` måste ligga bredvid varandra. Ladda inte upp enbart ZIP-filen.
4. Öppna repositoryts Settings → Pages.
5. Under Build and deployment, välj Deploy from a branch. Välj grenen main och mappen / (root), och spara.
6. När publiceringen är klar visas webbplatsens adress på samma sida. För ett repository som heter brollop blir adressen normalt https://DITT-ANVANDARNAMN.github.io/brollop/.

## Innehåll

- index.html: all HTML, CSS och JavaScript, inklusive kortets vändanimation.
- inbjudningskort-original.jpg: inbjudningskortet i originalupplösning.
- .nojekyll: gör att GitHub Pages serverar filerna utan Jekyll-bearbetning.

## Innan ni delar länken med gäster

Hemsidan innehåller fortfarande exempeluppgifter för vigselplats, festlokal, tider, klädsel och OSA-datum. OSA-knappen använder exempeladressen hej@modestyochelia.se. Ändra dessa uppgifter i index.html till era riktiga uppgifter. Knappen öppnar besökarens e-postprogram; sidan sparar inga svar i en databas.

Kortets text och bild är oförändrade. Övriga fotografier hämtas från Unsplash och typsnitt från Google Fonts, så dessa delar behöver internetanslutning.

## Uppdatera

Ändra index.html och ladda upp den nya versionen till samma repository. GitHub Pages publicerar ändringarna efter att de sparats på main.
