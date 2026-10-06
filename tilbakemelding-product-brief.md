# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G76 – G76-carlsen |
| **Product brief** | Ingen product brief funnet på main (siste commit `4ed7163`) |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Det ble ikke funnet noen product brief i repoet på main per 2026-10-06. Lag en brief før dere lager PRD og arkitektur.

Repoet inneholder foreløpig bare startfilene som ble opprettet ved oppstart (`README.md` og `.gitignore`), og det er ikke gjort egne commits. Vi fant heller ingen andre spor av prosjektideen, for eksempel en prosjektbeskrivelse i README eller i commit-meldinger. Derfor kan vi ikke gi en foreløpig vurdering av vanskelighetsgrad og gjennomførbarhet ennå. Har dere levert brief eller proposal et annet sted, bør den legges inn i repoet.

**Hvorfor briefen er viktig for del 1 av mappen:**

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen (applikasjon og prosess, 70 %) vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app (kriterium 1, prosess og KI-styring, 30 %). Den vurderes også på om appen gjør det dere har beskrevet, om den er testet, og om den kan kjøres etter README. Uten en brief i repoet mangler starten på denne sporbarheten, og både omfang og testbarhet blir vanskeligere å styre. Det er mye enklere å legge et godt grunnlag nå enn sent i semesteret.

**Hva briefen bør inneholde:**

- **Executive Summary:** hva appen er, og hvilket problem den løser, med noen få setninger.
- **The Problem:** et konkret problem, med reelle situasjoner og brukere.
- **The Solution:** hva brukeren opplever og får gjort i appen, ikke bare hvilken teknologi dere vil bruke.
- **What Makes This Different:** en ærlig vurdering av hva som finnes fra før, og hva som er deres vri.
- **Who This Serves:** én tydelig primærbruker og hva den trenger.
- **Success Criteria:** kriterier som kan sjekkes eller testes, for eksempel «brukeren kan registrere … og se det i oversikten».
- **Scope:** hva som er med i første versjon («In for v1»), og hva som bevisst er utelatt («Explicitly out»).
- **Vision:** hvor appen kan gå videre, uten at det blåser opp første versjon.
- **En begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet:** sammenlign med forslagslista «Prosjektforslag for IBE160» (for eksempel 6) To-do-liste med smarte etiketter som enkel, 7) Kurs-FAQ-chatbot som middels, eller 3) KI-styrt simulering av prosjektledelse som vanskelig). Vurder om dere kan kontrollere at KI-ens kode gir riktige svar, og om sensor kan kjøre appen etter README uten deres nøkler eller betalte kontoer.

**Slik kommer dere i gang:**

Bruk BMAD-flyten: product brief → PRD → arkitektur → epics og stories → implementering med Claude Code. Start med BMAD sin product brief-arbeidsflyt (for eksempel `bmad-product-brief` i Claude Code), og lagre resultatet i repoet, gjerne under `_bmad-output/planning-artifacts/briefs/`. Se faglærers eksempelprosjekt https://github.com/IBE160-2026/beergame for hvordan en brief og den videre BMAD-dokumentasjonen kan se ut.

## 3. Neste steg for gruppen

1. Bli enige om prosjektidé, gjerne med utgangspunkt i forslagslista, og velg et omfang dere tror dere kan gjøre ferdig og teste i løpet av semesteret.
2. Lag product brief med BMAD, med alle delene over og en egen vurdering av vanskelighetsgrad og gjennomførbarhet. Commit den til repoet.
3. Oppdater README med en kort beskrivelse av hva appen skal gjøre, og gå deretter videre til PRD.

Legg briefen inn i repoet så snart den er klar, og oppdater den når planen endrer seg, slik at historikken viser hvordan planen utviklet seg. Det er en del av prosessen sensor ser etter.
