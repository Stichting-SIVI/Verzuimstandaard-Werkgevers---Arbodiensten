**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel 0.2*

Transaction type: *Afspraken*

Functional message: ***Afspraken 2019***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

23 juni 2019

Summary

Bericht algemeen 1..1, R

Werkgever 0..1, O

Arbodienst 0..1, O

1 Contactpersoon 0..1, O

2 Communicatie 0..9, O

Afspraak 1..999, R

1 Werknemer 1..1, R

1 Straatadres Nederland 0..1, O

1 Uitvoerder afspraak 1..1, R

1 Dienstverband 0..9, O

2 Verzuim 0..1, O

BERICHT ALGEMEEN 1..1, R

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code R an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00105 Spreekuurafspraken

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

*xml tag:*

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

**Loonheffingennummer R an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

ARBODIENST 0..1, O

*ARBODIENST*

*xml tag:*

**<u>Handelsnaam</u>**

**Handelsnaam organisatie R an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Arbo-dienst</u>**

**Identificatie Arbo-dienst O an..40**

*xml tag:* IdArbdnst

Bilateraal afgesproken codering betreffende de Arbo-dienst waar het
bericht voor bestemd is.

CONTACTPERSOON 0..1, O

*arbodienst - CONTACTPERSOON*

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

COMMUNICATIE 0..9, O

*arbodienst - contactpersoon - COMMUNICATIE*

*xml tag:*

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

AFSPRAAK 1..999, R

*AFSPRAAK*

*xml tag:* Afspraak

**<u>Uniek kenmerk afspraak</u>**

**Identificatie afspraak R an..40**

*xml tag:* IdAfspraak

Unieke identificatie van de afspraak bij de zender.

**Identificatie afspraak oud O an..40**

*xml tag:* IdAfspraakOud

**Datum afspraak R an10**

*xml tag:* DatAfspraak

**Datum afspraak oud O an10**

*xml tag:* DatAfspraakOud

**Tijdstip afspraak R an8**

*xml tag:* TijdAfspraak

Begintijd van de afspraak

**Tijdstip afspraak oud O an8**

*xml tag:* TijdAfspraakOud

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

**Omschrijving soort afspraak R an..70**

*xml tag:* OmsSrtAfspraak

WERKNEMER 1..1, R

*afspraak - WERKNEMER*

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

**Overlijdensdatum O an10**

*xml tag:* Overldat

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

**<u>Identificatie</u>**

**Identificatie werknemer R an..40**

*xml tag:* IdWrknmr

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

STRAATADRES NEDERLAND 0..1, O

*afspraak - STRAATADRES NEDERLAND*

*xml tag:*

Een adres in Nederland dat wordt bepaald aan de hand van straatnaam en
huisnummer.

**<u>Generiek voor adres</u>**

**Postcode R an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam O an..24**

*xml tag:* Wnpl

De door de gemeente vastgestelde naam van een woonplaats.

Norm(instantie): NEN 5825 (Woonplaatsnaam)

**<u>Specifiek voor straatadres Nederland</u>**

**Straatnaam\_ O an..80**

*xml tag:* StraatLang

De officiële door de gemeente vastgestelde naam van een straat.

Als de officiële straatnaam echter langer is dan 24 posities dan mag

deze ingekort volgens de specificaties van de BOCO-norm.

Norm(instantie)

NEN 5825 (Straatnaam)

**Huisnummer R n..5**

*xml tag:* Huisnr

De numerieke aanduiding zoals deze door de gemeente aan het object is
toegekend.

Norminstantie: NEN 5825 (Huisnummer)

**Huisnummertoevoeging O an..4**

*xml tag:* HuisToev

De alfanumerieke aanduiding achter huisnummer, zoals toegekend door de
gemeente.

Norminstantie: NEN 5825 (Huisnummertoevoeging)

UITVOERDER AFSPRAAK 1..1, R

*afspraak - UITVOERDER AFSPRAAK*

*xml tag:* UitvoerderAfspraak

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

DIENSTVERBAND 0..9, O

*afspraak - DIENSTVERBAND*

*xml tag:*

**<u>Identificatie</u>**

**Identificatie dienstverband O an..40**

*xml tag:* IdDnstvbnd

Unieke code voor het dienstverband van de werknemer.

**<u>Personeelsnummer behorende bij het dienstverband</u>**

**Personeelsnummer O an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

VERZUIM 0..1, O

*afspraak - dienstverband - VERZUIM*

*xml tag:*

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
