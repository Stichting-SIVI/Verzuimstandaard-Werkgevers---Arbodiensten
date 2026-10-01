**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel*

Transaction type: *Basistransactie Verzuim*

Functional message: ***Dienstverbanden 2026***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

24 juni 2026

Summary

Bericht algemeen 1..1, V

Administratiekantoor 0..1, F

Werkgever 1..\*, V

1 Communicatie 0..9, F

1 Contactpersoon 0..9, F

2 Communicatie 1..9, V

1 Werknemer 1..\*, V

2 Dienstverband 1..999, V

3 Arbeidsrelatie 0..1, F

3 Kostenplaats 0..9, F

3 Contactpersoon 0..9, F

4 Communicatie 1..9, V

BERICHT ALGEMEEN 1..1, V

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code V an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00106 Dienstverbanden

**Versienummer bericht, code V an..5**

*xml tag:* VnrBrCd

*code list:* Versienummer bericht (subset selected)

00006 Versienummer 6

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht V an10**

*xml tag:* AandatBr

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

ADMINISTRATIEKANTOOR 0..1, F

*ADMINISTRATIEKANTOOR*

*xml tag:* AdmKantoor

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

**Vestigingsnummer F n..12**

*xml tag:* VestigingsnrHandelsregister

Een identificerend nummer voor een vestiging in het Handelsregister.

Norminstantie: Handelsregister

WERKGEVER 1..\*, V

*WERKGEVER*

*xml tag:* Wrkgvr

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

**Vestigingsnummer F n..12**

*xml tag:* VestigingsnrHandelsregister

Een identificerend nummer voor een vestiging in het Handelsregister.

Norminstantie: Handelsregister

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

**<u>Identificatie bij UWV</u>**

**Identificatie werkgever bij UWV F an..40**

*xml tag:* IdWrkgvrUWV

De identificatie die het UWV heeft aangeleverd aan de werkgever

waardoor de werkgever wordt onderscheiden van andere werkgevers in de
administratie van het UWV.

**<u>Loonbelasting / loonheffingen</u>**

**Loonheffingennummer V an..12**

*xml tag:* Lhnr

Een door de Belastingdienst toegekende identificatie voor de
administratieve eenheid waaronder de werkgever bekend is en
loonheffingen afdraagt.

COMMUNICATIE 0..9, F

*werkgever - COMMUNICATIE*

*xml tag:* Com

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

Het veld bevat een geldige duiding van de soort communicatie, zoals
e-mailadres of telefoonummer. In het geval van een telefoonnummer is het
formaat in het bericht volgens ITU-T E.164: +31201234567

CONTACTPERSOON 0..9, F

*werkgever - CONTACTPERSOON*

*xml tag:* Cntprsn

**<u>Identificerende gegevens</u>**

**Identificatie Werknemer F an..40**

*xml tag:* IdWrknmr

**Personeelsnummer F an..35**

*xml tag:* Persnr

De code waarmee de natuurlijk persoon in de loonadministratie van de
inhoudingsplichtige bekend is.

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

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**Rol contactpersoon, code V an2**

*xml tag:* RolCntprsnCd

*code list:* Rol contactpersoon (all selected)

01 Leidinggevende

02 Casemanager

03 Medewerker P&O

04 Vervangend leidinggevende

05 Algemeen contactpersoon

**<u>Identificatiegegevens contactpersoon</u>**

**Identificatie contactpersoon F an..40**

*xml tag:* IdCntctprsn

COMMUNICATIE 1..9, V

*werkgever - contactpersoon - COMMUNICATIE*

*xml tag:* Com

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

Het veld bevat een geldige duiding van de soort communicatie, zoals
e-mailadres of telefoonummer. In het geval van een telefoonnummer is het
formaat in het bericht volgens ITU-T E.164: +31201234567

WERKNEMER 1..\*, V

*werkgever - WERKNEMER*

*xml tag:* Wrknmr

Een werknemer is de natuurlijke persoon met wie een inkomstenverhouding
binnen de loonadministratie bestaat.

**<u>Wijze waarop de gegevens verwerkt moeten worden</u>**

**Ingangsdatum mutatie F an10**

*xml tag:* IngdatMut

**Geboortedatum V an10**

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

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code V an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**Niveau opleiding, code F an2**

*xml tag:* NivOpldngCd

*code list:* Niveau opleiding (all selected)

01 Geen opleiding afgemaakt, gevolgd

02 Basisonderwijs, lagere school

03 VMBO (LBO/MAVO)

04 HAVO/VWO

05 Middelbaar beroepsonderwijs (MBO)

06 Hoger beroepsonderwijs (HBO)

07 Wetenschappelijk onderwijs (universiteit)

99 Onbekend

**<u>Identificatie</u>**

**Identificatie werknemer V an..40**

*xml tag:* IdWrknmr

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

**Identificatie werknemer oud F an..40**

*xml tag:* IdWrknmrOud

DIENSTVERBAND 1..999, V

*werkgever - werknemer - DIENSTVERBAND*

