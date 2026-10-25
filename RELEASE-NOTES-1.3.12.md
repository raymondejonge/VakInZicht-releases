# VakInZicht 1.3.12 — 25 oktober 2026

Gerichte herstelupdate voor de bestaande interne/pilotuitgave op macOS met Apple silicon.

## Hersteld ten opzichte van 1.3.11

- De offlinekopie van Gedeeld en Algemeen accepteert nu ook het datumformaat
  dat de cloud gebruikt. Dit verhelpt de gereproduceerde fout
  `OFFLINE_CACHE_INVALID` bij het bijwerken van de offlinebibliotheek.
- Datumstrings met tijdzones en microseconden worden correct gecontroleerd;
  de oorspronkelijke inhoud blijft behouden. De ongewijzigde bovengrens is
  90 dagen sinds de laatste geslaagde online toegangscontrole. Tijdelijke
  bijdragen kunnen eerder verlopen.
- Accountwissel, afmelden, toegangsintrekking, tijdelijke afloop en demo-isolatie
  blijven bewaakt. Centrale wijzigingen blijven online; aanmeldduur wijzigt niet.

## Eerdere vernieuwingen blijven beschikbaar

- Gemiddelde beoordeling op de docentenlijst.
- Overzichtelijkere bibliotheek met handiger zoeken en beheren.
- Mappen en submappen ordenen en verplaatsen door te slepen.
- Jaaragenda makkelijker bijwerken, exporteren, verwijderen of leegmaken.
- Kleine bugfixes en de overige verbeteringen uit eerdere updates.

## Behoud en grenzen

De installatie behoudt lokale gegevens en instellingen en maakt vooraf een
herstelkopie. Raymon heeft de volledige uiteindelijke zespuntsmelding op
25 oktober expliciet goedgekeurd. Zonder verbinding kunnen latere centrale
intrekkingen pas bij de volgende online controle worden gezien, of uiterlijk
na afloop van de offlinegeldigheid. Eigen werk blijft behouden.

Gebruikelijke interne/ad-hoc ondertekende route, niet Apple-genotariseerd.
Deze reparatie lost de herhaalde macOS-sleutelhangertoestemming bij een nieuwe
apphandtekening niet structureel op. Zij wijzigt geen accounts, rollen, cloudschema
of telefoonapp; telefoonversie 14 blijft ongewijzigd. Geen nieuwe centrale
prullenbak, gedeelde-agendasynchronisatie, beheerdelegatie of analyseknop.
