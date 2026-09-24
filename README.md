# Vlinders determineren

Oefenspel voor het herkennen van de Nederlandse dagvlinders: mannetjes en vrouwtjes, boven- en onderzijde. Foto's worden live opgehaald van Wikimedia Commons.

## Publiceren op GitHub Pages
1. Maak een repository en zet `index.html` (en eventueel `curated.json`) in de root.
2. Ga naar Settings > Pages, kies "Deploy from a branch", branch `main`, map `/ (root)`.
3. Na een minuut staat het spel op `https://<gebruikersnaam>.github.io/<repository>/`.

## Hoe de foto's worden gekozen
Per soort zoekt het spel op Wikimedia Commons naar de wetenschappelijke naam (en synoniemen). Sekse en zijde worden afgeleid uit bestandsnaam, categorieën en beschrijving (onder meer male/female, upperside/underside, dorsal/ventral, ♂/♀, en Duitse, Franse en Nederlandse varianten). Rupsen, eitjes, kaarten en illustraties worden overgeslagen. Resultaten worden 30 dagen in de browser bewaard.

## Correcties delen
Labels die niet kloppen corrigeer je op het tabblad "Soorten en foto's". Exporteer ze als `curated.json` en commit dat bestand naast `index.html`; iedereen die de pagina opent krijgt dan dezelfde correcties.

## Soortenlijst aanpassen
Bovenaan het script staat de lijst `RAW`: Nederlandse naam, wetenschappelijke naam, familie, lijkt-op-groep (voor de moeilijke meerkeuze), status, of mannetje en vrouwtje duidelijk verschillen, en eventuele synoniemen.

## Licenties
Elke foto wordt getoond met maker en licentie en linkt naar de bronpagina op Wikimedia Commons.
