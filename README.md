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

## Versie 1.3.12

[Release-uitleg](RELEASE-NOTES-1.3.12.md) ·
[Installer 1.3.12](VakInZicht%20Kunstvakken%201.3.12.pkg) ·
[Controlesommen](CHECKSUMS-1.3.12.txt)

- Gemiddelde beoordeling op de docentenlijst.
- Overzichtelijkere bibliotheek met handiger zoeken en beheren.
- Mappen en submappen eenvoudig ordenen en verplaatsen door te slepen.
- Gedeeld en Algemeen ook offline gebruiken.
- Jaaragenda makkelijker bijwerken, exporteren, verwijderen of leegmaken.
- Kleine bugfixes.

Deze herstelupdate verhelpt de gereproduceerde fout `OFFLINE_CACHE_INVALID`
door het cloud-datumformaat correct te verwerken. De offlinekopie bevat alleen
toegestane gebruikersinhoud en wordt bij online openen van de bibliotheek
vernieuwd. De ongewijzigde bovengrens is 90 dagen na de laatste geslaagde online
controle; tijdelijk gedeeld materiaal kan eerder verlopen. Dit verandert geen
aanmeldduur; centrale wijzigingen blijven online. Zonder verbinding zijn latere
intrekkingen pas bij de volgende online controle of uiterlijk na afloop van de
offlinegeldigheid bekend. Eigen werk blijft behouden.

Deze Mac-update voert geen serveromschakeling uit. Accounts, rechten en online
sessiebeleid veranderen niet. Telefoonversie 14 blijft ongewijzigd. Herhaalde
macOS-sleutelhangertoestemming bij een nieuwe apphandtekening wordt hiermee niet
structureel opgelost. Een centrale prullenbak, gedeelde-agendasynchronisatie,
beheerdelegatie en de nieuwe analyseknop vallen buiten deze update. Bestaande
demo-isolatie blijft inbegrepen; demoresten worden niet automatisch verwijderd.

## Eerdere versies

- [1.3.11: offlinebibliotheek en vaste selectiebalk](RELEASE-NOTES-1.3.11.md)
- [1.3.10: jaaragenda beheren, export en kleine verbeteringen](RELEASE-NOTES-1.3.10.md)
- [1.3.9: bibliotheekindeling, slepen en docentenlijst](RELEASE-NOTES-1.3.9.md)
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
