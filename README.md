# VakInZicht releases

Publieke, ondertekende updatebestanden voor VakInZicht Kunstvakken.

Deze repository bevat geen broncode en geen gebruikersgegevens. `latest.json`
verwijst naar de nieuwste interne Apple-silicon-update. De app controleert de
updaterhandtekening met zijn ingebouwde publieke sleutel.

De PKG-installer is beschikbaar voor handmatige installatie of herstel. Deze
interne/pilotuitgave is voor macOS met Apple silicon; de app is ad-hoc ondertekend
en niet Apple-genotariseerd. Maak vóór installeren een actuele gegevensback-up.
Bestaande brugversies kunnen hetzelfde pakket via de ondertekende app-updater
ontvangen. Tussenupdates zijn niet nodig.

## Versie 1.3.9

[Release-uitleg](RELEASE-NOTES-1.3.9.md) ·
[Installer 1.3.9](VakInZicht%20Kunstvakken%201.3.9.pkg) ·
[Controlesommen](CHECKSUMS-1.3.9.txt)

- Overzichtelijkere bibliotheek met aparte mappen, compactere zoekbalk en rustige menu’s.
- Mappen en submappen eenvoudig ordenen en verplaatsen door te slepen.
- Handiger beheer: onderdelen toevoegen en meerdere bijdragen tegelijk controleren, vrijgeven en verplaatsen.
- Optioneel eindresultaat op de docentenlijst en duidelijkere schaalnamen, versieaanduidingen en jaaragendabronnen.

De centrale nieuwe indeling in Gedeeld en Algemeen wordt afzonderlijk op de
server omgeschakeld. De app is daarop voorbereid en blijft tot die omschakeling
de bestaande centrale bediening gebruiken. Installeren alleen activeert dit
niet. Na de serveromschakeling is deze Mac-update nodig voor veilig centraal
wijzigen; oudere apps kunnen een algemene foutmelding tonen.

De installer wijzigt geen accounts of online sessiebeleid. Telefoonversie 14
blijft ongewijzigd. Offline Gedeeld/Algemeen, een centrale prullenbak van 30 dagen,
gedeelde-agenda-synchronisatie en beheerdelegatie zijn geen onderdeel van deze
update. De bestaande demo-isolatie en eerdere verbeteringen blijven inbegrepen.
Bestaande demoresten worden niet automatisch verwijderd; laat die eerst veilig
controleren.

## Eerdere versies

- [1.3.8: mapknoppen en centrale submappen](RELEASE-NOTES-1.3.8.md)
- [1.3.7: bibliotheekbediening en apparatenoverzicht](RELEASE-NOTES-1.3.7.md)
- [1.3.6: eenvoudiger aanmelden](RELEASE-NOTES-1.3.6.md)
- [1.3.5: preventieve demo-hotfix](RELEASE-NOTES-1.3.5.md)
- [1.3.4: herstel van delen en groepsuitzonderingen](RELEASE-NOTES-1.3.4.md)
- [1.3.3: meer bibliotheekbeheer](RELEASE-NOTES-1.3.3.md)
- [1.3.2: archiveren en mapmeldingen](RELEASE-NOTES-1.3.2.md)
- [1.3.1: bibliotheek en selectieacties](RELEASE-NOTES-1.3.1.md)
- [1.3.0: vernieuwde bibliotheek](RELEASE-NOTES-1.3.0.md)
- [1.2.9](RELEASE-NOTES-1.2.9.md)
- [1.2.5](RELEASE-NOTES-1.2.5.md)

Oudere installers blijven behouden. Na de centrale omschakeling is teruggaan naar
oude bibliotheekschrijfroutes niet veilig ondersteund. Gebruik bij problemen een
gecontroleerd herstel, met behoud van de actuele administratie en herstelkopie.
Broncode wordt afzonderlijk privé beheerd.
