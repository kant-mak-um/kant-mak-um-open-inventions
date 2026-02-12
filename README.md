# Open Inventions

A public repository of defensive technical disclosures. Every invention documented here is published as **prior art** to prevent corporate capture through patents, while remaining freely available for anyone to use, build upon, and improve.

## Purpose

This repository serves three goals:

1. **Prevent patenting** — By publicly disclosing each invention with sufficient technical detail, we establish prior art that prevents anyone from obtaining a valid patent on these ideas.
2. **Enable open use** — Anyone can use, manufacture, and improve these inventions under open-source terms.
3. **Require openness** — Copyleft licensing ensures that derivative works must also remain open.

## Licensing

| Content Type | License |
|---|---|
| Documentation & Drawings | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| Hardware Designs | [CERN-OHL-S-2.0](https://ohwr.org/cern_ohl_s_v2.txt) |
| Software | [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html) |

## Invention Index

| ID | Title | Category | Status | Prototype |
|----|-------|----------|--------|-----------|
| [INV-001](inventions/INV-001-cam-strap-quick-release/DISCLOSURE.md) | Quick-Release Cam Strap Tightener | Mechanical / Fasteners | Draft | — |
<!-- Add new inventions here as rows -->

## Repository Structure

```
open-inventions/
├── README.md                          ← You are here
├── LICENSE-DOCS.md                    ← CC BY-SA 4.0
├── LICENSE-HARDWARE.md                ← CERN-OHL-S-2.0
├── LICENSE-SOFTWARE.md                ← GPL-3.0
├── CONTRIBUTING.md                    ← How others can contribute
│
├── inventions/
│   └── INV-001-descriptive-name/
│       ├── DISCLOSURE.md              ← Main technical disclosure
│       ├── metadata.yaml              ← Tags, categories, cross-references
│       ├── drawings/                  ← Diagrams, schematics, photos
│       ├── cad/                       ← CAD files (STEP, STL, etc.)
│       ├── software/                  ← Code (if applicable)
│       ├── tests/                     ← Test data and results
│       └── references/                ← Related patents, papers, datasheets
│
├── templates/
│   ├── disclosure-template.md         ← Copy this to start a new invention
│   └── metadata-template.yaml         ← Copy this for each invention's metadata
│
└── index/
    ├── by-category.md                 ← Inventions grouped by domain
    ├── by-component.md                ← Shared components across inventions
    └── dependency-map.md              ← Which inventions build on others
```

## How to Use This Repository

### To use an invention
Browse the [Invention Index](#invention-index) above, click into any disclosure, and follow the detailed description to build or implement it.

### To add a new invention
1. Copy `templates/disclosure-template.md` and `templates/metadata-template.yaml` into a new folder under `inventions/` named `INV-XXX-short-description/`
2. Fill in the template — include only the optional modules that apply
3. Add drawings to the `drawings/` subfolder
4. Update the Invention Index table in this README
5. Update the cross-reference indexes in `index/`

### To submit to the MIT Prior Art Archive
The Prior Art Archive accepts Word documents, PDFs, images, web pages, spreadsheets, text files, and video. For each invention:
1. Export the disclosure as a PDF (or submit the markdown directly)
2. Include all drawings as separate image files
3. Contact: priorartarchive@media.mit.edu to request upload access
4. Upload via the secured FTP server they provide

## Cross-Reference Indexes

- [**By Category**](index/by-category.md) — Inventions grouped by technical domain
- [**By Component**](index/by-component.md) — Shared components and subsystems
- [**Dependency Map**](index/dependency-map.md) — How inventions relate to each other

## Disclaimer

These disclosures are published for the purpose of establishing prior art. They are not patent applications. No warranties are made regarding fitness for any particular purpose. Users assume all responsibility for implementation and safety.
