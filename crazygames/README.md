# CrazyGames submission package

Denna mapp innehåller instruktioner och färdig text för att skicka spelet "Dodge the Blocks" till CrazyGames.

Filer i mappen:
- submission.txt — färdiga texter (title, short/long descriptions, tags, controls) som du kan kopiera in i formuläret.
- zip_instructions.sh — enkel script/kommando för att skapa en ZIP som CrazyGames vill ha (index.html i rot).
- thumbnail_instructions.md — rekommendationer för thumbnail + enkla steg för att skapa en bild.

Notera:
- Huvudspelfilen index.html ligger i repo-roten och är redan optimerad för publicering: inga alert()-popups, mobilkontroller och highscore i localStorage.
- Testa att spelet körs lokalt innan du laddar upp.

Hur du skapar ZIP snabbt (rekommenderat):
1. Ladda ner repo som ZIP från GitHub: https://github.com/Leon-smoljan/Dodge-the-blocks/archive/refs/heads/main.zip
2. Extrahera och öppna katalogen. Se till att index.html ligger i mappen du ska zippa.
3. Skapa en ny ZIP där index.html ligger i rot: zip -r dodge-the-blocks-crazygames.zip index.html assets/ (om du har en assets-mapp)

Lycka till!