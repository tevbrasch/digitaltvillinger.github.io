# Innsats team - Digital tvilling 

### Editors
Henrik Gulliksen Schuller;
Reidun Kittelsrud;
Boele Kuipers;
Jon Moe;
Nancy Niemann;
Per Erik Opseth;
Ivar Oveland;
Samuel Schiess;
Niels Torge Granum;
Tom Ellett von Brasch;

### Abstrakt

Dette dokumentet beskriver brukstilfeller som krever anvendelse av en av flere digitale tvillinger. Det underbygger arbeidet til Kartverkets Innsats-teamet med digitale tvillinger

### Status av dokumentet

Dokumentet er et internt dokument som inneholder informasjon som kan endres etter behov. 

### 1.Introduksjon 

### 2. Metodikk

For å bedre forstå kravene til en digital tvilling ble brukssaker samlet inn. For arbeidsgruppens formål er et brukstilfelle en historie som beskriver utfordringer med hensyn til nye teknologier eller metoder knyttet til en digital tvilling og dens planlagte informasjonssystemer. Det trenger ikke å følge visse standardiserte format. Brukssaker brukes primært som en kilde til krav, men et brukstilfelle kan bli revidert nær det tidspunktet prosjektgruppens arbeid er ferdig, for å demonstrere at det nå er mulig å få brukstilfellet til å fungere. 
Brukstilfellene bør beskrive problemer som enten ikke kan løses, eller ikke kan løses på en enkel eller effektiv måte, av eksisterende teknologier og systemer. I tillegg bør brukstilfellene kreve behov for data eller tjenester som forvaltes av Kartverket. 
Arbeidsgruppen har avledet krav fra de innsamlede brukssakene. Et krav er noe som må oppnås (teoretisk eller praktisk) av prosjektet og formuleres som en spesifikasjon av funksjonalitet. Krav kan føre til en eller flere tester som kan bevise om kravet er oppfylt. 


### 3. Brukstilfeller

Brukstilfellene som er gitt her kommer fra en rekke nasjonale og internasjonale prosjekter, samt teoretiske brukstilfeller opprettet av medlemmer av arbeidsgruppen etter dialog med brukere. I kapittel 4 er brukstilfellene oppført og identifisert og deretter koblet til et av flere krav (både funksjonelt og ikke-funksjonelt). Innsatsteamet har valgt å sette sammen momenter fra noen av disse som vi oppfatter godt egnet for en pilot. Hensikten er å demonstrere nytteverdi av etablerte og nye geografiske data i en digital tvilling inn mot faktiske bruksformål: 

## 3.1 Pilot brukstilfelle -<beredskap og forvaltning kyst>
  
**Komplett beskrivelse av brukstilfellet:** 

- Kommunene i Rogaland + Ålesund ønsker å tilrettelegge for bedre beredskapsplanlegging, der de kan få et riktig sanntidsbilde og beregnet sannsynlighet for havnivå, stormflo, flomveier i bebygde områder, rasfare - de ønsker å visualisere utsatte områder, og alternative adkomster for de ulike beredskapsetatene gitt ulike scenarier. Dette er tenkt for å simulere øvelser, men også som grunnlag for å tydeliggjøre behov for tiltak som flomsikring, alternative veier/sikring av veier, avgrense bygging i utsatte områder etc. Det kan også være aktuelt å simulere hendelser som for eksempel brann ved sentrale institusjoner i kombinasjon med naturhendelser/stengt veg etc. Ulike værforhold, adkomst fra nærmeste redningshelikopter og landingsplass aktuelt. Trafikkforholdene på veiene til ulike tider på døgnet kan være avgjørende for å vurdere beste adkomst til en hendelse. Framtidsscenario inkluderer også dronetransport med medisinsk personell fra sykehuset. Noen offentlige bygg som ligger særlig utsatt til, har sensorer som registrerer antall personer som oppholder seg i bygget til enhver tid – dette er viktig informasjon for beredskapsetatene og man ønsker at de som eier byggene enkelt skal supplere med slik info og BIM-modeller (adgangsbegrenset). Løsningen skal ikke bare brukes ved øvelser og planlegging av tiltak, men også støtte en reell uttrykning ved å anbefale raskeste adkomst for den enkelte beredskapsetat, tilgjengelig på mobil/i bilen for personell. Sentrale spørsmål løsningen skal støtte for visualisering og simulering: Hva KAN skje, hva GJØR vi da, hvordan VIRKER det, hvilke UTFORDRINGER møter vi på - og hvilke TILTAK kan avhjelpe utfordringene.   

