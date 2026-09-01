# EVIDENCE CHAIN RULES

Alle analysepåstande i kapitel 4 skal følge:

**Empiri → Observation → Teori → Analytisk fortolkning → Analytisk delkonklusion**

Mangler et led, er teksten ikke færdig analyse.

## Kæden

| Led | Krav | Eksempel (generisk) |
|-----|------|---------------------|
| Empiri | Konkret bilag, figur, tabel, interview, artefakt eller dataset i `context/evidence/` | Interview A; figur 4.1; tabel i `research/data/` |
| Observation | Hvad empirien viser, uden overfortolkning | Informanten beskriver X; dataene viser mønster Y |
| Teori | Navngivet model fra `THEORY_REGISTRY.md` | `[jeres teori]` |
| Fortolkning | Betydning set gennem teorien | Observation Z kan forstås som ... |
| Delkonklusion | Scoped svar på USP/PF | Fundet indikerer ..., inden for scope |

## Grundregler

- Ingen claim uden empiri.
- Ingen teori uden funktion.
- Ingen kilde uden author-year.
- Sidetal kun når verificeret. Ellers `[MANGLER: sidetal]`.
- Adskil interview, artefakt, tal og ekstern kilde.
- Brug aldrig en ulæst kilde.

## Datatype

| Type | Funktion | Må bruges til | Må ikke bruges til |
|------|----------|---------------|-------------------|
| QUANT | Mønster, indikator | Flow, rater, tider, volumen *hvis data findes* | Alene at forklare praksis |
| QUAL | Forklaring, betydning | Interviews, vurdering, oplevet friktion | At dokumentere målte effekter |
| THEORY | Fortolkende ramme | Registrerede kap. 3-teorier | At erstatte empiri |

**CLAIM-regel:** Bland ikke QUANT, QUAL og THEORY uden eksplicit overgang.

## Forbudt

- Teori uden empiri; empiri uden fortolkning; figurer uden læsning.
- Overclaim: "beviser", "viser entydigt", "forbedrer" uden dokumenteret effekt.
- Interview som repræsentativ måling.
- Tal som årsagsforklaring uden kvalitativ triangulering (hvis I har QUAL).

## Acceptable formuleringer

- "Interviewdataene indikerer..."
- "Dataene peger på..."
- "Proceskortlægningen visualiserer..."
- "Set gennem [teori] kan dette fortolkes som..."
- "Fundet begrænser ..., fordi..."

## Ikke acceptable

- "Det virker som om..."
- "Man kan argumentere for..." (uden evidens)
- "Dette beviser..."
- "[Teknologi] vil forbedre processen..."
