# BRD4 drug repurposing scoping review — Search strategies

**Review title:** Drug Repurposing for BRD4: A Scoping Review of Screening Strategies and Experimental Evidence  
**Search-session date reported in project discussion:** 5 November 2026  
**Archived here:** 18 November 2026

## Scopus — TITLE-ABS-KEY search

```text
TITLE-ABS-KEY(
  (BRD4 OR "bromodomain-containing protein 4"
   OR "bromodomain 4" OR "BET bromodomain*"
   OR "BET protein*")
  AND
  (repurpos* OR reposition* OR "drug rediscovery"
   OR "existing drug*" OR "approved drug*"
   OR "FDA-approved" OR "drug library"
   OR "virtual screening" OR "high-throughput screening"
   OR "structure-based screening"
   OR "ligand-based screening"
   OR "pharmacophore screening"
   OR "molecular docking" OR "similarity search"
   OR "machine learning" OR QSAR)
)
```

**Search/export counts noted in earlier discussion:** 910, 430 and 796. These represent different Scopus searches/exports, **not** unique records, and cannot be added as a deduplicated screening count without the original export log.

## PubMed — Primary search

```text
(
  BRD4[tiab]
  OR "bromodomain-containing protein 4"[tiab]
  OR "bromodomain 4"[tiab]
  OR "BET bromodomain"[tiab]
  OR "BET bromodomains"[tiab]
)
AND
(
  repurpos*[tiab]
  OR reposition*[tiab]
  OR "drug library"[tiab]
  OR "drug libraries"[tiab]
  OR "compound library"[tiab]
  OR "FDA-approved"[tiab]
  OR "approved drugs"[tiab]
  OR "existing drugs"[tiab]
  OR "kinase inhibitors"[tiab]
  OR "virtual screening"[tiab]
  OR "high-throughput screening"[tiab]
  OR "biochemical screening"[tiab]
  OR "pharmacophore screening"[tiab]
  OR "structure-based screening"[tiab]
  OR "ligand-based screening"[tiab]
  OR "drug screening"[tiab]
  OR "molecular docking"[tiab]
  OR "similarity searching"[tiab]
)
```

## PubMed — Supplementary BET-family search (excluding explicit BRD4 terms)

```text
(
  "BET bromodomain*"[tiab]
  OR "BET protein*"[tiab]
  OR "bromodomain and extraterminal"[tiab]
  OR "bromodomain and extra-terminal"[tiab]
  OR "bromodomain extraterminal"[tiab]
)
AND
(
  repurpos*[tiab]
  OR reposition*[tiab]
  OR "drug library"[tiab]
  OR "drug libraries"[tiab]
  OR "approved drug*"[tiab]
  OR "FDA-approved"[tiab]
  OR "kinase inhibitor*"[tiab]
  OR "drug screening"[tiab]
  OR "virtual screening"[tiab]
  OR "high-throughput screening"[tiab]
  OR "pharmacophore screening"[tiab]
  OR "biochemical screening"[tiab]
  OR "database mining"[tiab]
  OR "drug discovery"[tiab]
)
NOT
(
  BRD4[tiab]
  OR "bromodomain-containing protein 4"[tiab]
  OR "bromodomain 4"[tiab]
)
```

## Europe PMC — original chat recovered (5 November 2026)

### Europe PMC Search 1 — 257 records in initial report

Recovered from the original conversation message dated **5 November 2026, 17:50:44 UTC**:

```text
(TITLE_ABS:BRD4 OR TITLE_ABS:"bromodomain-containing protein 4" OR TITLE_ABS:"bromodomain 4" OR TITLE_ABS:"BET bromodomain" OR TITLE_ABS:"BET bromodomains") AND (TITLE_ABS:repurpos* OR TITLE_ABS:reposition* OR TITLE_ABS:"FDA-approved" OR TITLE_ABS:"approved drugs" OR TITLE_ABS:"existing drugs" OR TITLE_ABS:"drug library" OR TITLE_ABS:"drug libraries" OR TITLE_ABS:"kinase inhibitors" OR TITLE_ABS:"virtual screening" OR TITLE_ABS:"high-throughput screening" OR TITLE_ABS:"biochemical screening" OR TITLE_ABS:"pharmacophore screening" OR TITLE_ABS:"structure-based screening" OR TITLE_ABS:"ligand-based screening" OR TITLE_ABS:"drug screening" OR TITLE_ABS:"molecular docking" OR TITLE_ABS:"database mining")
```

The original conversation associates Search 1 with `europepmc.xml` and **257 records**; a later XML recount gave **258**. This discrepancy is retained, not reconciled without the export.

### Europe PMC Search 2 — 67 records

The original conversation records a second BET-family search returning **67 records**, with **24** overlapping Search 1. Its complete original Boolean query could not yet be retrieved from the accessible conversation excerpts. Initial conversation count was **300 unique Europe PMC source records** (257 + 67 − 24). The second export was associated with `europepmc (1).xml`, subject to file-level verification.

## Embase — original chat recovered (5 November 2026)

The original conversation dated **5 November 2026, 18:13:27 UTC** reports **411 results for Search 1**, **111 for Search 2**, **47 overlapping**, and **475 unique Embase records**.

### Embase Search 1 — recovered portion