- Forsvaret ønsker mulighet for detaljplanlegging for operasjoner i strandsonen, inkl. samkjøring av styrker på land og til sjøs. De trenger derfor en sammenhengende terrengmodell over sjø og land.  

**Forvaltningsbehov:**

- Kommunene har en viktig oppgave med å forvalte strandsonen og veie hensynet til utbyggingsinteresser opp mot lokale, regionale og nasjonale interesser. Strandsonen langs kysten har kvaliteter som gjør den verdifull som fellesgode for alle. Det er viktig å ta vare på disse arealene på lang sikt. I arealplanlegging og jus er begrepet strandsone ofte brukt om landbeltet 100 meter innover fra sjøen eller vassdraget.  

- Strandsonen er av nasjonal betydning og skal forvaltes slik at miljøverdier og allmenne interesser tas vare på. Det er viktig å unngå uheldig utbygging. Mange enkeltinngrep i strandsonen påvirker naturen og landskapet over tid, og forringer kvalitetene til områdene. Klimaendringene med flom og stormflo rammer strandsonen spesielt og gjør det enda viktigere å planlegge på en balansert og langsiktig måte. 

Kommunen ønsker å ta i bruk “veileder for arealplanleggeren - strandsonen i 3D” slik de er oppfordret til fra KMD.

- Det kommer etter hvert nesten ukentlig forespørsler til hoydedata@kartverket.no om hvordan våre terrengdata kan eksporteres og benyttes i spillmotorer, 3D-visualiseringsverktøy etc. Dersom vi kan tilby DTM/DOM og gjerne også kart og ortofoto i enkle format som kan benyttes i slike verktøy, vil vi senke terskelen betraktelig for å lage modeller basert på våre data.   

Brukere kan både være privatpersoner og Norge Digitalt medlemmer som ønsker å bruke våre data i system som ikke håndterer georefererte GIS-data. Det vil derfor være fint å kunne tilby ferdige pakker for begge brukergrupper basert på hva de har tilgang til. (N-50/FKB, etc)

### Relaterte krav:  
[5.1 sanntidslevering av store data](#5.1), [5.2 Dynamiske sensor data](#5.2), [5.3 Lett API grensesnitt](#5.3), [5.5 3D data](#5.5), [5.6 Felles sikkerhetslag](#5.6), [5.7 Linkability](#5.7), [5.8 Authoritative data](#5.8), [5.11 Felles referanseramme sjø og land ](#5.11)

Datakilder: Strandsonen aktualiserer behovet for felles referanseramme sjø og land, sammenstilt terrengmodell (sjø/land), N-50/FKB, ortofoto/satellittfoto, havnivåstigning, bygg (BIM-modeller vi får «låne», matrikkel, FKB), vannstand/stormflo i nær sanntid (inkl våre vannstandsmålere) og varsel fram i tid, Kobling med overvann/avrenning, og helst også elver og ferskvann. (Bølger alltid ønska). Havnedata der dette finnes, Artsdatabanken, kilder fra NVE og DSB? 

Åpent API hvor vi kan kommuner kan teste live oppdatering av tilgjengelighetsdata og havnedata – kan inngå i et case (kjører på samme plattform som FKB) 

Forhold som skal hensyntas i utvikling av strandsonen, ref Mdir, nederst på denne siden er også lenker til relevante datakilder.   

**Platform:**
visualisering kan gjøres via 3D Norge (https://kart.geonorge.no/3d/) og i samarbeid med Ålesund kommune inn i Augmentcity sin software.

**Samarbeidsparter:**
Meteorologisk institutt, NVE, kommuner (Ålesund, Stavanger), Kystverket


### 4. Opplisting brukstilfeller 

{% include_relative usecases/Katastrofeplanlegging.md %}


{% include_relative usecases/sanntids3Dkart.md %}


{% include_relative usecases/interconnectivity.md %}


{% include_relative usecases/digital_husnummer.md %}


{% include_relative usecases/bim_digital_kartmuseum.md %}


{% include_relative usecases/havomraade_strandsone.md %}


{% include_relative usecases/kommunal_planlegging.md %}


{% include_relative usecases/vaer_og_foreforhold.md %}


{% include_relative usecases/terrengmodell_sjo_land.md %}


{% include_relative usecases/forsvunnede_personer.md %}


{% include_relative usecases/kalkulere_mulighet_for_utslipp.md %}


{% include_relative usecases/ledig_parkeringsplass.md %}


{% include_relative usecases/byplanlegging.md %}


{% include_relative usecases/beredskapsplanlegging.md %}


{% include_relative usecases/ikke_gis_personer.md %}


{% include_relative usecases/segnss.md %}

## Krav

{% include_relative krav/5_1.md %}
