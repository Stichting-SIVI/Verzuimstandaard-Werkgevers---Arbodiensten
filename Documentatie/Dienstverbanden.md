**Functional message: Hierarchic**

Business chain: *Verzuim Datamodel 0.2*

Transaction type: *Basistransactie Verzuim*

Functional message: ***Dienstverbanden 2019***

Actor group: *Verzuimstandaard Werkgever - Arbodienst*

XML Tag Set: *Standard XML*

**Copyright SIVI**

23 juni 2019

Summary

Bericht algemeen 1..1, R

Administratiekantoor 0..1, O

Werkgever 1..\*, R

1 Straatadres Nederland 0..9, O

1 Postbusadres Nederland 0..9, O

1 Communicatie 0..9, O

1 Contactpersoon 0..9, O

2 Communicatie 1..9, R

1 Werknemer 1..\*, R

2 Dienstverband 1..99, R

3 Arbeidsrelatie 0..1, O

3 Kostenplaats 0..9, O

3 Contactpersoon 0..9, O

4 Communicatie 1..9, R

BERICHT ALGEMEEN 1..1, R

*BERICHT ALGEMEEN*

*xml tag:* BrAlg

**<u>Soort bericht + versienummer</u>**

**Bericht, code R an..5**

*xml tag:* BrCd

*code list:* Berichtcode (subset selected)

00106 Dienstverbanden

**Versienummer bericht, code R an..5**

*xml tag:* VnrBrCd

*code list:* Versienummer bericht (subset selected)

00002 Versienummer 2

**<u>Aanmaakdatum</u>**

**Aanmaakdatum bericht R an10**

*xml tag:* AandatBr

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

STRAATADRES NEDERLAND 0..9, O

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

CONTACTPERSOON 0..9, O

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

WERKNEMER 1..\*, R

*werkgever - WERKNEMER*

*xml tag:* Wrknmr

Een werknemer is de natuurlijke persoon met wie een inkomstenverhouding
binnen de loonadministratie bestaat.

**<u>Wijze waarop de gegevens verwerkt moeten worden</u>**

**Ingangsdatum mutatie O an10**

*xml tag:* IngdatMut

**Geboortedatum R an10**

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

**<u>Overige gegevens</u>**

**Geslachtsaanduiding, code R an1**

*xml tag:* GslchtCd

De sekse van een persoon, zoals bij de geboorte formeel vastgesteld of
nadien formeel gewijzigd.

Bron: NEN 1888: 2002 - Geslacht

*code list:* Geslacht (subset selected)

M Man

V Vrouw

**Niveau opleiding, code O an2**

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

**Identificatie werknemer R an..40**

*xml tag:* IdWrknmr

Een unieke identificatie van de werknemer bij de werkgever. Een eenmaal
uitgegeven identificatie wordt niet hergebruikt.

**Identificatie werknemer oud O an..40**

*xml tag:* IdWrknmrOud

DIENSTVERBAND 1..99, R

*werkgever - werknemer - DIENSTVERBAND*

*xml tag:* Dnstvbnd

**<u>Wijze waarop de gegevens verwerkt moeten worden</u>**

**Ingangsdatum mutatie O an10**

*xml tag:* IngdatMut

**<u>Identificatie</u>**

**Identificatie dienstverband R an..40**

*xml tag:* IdDnstvbnd

Unieke code voor het dienstverband van de werknemer.

**Identificatie dienstverband oud O an..40**

*xml tag:* IdDnstvbndOud

**<u>Datums</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Einddatum O an10**

*xml tag:* Enddat

**<u>Einde dienstverband</u>**

**Reden einde dienstverband, code O an2**

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

**Personeelsnummer O an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

**Personeelsnummer oud O an..35**

*xml tag:* PersNrOud

**<u>Contractnummer</u>**

**Contractnummer bij Arbo-dienst O an..40**

*xml tag:* CntrnrArbdnst

Het door de Arbo-dienst gebruikte contractnummer en waaronder de
desbetreffende werknemer met zijn dienstverband valt.

**<u>Beschrijving werkzaamheden</u>**

**Soort dienstverband, code O an2**

*xml tag:* SrtDnstvbndCd

Bron: ArboNed (2006)

*code list:* Soort dienstverband (all selected)

01 Normale arbeidsovereenkomst

02 Aanneming werk

03 Vertegenwoordiger

04 WSW'er

05 Stagiair

06 Thuiswerker

07 Uitzendkracht

08 Musicus / artiest /beroepssporter

09 Persoonlijke arbeid tegen beloning

10 Maatschapsvisser

11 Bestuurder van een cooperatieve vereniging

Vereniging met werknemers zelfbestuur.

12 Oproep / invalkracht

13 Vakantiewerk

14 Dienstplichtig militair

15 Ambtenaar / ABP-er

16 Deelvisser

17 Gemoedsbezwaarde

18 Topsporter

19 65-plusser

**Functiecode O an..15**

*xml tag:* Fnctcd

De code van de functie zoals die bij de klant bekend is of zoals die is
overeengekomen met de Arbo-dienst.

**Naam functie O an..35**

*xml tag:* NmFnct

**<u>Flex & Zekerheid</u>**

**Code fase indeling F&Z O an..2**

*xml tag:* FsIndFZ

Code die aangeeft in welke fase de inkomstenverhouding voor bepaalde
tijd zich bevindt in het kader van de Wet flexibiliteit en zekerheid.

Bron: Loonaangifte.

*code list:* Code fase indeling F&Z (all selected)

0 Onbekend of n.v.t.

1 Fase 1 (met uitzendbeding)

