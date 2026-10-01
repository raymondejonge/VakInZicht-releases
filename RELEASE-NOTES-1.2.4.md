# VakInZicht Kunstvakken 1.2.4

Deze update bevat alle lokale verbeteringen sinds 1.2.3.

## Afdrukken en PDF

- De Mac-app gebruikt voor rubricformulieren en docentenlijsten dezelfde vector-PDF als de PDF-export. Rubrictekst, lijnen, aankruisvakjes en geselecteerde scores worden niet opnieuw ingedeeld door de algemene appvormgeving.
- De browser drukt deze documenten af in een afzonderlijk printdocument zonder appstijlen. Dit herstelt de afwijkende rubric- en aankruisvakjesweergave in de webversie.
- Een naslagrubric krijgt eigen liggende A4-pagina’s; de docentenlijst behoudt zijn eigen richting. Bij gemengde richting kan macOS pagina’s draaien om ze op het gekozen papier te plaatsen.
- **Maak rubric passend op pagina** verkleint tekst, lijnen en vakjes samen. Deze optie staat bij een nieuwe afdruk standaard uit, zodat leesbaarheid voorgaat.
- De lijnenschuif en **Standaardlijnen** gebruiken het midden (50). Bewuste eigen waarden blijven behouden.

## Start en aftellers

- De Startbalk toont standaard één rij met maximaal vijf even grote knoppen. Een optionele tweede rij biedt maximaal tien plaatsen. Bij signaalknoppen kan de rij voor aftellers worden gekozen.
- Rijen zijn rechts uitgelijnd en precies zo breed als hun aanwezige knoppen; geen lege lijnen of zware schaduwranden.
- Aftellers volgen hun eigen kleurinstellingen. De standaard Startkleur is dezelfde rustige signaalkleur. Kleuren worden gekozen met zichtbare kleurvakjes.
- Een optionele waarschuwingskleur verandert één, twee of drie kalenderweken vóór de einddatum; standaard geel. Deze waarschuwing geldt op zowel Start als Mijn Taken.
- Het aftelleroverzicht begint volledig ingeklapt. Elke regel toont naam, resterende tijd, datum, telwijze en waarschuwingsinstelling. Eén klik opent of sluit de instellingen.
- **Toetsweken aftrekken van** combineert de keuze om af te trekken met het leerjaar. Bij de eerste inschakeling is leerjaar 4 de standaard; eigen keuzes blijven behouden. Automatische schoolaftellers trekken standaard geen toetsweken af.
- **Prioriteit** geeft een afteller voorrang boven andere aftellers. Zonder prioriteit bepaalt de dichtstbijzijnde datum de volgorde. Voorbije persoonlijke aftellers maken plaats voor de volgende; automatische schoolaftellers volgen hun bronplanning.

## Installatie en bekende grenzen

Voor macOS op Apple silicon. De bestaande bundle-ID, opslaglocatie en update-sleutel blijven gelijk. Maak vóór bijwerken een actuele gegevensbackup. De app-update vervangt niet de inhoudelijke database; de updater maakt vooraf een herstelpunt.

De updatebundel is cryptografisch ondertekend. De PKG bevat een ad-hocondertekende app, maar heeft geen Developer ID en is niet door Apple genotariseerd. macOS of schoolbeheer kan daarom waarschuwen. Dit blijft een interne/pilotdistributie, geen volledig door Apple vertrouwde publieke Mac-distributie.

Automatische controles omvatten browserflows, opslag/import, demo, print/PDF en native macOS print-to-file. Zij bewijzen niet de specifieke Canon-driver of fysieke afdrukuitvoer. Een installatie/update vanaf 1.2.3 op een afzonderlijke pilot-Mac en een kleine Canon-proefafdruk zijn nog handmatig nodig vóór brede uitrol. De bestaande beperking rond strikte CSP blijft onveranderd.
