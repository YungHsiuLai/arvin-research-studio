# Changelog

Release notes for Arvin Research Studio. This public-safe file is maintained in
the research source repository and copied to the public website repository.

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
