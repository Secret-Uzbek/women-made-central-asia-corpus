# Reading Status Register

Status: schema created; population pending
Date: 2026-05-28

This register prevents vague claims such as “read”, “processed”, or “integrated”. Every source must have an explicit reading status.

## Allowed reading statuses

| Status | Meaning |
|---|---|
| `not_opened` | file exists but has not been opened |
| `metadata_only` | only title, filename, citation, or source-card metadata was inspected |
| `opened_first_pages` | opening pages were inspected for title, author, publication data |
| `skimmed_structurally` | table of contents, headings, and document structure were inspected |
| `read_key_sections` | relevant sections were read and cited in notes |
| `full_text_read` | full text was read from beginning to end |
| `OCR_or_visual_pass_needed` | text extraction is insufficient and OCR/visual pass is required |
| `blocked_or_not_fulltext` | file is not a usable full text, e.g. login page, pointer file, blocked download |

## Schema

| Field | Meaning |
|---|---|
| `source_id` | source ID from raw source register |
| `file_name` | original file name |
| `reading_status` | one allowed reading status |
| `evidence` | what was actually inspected |
| `notes` | short explanation |
| `next_reading_action` | exact next action |

## Register

| source_id | file_name | reading_status | evidence | notes | next_reading_action |
|---|---|---|---|---|---|
| WMCA-SRC-000001 | TBD | not_opened | none | placeholder row | replace with real uploaded source rows |
