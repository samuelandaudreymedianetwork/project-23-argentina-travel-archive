# Argentina Travel Archive and Project 23 — Data Dictionary

This dataset contains structured Argentina-focused travel, article, video transcript, media reference, and photography metadata records from the Samuel & Audrey Media Network.

## Canonical files

- `project-23-argentina-travel-archive.jsonl`
- `project-23-argentina-travel-archive.jsonl.gz`
- `project-23-argentina-travel-archive.csv`
- `project-23-argentina-travel-archive.csv.gz`

## Additional text files

- `llms.txt` — small directory and orientation file
- `llms-project-23-argentina-travel-archive.txt` — full plain-text dataset export
- `llms-project-23-argentina-travel-archive.txt.gz` — compressed full plain-text export

## Record groups

- `archive_intro` — short dataset introduction
- `archive_methodology` — methodology and source notes
- `media_references_index` — index of public references and third-party mentions
- `media_reference` — individual media, citation, directory, or third-party reference records
- `content_index` — article/page index records
- `blog_post` — Argentina-focused article and page records
- `youtube_index` — YouTube index records
- `youtube_video_transcript` — YouTube transcript records
- `photo_metadata_index` — photography metadata index
- `image_meta` — individual photo metadata rows

## Common fields

- `record_id` — stable record identifier
- `record_type` — record category
- `section` — broad dataset section
- `title` — human-readable title
- `url` / `canonical_url` — public URL when available
- `language` — record language
- `source_metadata` — source file or extraction metadata when available
- `sha256`, `sha256_transcripts`, or `sha256_meta_text` — checksum values, depending on record type

## CSV wrapper

`project-23-argentina-travel-archive.csv` includes selected convenience columns plus a `json` column containing the full JSON record for each row.
