**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel*

Transaction type: *Basistransactie Verzuim*

Functional message: ***Werkgevers Gegevens Basisregistratie 2021***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

25 juni 2021

Summary

Bericht algemeen 1..1, R

Administratiekantoor 0..1, O

Werkgever 1..\*, R

1 Arbocontract 0..1, O

1 Personeelssterkte 0..999, O

1 Straatadres Nederland 1..9, R

1 Postbusadres Nederland 0..9, O

1 Communicatie 0..9, O

1 Contactpersoon 1..9, R

2 Communicatie 1..9, R

1 Organisatie eenheid 0..9999, O

2 Arbocontract 0..1, O

2 Personeelssterkte 0..999, O

2 Straatadres Nederland 0..9, O

2 Postbusadres Nederland 0..9, O

2 Contactpersoon 0..9, O

3 Communicatie 1..9, R

2 Verzekeraar/Volmacht 0..9, O

3 Contract 1..1, R

1 Kostenplaats 0..9999, O

2 Personeelssterkte 0..999, O

1 Verzekeraar/Volmacht 0..9, O

2 Contract 1..1, R

BERICHT ALGEMEEN 1..1, R

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code R an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00101 Werkgevers gegevens - basisregistratie

**Versienummer bericht, code R an..5**

*xml tag:* VnrBrCd

*code list:* Versienummer bericht (subset selected)

00008 Versienummer 8

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht R an10**

*xml tag:* AandatBr

**Aanmaaktijd bericht R an8**

*xml tag:* AantijdBr

**<u>Inzender</u>**

**Identificatie inzender R an..40**

*xml tag:* IdInzndr

Bilateraal afgesproken codering betreffende de inzender van het bericht.

**Gebruikt softwarepakket R an..35**

*xml tag:* GebrSwPakket

Beschrijving van het softwarepakket dat de aanleveraar heeft gebruikt
voor de vervaardiging van het bericht.

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

ADMINISTRATIEKANTOOR 0..1, O

*ADMINISTRATIEKANTOOR*

*xml tag:* AdmKantoor

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

WERKGEVER 1..\*, R

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

**<u>Identificatie bij UWV</u>**

**Identificatie werkgever bij UWV O an..40**

*xml tag:* IdWrkgvrUWV

De identificatie die het UWV heeft aangeleverd aan de werkgever

waardoor de werkgever wordt onderscheiden van andere werkgevers in de
administratie van het UWV.

**<u>Loonbelasting / loonheffingen</u>**

**Loonheffingennummer R an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

**<u>Codering organisatie-eenheid</u>**

**Organisatie-eenheid, code R an..70**

*xml tag:* OrgeenhCd

Bilateraal afgesproken codering van de organisatie-eenheid.

**<u>Eigenrisicodragerschap</u>**

**Indicatie eigenrisicodrager voor de WGA O a1**

*xml tag:* IndERDWGA

Aanduiding of de Inhoudingsplichtige eigenrisicodrager (ERD) is voor de
WGA.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

**Ingangsdatum ERD WGA O an10**

*xml tag:* IngdatERDWGA

Datum vanaf wanneer de Inhoudingsplichtige eigenrisicodrager (ERD) is
voor de WGA.

**Einddatum ERD WGA O an10**

*xml tag:* EnddatERDWGA

Datum tot wanneer de Inhoudingsplichtige eigenrisicodrager (ERD) is voor
de WGA.

**Indicatie eigenrisicodrager voor de ZW O a1**

*xml tag:* IndERDZW

Aanduiding of de Inhoudingsplichtige eigenrisicodrager (ERD) is voor de
ZW.

*code list:* Logische eenheid (subset selected)

J Ja

N Nee

**Ingangsdatum ERD ZW O an10**

*xml tag:* IngdatERDZW

Datum vanaf wanneer de Inhoudingsplichtige eigenrisicodrager (ERD) is
voor de ZW.

**Einddatum ERD ZW O an10**

*xml tag:* EnddatERDZW

Datum tot wanneer de Inhoudingsplichtige eigenrisicodrager (ERD) is voor
de ZW.

ARBOCONTRACT 0..1, O

*werkgever - ARBOCONTRACT*

*xml tag:* ArboCntrct

Het contract dat de werkgever met de arbodienst heeft gesloten.

**<u>Identificatie contract</u>**

**Contractnummer R an..40**

*xml tag:* Cntrnr

**<u>Data</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

PERSONEELSSTERKTE 0..999, O

*werkgever - PERSONEELSSTERKTE*

*xml tag:* Personeelssterkte

Gegevens met betrekking tot het aantal werknemers.

**<u>Datum waarop de Personeelssterkte is vastgesteld</u>**

**Peildatum personeelssterkte R an10**

*xml tag:* PeildatPersoneelssterkte

