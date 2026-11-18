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

## Europe PMC

Two searches were associated with these export filenames:

- `europepmc (1).xml` — Europe PMC Search 1.
- `europepmc.xml` — Europe PMC Search 2.

**Exact Boolean queries have not been recovered** and are not fabricated here.

## Search-documentation and provenance note

These strings are archived **verbatim from the search-strategy transcription supplied in the project conversation**. This archive does **not** independently authenticate them against the original platform query-history export or saved search logs. Consult original database search histories before describing them as the final executed strategies in a journal supplementary appendix.

Original Scopus, PubMed, Europe PMC, Embase and Web of Science search counts, filters and run timestamps should be reconciled with exported files where available. The approved title-and-abstract ledger records 1,445 screened and 369 retained, which are screening-level counts rather than a replacement for database-level retrieval counts.

**Syntax caution:** PubMed truncation inside quotation marks with `[tiab]` and some quoted phrases may be parsed differently than expected; preserve these archived expressions for provenance and independently check the live query translations before rerunning or describing their execution.
