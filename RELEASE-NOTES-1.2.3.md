# VakInZicht Kunstvakken 1.2.3

Deze update bevat alle verbeteringen sinds 1.2.2.

- **Afdrukken:** de berekende keuze staand/liggend wordt nu doorgegeven aan het macOS-afdrukvenster. Richting en papierformaat zijn daar beschikbaar. De globale printervoorinstellingen worden niet overschreven. PDF-export blijft behouden.
- **Schooljaarinstellingen:** een apart blok **Toetsweken & eindtoetsen**, naast Periodes. Beheer toetsweken, praktische eindtoetsen en theoretische eindtoetsen met naam, datumbereik en schoolbrede of leerjaargebonden doelgroep. Verwijderen vraagt bevestiging.
- **Jaaragenda-import:** expliciete toetsweekomschrijvingen en praktische/theoretische eindtoetsen (ook CSPE/CSE) worden herkend. Een aangegeven dinsdagstart wordt meegenomen; voorbereidende lesdagen worden niet als toetsweek afgetrokken. Herkende datums en doelgroepen blijven vóór import controleerbaar.
- **Aftellers:** instellingen en jaaragenda gebruiken dezelfde gegevens. ‘Toetsweken aftrekken’ geldt bij Lesweken alleen voor toetsweken die bij de gekozen doelgroep horen, niet automatisch voor alle eindtoetsen.

Eerder geïmporteerde activiteiten worden niet achteraf stilzwijgend geherclassificeerd. Pas zo nodig hun soort aan in de jaaragenda. De normale importbeveiliging tegen duplicaten en overschrijven van eigen wijzigingen blijft gelden.

## Installatie en beperkingen

Voor macOS op Apple silicon. Bestaande app-identiteit, opslaglocatie en updater-sleutel blijven gelijk. Maak vóór bijwerken een actuele gegevensbackup.

De updatebundel is cryptografisch ondertekend. De PKG bevat een ad-hocondertekende app maar is **niet door Apple genotariseerd** en niet met Developer ID ondertekend. macOS kan daarom waarschuwen.

De nieuwe native afdrukroute is gecompileerd en automatisch getest op overdracht van richting; een echte Canon-afdruk en installatie/update op een afzonderlijke pilot-Mac zijn nog niet beproefd. Controleer dit vóór brede uitrol, naast demo, bestaande gegevens en opslaan/heropenen.
