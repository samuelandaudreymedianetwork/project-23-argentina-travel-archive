# Project 23 GitHub Split Files

These are binary split files created so each uploaded part is under GitHub's web-upload limit.

Important: each `.part1` / `.part2` file is NOT meant to be opened independently.
To restore the original `.gz` file, concatenate Part 1 and Part 2 in order.

## Files split

- `project-23-argentina-travel-archive.jsonl.gz.part1`
- `project-23-argentina-travel-archive.jsonl.gz.part2`

Recombine to:

- `project-23-argentina-travel-archive.jsonl.gz`

---

- `project-23-argentina-travel-archive.csv.gz.part1`
- `project-23-argentina-travel-archive.csv.gz.part2`

Recombine to:

- `project-23-argentina-travel-archive.csv.gz`

---

- `llms-project-23-argentina-travel-archive.txt.gz.part1`
- `llms-project-23-argentina-travel-archive.txt.gz.part2`

Recombine to:

- `llms-project-23-argentina-travel-archive.txt.gz`

## Recombine on Mac/Linux

```bash
cat project-23-argentina-travel-archive.jsonl.gz.part1 project-23-argentina-travel-archive.jsonl.gz.part2 > project-23-argentina-travel-archive.jsonl.gz

cat project-23-argentina-travel-archive.csv.gz.part1 project-23-argentina-travel-archive.csv.gz.part2 > project-23-argentina-travel-archive.csv.gz

cat llms-project-23-argentina-travel-archive.txt.gz.part1 llms-project-23-argentina-travel-archive.txt.gz.part2 > llms-project-23-argentina-travel-archive.txt.gz
```

## Suggested GitHub README note

Large compressed data files are split into `.part1` and `.part2` files for GitHub upload. The complete canonical files remain available on Hugging Face.

