**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel 0.2*

Transaction type: *Documenten*

Functional message: ***Documenten 2019***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

23 juni 2019

Summary

Bericht algemeen 1..1, R

Werkgever 0..1, O

Contactpersoon ontvanger 0..1, O

1 Communicatie 0..9, O

Contactpersoon zender 0..1, O

1 Communicatie 0..9, O

Document 1..9999, R

1 Werknemer 1..1, R

1 Dienstverband 0..9, O

2 Verzuim 0..1, O

1 Afspraak 0..1, O

2 Uitvoerder afspraak 0..1, O

BERICHT ALGEMEEN 1..1, R

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code R an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00500 Documenten

**Versienummer bericht, code R an..5**

*xml tag:* VnrBrCd

*code list:* Versienummer bericht (subset selected)

00003 Versienummer 3

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht R an10**

*xml tag:* AandatBr

**<u>Aanmaaktijd</u>**

**Aanmaaktijd bericht R an8**

*xml tag:* AantijdBr

**<u>Inzender</u>**

**Identificatie inzender R an..40**

*xml tag:* IdInzndr

Bilateraal afgesproken codering betreffende de inzender van het bericht.

**<u>Ontvanger</u>**

**Identificatie ontvanger R an..40**

*xml tag:* IdOntvngr

Bilateraal afgesproken codering betreffende de ontvanger
(eindbestemming) van het bericht.

**<u>Berichtreferentie</u>**

**Berichtreferentienummer R an..512**

*xml tag:* Berrefnr

**<u>Testindicatie</u>**

**Test J/N R a1**

*xml tag:* TestJN

Geeft aan of het een testbericht betreft.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

**<u>Ontvangstbevestiging</u>**

**Ontvangstbevestiging gewenst J/N R a1**

*xml tag:* OntvngstbevJN

Geeft aan of de inzender van het bericht een ontvangstbevestiging wenst.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

WERKGEVER 0..1, O

*WERKGEVER*

*xml tag:* Wrkgvr

Bij het beschrijven van de kenmerken van de Werkgever wordt in een
aantal gevallen de term Inhoudingsplichtige gebruikt.

**<u>Handelsnaam</u>**

**Handelsnaam organisatie R an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Kamer van Koophandel</u>**

**Inschrijvingsnummer Kamer van Koophandel O n..8**

*xml tag:* InschrijvingsnrKvK

Een identificerend nummer dat de Kamer van Koophandel toekent aan
ondernemingen zoals vermeld in de Handelsregisterwet.

Bron: SUWI Gegevens Register

**Vestigingsnummer O n..12**

*xml tag:* VestigingsnrHandelsregister

Een identificerend nummer voor een vestiging in het Handelsregister.

Norminstantie: Handelsregister

**<u>Identificatie bij de Arbo-dienst</u>**

**Identificatie werkgever bij Arbo-dienst R an..40**

*xml tag:* IdWrkgvrArbdnst

De identificatiecode die de arbodienst heeft aangeleverd aan de
werkgever waardoor de werkgever wordt onderscheden van andere werkgevers
in de administratie van de arbodienst.

**Aansluitnummer gegevensuitwisseling Arbodienst R an..70**

*xml tag:* AansltnrGeguitwlngArbdnst

Het aansluitnummer voor de gegevensuitwisseling dat de arbodienst heeft
aangeleverd aan de werkgever waardoor de werkgever wordt onderscheden
van andere werkgevers in de administratie van de arbodienst.

**<u>Loonbelasting / loonheffingen</u>**

**Loonheffingennummer O an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

CONTACTPERSOON ONTVANGER 0..1, O

*CONTACTPERSOON ONTVANGER*

*xml tag:* CntprsnOntvanger

**<u>Naamgegevens</u>**

**Achternaam/Achternamen R an..200**

*xml tag:* Achternaam

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

**Voorletters O a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam O a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code O an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

COMMUNICATIE 0..9, O

*contactpersoon ontvanger - COMMUNICATIE*

*xml tag:* Com

Communicatie is de verzameling van gegevens die het partijen mogelijk
maakt met hulpmiddelen met elkaar te communiceren.