De datum waarop de personeelssterkte - in termen van aantallen
werknemers en FTE - is vastgesteld.

**<u>Gegevens over de personeelssterkte</u>**

**Aantal werknemers R n..7**

*xml tag:* AantWrknmrs

**Aantal FTE O n..7**

*xml tag:* AantFTE

**Aantal vrouwelijke werknemers O n..5**

*xml tag:* AantVrouwelijkeWrknmrs

Het aantal vrouwelijke werknemers dat werkt bij de werkgever.

**Aantal vrouwelijke FTE O n..5**

*xml tag:* AantVrouwelijkeFTE

Het aantal vrouwelijke FTE dat werkt bij de werkgever.

**Aantal mannelijke werknemers O n..5**

*xml tag:* AantMannelijkeWrknmrs

Het aantal mannelijke werknemers dat werkt bij de werkgever.

**Aantal mannelijke FTE O n..5**

*xml tag:* AantMannelijkeFTE

Het aantal mannelijke FTE dat werkt bij de werkgever.

**Aantal uren FTE O n..3**

*xml tag:* AantUrenFTE

Aantal uren dat 1 FTE wordt geacht te werken in een werkweek.

STRAATADRES NEDERLAND 1..9, R

*werkgever - STRAATADRES NEDERLAND*

*xml tag:* StrAdrNl

Een adres in Nederland dat wordt bepaald aan de hand van straatnaam en
huisnummer.

**<u>Soort adres</u>**

**Soort adres, code R an2**

*xml tag:* SrtAdrsCd

*code list:* Soort adres (subset selected)

01 Woonadres, verblijfadres of vestigingsadres

02 Postadres cq correspondentie adres

03 Factuuradres

05 OR adres

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Generiek voor adres</u>**

**Postcode R an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam R an..24**

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

POSTBUSADRES NEDERLAND 0..9, O

*werkgever - POSTBUSADRES NEDERLAND*

*xml tag:* PbadrsNl

De gegevens van een postbusadres in Nederland.

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Generiek voor adres</u>**

**Postcode R an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam R an..24**

*xml tag:* Wnpl

De door de gemeente vastgestelde naam van een woonplaats.

Norm(instantie): NEN 5825 (Woonplaatsnaam)

**<u>Specifiek voor postbusadres</u>**

**Postbusnummer R n..5**

*xml tag:* Pbnr

De numerieke aanduiding zoals deze door de Nederlandse TPG Post is
vastgesteld voor postbusadressen.

Norminstantie: NEN 5825 (Postbusnummer)

COMMUNICATIE 0..9, O

*werkgever - COMMUNICATIE*

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

CONTACTPERSOON 1..9, R

*werkgever - CONTACTPERSOON*

*xml tag:* Cntprsn

**<u>Identificerende gegevens</u>**

**Identificatie Werknemer O an..40**

*xml tag:* IdWrknmr

**Personeelsnummer O an..35**

*xml tag:* Persnr

De code waarmee de natuurlijk persoon in de loonadministratie van de
inhoudingsplichtige bekend is.

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

O Onbekend/niet gespecificeerd

V Vrouw

**Rol contactpersoon, code R an2**

*xml tag:* RolCntprsnCd

*code list:* Rol contactpersoon (all selected)

01 Leidinggevende

02 Casemanager

03 Medewerker P&O

04 Vervangend leidinggevende

05 Algemeen contactpersoon

COMMUNICATIE 1..9, R

*werkgever - contactpersoon - COMMUNICATIE*

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

ORGANISATIE EENHEID 0..9999, O

*werkgever - ORGANISATIE EENHEID*

*xml tag:* OrgEenh

**Verwerking, code R an2**

*xml tag:* VrwrkCd

*code list:* Verwerkingscode (all selected)

01 Nieuw

02 Gewijzigd

03 Vervallen

04 Ter identificatie en/ of ter informatie

05 Correctie

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Ingangsdatum mutatie O an10**

*xml tag:* IngdatMut

**Einddatum O an10**

*xml tag:* Enddat

**<u>Naam / referentie</u>**

**Naam organisatie-eenheid R an..70**

*xml tag:* NmOrgeenh

**Organisatie-eenheid, code R an..70**

*xml tag:* OrgeenhCd

Bilateraal afgesproken codering van de organisatie-eenheid.

**Onderdeel van organisatieeenheid, code O an..70**

*xml tag:* OndOrgeenhCd

Iedere organisatie-eenheid kan weer onderdeel zijn van een andere
organisatie-eenheid.

**<u>Loonheffingen</u>**

**Loonheffingennummer O an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de organisatie eenheid bekend is en
loonheffingen afdraagt.

ARBOCONTRACT 0..1, O

*werkgever - organisatie eenheid - ARBOCONTRACT*

*xml tag:* ArboCntrct

Het contract dat de werkgever met de arbodienst heeft gesloten.