The available history preserves this exact expression up to its final visible term; it may continue beyond `molecular docking`, so this is **not represented as a complete executed query**:

```text
(BRD4:ti,ab,kw OR 'bromodomain-containing protein 4':ti,ab,kw OR 'bromodomain 4':ti,ab,kw OR 'BET bromodomain':ti,ab,kw OR 'BET bromodomains':ti,ab,kw) AND (repurpos*:ti,ab,kw OR reposition*:ti,ab,kw OR 'approved drugs':ti,ab,kw OR 'FDA-approved':ti,ab,kw OR 'existing drugs':ti,ab,kw OR 'drug library':ti,ab,kw OR 'drug libraries':ti,ab,kw OR 'compound library':ti,ab,kw OR 'compound libraries':ti,ab,kw OR 'kinase inhibitors':ti,ab,kw OR 'virtual screening':ti,ab,kw OR 'high-throughput screening':ti,ab,kw OR 'biochemical screening':ti,ab,kw OR 'pharmacophore screening':ti,ab,kw OR 'structure-based screening':ti,ab,kw OR 'ligand-based screening':ti,ab,kw OR 'drug screening':ti,ab,kw OR 'molecular docking':ti,ab,kw
```

Embase Search 2 used per-term `:ti,ab,kw` syntax. Its full Boolean text has not been recovered.

## Search-documentation and provenance note

These strings are archived **verbatim from the search-strategy transcription supplied in the project conversation**. This archive does **not** independently authenticate them against the original platform query-history export or saved search logs. Consult original database search histories before describing them as the final executed strategies in a journal supplementary appendix.

Original Scopus, PubMed, Europe PMC, Embase and Web of Science search counts, filters and run timestamps should be reconciled with exported files where available. The approved title-and-abstract ledger records 1,445 screened and 369 retained, which are screening-level counts rather than a replacement for database-level retrieval counts.

**Syntax caution:** PubMed truncation inside quotation marks with `[tiab]` and some quoted phrases may be parsed differently than expected; preserve these archived expressions for provenance and independently check the live query translations before rerunning or describing their execution.


## Additional original-conversation Scopus strings recovered (18 November re-audit)

Original conversation indexed at **5 November 2026, 17:15:12 UTC**, includes another Scopus Search A version. It differs from the broader previously archived TITLE-ABS-KEY string above; keep both as distinct recorded expressions until the original Scopus search-history export links each executed query to its result count.

### Scopus Search A — fully recovered version

```text
TITLE-ABS-KEY((BRD4 OR "bromodomain-containing protein 4" OR "bromodomain 4" OR "BET-BRD4" OR "BET bromodomain*") AND (repurpos* OR reposition* OR "existing drug*" OR "approved drug*" OR "FDA-approved drug*" OR "known drug*" OR "investigational drug*" OR "drug librar*" OR "drug screening" OR ("virtual screening" OR "high-throughput screening" OR "biochemical screening" OR "pharmacophore screening" OR "structure-based screening" OR "ligand-based screening" OR "similarity screening" OR "database mining" OR "molecular docking") AND (drug* OR compound* OR inhibitor* OR ligand*)))
```

**Interpretation warning:** This archived expression contains an AND before the nested screening terms; do not silently change the logic or claim it is the only Scopus Search A variant. Other original-chat result excerpts show a different Scopus Search A string with additional pharmacological compound terms.

### Scopus Search B — recovered fragment only

```text
TITLE-ABS-KEY((BRD4 OR "bromodomain-containing protein 4" OR "bromodomain 4" OR "BET-BRD4") AND ("virtual screening" OR "high-throughput screening" OR "biochemical screening" OR "drug screening" OR "pharmacophore screening" OR "pharmacophore-based screening" OR "ligand-based screening" OR "structure-based screening" OR "
```

**NOT the complete query**; the original conversation retrieval truncates this expression after the final visible quotation mark. Do not run it as-is.

### Earlier user's Scopus query — incomplete transcript fragment

A user-provided Scopus query at **5 November 2026, 17:06 UTC** began with `TITLE-ABS-KEY ( ( repurpos* OR "drug repurposing"...` and included the closing clause `( BRD4 OR BET ) W/3 ( phenotype* OR "gene expression" OR transcript* OR transcriptional )`. The middle of the expression has not been retrieved. This is evidence of another distinct historical query, **not** a reconstructable complete search string.

### Remaining exact-query evidence gaps after searching original chat and Library

- Europe PMC Search 2: **67** records and **24** overlaps reported; full Boolean text unavailable in accessible original message.
- Embase Search 2: **111** records and **47** overlaps reported; full Boolean text unavailable in accessible original message.
- Embase Search 1: recorded only up to `'molecular docking':ti,ab,kw`; trailing expression not retrievable.
- Web of Science: no verified historical exact query retrieved; no new query is attributed to original search.
- Scopus exports: `export_e33d2282-2165-44a5-b0e2-854802c7fd68_2026-11-05T170737.422083188.csv`, `export_1d254ca2-948a-475d-9c45-2f6f13848f87_2026-11-05T171719.377607191.csv`, `export_e294a87c-7431-405e-a936-bb497012f289_2026-11-05T172207.23174059.csv` recorded in `BRD4_Repurposing_Source_Provenance.csv`. Exact query/export mapping has not been established.
