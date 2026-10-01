**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel*

Transaction type: *Afspraken*

Functional message: ***Afspraken 2024***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

9 juli 2024

Summary

Bericht algemeen 1..1, V

Werkgever 0..1, F

Arbodienst 0..1, F

1 Contactpersoon 0..1, F

2 Communicatie 0..9, F

Afspraak 1..999, V

1 Werknemer 1..1, V

1 Straatadres Nederland 0..1, F

1 Uitvoerder afspraak 1..1, V

1 Dienstverband 0..9, F

2 Verzuim 0..1, F

BERICHT ALGEMEEN 1..1, V

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code V an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00105 Spreekuurafspraken

**Versienummer bericht, code V an..5**

*xml tag:* VnrBrCd

*code list:* Versienummer bericht (subset selected)

00005 Versienummer 5

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht V an10**

*xml tag:* AandatBr

**<u>Aanmaaktijd</u>**

**Aanmaaktijd bericht V an8**

*xml tag:* AantijdBr

**<u>Inzender</u>**

**Identificatie inzender V an..40**

*xml tag:* IdInzndr

Bilateraal afgesproken codering betreffende de inzender van het bericht.

**Gebruikt softwarepakket V an..35**

*xml tag:* GebrSwPakket

Beschrijving van het softwarepakket dat de aanleveraar heeft gebruikt
voor de vervaardiging van het bericht.

**<u>Ontvanger</u>**

**Identificatie ontvanger V an..40**

*xml tag:* IdOntvngr

Bilateraal afgesproken codering betreffende de ontvanger
(eindbestemming) van het bericht.

**<u>Berichtreferentie</u>**

**Berichtreferentienummer V an..512**

*xml tag:* Berrefnr

**<u>Testindicatie</u>**

**Test J/N V a1**

*xml tag:* TestJN

Geeft aan of het een testbericht betreft.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

**<u>Ontvangstbevestiging</u>**

**Ontvangstbevestiging gewenst J/N V a1**

*xml tag:* OntvngstbevJN

Geeft aan of de inzender van het bericht een ontvangstbevestiging wenst.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

WERKGEVER 0..1, F

*WERKGEVER*

*xml tag:*

Bij het beschrijven van de kenmerken van de Werkgever wordt in een
aantal gevallen de term Inhoudingsplichtige gebruikt.

**<u>Handelsnaam</u>**

**Handelsnaam organisatie V an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Kamer van Koophandel</u>**

**Inschrijvingsnummer Kamer van Koophandel F n..8**

*xml tag:* InschrijvingsnrKvK

Een identificerend nummer dat de Kamer van Koophandel toekent aan
ondernemingen zoals vermeld in de Handelsregisterwet.

Bron: SUWI Gegevens Register

**<u>Identificatie bij de arbodienst</u>**

**Identificatie werkgever bij arbodienst V an..40**

*xml tag:* IdWrkgvrArbdnst

De identificatiecode die de arbodienst heeft aangeleverd aan de
werkgever waardoor de werkgever wordt onderscheden van andere werkgevers
in de administratie van de arbodienst.

**Aansluitnummer gegevensuitwisseling Arbodienst V an..70**

*xml tag:* AansltnrGeguitwlngArbdnst

Het aansluitnummer voor de gegevensuitwisseling dat de arbodienst heeft
aangeleverd aan de werkgever waardoor de werkgever wordt onderscheden
van andere werkgevers in de administratie van de arbodienst.

**<u>Loonbelasting / loonheffingen</u>**

**Loonheffingennummer V an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

ARBODIENST 0..1, F

*ARBODIENST*

*xml tag:*

**<u>Handelsnaam</u>**

**Handelsnaam organisatie V an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Arbo-dienst</u>**

**Identificatie Arbo-dienst F an..40**

*xml tag:* IdArbdnst

Bilateraal afgesproken codering betreffende de Arbo-dienst waar het
bericht voor bestemd is.

CONTACTPERSOON 0..1, F

*arbodienst - CONTACTPERSOON*

*xml tag:*

**<u>Naamgegevens</u>**

**Achternaam/Achternamen V an..200**

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

**Voorletters V a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam F a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code V an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

COMMUNICATIE 0..9, F

*arbodienst - contactpersoon - COMMUNICATIE*

*xml tag:*

Communicatie is de verzameling van gegevens die het partijen mogelijk
maakt met hulpmiddelen met elkaar te communiceren.

**<u>Soort communicatie</u>**

**Soort communicatie, code V an2**

*xml tag:* SrtComCd

*code list:* Communicatiesoort (subset selected)

06 Zakelijk e-mail adres

08 Zakelijk vaste telefoon

10 Zakelijk mobiele telefoon

**<u>Nummer</u>**

**Nummer/adres communicatie V an..512**

*xml tag:* NrCom

AFSPRAAK 1..999, V

*AFSPRAAK*

*xml tag:* Afspraak

**<u>Uniek kenmerk afspraak</u>**

**Identificatie afspraak V an..40**

*xml tag:* IdAfspraak

Unieke identificatie van de afspraak bij de zender.

**Identificatie afspraak oud F an..40**

*xml tag:* IdAfspraakOud

