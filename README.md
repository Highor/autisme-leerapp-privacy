# Privacy-pagina publiceren

`index.html` is een volledig zelfstandige Engelstalige privacy-pagina. De pagina
gebruikt geen externe scripts, cookies, analytics, afbeeldingen of lettertypen.

## Aanbevolen route: GitHub Pages

1. Maak een gratis GitHub-account als dat nog niet bestaat.
2. Maak een openbare repository, bijvoorbeeld `autisme-leerapp-privacy`.
3. Upload `index.html` naar de hoofdmap van de repository.
4. Open in de repository `Settings > Pages`.
5. Kies publiceren vanuit de hoofdbranch en de hoofdmap.
6. Gebruik eerst de toegekende `https://<naam>.github.io/...`-URL in Play
   Console.
7. Optioneel: voeg in GitHub Pages `privacy.highor.com` als custom domain toe en
   maak daarna bij de domeinprovider een CNAME-record `privacy` dat verwijst naar
   `<githubnaam>.github.io`.
8. Schakel `Enforce HTTPS` in zodra GitHub dit beschikbaar maakt.

Voeg het eigen subdomein eerst in GitHub Pages toe en pas daarna in DNS, zodat
een ander het subdomein niet kan claimen. DNS- en HTTPS-activatie kunnen tot 24
uur duren.

## Alternatief: Cloudflare Pages

Cloudflare Pages kan hetzelfde losse bestand gratis hosten. Het geeft een
`*.pages.dev`-URL en ondersteunt `privacy.highor.com` via een CNAME-record zonder
dat het hoofddomein naar Cloudflare hoeft te verhuizen.

## Voor Google Play

Controleer vóór indienen dat de uiteindelijke URL:

- zonder login openbaar bereikbaar is;
- HTTPS gebruikt;
- niet downloadt maar als gewone webpagina opent;
- exact de ingediende app en actuele gegevenspraktijken beschrijft;
- een werkend supportadres bevat.