*xml tag:* Dnstvbnd

**<u>Wijze waarop de gegevens verwerkt moeten worden</u>**

**Ingangsdatum mutatie F an10**

*xml tag:* IngdatMut

**<u>Identificatie</u>**

**Identificatie dienstverband V an..40**

*xml tag:* IdDnstvbnd

Unieke code voor het dienstverband van de werknemer.

**Identificatie dienstverband oud F an..40**

*xml tag:* IdDnstvbndOud

**<u>Datums</u>**

**Ingangsdatum V an10**

*xml tag:* Ingdat

**Einddatum F an10**

*xml tag:* Enddat

De datum van de laatste dag waarop de gegevens geldig zijn.

**<u>Einde dienstverband</u>**

**Reden einde dienstverband, code F an2**

*xml tag:* RdEndDnstvbndCd

Bron: Arbo Unie

*code list:* Reden einde dienstverband (subset selected)

01 Ontslag

03 Pensioen

05 Overleden

06 Tijdelijk ouderdomspensioen

08 Beëindiging dienstverband

09 WIA

10 Beëindiging tijdelijk dienstverband

99 Onbekend

**<u>Personeelsnummer behorende bij het dienstverband</u>**

**Personeelsnummer F an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

**Personeelsnummer oud F an..35**

*xml tag:* PersNrOud

**<u>Contractnummer</u>**

**Contractnummer bij Arbo-dienst F an..40**

*xml tag:* CntrnrArbdnst

Het door de Arbo-dienst gebruikte contractnummer en waaronder de
desbetreffende werknemer met zijn dienstverband valt.

**<u>Beschrijving werkzaamheden</u>**

**Soort dienstverband, code F an2**

*xml tag:* SrtDnstvbndCd

Bron: ArboNed (2021)

*code list:* Soort dienstverband (subset selected)

04 WSW'er

05 Stagiair

07 Uitzendkracht

20 Dienstverband onbepaalde tijd

21 Tijdelijke arbeidsovereenkomst

22 Dienstverband fictief

23 Oproep/invalkracht

24 ZZP

**Functiecode F an..15**

*xml tag:* Fnctcd

De code van de functie zoals die bij de klant bekend is of zoals die is
overeengekomen met de Arbo-dienst.

**Naam functie F an..35**

*xml tag:* NmFnct

**<u>Flex & Zekerheid</u>**

**Code fase indeling F&Z F an..2**

*xml tag:* FsIndFZ

Code die aangeeft in welke fase de inkomstenverhouding voor bepaalde
tijd zich bevindt in het kader van de Wet flexibiliteit en zekerheid.

Bron: Loonaangifte.

*code list:* Code fase indeling F&Z (subset selected)

1 Fase 1-2 met uitzendbeding

3 Fase 3

4 Fase 4

5 Wettelijk regime

6 Ketensysteem

17 Fase A met uitzendbeding

18 Fase B

19 Fase C

38 Fase A zonder uitzendbeding, met loonuitsluiting

40 Fase A zonder uitzendbeding

41 Fase 1-2 zonder uitzendbeding

43 Fase 1-2 zonder uitzendbeding, met loonuitsluiting

**<u>Locatie</u>**

**Naam organisatie-eenheid F an..70**

*xml tag:* NmOrgeenh

**Organisatie-eenheid, code V an..70**

*xml tag:* OrgeenhCd

De code van de organisatie-eenheid, zoals die bij de klant bekend is of
zoals die is overeengekomen met de Arbo-dienst.

**Onderdeel van organisatieeenheid, code F an..70**

*xml tag:* OndOrgeenhCd

Iedere organisatie-eenheid kan weer onderdeel zijn van een andere
organisatie-eenheid.

**Onderdeel van organisatie-eenheid, naam F an..70**

*xml tag:* OndOrgeenhCdNm

Deze naam hoort bij Onderdeel van organisatie-eenheid, code

**Postcode standplaats F an..9**

*xml tag:* PcStandplts

Postcode van de standplaats waar de werknemer is tewerkgesteld.

**Omschrijving standplaats F an..70**

*xml tag:* OmsStandplts

Beschrijving of verbijzondering van de plaats of locatie waar de
werknemer is tewerkgesteld.

**Verdeling, code F an..35**

*xml tag:* VrdlngCd

Bilateraal afgesproken codering ten behoeve van de verdeling van het
werk.

**<u>Gegevens over arbeidsovereenkomst</u>**

**Code contract onbepaalde / bepaalde tijd F an1**

*xml tag:* CdBepTd

Code die aangeeft of het arbeidscontract voor bepaalde of onbepaalde
tijd geldig is.

Bron: Loonaangifte.

*code list:* Code contract onbepaalde / bepaalde tijd (all selected)

B Bepaalde tijd

O Onbepaalde tijd

**<u>Beschrijving aantal uren e.d.</u>**

**Aantal contracturen per week F n..5,2**

*xml tag:* AantCtrcturenPWk