2 Fase 2 (met uitzendbeding)

3 Fase 3

4 Fase 4

5 Wettelijk regime

6 Ketensysteem

17 Fase A met uitzendbeding

18 Fase B

19 Fase C

38 Fase A zonder uitzendbeding, met loonuitsluiting

40 Fase A zonder uitzendbeding

41 Fase 1 zonder uitzendbeding

42 Fase 2 zonder uitzendbeding

43 Fase 1 zndr uitzendbedi met uitsl. loondrbet.vrplicht.

Fase 1 zonder uitzendbeding, met uitsluiting van
loondoorbetalingsverplichting.

44 Fase 2 zndr uitzendbedi met uitsl. loondrbet.vrplicht.

Fase 2 zonder uitzendbeding, met uitsluiting van
loondoorbetalingsverplichting.

**<u>Locatie</u>**

**Naam organisatie-eenheid O an..70**

*xml tag:* NmOrgeenh

**Organisatie-eenheid, code R an..70**

*xml tag:* OrgeenhCd

De code van de organisatie-eenheid, zoals die bij de klant bekend is of
zoals die is overeengekomen met de Arbo-dienst.

**Onderdeel van organisatieeenheid, code O an..70**

*xml tag:* OndOrgeenhCd

Iedere organisatie-eenheid kan weer onderdeel zijn van een andere
organisatie-eenheid.

**Onderdeel van organisatie-eenheid, naam O an..70**

*xml tag:* OndOrgeenhCdNm

Deze naam hoort bij Onderdeel van organisatie-eenheid, code

**Postcode standplaats O an..9**

*xml tag:* PcStandplts

Postcode van de standplaats waar de werknemer is tewerkgesteld.

**Verdeling, code O an..35**

*xml tag:* VrdlngCd

Bilateraal afgesproken codering ten behoeve van de verdeling van het
werk.

**<u>Duur contract</u>**

**Code contract onbepaalde / bepaalde tijd O an1**

*xml tag:* CdBepTd

Code die aangeeft of het arbeidscontract voor bepaalde of onbepaalde
tijd geldig is.

Bron: Loonaangifte.

*code list:* Code contract onbepaalde / bepaalde tijd (all selected)

B Bepaalde tijd

O Onbepaalde tijd

**<u>Beschrijving aantal uren e.d.</u>**

**Contractueel aantal uren per week O n..6,2**

*xml tag:* CntrctUrnWk

Het aantal uren - conform het arbeidscontract dat van toepassing is bij
de werkgever - waarop arbeid wordt verricht bij een volledige werkweek.

**Deeltijdfactor NVS O n..5,2**

*xml tag:* DltfctNVS

Bedoeld voor werknemers die niet voor de volledige werktijd in dienst
zijn. Vaak vindt berekening plaats door op weekbasis het aantal werkuren
te delen op het aantal werkuren bij een volledige aanstelling
(bijvoorbeeld: bij korter werken 24/38 = 0,63; bij langer werken 40/36 =
1,11).

Berekening: Deeltijdfactor= Werkuren week/Werkuren week volledige
aanstelling

Bron:

Berekening van ziekteverzuim

NVS Standaard voor verzuimregistratie

Nationale Verzuimstatistiek

November 2004

**Soort variabele werktijden, code O an2**

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

**Aantal loonwachtdagen O n..3**

*xml tag:* AantLnwchtdgn

Aantal wachtdagen voor loondoorbetaling bij ziekte, volgens de (c)ao.

Bron: UWV

**<u>Loondoorbetaling</u>**

**Percentage loondoorbetaling O n..6,2**

*xml tag:* PrcLndrbtng

Bij arbeidsgehandicapten.

Percentage loondoorbetaling bij ziekte, volgens de (c)ao.

ARBEIDSRELATIE 0..1, O

*werkgever - werknemer - dienstverband - ARBEIDSRELATIE*

*xml tag:* Arbeidsrelatie

De betrekking tussen werkgever en werknemer die ontstaat bij loonarbeid
na afsluiting van een arbeidsovereenkomst.

Dit wordt ook wel aanstelling genoemd.

**<u>Identificerende gegevens arbeidsrelatie</u>**

**Identificatie arbeidsrelatie R an..40**

*xml tag:* IdArbeidsrelatie

**Identificatie arbeidsrelatie oud O an..40**

*xml tag:* IdArbeidsrelatieOud

**Personeelsnummer O an..35**

*xml tag:* PersNr

De code waarmee de natuurlijk persoon in de administratie van de
inhoudingsplichtige bekend is.

Bron: Loonaangifte.

**Personeelsnummer oud O an..35**

*xml tag:* PersNrOud

**<u>Data</u>**

**Ingangsdatum R an10**

*xml tag:* Ingdat

**Ingangsdatum mutatie O an10**

*xml tag:* IngdatMut

**Einddatum O an10**

*xml tag:* Enddat

**<u>Uren per week</u>**

**Aantal contracturen per week R n..5,2**

*xml tag:* AantCtrcturenPWk

De formele arbeidsduur per week, zoals die is opgenomen in het contract
bij arbeidsverhouding/aanstelling.

KOSTENPLAATS 0..9, O

*werkgever - werknemer - dienstverband - KOSTENPLAATS*

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

**Onderdeel van kostenplaats, naam O an..70**

*xml tag:* OndKostenplaatsNm

CONTACTPERSOON 0..9, O

*werkgever - werknemer - dienstverband - CONTACTPERSOON*

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

*werkgever - werknemer - dienstverband - contactpersoon - COMMUNICATIE*

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
