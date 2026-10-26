# Changelog

Release notes for Arvin Research Studio. This public-safe file is maintained in
the research source repository and copied to the public website repository.

## 2026-10-26 — EDGAR documents and financial-data mapping

- Added SEC EDGAR as a separate dataset, with an EX-11 section and three verified historical earnings-per-share exhibits. Its eleven dictionary fields describe a document manifest, not extracted financial observations.
- Added reproducible R edgar collection and offline registration with source-document type, accession, byte-length and SHA-256 checks. Public pages expose reviewed document metadata and official links; downloads and request logs remain local.
- Added fifteen bilingual form-use categories, a searchable official submission-type registry, current and historical exhibit meanings, and scoped file-size evidence. The registry includes nonpublic and historical labels; it is not a count of public datasets. Whole-archive and per-category sizes remain unmeasured.
- Distinguished historical EX-11 earnings-per-share exhibits from EX-10 material contracts, and bulk filing-history / XBRL ZIP sizes from full filing documents.
- Expanded RoyaltyStat's identifier notes with documented financial-data mapping routes and their limits, without claiming that a crosswalk was executed.
- Updated both versions, maintenance instructions and verification for six datasets.

## 2026-10-26 — RoyaltyStat field categories

- Added identifiers, transaction attributes, governance and performance as logical field categories within the RoyaltyStat dictionary, with bilingual descriptions and a rationale for each field.
- Grounded the distinction in Mooi and Ghosh's 2010 Journal of Marketing article, read through the user's Zotero API. The article provides a conceptual reference; it did not use RoyaltyStat.
- Retained an explicitly empty performance category because contractual royalty rates and payment terms do not measure realized performance or the article's contracting-cost outcomes.
- Kept the original SQL table, field definitions and examples intact. Category selection filters the existing dictionary and export instead of inventing new database tables.
- Renamed the second definition bullet to AI verification / AI查核 while preserving the original source definition and unresolved measurement limits.

## 2026-10-26 — Field examples and plain-language datatype help

- Replaced the public dictionary's local-only messages with reviewed examples for every registered field. Personal identifiers and identifying text are anonymized, and transformed values or short excerpts are explicitly labeled.
- Kept reviewed field examples separate from coherent sample rows, query records and private analysis results. Public builds read only the curated example registry.
- Added a short bilingual explanation and concrete example in parentheses at the first visible occurrence of each SQL datatype family in a dataset. Explanations update after filtering, table selection, collapsing and language changes; original SQL type labels and CSV exports stay unchanged.
- Updated both local and public versions, maintenance instructions and validation.

## 2026-10-25 — Live measurement checks and selectable method formulas

- Rechecked the registered WRDS tables with read-only schema and aggregate queries. Updated preview SQL types, category descriptions, Supply Chain currency/source links and its historical table's observed subset relationship.
- Added dated aggregate scope facts for Revelio: exact counts where queries completed, estimates where large scans timed out, verified date extrema and server storage with partitions counted once. Kept missing provider definitions and inaccessible codebooks explicit.
- Corrected the old Compustat sample description: its current selection includes USD and CAD reporting currencies, so the sales threshold is not uniformly a US-dollar threshold.
- Typeset method, article-variant and pipeline formulas as selectable MathML. Added Copy LaTeX to formulas, including the full HTML handout, with controls that appear on hover or keyboard focus.
- Added one concise practical scenario in each language for all 12 methods. Updated both versions, validation and maintenance instructions.

## 2026-10-25 — Research design, methods and analysis records

- Added Research design & methods as the second, global navigation item, organized by method with expandable article-specific variants.
- Seeded 12 methods from the authored Farronato–Zervas handout, with purposes, inputs/outputs, assumptions, diagnostics and implementation choices.
- Converted both handout languages into HTML with native mathematical notation, the full comparison table and footnotes. Rebuilt its branching research-design pipeline as interactive HTML.
- Added dataset-scoped Data analysis with two documented existing assistant-run audits, execution details and separate local result snapshots. Datasets without recorded analyses remain empty.
- Kept actual analysis results local; the public version displays only reviewed summaries. Added source-hash checks, record validation and maintenance instructions for future additions.

## 2026-10-25 — Dataset navigation and table controls

- Added a dataset selector beside the language selector on dataset pages. Switching datasets preserves the current section and language.
- Aligned table-index and CSV-export buttons with the column-width controls.
- Added Expand all / Collapse all in All fields view, scoped to the current search and filter results.
- Kept both selectors usable on mobile, including while the sidebar is open.
- Established a maintenance rule: update this changelog and relevant README guidance, rebuild and check the local and public versions, then sync both repositories and verify the published pages.

## 2026-10-25 — Public bilingual studio

- Published a metadata-only website with five dataset entries, dictionaries, measurement notes and literature cases.
- Added English and Traditional Chinese, with English as the first-visit default.
- Split each field definition into its verbatim original and verified measurement details, with unresolved points clearly marked.
- Added concise time-coverage, sample-size and file-size bullets; removed redundant single-table index entries.
- Added smooth sidebar motion, column-width controls and a floating horizontal scrollbar.
- Simplified dataset titles and entry links, explained Preview availability, and moved the maintenance date to the bottom-right footer.
- Kept licensed observations and private practice records in the local version.