**<u>Identificatie contract</u>**

**Contractnummer R an..40**

*xml tag:* Cntrnr

**<u>Data</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

PERSONEELSSTERKTE 0..999, O

*werkgever - organisatie eenheid - PERSONEELSSTERKTE*

*xml tag:* Personeelssterkte

Gegevens met betrekking tot het aantal werknemers.

**<u>Datum waarop de Personeelssterkte is vastgesteld</u>**

**Peildatum personeelssterkte R an10**

*xml tag:* PeildatPersoneelssterkte

De datum waarop de personeelssterkte - in termen van aantallen
werknemers en FTE - is vastgesteld.

**<u>Gegevens over de personeelssterkte</u>**

**Aantal werknemers R n..7**

*xml tag:* AantWrknmrs

**Aantal FTE O n..7**

*xml tag:* AantFTE

**Aantal vrouwelijke werknemers O n..5**

*xml tag:* AantVrouwelijkeWrknmrs

Het aantal vrouwelijke werknemers dat werkt bij de werkgever.

**Aantal vrouwelijke FTE O n..5**

*xml tag:* AantVrouwelijkeFTE

Het aantal vrouwelijke FTE dat werkt bij de werkgever.

**Aantal mannelijke werknemers O n..5**

*xml tag:* AantMannelijkeWrknmrs

Het aantal mannelijke werknemers dat werkt bij de werkgever.

**Aantal mannelijke FTE O n..5**

*xml tag:* AantMannelijkeFTE

Het aantal mannelijke FTE dat werkt bij de werkgever.

**Aantal uren FTE O n..3**

*xml tag:* AantUrenFTE

Aantal uren dat 1 FTE wordt geacht te werken in een werkweek.

STRAATADRES NEDERLAND 0..9, O

*werkgever - organisatie eenheid - STRAATADRES NEDERLAND*

*xml tag:* StrAdrNl

Een adres in Nederland dat wordt bepaald aan de hand van straatnaam en
huisnummer.

**<u>Soort adres</u>**

**Soort adres, code R an2**

*xml tag:* SrtAdrsCd

*code list:* Soort adres (subset selected)

01 Woonadres, verblijfadres of vestigingsadres

02 Postadres cq correspondentie adres

03 Factuuradres

05 OR adres

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Generiek voor adres</u>**

**Postcode R an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam R an..24**

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

POSTBUSADRES NEDERLAND 0..9, O

*werkgever - organisatie eenheid - POSTBUSADRES NEDERLAND*

*xml tag:* PbadrsNl

De gegevens van een postbusadres in Nederland.

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Generiek voor adres</u>**

**Postcode R an6**

*xml tag:* Pc

De officiële Nederlandse codering, bestaande uit een numerieke
woonplaatscode een alfabetische lettercode.

Norminstantie: NEN 5825 (Postcode)

**Woonplaatsnaam R an..24**

*xml tag:* Wnpl

De door de gemeente vastgestelde naam van een woonplaats.

Norm(instantie): NEN 5825 (Woonplaatsnaam)

**<u>Specifiek voor postbusadres</u>**

**Postbusnummer R n..5**

*xml tag:* Pbnr

De numerieke aanduiding zoals deze door de Nederlandse TPG Post is
vastgesteld voor postbusadressen.

Norminstantie: NEN 5825 (Postbusnummer)

CONTACTPERSOON 0..9, O

*werkgever - organisatie eenheid - CONTACTPERSOON*

*xml tag:* Cntprsn

**<u>Identificerende gegevens</u>**

**Identificatie Werknemer O an..40**

*xml tag:* IdWrknmr

**Personeelsnummer O an..35**

*xml tag:* Persnr

De code waarmee de natuurlijk persoon in de loonadministratie van de
inhoudingsplichtige bekend is.

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

O Onbekend/niet gespecificeerd

V Vrouw

**Rol contactpersoon, code R an2**

*xml tag:* RolCntprsnCd

*code list:* Rol contactpersoon (all selected)

01 Leidinggevende

02 Casemanager

03 Medewerker P&O

04 Vervangend leidinggevende

05 Algemeen contactpersoon

COMMUNICATIE 1..9, R

*werkgever - organisatie eenheid - contactpersoon - COMMUNICATIE*

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

VERZEKERAAR/VOLMACHT 0..9, O

*werkgever - organisatie eenheid - VERZEKERAAR/VOLMACHT*

*xml tag:* Vrzkr

**<u>Handelsnaam</u>**

**Handelsnaam organisatie R an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Identificerende gegevens</u>**

**Identificatie verzekeraar/volmacht, code O an..4**

*xml tag:* IdVrzkrVolmachtCd

Hiervoor wordt de POR-code gebruikt. Op dit moment wordt de POR-code
branchebreed gebruikt voor het uniek identificeren van bijna 700
verzekeraars/volmachten. Zie www.sivi.org.

