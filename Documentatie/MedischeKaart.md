**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel*

Transaction type: *Documenten*

Functional message: ***Medische kaart 2024***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

**Copyright SIVI**

15 juli 2024

Summary

Bericht algemeen 1..1, V

Werkgever 0..1, F

Document 1..9999, V

1 Werknemer 1..1, V

1 Dienstverband 0..9, F

2 Preventieve dienst 0..1, F

2 Verzuim 0..1, F

1 Afspraak 0..1, F

2 Uitvoerder afspraak 0..1, F

BERICHT ALGEMEEN 1..1, V

*BERICHT ALGEMEEN*

**<u>Soort bericht + versienummer</u>**

**Bericht, code V an..5**

*code list:* Berichtcode (subset selected)

00501 Medische kaart

**Versienummer bericht, code V an..5**

*code list:* Versienummer bericht (subset selected)

00001 Versienummer 1

**<u>Functie bericht</u>**

**Functie bericht, code V an2**

*code list:* SIVI (subset selected)

07 Machtiging opvraag medische kaart

08 Zenden medische kaart

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht V an10**

**<u>Aanmaaktijd</u>**

**Aanmaaktijd bericht V an8**

**<u>Inzender</u>**

**Identificatie inzender V an..40**

Bilateraal afgesproken codering betreffende de inzender van het bericht.

**<u>Ontvanger</u>**

**Identificatie ontvanger V an..40**

Bilateraal afgesproken codering betreffende de ontvanger
(eindbestemming) van het bericht.

**<u>Berichtreferentie</u>**

**Berichtreferentienummer V an..512**

**<u>Testindicatie</u>**

**Test J/N V a1**

Geeft aan of het een testbericht betreft.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

**<u>Ontvangstbevestiging</u>**

**Ontvangstbevestiging gewenst J/N V a1**

Geeft aan of de inzender van het bericht een ontvangstbevestiging wenst.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

WERKGEVER 0..1, F

*WERKGEVER*

Bij het beschrijven van de kenmerken van de Werkgever wordt in een
aantal gevallen de term Inhoudingsplichtige gebruikt.

**<u>Handelsnaam</u>**

**Handelsnaam organisatie V an..100**

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Kamer van Koophandel</u>**

**Inschrijvingsnummer Kamer van Koophandel F n..8**

Een identificerend nummer dat de Kamer van Koophandel toekent aan
ondernemingen zoals vermeld in de Handelsregisterwet.

Bron: SUWI Gegevens Register

**Vestigingsnummer F n..12**

Een identificerend nummer voor een vestiging in het Handelsregister.

Norminstantie: Handelsregister

**<u>Identificatie bij de arbodienst</u>**

**Identificatie werkgever bij arbodienst V an..40**

De identificatiecode die de arbodienst heeft aangeleverd aan de
werkgever waardoor de werkgever wordt onderscheden van andere werkgevers
in de administratie van de arbodienst.

**Aansluitnummer gegevensuitwisseling Arbodienst V an..70**

Het aansluitnummer voor de gegevensuitwisseling dat de arbodienst heeft
aangeleverd aan de werkgever waardoor de werkgever wordt onderscheden
van andere werkgevers in de administratie van de arbodienst.

**<u>Loonbelasting / loonheffingen</u>**

**Loonheffingennummer F an..12**

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

DOCUMENT 1..9999, V

*DOCUMENT*

**<u>Uniek kenmerk van het document</u>**

**Identificatie document V an..40**

**Identificatie document oud F an..40**

**<u>Datum dat het document is aangemaakt</u>**

**Datum document V an10**

**<u>Kenmerken document</u>**

**Soort document, code V an3**

*code list:* Document (subset selected)

920 Machtiging medische kaart

921 Medische kaart

**Bestand type, code F an2**

*code list:* Bestandtype (all selected)

01 HTML

02 HTM

03 Txt

04 XML

05 Rtf

06 PDF

07 Tif

08 Tiff

09 Doc

10 Docx

11 XLS

12 XLSX

13 JPG

14 JPEG

**Bestandsnaam F an..70**

**<u>Het document</u>**

**Datastring V an..\***

Datastring bevat het document.

WERKNEMER 1..1, V

*document - WERKNEMER*

Een werknemer is de natuurlijke persoon met wie een inkomstenverhouding
binnen de loonadministratie bestaat.

**<u>Identificerende gegevens</u>**

**Burgerservicenummer V n..9**

Een door de Gemeente aan een natuurlijk persoon toegekend uniek
administratief nummer, ook wel BSN genoemd.

Indien de inhoudingsplichtige niet beschikt of kan beschikken over het
BSN dan moet in ieder geval het Personeelsnummer doorgegeven worden.

Bron: Loonaangifte.

**Geboortedatum V an10**

Datum waarop de natuurlijke persoon is geboren.

Als de geboortedatum niet bekend is moet een bestaanbare geboortedatum
worden ingevuld. Hierbij moet de volgende werkwijze worden gehanteerd:

1\. Als de dag, maand en jaar niet bekend zijn moet u het jaar schatten
en voor de dag en maand 01-07 invullen.

2\. Als de dag en de maand niet bekend zijn: 01-07-jaar

3\. Als de dag niet bekend is: 16-maand-jaar.

Bron: Loonaangifte.

**<u>Naamgegevens</u>**

**Achternaam/Achternamen V an..200**

Achternaam/achternamen inclusief voorvoegsel(s).