**<u>Soort communicatie</u>**

**Soort communicatie, code R an2**

*xml tag:* SrtComCd

*code list:* Communicatiesoort (subset selected)

06 Zakelijk e-mail adres

08 Zakelijk vaste telefoon

10 Zakelijk mobiele telefoon

**<u>Nummer</u>**

**Nummer/adres communicatie R an..512**

*xml tag:* NrCom

CONTACTPERSOON ZENDER 0..1, O

*CONTACTPERSOON ZENDER*

*xml tag:* CntprsnZender

**<u>Naamgegevens</u>**

**Achternaam/Achternamen R an..200**

*xml tag:* Achternaam

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

**Voorletters O a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam O a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code O an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

COMMUNICATIE 0..9, O

*contactpersoon zender - COMMUNICATIE*

*xml tag:* Com

Communicatie is de verzameling van gegevens die het partijen mogelijk
maakt met hulpmiddelen met elkaar te communiceren.

**<u>Soort communicatie</u>**

**Soort communicatie, code R an2**

*xml tag:* SrtComCd

*code list:* Communicatiesoort (subset selected)

06 Zakelijk e-mail adres

08 Zakelijk vaste telefoon

10 Zakelijk mobiele telefoon

**<u>Nummer</u>**

**Nummer/adres communicatie R an..512**

*xml tag:* NrCom

DOCUMENT 1..9999, R

*DOCUMENT*

*xml tag:* Document

**<u>Uniek kenmerk van het document</u>**

**Identificatie document R an..40**

*xml tag:* IdDocument

**Identificatie document oud O an..40**

*xml tag:* IdDocumentOud

**<u>Datum dat het document is aangemaakt</u>**

**Datum document R an10**

*xml tag:* DatDocument

**<u>Kenmerken document</u>**

**Soort document, code R an3**

*xml tag:* SrtDocumentCd

*code list:* Document (subset selected)

100 Probleemanalyse

104 Bijstelling probleemanalyse

158 Tussentijdse evaluatie

208 Telefonisch contact met werkgever

215 Telefonische eigen verklaring werknemer

217 Terugkoppelingsbrief spreekuur

219 Spreekuur oproep wijziging

250 Rapportage arbeidsdeskundig onderzoek

253 Reïntegratieverslag

303 Plan van aanpak

305 Advies AAG

306 Advies aanvullende interventie werkgever

451 Inzetbaarheidsadvies

453 Functionele mogelijkheden lijst

700 Notitie

701 Vraagstelling bedrijfsarts

909 No show

916 Actueel oordeel

918 Interventieadvies

919 Kennisgeving oproep

999 Overig

**Soort document, omschrijving O an..70**

*xml tag:* SrtDocumentOms

Verplicht indien Soort document, code = 999

**Status document, code O an2**

*xml tag:* StatDocumentCd

*code list:* Status document (all selected)

01 Definitief

02 Concept

**Kenmerk zendende partij R an..512**

*xml tag:* KenmerkZendPartij

Een typerend kenmerk dat de zendende partij aan het document toekent.

**Reden aanlevering document, code O an2**

*xml tag:* RdAanlevDocumentCd

*code list:* Reden aanlevering document (all selected)

01 Ter beoordeling

02 Ter informatie

03 Archivering

**Prioriteit, code O an2**

*xml tag:* PrioriteitCd

*code list:* Prioriteit (all selected)

01 Hoog

02 Normaal

03 Laag

**Bestand type, code O an2**

*xml tag:* BestandTypCd

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

**Bestandsnaam O an..70**

*xml tag:* Bestandsnm

**Adressering, code O an2**

*xml tag:* AdresseringCd

*code list:* Adressering (all selected)

01 Werkgever

02 Werknemer

03 Werkgever en werknemer

**<u>Het document</u>**

**Datastring R an..\***

*xml tag:* Datastring

Datastring bevat het document.

WERKNEMER 1..1, R

*document - WERKNEMER*

*xml tag:* Wrknmr

Een werknemer is de natuurlijke persoon met wie een inkomstenverhouding
binnen de loonadministratie bestaat.

**<u>Identificerende gegevens</u>**

