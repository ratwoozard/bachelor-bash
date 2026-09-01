# PROJECT — udfyld før I skriver

Dette er den eneste projektlås. Agenter læser filen først. Opdigt ikke det, der står tomt.

Erstat alle `[...]`. Sæt `PF_STATUS` til `låst`, når problemformuleringen er aftalt med vejleder.

---

## Stamdata

| Felt | Værdi |
|------|-------|
| Uddannelse | `[fx KEA Bachelor i Økonomi & IT]` |
| Institution | `[fx KEA]` |
| Forfattere | `[navne]` |
| Vejleder | `[navn]` |
| Deadline | `[dato klokkeslæt]` |
| Sprog | `da` |
| Anslag / sidetal (mål) | `[...]` |

## Problemformulering

**PF_STATUS:** `kladde` | `låst`

**Problemformulering:**

> `[Hvordan kan ... ?]`

**Underspørgsmål:**

1. `[...]`
2. `[...]`
3. `[...]`
4. `[...]`

## Case og scope

| Felt | Værdi |
|------|-------|
| Organisation / case | `[navn, eller "anonymiseret"]` |
| Fænomen | `[det I undersøger]` |
| Inde i scope | `[proces, periode, enhed]` |
| Ude af scope | `[det I bevidst lader ligge]` |
| Case-type | `[fx indlejret single-case / holistisk / multiple]` |

Skriv caseviden i `context/case/`. Skriv ikke fortrolige detaljer her, hvis repoet er offentligt.

## Videnskabsteori og metode

| Felt | Værdi |
|------|-------|
| Position | `[fx pragmatisme]` |
| Slutningsform | `[fx abduktion]` |
| Design | `[fx eksplorativt casestudie]` |
| Datakilder planlagt | `[fx interviews, artefakt, dokumenter, tal]` |
| Særlige pensumregler | `[fx ikke Yin; Rossman & Wilson til strategi]` |

Begrund valgene i `report/02-method.md`. Kopiér ikke denne tabel ind som metodekapitel.

## Datakilder I faktisk har

Kun det, der ligger i repoet eller er registreret her. Tom celle = findes ikke.

| Kilde | Status | Sti / bilag | Må bruges til | Må ikke bruges til |
|-------|--------|-------------|---------------|-------------------|
| Interviews | `[mangler / indsamlet / kodet]` | `context/interviews/` | | |
| Artefakt / dokumenter | `[...]` | `context/case/` | | |
| Kvantitative data | `[...]` | `research/data/` | | |
| Andet | `[...]` | | | |

Opdater `context/evidence/EMPIRI_STATUS.md` når noget ændrer sig.

## Kapitel 3 — teorier I faktisk bruger

Udfyld `system/THEORY_REGISTRY.md` med de samme rækker. Agenten må **ikke** antage Lean, DSS, TOE eller andre domænemodeller, medmindre de står her.

| Teori / model | Primær kilde (forfatter, år) | Bruges til | Må ikke bruges til |
|---------------|------------------------------|------------|-------------------|
| `[...]` | `[...]` | `[...]` | `[...]` |

## Skriveprioritet lige nu

Aktiv front: `[fx report/02-method.md]`

Næste handling: `[én konkret opgave]`

## Agent-instruks (kort)

- Læs denne fil før `report/`.
- Skriv kun i det kapitel, brugeren peger på, medmindre brugeren beder om andet.
- Ingen tal, citater eller kilder, der ikke kan pege på en fil eller en verificeret reference.
- Brug `indikerer` / `påvirker` — ikke `beviser` / `forbedrer`.
