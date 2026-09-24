# Vlinders determineren

Oefenspel voor het herkennen van de Nederlandse dagvlinders: mannetjes en vrouwtjes. Foto's worden live opgehaald van Wikimedia Commons.

## Publiceren op GitHub Pages
1. Maak een repository en zet `index.html` (en eventueel `curated.json`) in de root.
2. Ga naar Settings > Pages, kies "Deploy from a branch", branch `main`, map `/ (root)`.
3. Na een minuut staat het spel op `https://<gebruikersnaam>.github.io/<repository>/`.

## Hoe de foto's worden gekozen
Per soort zoekt het spel op Wikimedia Commons naar de wetenschappelijke naam (en synoniemen). De sekse wordt afgeleid uit bestandsnaam, categorieën en beschrijving (onder meer male/female, ♂/♀, en Duitse, Franse en Nederlandse varianten). Rupsen, eitjes, kaarten en illustraties worden overgeslagen. Resultaten worden 30 dagen in de browser bewaard.

## Kenmerken bij foute antwoorden
Bij een fout antwoord toont het spel waar je op moet letten: een gerichte tip voor bekende verwarringsparen (lijst `TIPS`), de kenmerken van de juiste soort en van jouw keuze naast elkaar (lijst `KEN`), een vergelijkingsfoto van de soort die je koos en een link naar de herkenningssectie op vlinderstichting.nl. De kenmerkteksten zijn een eigen samenvatting, geen overgenomen tekst. Wijkt de naam op de site van De Vlinderstichting af, zet dan de juiste slug als achtste element in de regel van die soort in `RAW` (zet bij geen synoniemen `[]` op de zevende plek).

## Correcties delen
Labels die niet kloppen corrigeer je op het tabblad "Soorten en foto's". Exporteer ze als `curated.json` en commit dat bestand naast `index.html`; iedereen die de pagina opent krijgt dan dezelfde correcties.

## Soortenlijst aanpassen
Bovenaan het script staat de lijst `RAW`: Nederlandse naam, wetenschappelijke naam, familie, lijkt-op-groep (voor de moeilijke meerkeuze), status, of mannetje en vrouwtje duidelijk verschillen, en eventuele synoniemen.

## Licenties
Elke foto wordt getoond met maker en licentie en linkt naar de bronpagina op Wikimedia Commons.