**Burgerservicenummer O n..9**

*xml tag:* SofiNr

Een door de Gemeente aan een natuurlijk persoon toegekend uniek
administratief nummer, ook wel BSN genoemd.

Indien de inhoudingsplichtige niet beschikt of kan beschikken over het
BSN dan moet in ieder geval het Personeelsnummer doorgegeven worden.

Bron: Loonaangifte.

**Geboortedatum O an10**

*xml tag:* Gebdat

Datum waarop de natuurlijke persoon is geboren.

Als de geboortedatum niet bekend is moet een bestaanbare geboortedatum
worden ingevuld. Hierbij moet de volgende werkwijze worden gehanteerd:

1\. Als de dag, maand en jaar niet bekend zijn moet u het jaar schatten
en voor de dag en maand 01-07 invullen.

2\. Als de dag en de maand niet bekend zijn: 01-07-jaar

3\. Als de dag niet bekend is: 16-maand-jaar.

Bron: Loonaangifte.

**<u>Naamgegevens</u>**

**Achternaam/Achternamen O an..200**

*xml tag:* Achternaam

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

**Voorletters O a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam O a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code O an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

**<u>Identificatie</u>**

**Identificatie werknemer R an..40**

*xml tag:* IdWrknmr

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

DIENSTVERBAND 0..9, O

*document - DIENSTVERBAND*

*xml tag:* Dnstvbnd

**<u>Identificatie</u>**

**Identificatie dienstverband O an..40**

*xml tag:* IdDnstvbnd

Unieke code voor het dienstverband van de werknemer.

**<u>Datums</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**<u>Personeelsnummer behorende bij het dienstverband</u>**

**Personeelsnummer O an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

VERZUIM 0..1, O

*document - dienstverband - VERZUIM*

*xml tag:* Vrzm

**<u>Identificatie</u>**

**Verzuimgeval identificatie O an..40**

*xml tag:* VrzmgvlId

Unieke identificatie van het verzuimgeval.

Uniek per werkgever ook in de tijd.

**<u>Data</u>**

**Datum eerste verzuimdag R an10**

*xml tag:* DatEerstVrzmdg

De eerste dag waarop iemand zou moeten werken maar verzuimt, of
verminderd inzetbaar is, wegens ziekte of een ongeval. Is er sprake van
ziekte of een ongeval tijdens zwangerschaps- en bevallingsverlof en
waarvoor men nog verzuimt na beëindiging van dat verlof, dan is de
aanvangsdatum de dag waarop men zou moeten werken na beëindiging van de
zwangerschaps- en bevallingsuitkering. Tijdens regulier verlof wordt het
ziekteverzuim ook meegeteld.

Bron:

Berekening van ziekteverzuim

NVS Standaard voor verzuimregistratie

Nationale Verzuimstatistiek

November 2004

AFSPRAAK 0..1, O

*document - AFSPRAAK*

*xml tag:*

**<u>Uniek kenmerk afspraak</u>**

**Identificatie afspraak O an..40**

*xml tag:* IdAfspraak

Unieke identificatie van de afspraak bij de zender.

**Datum afspraak R an10**

*xml tag:* DatAfspraak

**Tijdstip afspraak O an8**

*xml tag:* TijdAfspraak

Begintijd van de afspraak

**<u>Overige gegevens</u>**

**Duur afspraak O n..5,2**

*xml tag:* DuurAfspraak

Duur van de afspraak in uren.

**Status afspraak, code O an2**

*xml tag:* StatusAfspraakCd

*code list:* Status afspraak (all selected)

01 Gepland

02 Uitgevoerd

03 Geannuleerd

04 Te laat geannuleerd

05 Gewijzigd

06 No show

**Omschrijving soort afspraak O an..70**

*xml tag:* OmsSrtAfspraak

UITVOERDER AFSPRAAK 0..1, O

*document - afspraak - UITVOERDER AFSPRAAK*

*xml tag:*

**<u>Naamgegevens</u>**

**Achternaam/Achternamen R an..200**

*xml tag:* Achternaam

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

**Voorletters O a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam O a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code O an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

**Naam functie R an..35**

*xml tag:* NmFnct
