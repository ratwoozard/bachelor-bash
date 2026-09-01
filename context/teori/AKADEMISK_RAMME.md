# Akademisk ramme — videnskabsteori, metode og teori

Undervisningsskabelon. Erstat `[JERES PF]` og casefelter. Domæneeksempler (Lean, DSS, TOE) er **ikke** default — kun hvis de står i `PROJECT.md`.

Se også `docs/PENSUM_VIDENSBASE.md` og `docs/PENSUM_KILDEKORT_*.md`.

## DEL A: Videnskabsteori

### A.1 Fire hovedpositioner

| Position | Ontologi | Epistemologi | Typisk metode | Slutningsform |
|----------|----------|--------------|---------------|---------------|
| Positivisme | Én målbar virkelighed | Objektiv, lovmæssig viden | Kvantitativ, test | Deduktion |
| Fortolkende / hermeneutik | Socialt konstrueret | Kontekstuel fortolkning | Kvalitativ | Induktion |
| Kritisk realisme | Lagdelt virkelighed | Fejlbar tilnærmelse til mekanismer | Mixed, retroduktion | Retroduktion |
| Pragmatisme | Kompleks; det praktisk relevante | Viden vurderes på anvendelighed i forhold til spørgsmålet | Det der besvarer PF | Ofte abduktion |

Vælg den position, der matcher *jeres* PF. "Bredest" er ikke en begrundelse.

### A.2 Pragmatisme (hvis I vælger den)

Forskningsspørgsmålet driver metodevalget (Dewey, Peirce, James). I 7. semester: Holm (2023) og Saunders et al. (2023) til anvendt videnskabsteori; Kuada (2012) til korte begreber og kvalitet; Rossman & Wilson (1984) til strategien, når kval og kvant kombineres.

| Dimension | Krav til teksten |
|-----------|------------------|
| Ontologi | Vis at PF rummer både observerbare forhold og fortolkede praksisser — hvis det er tilfældet |
| Epistemologi | Hvordan forskellige evidensformer legitimeres. Ikke kun frasen "anvendelighed" |
| Slutning | Abduktion: vekslen empiri ↔ teori, hvis det er jeres primære form |
| Metode | Hver datakilde har en rolle. Metodepluralisme er ikke "lidt af hvert" |

**Typiske fejl:** "vi valgte den fordi den er bred"; at blande alt uden rollefordeling; at glemme at vise abduktionen i analysen.

**Skabelon (tilpas):**

> Projektet anlægger en pragmatisk position forankret i Holm (2023) og Saunders et al. (2023), med Kuada (2012) til begreber og kvalitetskriterier. Positionen er valgt, fordi `[JERES PF]` kræver både `[fx måling af procesmønstre]` og `[fx fortolkning af praksis]`. `[Rossman & Wilson (1984) bærer strategien for kombinationen, hvis I har mixed methods.]`

### A.3 Slutningsformer

| Form | Retning | Brug |
|------|---------|------|
| Deduktion | Teori → empiri | Når I tester en forudsigelse |
| Induktion | Empiri → mønstre | Når I koder og finder temaer |
| Abduktion | Empiri ↔ teori | Bedste forklaring; typisk i casearbejde |

```
OBSERVATION (empiri)
    ↓
TEORI (navngivet, fra kapitel 3)
    ↓
NY OBSERVATION eller anomali
    ↓
NUANCERET FUND (indikerer, ikke beviser)
```

### A.4 Hvornår pragmatisme er forkert

- I vil teste én hypotese strengt → positivisme/deduktion
- I vil forstå dyb mening → hermeneutik
- I vil afdække magtstrukturer → kritisk position
- PF er rent "hvorfor oplever X at..." uden praktisk designbehov → fortolkende

## DEL B: Metode

### B.1 Casestudie (Holm, 2023; Kuada, 2012; Saunders et al., 2023)

Yin (2018) er **ikke** default-pensum. Brug Yin kun hvis `PROJECT.md` siger det.

- **Holistisk:** organisationen som helhed
- **Indlejret:** en organisatorisk delmængde (afdeling, team, procesejerskab) — ikke tekniske workflow-states som selve case-enheden

Udfyld:

| Element | Jeres projekt |
|---------|----------------|
| Casen (helhed) | `[organisation]` |
| Indlejret afgrænsning | `[enhed / team]` |
| Analytisk fokus | `[fænomen / artefakt / proces]` |
| Kontekst | `[branche, tid, geografi]` |

**Analytisk generaliserbarhed:** til teori, ikke til population (Holm, 2023; Kuada, 2012).  
Ikke: "dette gælder alle virksomheder".  
Jo: "fundet nuancerer [teori X] i denne kontekst".

### B.2 Semistrukturerede interviews

Purposive sampling efter rolle i fænomenet. Åbne spørgsmål. Guide: `report/appendices/interviewguide.md`.

### B.3 Artefakt- eller dokumentanalyse

Hvis I har et system, en procesmodel eller dokumenter: funktionel analyse af hvad artefaktet **gør** i praksissen — ikke code review, medmindre PF kræver det.

### B.4 Tematisk analyse (Braun & Clarke, 2006) — hvis I koder interviews

Seks faser. Deduktive temaer fra kapitel 3 + emergente temaer. Det er abduktion i praksis, hvis I veksler.

### B.5 Kvalitet (Lincoln & Guba via Kuada)

| Kriterium | I teksten vises |
|-----------|-----------------|
| Credibility | Triangulering, informantvalidering, engagement |
| Transferability | Tyk kontekstbeskrivelse |
| Dependability | Transparent procedure |
| Confirmability | Bias, negative cases |

## DEL C: Teoretisk ramme

Skriv jeres teorier i kapitel 3 og i `system/THEORY_REGISTRY.md`.

Valgfrie IT/proces-kort (slet hvis irrelevante): `context/teori/teori_bibliotek/domain-okonomi-it/`.

Hver teori: definition → funktion i *jeres* USP → operationalisering → misbrugsrisiko.

Afslut kapitel 3 med, hvordan teorierne fordeles på underspørgsmål.

## DEL D: Begreber

Definér nøglebegreber konsistent. Skabelon:

| Begreb | Definition i dette projekt | Kilde |
|--------|----------------------------|-------|
| `[...]` | | |
| Analytisk generaliserbarhed | Generalisering fra case til teori | Holm (2023); Kuada (2012) |