Het tussen de werkgever en werknemer vast overeengekomen aantal uren per
week zoals opgenomen in of af te leiden uit de CAO of individuele
arbeidsovereenkomst of dat voortvloeit uit de publiekrechtelijke
aanstelling of de fictieve dienstbetrekking.

Bron: Loonaangifte

**Normuren per week F n..6,2**

*xml tag:* AantUNormWk

Norm aantal uren per week. Dit wordt bepaald door de CAO en/of
aanvullende afspraken bij de werkgever.

Bron: Uniforme Pensioenaangifte

**Soort variabele werktijden, code F an2**

*xml tag:* SrtVarWrktdCd

Bron:

Berekening van ziekteverzuim

NVS Standaard voor verzuimregistratie

Nationale Verzuimstatistiek

November 2004

*code list:* Soort variabele werktijden (all selected)

01 Regelmatige dienst (eventueel met verschoven uren)

02 Tweeploegendienst

03 Meer dan tweeploegendiensten

04 Onregelmatige dienst (geen ploegendienst)

**Aantal loonwachtdagen F n..3**

*xml tag:* AantLnwchtdgn

Aantal wachtdagen voor loondoorbetaling bij ziekte, volgens de (c)ao.

Bron: UWV

**<u>Loondoorbetaling</u>**

**Percentage loondoorbetaling F n..6,2**

*xml tag:* PrcLndrbtng

Bij arbeidsgehandicapten.

Percentage loondoorbetaling bij ziekte, volgens de (c)ao.

ARBEIDSRELATIE 0..1, F

*werkgever - werknemer - dienstverband - ARBEIDSRELATIE*

*xml tag:* Arbeidsrelatie

De betrekking tussen werkgever en werknemer die ontstaat bij loonarbeid
na afsluiting van een arbeidsovereenkomst.

Dit wordt ook wel aanstelling genoemd.

**<u>Identificerende gegevens arbeidsrelatie</u>**

**Identificatie arbeidsrelatie V an..40**

*xml tag:* IdArbeidsrelatie

**Identificatie arbeidsrelatie oud F an..40**

*xml tag:* IdArbeidsrelatieOud

**Personeelsnummer F an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

**Personeelsnummer oud F an..35**

*xml tag:* PersNrOud

**<u>Data</u>**

**Ingangsdatum V an10**

*xml tag:* Ingdat

**Ingangsdatum mutatie F an10**

*xml tag:* IngdatMut

**Einddatum F an10**

*xml tag:* Enddat

De datum van de laatste dag waarop de gegevens geldig zijn.

**<u>Uren per week</u>**

**Aantal contracturen per week V n..5,2**

*xml tag:* AantCtrcturenPWk

De formele arbeidsduur per week, zoals die is opgenomen in het contract
bij arbeidsverhouding/aanstelling.

KOSTENPLAATS 0..9, F

*werkgever - werknemer - dienstverband - KOSTENPLAATS*

*xml tag:* Kostenplaats

**<u>Periode geldig</u>**

**Ingangsdatum F an10**

*xml tag:* Ingdat

**Ingangsdatum mutatie F an10**

*xml tag:* IngdatMut

**Einddatum F an10**

*xml tag:* Enddat

De datum van de laatste dag waarop de gegevens geldig zijn.

**<u>Gegevens kostenplaats</u>**

**Naam kostenplaats V an..70**

*xml tag:* NmKostenplaats

**Kostenplaats, code V an..70**

*xml tag:* KostenplaatsCd

Bilateraal afgesproken codering van de kostenplaats.

**Onderdeel van kostenplaats, code F an..70**

*xml tag:* OndKostenplaatsCd

**Onderdeel van kostenplaats, naam F an..70**

*xml tag:* OndKostenplaatsNm

CONTACTPERSOON 0..9, F

*werkgever - werknemer - dienstverband - CONTACTPERSOON*

*xml tag:* Cntprsn

**<u>Identificerende gegevens</u>**

**Identificatie Werknemer F an..40**

*xml tag:* IdWrknmr

**Personeelsnummer F an..35**

*xml tag:* Persnr

De code waarmee de natuurlijk persoon in de loonadministratie van de
inhoudingsplichtige bekend is.

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

*code list:* Geslacht (all selected)

M Man

O Onbekend/niet gespecificeerd

V Vrouw

**Rol contactpersoon, code V an2**

*xml tag:* RolCntprsnCd

*code list:* Rol contactpersoon (all selected)

01 Leidinggevende

02 Casemanager

03 Medewerker P&O

04 Vervangend leidinggevende

05 Algemeen contactpersoon

**<u>Identificatiegegevens contactpersoon</u>**

**Identificatie contactpersoon F an..40**

*xml tag:* IdCntctprsn

COMMUNICATIE 1..9, V

*werkgever - werknemer - dienstverband - contactpersoon - COMMUNICATIE*

*xml tag:* Com

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

Het veld bevat een geldige duiding van de soort communicatie, zoals
e-mailadres of telefoonummer. In het geval van een telefoonnummer is het
formaat in het bericht volgens ITU-T E.164: +31201234567
