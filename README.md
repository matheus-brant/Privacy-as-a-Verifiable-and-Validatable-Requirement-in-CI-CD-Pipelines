# Towards Privacy Verification in DevOps Pipelines — Research Replication Package

This repository documents the empirical procedures and research materials associated with a dissertation on privacy verification and validation in continuous software engineering and CI/CD pipelines. Its purpose is to support **methodological transparency, traceability, and research replicability**, while distinguishing reproducible computational steps from the interpretive nature of qualitative analysis.

## Repository structure

| Directory | Contents |
| --- | --- |
| [`01-tertiary-study/`](01-tertiary-study/) | Tertiary study protocol, Parsifal workflow documentation, and screenshots. |
| [`02-thematic-analysis/`](02-thematic-analysis/) | Interview-based reflexive thematic analysis protocol, ATLAS.ti workflow documentation, and screenshots. |
| [`03-rstudio-analysis/`](03-rstudio-analysis/) | RStudio project folder, analysis scripts, spreadsheets/CSVs, and graphical outputs supplied with the project. |
| [`docs/`](docs/) | Reproducibility guidance and data-availability restrictions. |

## Stage 1 — Tertiary study (Parsifal)

The tertiary study investigated existing secondary evidence concerning privacy verification and validation in DevOps and CI/CD environments. It covered secondary studies published from **January 2014 through December 2025**, searched seven sources, and used Parsifal for protocol management, study selection, quality appraisal, and data extraction.

The initial search on **18 February 2025** retrieved **6,890 records**. The updated retrieval on **23 March 2026** brought the reported retrieval total to **10,722 records**. The materials include an updated protocol workbook and an illustrated procedure for reviewing the Parsifal workflow.

Begin with the [tertiary study README](01-tertiary-study/README.md) and its [execution guide](01-tertiary-study/procedures/parsifal-execution-guide.md).

## Stage 2 — Interview-based reflexive thematic analysis (ATLAS.ti)

The interview stage involved **16 interviews** organized and analyzed with ATLAS.ti. The documented project state includes **4,204 quotations, 3,996 codes, 12 memos, and 35 consolidated thematic groups** across five specific research questions. These quantities describe the project's organization and **must not be interpreted as statistical measures of a theme's importance**.

The protocol and illustrated workflow document the chain from interview documents to quotations, codes, analytical groups, and themes. The original ATLAS.ti `.qdpx` project and interview transcripts are **not published in this repository**.

Begin with the [thematic analysis README](02-thematic-analysis/README.md) and its [ATLAS.ti execution guide](02-thematic-analysis/procedures/atlas-ti-execution-guide.md).

## RStudio — Computational analysis, figures, and synthesis

The repository now contains the **RStudio project directory**, rather than only an isolated R Markdown file. The project folder `03-rstudio-analysis/tertiary-study-privacy/` includes an RStudio project file (`rsl-privacy.Rproj`), an R Markdown source (`tertiary-study-privacy.Rmd`), and supporting `.xlsx`, `.csv`, and figure files visible in the uploaded project structure.

These materials support the descriptive analyses and graphical syntheses reported across the tertiary study and interview-analysis stages. The supplied files include research inputs and outputs, but **the relationship between every individual input, script section, and generated figure has not yet been independently validated**. Before reproducing outputs, inspect the project's file paths and dependencies and review which datasets are approved for sharing.

See the [RStudio documentation](03-rstudio-analysis/README.md) for the project layout, suggested execution procedure, and limitations.

## Reproducibility and data availability

The documentation is intended to support:

1. **Procedural reproducibility:** understanding how Parsifal and ATLAS.ti were used and which methodological decisions were documented.
2. **Computational reproducibility:** inspecting and, after verifying dependencies and input data, rerunning the R Markdown analysis.
3. **Analytical traceability:** linking study selection and qualitative coding procedures to reported syntheses, to the extent permitted by research ethics and data availability.

Reproducing the qualitative interpretation does not require an independent analyst to obtain identical themes. The presence of scripts and datasets does not itself establish that every figure can be regenerated without additional setup.

Consult the [reproducibility guide](docs/reproducibility-guide.md) and [data-availability statement](docs/data-availability.md). **Before making this repository public**, review every data table, image, filename, and script for participant information or other restricted content, including files within the newly uploaded RStudio project.

## Citation and licensing

Please cite the associated dissertation when using these materials. Bibliographic metadata and the appropriate license should be completed or confirmed by the author before public release.
