---
layout: default
titel: template
---

## <span><img class="inline-h1-icon" src="../assets/svg/info.svg" /> Parkeren in Eindhoven</span>

Veel overheidsinstanties bieden data online aan. Dat is fijn, want met die openbare gegevens kun je jouw dashboard makkelijk beter maken.

In dit werkboek worden [postcode gegevens van Eindhoven](https://data.eindhoven.nl/explore/dataset/postcode-buurt-wijk/information/?disjunctive.buurtnaam&disjunctive.wijknaam&disjunctive.stadsdeelnaam&disjunctive.straatnaam&disjunctive.postcode6&disjunctive.postcode4&disjunctive.hsnr_aant) gekoppeld aan [parkeerplaatsen in Eindhoven](https://data.eindhoven.nl/explore/dataset/parkeerplaatsen/information/?disjunctive.straat&disjunctive.type_en_merk&disjunctive.aantal).

Door die informatie te combineren kun je de bereikbaarheid van voorzieningen bepalen en adviezen geven voor bijvoorbeeld de vestiging van een winkel.

Bepaal zelf welke informatie belangrijk jij zou willen presenteren aan de gemeenteraad, de wijkagent, een buurthuis, enz. Kijk wat een passende manier is om de gegevens te laten zien. Is dat een pie-chart, een staafdiagram of een andere grafiek?

### <span><img class="inline-h2-icon" src="../assets/svg/crosshairs.svg" /> Doel</span>

Om gegevens van verschillende bronnen te kunnen combineren, moet je de data analyseren en bepalen hoe je die aan elkaar kunt koppelen. Daarbij kan het zijn dat je `data cleaning` moet toepassen om te zorgen dat de data niet vervuild wordt. Daarna kun je de gegevens weergeven in allerlei grafieken en overzichten.

In dit voorbeeld wordt expliciet de bibliotheek `leaflet` gebruikt om de informatie weer te geven op de kaart van Eindhoven. Daarmee krijgt de informatie een extra dimensie.

> De `leaflet` bibliotheek is niet beschikbaar op de online omgeving. Daarvoor moet je R op je eigen laptop geïnstalleerd hebben.

### <span><img class="inline-h2-icon" src="../assets/svg/brain.svg" /> Voorkennis</span>

Kennis van SQL is vereist. In eerdere opdrachten is alleen aandacht besteed aan het `SELECT` statement, maar voor de data cleaning is kennis van het `UPDATE` statement vereist. Kijk [hier](https://learn.microsoft.com/en-us/sql/t-sql/queries/update-transact-sql?view=sql-server-ver17) voor de beschrijving ervan.

Kijk [hier](https://r-charts.com/spatial/interactive-maps-leaflet/) voor meer informatie over de `leaflet` bibliotheek.

### <span><img class="inline-h2-icon" src="../assets/svg/download.svg" /> Materialen</span>

- [Data bestanden](../dataset/parkeren-in-eindhoven.zip) een zip-bestand met alle databestanden in Excel formaat.
- [Notebook](../notebook/parkeren-in-eindhoven.Rmd) In het notebook is het inlezen van de bestanden opgenomen en er zijn al chunks aangemaakt voor alle opdrachten.
- [Voorbeeld](../werkboek/parkeren-in-eindhoven.pdf)
