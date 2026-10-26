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

## Versie 1.3.14

[Release-uitleg](RELEASE-NOTES-1.3.14.md) ·
[Installer 1.3.14](VakInZicht%20Kunstvakken%201.3.14.pkg) ·
[Controlesommen](CHECKSUMS-1.3.14.txt)

- Gemiddelde beoordeling op de docentenlijst.
- Bibliotheek ook offline, met handiger zoeken en rechtenbeheer.
- Mappen verslepen en het linkermenu inklappen.
- Jaaragenda makkelijker bijwerken, exporteren en opruimen.
- Rustigere weergave en kleine bugfixes.

Nieuw in deze update: één inklapknop onderaan het linkermenu, stabielere
bibliotheekbediening tijdens het laden, alleen relevante statusfilters en
een duidelijke knop Gebruikersrechten naast de weergavekeuze. Bestaande bevoegde
beheerders kunnen gewone bibliotheekrechten per actieve gebruiker bewust bewaren.
Notitierechten en accounttoegang blijven daarbij behouden; beschermde
beheeraccounts blijven vergrendeld. Zonder actuele bevoegdheid of bestaande
serverondersteuning wordt het rechtenoverzicht alleen-lezen.

Achtergrondbijwerken maakt tussen de afzonderlijke catalogusaanvragen ruimte
voor actieve aanvragen. Aanmeld-/intrekkingsgrenzen en volledige validatie
blijven verplicht; onvolledige downloads worden niet opgeslagen.

Geen continue live push: automatisch controleren gebeurt bij openen/terugkeren
naar een bron-/typeweergave of via Vernieuwen. De offlinekopie bevat alleen
gecontroleerde gebruikersinhoud, maximaal 90 dagen sinds de laatste geslaagde
online controle; tijdelijk materiaal kan eerder verlopen. Zonder verbinding zijn
latere intrekkingen pas bij de volgende controle of uiterlijk na afloop bekend.
Centrale wijzigingen blijven online; eigen kopieën en beoordelingen worden niet
automatisch aangepast. Aanmeldduur verandert niet.

Deze Mac-update voert geen serveromschakeling uit en verandert op zichzelf geen
bestaande rechten of accounts. Telefoonversie 14 blijft ongewijzigd. Herhaalde
macOS-sleutelhangertoestemming bij een nieuwe apphandtekening wordt hiermee niet
structureel opgelost. Een centrale prullenbak, gedeelde-agendasynchronisatie,
beheerdelegatie en de nieuwe analyseknop vallen buiten deze update. Bestaande
demo-isolatie blijft inbegrepen; demoresten worden niet automatisch verwijderd.

## Eerdere versies

- [1.3.13: rustige achtergrondweergave en vernieuwicoon](RELEASE-NOTES-1.3.13.md)
- [1.3.12: herstel offline cloud-datumformaat](RELEASE-NOTES-1.3.12.md)
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
