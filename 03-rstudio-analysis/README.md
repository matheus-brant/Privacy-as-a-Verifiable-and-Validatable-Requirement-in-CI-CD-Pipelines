# RStudio — Computational Analysis and Visual Synthesis

This directory contains the **RStudio project used to organize computational analyses, descriptive summaries, and figures** associated with the two empirical stages of the dissertation:

- **Stage 1 — Tertiary study:** synthesis and visualization of data extracted or consolidated from the literature review conducted with Parsifal.
- **Stage 2 — Interview-based reflexive thematic analysis:** descriptive and graphical syntheses of material organized through ATLAS.ti, without treating code frequency as a measure of interpretive significance.

Unlike the initial version of this repository, which distributed an isolated `rsl_privacy.Rmd` file, the current version includes the **project directory and its accompanying materials**.

## Project structure

The folder shown in the repository is:

```text
03-rstudio-analysis/
├── README.md
└── tertiary-study-privacy/
    ├── rsl-privacy.Rproj
    ├── tertiary-study-privacy.Rmd
    ├── *.xlsx
    ├── *.csv
    └── figure_*.png  (and other available figure files)
```

The listing summarizes the file types visible in the project; it is **not an exhaustive file manifest**. Examples of visible workbooks include `dados.xlsx`, `search_string.xlsx`, `selection_process.xlsx`, `keywords.xlsx`, and `final_summary_table.xlsx`. Some files appear to contain interview-related summaries and figure outputs. The exact set of files should be checked in the GitHub directory.

## Opening and running the project

1. Download the contents of this repository (GitHub: **Code → Download ZIP**) and extract them locally.
2. Install R and RStudio, if necessary.
3. Open [`tertiary-study-privacy/rsl-privacy.Rproj`](tertiary-study-privacy/rsl-privacy.Rproj) in RStudio.
4. Open [`tertiary-study-privacy/tertiary-study-privacy.Rmd`](tertiary-study-privacy/tertiary-study-privacy.Rmd).
5. Inspect the package-loading statements and install the required R packages in your local environment. Dependencies and package versions have **not** been independently locked or verified.
6. Check all paths to `.xlsx`, `.csv`, and other inputs. The working directory used by the original project may differ from the location where you extracted the repository; correct relative paths only where needed.
7. Review the datasets and intended outputs associated with the tertiary study and interview-stage analyses. Execute code chunks incrementally, examine any errors, and compare generated figures and tables with the reported dissertation results.
8. Preserve regenerated outputs separately, or give them clearly distinguishable names, to avoid accidentally overwriting the files originally supplied with the project.

> **Reproducibility status:** Project files and supporting materials are present in the repository according to the supplied screenshots. A clean-environment execution, dependency audit, complete input/output mapping, and full figure-by-figure verification have **not** been performed.

## Interpretation and scope

The RStudio materials may include analyses and graphics related to both stages, although the project directory is named `tertiary-study-privacy`. Do not assume that every file was generated directly by the R Markdown document or that each R chunk maps one-to-one to a published figure; inspect the code and inputs to establish these relationships.

Graphs reporting counts or distributions from ATLAS.ti are **descriptive representations of the coded corpus**, not statistical estimates of prevalence, participant representativeness, or thematic importance. Interpretation of the final themes remains grounded in the qualitative analysis.

## Data protection and sharing

The original ATLAS.ti `.qdpx` project, complete interview transcripts, and participant-level identifiable data should not be added to this directory. **Before publishing the complete RStudio folder**, inspect `.xlsx`, `.csv`, `.png`, and any project metadata for names, interview excerpts, hidden spreadsheet sheets, absolute local paths, or other information that should not be disclosed.

For the broader protocol and data restrictions, see the [repository README](../README.md) and [data-availability statement](../docs/data-availability.md).
