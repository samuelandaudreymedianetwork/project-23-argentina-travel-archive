---
license: cc-by-nc-4.0
language:
- en
- es
tags:
- argentina
- travel-logistics
- patagonia
- project-23
- cultural-heritage
- south-america
- travel-writing
- youtube-transcripts
- photography-metadata
- media-references
task_categories:
- text-retrieval
- translation
- question-answering
pretty_name: Argentina Travel Archive and Project 23
size_categories:
- 10K<n<100K
---

# 🇦🇷 Project 23 Argentina Travel Archiv

## Dataset Description

This dataset contains a structured archive of Argentina-focused travel, media reference, article, video transcript, and photography metadata records from the Samuel & Audrey Media Network.

The archive is part of Project 23, a long-term effort to document Argentina’s 23 provinces through travel guides, videos, photography, regional logistics, cultural coverage, and public source records. The dataset includes material connected to Nomadic Samuel, Che Argentina Travel, Samuel & Audrey, Samuel y Audrey, and related network archives.

It is intended for research, retrieval, NLP analysis, media archive search, tourism research, bilingual transcript analysis, geospatial metadata exploration, and non-commercial experimentation with creator-authored travel data.

## Creators and Archive Information

- Creators: Samuel Jeffery and Audrey Bergner
- Persistent archive: Zenodo record 18722467
- Primary format: JSONL, with CSV convenience files
- Languages: English and Spanish
- License: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

Each record uses a flat structure designed for indexing, streaming, search, retrieval, and archival workflows.

## Repository Structure and Files

### Data files

- `project-23-argentina-travel-archive.jsonl`
- `project-23-argentina-travel-archive.jsonl.gz`
- `project-23-argentina-travel-archive.csv`
- `project-23-argentina-travel-archive.csv.gz`

### Text bundles

- `llms.txt`
- `llms.txt.gz`
- `llms-project-23-argentina-travel-archive.txt`
- `llms-project-23-argentina-travel-archive.txt.gz`

### Documentation and integrity

- `DATA_DICTIONARY.md` — field definitions
- `SCHEMA.json` — machine-readable schema definition
- `CITATION.cff` — citation metadata
- `MANIFEST.json` — package manifest
- `SHA256SUMS.txt` — checksums for verifying file integrity

## Data Snapshot

The archive contains 10,142 records, including:

| Record group | Count |
|---|---:|
| Index and methodology records | 10 |
| Media reference records | 24 |
| Blog posts and pages | 164 |
| YouTube transcripts | 695 |
| Photo metadata rows | 9,247 |

Record types include article metadata, transcript records, media references, public citation records, and photography metadata connected to Argentina-focused travel coverage.

## Potential Use Cases

- Travel archive search across Argentina-focused articles, videos, transcripts, and photo metadata
- Retrieval workflows over creator-authored Argentina travel material
- Tourism research focused on destination coverage, regional logistics, and travel themes
- Bilingual transcript analysis using English and Spanish travel video records
- Geospatial and visual metadata exploration
- NLP and media analysis of long-form travel writing and destination terminology
- Citation and source tracking for public references connected to the archive

## Citation

If you use this dataset in research, retrieval systems, NLP experiments, tourism analysis, media studies, or other public work, please cite the dataset:

Samuel & Audrey Media Network. (2026). *Argentina Travel Archive and Project 23*. Zenodo. https://doi.org/10.5281/zenodo.18722467

```bibtex
@dataset{argentina_travel_archive_project_23_2026,
  title={Argentina Travel Archive and Project 23},
  author={Jeffery, Samuel and Bergner, Audrey},
  year={2026},
  publisher={Zenodo},
  doi={10.5281/zenodo.18722467},
  url={https://huggingface.co/datasets/samuelandaudreymedianetwork/project-23-argentina-travel-archive},
  note={License: CC BY-NC 4.0}
}
```