CONTRACT 1..1, R

*werkgever - organisatie eenheid - verzekeraar/volmacht - CONTRACT*

*xml tag:* Cntrct

**<u>Identificatie contract</u>**

**Contractnummer R an..40**

*xml tag:* Cntrnr

**Contractnummer pakket O an..40**

*xml tag:* CntrnrPakket

Identificerende kenmerk van de pakketverzekering waarvan het contract
deel uitmaakt.

**<u>Data</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Gegevens over de verzuimverzekering</u>**

**Soort verzuimverzekering, code R an2**

*xml tag:* SrtVrzmvrzCd

*code list:* Soort verzuimverzekering (all selected)

01 Inloop

02 Uitloop

**Aantal verzekerden O n..5**

*xml tag:* AantVrzkrdn

KOSTENPLAATS 0..9999, O

*werkgever - KOSTENPLAATS*

*xml tag:* Kostenplaats

**<u>Periode geldig</u>**

**Ingangsdatum O an10**

*xml tag:* Ingdat

**Ingangsdatum mutatie O an10**

*xml tag:* IngdatMut

**Einddatum O an10**

*xml tag:* Enddat

**<u>Gegevens kostenplaats</u>**

**Naam kostenplaats R an..70**

*xml tag:* NmKostenplaats

**Kostenplaats, code R an..70**

*xml tag:* KostenplaatsCd

Bilateraal afgesproken codering van de kostenplaats.

**Onderdeel van kostenplaats, code O an..70**

*xml tag:* OndKostenplaatsCd

PERSONEELSSTERKTE 0..999, O

*werkgever - kostenplaats - PERSONEELSSTERKTE*

*xml tag:* Personeelssterkte

Gegevens met betrekking tot het aantal werknemers.

**<u>Datum waarop de Personeelssterkte is vastgesteld</u>**

**Peildatum personeelssterkte R an10**

*xml tag:* PeildatPersoneelssterkte

De datum waarop de personeelssterkte - in termen van aantallen
werknemers en FTE - is vastgesteld.

**<u>Gegevens over de personeelssterkte</u>**

**Aantal werknemers R n..7**

*xml tag:* AantWrknmrs

**Aantal FTE O n..7**

*xml tag:* AantFTE

**Aantal vrouwelijke werknemers O n..5**

*xml tag:* AantVrouwelijkeWrknmrs

Het aantal vrouwelijke werknemers dat werkt bij de werkgever.

**Aantal vrouwelijke FTE O n..5**

*xml tag:* AantVrouwelijkeFTE

Het aantal vrouwelijke FTE dat werkt bij de werkgever.

**Aantal mannelijke werknemers O n..5**

*xml tag:* AantMannelijkeWrknmrs

Het aantal mannelijke werknemers dat werkt bij de werkgever.

**Aantal mannelijke FTE O n..5**

*xml tag:* AantMannelijkeFTE

Het aantal mannelijke FTE dat werkt bij de werkgever.

**Aantal uren FTE O n..3**

*xml tag:* AantUrenFTE

Aantal uren dat 1 FTE wordt geacht te werken in een werkweek.

VERZEKERAAR/VOLMACHT 0..9, O

*werkgever - VERZEKERAAR/VOLMACHT*

*xml tag:* Vrzkr

**<u>Handelsnaam</u>**

**Handelsnaam organisatie R an..100**

*xml tag:* HndlsnmOrg

De naam waaronder een organisatie aan het maatschappelijk verkeer
deelneemt.

Norminstantie: SUWI

**<u>Identificerende gegevens</u>**

**Identificatie verzekeraar/volmacht, code O an..4**

*xml tag:* IdVrzkrVolmachtCd

Hiervoor wordt de POR-code gebruikt. Op dit moment wordt de POR-code
branchebreed gebruikt voor het uniek identificeren van bijna 700
verzekeraars/volmachten. Zie www.sivi.org.

*code list:* POR maatschappij aanduiding (all selected)

*The codes of this codelist are documented in a separate document*

CONTRACT 1..1, R

*werkgever - verzekeraar/volmacht - CONTRACT*

*xml tag:* Cntrct

**<u>Identificatie contract</u>**

**Contractnummer R an..40**

*xml tag:* Cntrnr

**Contractnummer pakket O an..40**

*xml tag:* CntrnrPakket

Identificerende kenmerk van de pakketverzekering waarvan het contract
deel uitmaakt.

**<u>Data</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Gegevens over de verzuimverzekering</u>**

**Soort verzuimverzekering, code R an2**

*xml tag:* SrtVrzmvrzCd

*code list:* Soort verzuimverzekering (all selected)

01 Inloop

02 Uitloop

**Aantal verzekerden O n..5**

*xml tag:* AantVrzkrdn
