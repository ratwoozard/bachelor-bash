# Guide til studerende

bachelor-os er et skrive-OS: mapper, regler og agent-instruktioner. Det er **ikke** en færdig bachelor og **ikke** et facit.

## Første 30 minutter

1. Clone eller fork repoet. Åbn mappen i Cursor.
2. Udfyld [PROJECT.md](PROJECT.md): PF, case, scope, position, datakilder, kap. 3-teorier.
3. Læs [report/STATUS.md](report/STATUS.md). Sæt aktiv front til det kapitel, I faktisk skriver på.
4. Sig til agenten: *Læs PROJECT.md og AGENTS.md. Skriv ikke i andre kapitler end X.*

Hvis empirien er fortrolig: **privat** fork, eller hold `context/interviews/` og `research/data/` ude af git (de er delvist gitignored).

## Arbejdsgang

```
PF i PROJECT.md
    → metode (kap. 2) med @bachelor-metode-mode
    → teori (kap. 3) + THEORY_REGISTRY.md
    → empiri først (EMPIRI_STATUS.md)
    → analyse (kap. 4) med evidenskæde
    → diskussion og konklusion
```

Empiri før analyse. Tom `EMPIRI_STATUS` = I har ikke fundet noget endnu = agenten må ikke citere det.

## Hvad I ikke må lade agenten gøre

- Opfinde interviews, tal, sidetal eller bøger
- Låse PF uden at I har sagt ja
- Trække Lean, DSS eller TOE ind, medmindre I har skrevet dem i `PROJECT.md`
- Skrive "beviser" / "forbedrer" / "gælder alle virksomheder"
- Omskrive hele rapporten "for at gøre den bedre"

Hvis agenten gør det: ret `PROJECT.md`, peg på `FORBUDTE_FORMULERINGER.md`, og bed om salvage (`prompts/analysis-salvage.md`).

## Sådan styrer I agenten

| I vil | I skriver |
|-------|-----------|
| Metode | `@bachelor-metode-mode` + `report/02-method.md` |
| Analyse | `@bachelor-analyse-mode` + konkret afsnit |
| Tjek teori | brug `prompts/theory-validation.md` |
| Finpuds | `prompts/finpudefase-promptpakke.md` |

Autoritet: `PROJECT.md` → `report/` → `system/` → `context/`.

## Pensum

Default er KEA Økonomi & IT: Holm, Kuada, Saunders. Mixed methods-strategi: Rossman & Wilson (1984). Andet pensum: ret `SOURCE_PRIORITY.md` og `PROJECT.md`.

Domænekort under `context/teori/teori_bibliotek/domain-okonomi-it/` er eksempler. Slet dem, hvis de ikke er jeres.

## Offentligt vs. privat

Dette repo er offentligt og indeholder **ingen** andres interviews eller virksomhedsdata. Jeres kopi må ikke blive det sted, I lækker samtykkebeskyttede transskriptioner.

## Næste filer

- [AGENTS.md](AGENTS.md) — det agenten skal følge
- [context/teori/AKADEMISK_RAMME.md](context/teori/AKADEMISK_RAMME.md) — videnskabsteori
- [context/guides/KVALITET_OG_SKRIVEGUIDE.md](context/guides/KVALITET_OG_SKRIVEGUIDE.md) — kapitelhåndværk