**Datum afspraak V an10**

*xml tag:* DatAfspraak

**Datum afspraak oud F an10**

*xml tag:* DatAfspraakOud

**Tijdstip afspraak V an8**

*xml tag:* TijdAfspraak

Begintijd van de afspraak

**Tijdstip afspraak oud F an8**

*xml tag:* TijdAfspraakOud

**<u>Overige gegevens</u>**

**Duur afspraak F n..5,2**

*xml tag:* DuurAfspraak

Duur van de afspraak in uren.

**Status afspraak, code F an2**

*xml tag:* StatusAfspraakCd

*code list:* Status afspraak (all selected)

01 Gepland

02 Uitgevoerd

03 Geannuleerd

04 Te laat geannuleerd

05 Gewijzigd

06 No show

**Omschrijving soort afspraak V an..70**

*xml tag:* OmsSrtAfspraak

WERKNEMER 1..1, V

*afspraak - WERKNEMER*

*xml tag:* Wrknmr

Een werknemer is de natuurlijke persoon met wie een inkomstenverhouding
binnen de loonadministratie bestaat.

**<u>Identificerende gegevens</u>**

**Burgerservicenummer F n..9**

*xml tag:* SofiNr

Een door de Gemeente aan een natuurlijk persoon toegekend uniek
administratief nummer, ook wel BSN genoemd.

Indien de inhoudingsplichtige niet beschikt of kan beschikken over het
BSN dan moet in ieder geval het Personeelsnummer doorgegeven worden.

Bron: Loonaangifte.

**Geboortedatum F an10**

*xml tag:* Gebdat

Datum waarop de natuurlijke persoon is geboren.

Als de geboortedatum niet bekend is moet een bestaanbare geboortedatum
worden ingevuld. Hierbij moet de volgende werkwijze worden gehanteerd:

1\. Als de dag, maand en jaar niet bekend zijn moet u het jaar schatten
en voor de dag en maand 01-07 invullen.

2\. Als de dag en de maand niet bekend zijn: 01-07-jaar

3\. Als de dag niet bekend is: 16-maand-jaar.

Bron: Loonaangifte.

**Overlijdensdatum F an10**

*xml tag:* Overldat

**<u>Naamgegevens</u>**

**Achternaam/Achternamen V an..200**

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

**Voorletters F a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam F a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code F an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**<u>Identificatie</u>**

**Identificatie werknemer V an..40**

*xml tag:* IdWrknmr

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

STRAATADRES NEDERLAND 0..1, F

*afspraak - STRAATADRES NEDERLAND*

*xml tag:*

Een adres in Nederland dat wordt bepaald aan de hand van straatnaam en
huisnummer.

**<u>Generiek voor adres</u>**

**Postcode V an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam F an..24**

*xml tag:* Wnpl

De door de gemeente vastgestelde naam van een woonplaats.

Norm(instantie): NEN 5825 (Woonplaatsnaam)

**<u>Specifiek voor straatadres Nederland</u>**

**Straatnaam\_ F an..80**

*xml tag:* StraatLang

De officiële door de gemeente vastgestelde naam van een straat.

Als de officiële straatnaam echter langer is dan 24 posities dan mag

deze ingekort volgens de specificaties van de BOCO-norm.

Norm(instantie)

NEN 5825 (Straatnaam)

**Huisnummer V n..5**

*xml tag:* Huisnr

De numerieke aanduiding zoals deze door de gemeente aan het object is
toegekend.

Norminstantie: NEN 5825 (Huisnummer)

**Huisnummertoevoeging F an..4**

*xml tag:* HuisToev

De alfanumerieke aanduiding achter huisnummer, zoals toegekend door de
gemeente.

Norminstantie: NEN 5825 (Huisnummertoevoeging)

UITVOERDER AFSPRAAK 1..1, V

*afspraak - UITVOERDER AFSPRAAK*

*xml tag:* UitvoerderAfspraak

**<u>Naamgegevens</u>**

**Achternaam/Achternamen V an..200**

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

**Voorletters F a..6**

*xml tag:* Voorl

De verzameling letters die wordt gevormd door de eerste letter van alle
in volgorde voorkomende voornamen.

Bestaan uit hoofdletters, zijn aaneengesloten en bevatten geen punten.
Alleen alfabetische tekens zijn toegestaan.

Bron: Loonaangifte.

**Roepnaam F a..35**

*xml tag:* Roepnaam

Voornaam waarmee iemand wordt aangesproken.

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code F an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**Naam functie V an..35**

*xml tag:* NmFnct

DIENSTVERBAND 0..9, F

*afspraak - DIENSTVERBAND*

*xml tag:*

**<u>Identificatie</u>**

**Identificatie dienstverband F an..40**

*xml tag:* IdDnstvbnd

Unieke code voor het dienstverband van de werknemer.

**<u>Personeelsnummer behorende bij het dienstverband</u>**

**Personeelsnummer F an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

VERZUIM 0..1, F

*afspraak - dienstverband - VERZUIM*

*xml tag:*

**<u>Data</u>**

**Datum eerste verzuimdag V an10**

*xml tag:* DatEerstVrzmdg

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
