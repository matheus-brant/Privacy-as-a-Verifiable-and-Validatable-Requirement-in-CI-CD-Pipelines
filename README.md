# Towards Privacy Verification in DevOps Pipelines — Research Replication Package

This repository documents the empirical procedures and shareable research artifacts associated with a dissertation on privacy verification and validation in CI/CD environments. It distinguishes **procedural reproducibility**, **computational reproducibility**, and the interpretive limits of qualitative research.

## Stage 1 — Tertiary study (Parsifal)

See [`01-tertiary-study/README.md`](01-tertiary-study/README.md). The study searched seven databases for secondary studies published January 2014–December 2025. The first retrieval on 18 February 2025 yielded 6,890 records; the updated retrieval on 23 March 2026 yielded 10,722 records. Parsifal supported selection, quality appraisal, and data extraction. The workbook documents the protocol and its methodological updates; screenshots and a stepwise guide illustrate software operations.

## Stage 2 — Interview-based reflexive thematic analysis (ATLAS.ti)

See [`02-thematic-analysis/README.md`](02-thematic-analysis/README.md). Sixteen anonymized interviews were organized and coded in ATLAS.ti. The documented project contains 4,204 quotations, 3,996 codes, 12 memos and 35 consolidated thematic groups. The analysis is interpretive, and these counts do not measure thematic importance. The proprietary QDPX project and interview transcripts are **not distributed**.

## RStudio — Figures and data synthesis for both stages

See [`03-rstudio-analysis/README.md`](03-rstudio-analysis/README.md). The R Markdown script [`rsl_privacy.Rmd`](03-rstudio-analysis/rsl_privacy.Rmd) contains code for analysis and graphics across both empirical stages. **Its referenced input workbooks are not included in this initial package.** Run the document only after supplying ethically shareable input data with the filenames and schemas expected by the script; do not assume it executes from a fresh clone.

## Replicability and data availability

Start with [`docs/reproducibility-guide.md`](docs/reproducibility-guide.md) and [`docs/data-availability.md`](docs/data-availability.md). This repository documents methods and includes the R Markdown source; it does not claim independent verification or exact regeneration of all published outputs. Restricted data are intentionally excluded.

## Citation and licensing

Please cite the associated dissertation when using these materials. Bibliographic metadata and a publication license should be confirmed by the author before public release.