Mensen die getrouwd zijn of een geregistreerd partnerschap zijn
aangegaan, kunnen in het dagelijks leven de achternaam van hun partner
combineren met hun eigen achternaam. Aan een gecombineerde achternaam
alléén is niet te zien of het om een man of een vrouw gaat, en ook niet
welke van de twee achternamen de geboortenaam is en welke de
'aangetrouwde'. Alle combinaties zijn namelijk denkbaar. Stel dat de
heer of mevrouw Oudewater getrouwd is met de heer of mevrouw Simons, dan
kunnen zij elk in het dagelijks leven naar eigen inzicht kiezen uit een
van de volgende namen:

\- Simons

\- Oudewater

\- Simons-Oudewater

\- Oudewater-Simons

Bron: Genootschap Onze Taal

**Voorletters V a..6**

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam F a..35**

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code V an1**

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**<u>Identificatie</u>**

**Identificatie werknemer F an..40**

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

DIENSTVERBAND 0..9, F

*document - DIENSTVERBAND*

**<u>Identificatie</u>**

**Identificatie dienstverband F an..40**

Unieke code voor het dienstverband van de werknemer.

**<u>Datums</u>**

**Ingangsdatum F an10**

**<u>Personeelsnummer behorende bij het dienstverband</u>**

**Personeelsnummer F an..35**

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

PREVENTIEVE DIENST 0..1, F

*document - dienstverband - PREVENTIEVE DIENST*

**<u>Identificatie</u>**

**Identificatie preventieve dienst V an..40**

**<u>Preventieve dienst</u>**

**Preventieve dienst, code V an2**

*code list:* Preventieve dienst (all selected)

01 Preventief spreekuur

02 Preventief medisch onderzoek (PMO)

03 Aanstellingskeuring

04 Periodieke keuring, (o.a. PAGO)

05 Chauffeurskeuring

06 Rijbewijskeuring

07 Binnen-/zeevaartkeuring

08 Duikkeuring

09 Offshorekeuring

10 Ademluchtkeuring

11 Asbestkeuring

12 Bodemsaneringskeuring

13 Stralingskeuring

14 Brandweerkeuring

15 Bloedonderzoek

16 Vaccinatie

17 Werken op hoogte

18 Beroepskeuring

50 Training voor leidinggevenden

51 Beoordeling veiligheid in en om bedrijf

52 Risico verzuimanalyses

99 Overig

**Preventieve dienst toevoeging F an..70**

Aanvulling op Preventieve dienst, code

**Datum uitvoering preventieve dienst F an10**

Uiterste datum dat de (volgende) preventieve dienst uitgevoerd moet
worden.

**Verbijzondering prev. dienst, code F an..10**

Een bilateraal afgesproken code. Dit betreft een verbijzondering van de
Code preventieve dienst.

**Verbijz. prev. dienst, omschrijving F an..70**

Een omschrijving van de aangevraagde keuring die overeenkomt met
Verbijzondering prev. dienst, code.

VERZUIM 0..1, F

*document - dienstverband - VERZUIM*

**<u>Identificatie</u>**

**Verzuimgeval identificatie F an..40**

Unieke identificatie van het verzuimgeval voor één dienstverband. Als
een werknemer verzuim heeft op meerdere dienstverbanden, geldt per
dienstverband een unieke "Verzuimgeval identificatie".

Uniek per werkgever ook in de tijd.

**<u>Data</u>**

**Datum eerste verzuimdag V an10**

De eerste dag waarop iemand zou moeten werken maar verzuimt, of
verminderd inzetbaar is, wegens ziekte of een ongeval. Is er sprake van
ziekte of een ongeval tijdens zwangerschaps- en bevallingsverlof en
waarvoor men nog verzuimt na beëindiging van dat verlof, dan is de
aanvangsdatum de dag waarop men zou moeten werken na beëindiging van de
zwangerschaps- en bevallingsuitkering. Tijdens regulier verlof wordt het
ziekteverzuim ook meegeteld.

Datum mag niet in de toekomst liggen.

Bron:

Berekening van ziekteverzuim

NVS Standaard voor verzuimregistratie

Nationale Verzuimstatistiek

November 2004

AFSPRAAK 0..1, F

*document - AFSPRAAK*

**<u>Uniek kenmerk afspraak</u>**

**Identificatie afspraak F an..40**

Unieke identificatie van de afspraak bij de zender.

**Datum afspraak V an10**

**Tijdstip afspraak F an8**

Begintijd van de afspraak

**<u>Overige gegevens</u>**

**Duur afspraak F n..5,2**

Duur van de afspraak in uren.

**Status afspraak, code F an2**

*code list:* Status afspraak (all selected)

01 Gepland

02 Uitgevoerd

03 Geannuleerd

04 Te laat geannuleerd

05 Gewijzigd

06 No show

**Omschrijving soort afspraak F an..70**

UITVOERDER AFSPRAAK 0..1, F

*document - afspraak - UITVOERDER AFSPRAAK*

**<u>Naamgegevens</u>**

**Achternaam/Achternamen V an..200**

Achternaam/achternamen inclusief voorvoegsel(s).

Mensen die getrouwd zijn of een geregistreerd partnerschap zijn
aangegaan, kunnen in het dagelijks leven de achternaam van hun partner
combineren met hun eigen achternaam. Aan een gecombineerde achternaam
alléén is niet te zien of het om een man of een vrouw gaat, en ook niet
welke van de twee achternamen de geboortenaam is en welke de
'aangetrouwde'. Alle combinaties zijn namelijk denkbaar. Stel dat de
heer of mevrouw Oudewater getrouwd is met de heer of mevrouw Simons, dan
kunnen zij elk in het dagelijks leven naar eigen inzicht kiezen uit een
van de volgende namen:

\- Simons

\- Oudewater

\- Simons-Oudewater

\- Oudewater-Simons

Bron: Genootschap Onze Taal

**Voorletters F a..6**

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam F a..35**

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code F an1**

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**Naam functie V an..35**
