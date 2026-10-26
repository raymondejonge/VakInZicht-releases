# VakInZicht 1.3.14 — 25 oktober 2026

Bibliotheek- en weergaveverbeteringen voor de bestaande interne/pilotuitgave op macOS met Apple silicon.

## Nieuw ten opzichte van 1.3.13

- Het linkermenu kan met één knop onderaan worden ingeklapt voor meer werkruimte.
  De keuze wordt op dit apparaat onthouden. De gewone weergave blijft standaard;
  op smalle vensters blijft de bestaande navigatie met labels beschikbaar.
- De overgang van opgeslagen bibliotheekinhoud naar online beheer krijgt een
  stabielere indeling. Voor een eerder bevestigde beheerder kunnen voorlopige,
  uitgeschakelde knoppen de ruimte reserveren. Pas vers bevestigde online
  bevoegdheden maken centrale beheeracties bruikbaar.
- Achtergrondbijwerken houdt de gedeelde Mac-verbindingspoort niet meer voor
  de hele viercatalogusbatch bezet. Wachtende actieve aanvragen kunnen tussen
  de afzonderlijke stappen door. Sessiewissel/intrekking onderbreekt de batch;
  onvolledige downloads worden niet opgeslagen. Geen extra parallelle sessies
  of overgeslagen rechtencontroles, en geen garantie van vaste secondenwinst.
- Een duidelijke knop Gebruikersrechten naast de weergavekeuze vervangt het
  oude rechtenmenu/formulier. Bestaande bevoegde gebruikers kunnen gewone
  bibliotheekrechten per actieve collega bewust bewaren. Notitierechten,
  accounttoegang, eigen kopieën en beoordelingen blijven daarbij ongewijzigd.
  Beschermde beheeraccounts blijven vergrendeld. Zonder actuele bevoegdheid of
  bestaande serverondersteuning wordt het overzicht alleen-lezen.
- Status is weg bij Mijn bibliotheek en bij de gebruikersweergave van Gedeeld
  en Algemeen. Het blijft beschikbaar voor online bevoegde bibliotheekbeheerders.
  Verborgen oude statuskeuzes blijven niet doorfilteren.

## Eerdere vernieuwingen blijven beschikbaar

- Gemiddelde beoordeling op de docentenlijst.
- Handiger zoeken en beheren in de bibliotheek en mappen/submappen verslepen.
- Gedeeld en Algemeen offline gebruiken; reeds bevestigde inhoud blijft zichtbaar
  tijdens bijwerken, met vernieuwicoon naast de bijwerktijd.
- Jaaragenda bijwerken, exporteren, verwijderen of leegmaken.
- Kleine verbeteringen en bugfixes uit eerdere updates.

## Behoud en grenzen

De installatie behoudt lokale gegevens en instellingen en maakt vooraf een
herstelkopie. Raymon heeft de volledige uiteindelijke vijfpuntsmelding na zijn
verzoek om verkorting expliciet goedgekeurd. Geen oude inlogwaarschuwing toegevoegd.

Geen continue live push. Online controleren gebeurt bij openen/terugkeren of
Vernieuwen. De offlinebovengrens blijft 90 dagen na de laatste geslaagde controle;
tijdelijke bijdragen kunnen eerder verlopen. Centrale wijzigingen blijven online.
De nieuwe bediening verandert op zichzelf geen bestaande rollen of accounts.

Gebruikelijke interne/ad-hoc ondertekende route, niet Apple-genotariseerd.
Herhaalde macOS-sleutelhangertoestemming na een nieuwe apphandtekening wordt
hiermee niet structureel opgelost. Geen cloudactivering, schemawijziging,
aanmeldduurwijziging of telefoonupdate; telefoonversie 14 blijft ongewijzigd.
