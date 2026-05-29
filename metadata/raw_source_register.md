# Raw Source Register

Status: schema created; population pending
Date: 2026-05-28

This register controls every source file in the Women Made Central Asia Corpus.

## Schema

| Field | Meaning |
|---|---|
| `source_id` | stable ID, e.g. `WMCA-SRC-000001` |
| `file_name` | original file name |
| `actual_title` | verified title after opening the file |
| `author_editor` | author/editor/institution |
| `year` | publication year or unknown |
| `language` | main language(s) |
| `source_type` | book, article, thesis, archive item, image, scan, DOCX, PDF, pointer, etc. |
| `region` | Central Asia, Uzbekistan, Bukhara, Samarkand, Fergana, etc. |
| `topic_layer` | women, continuity, textile, oral tradition, shrine keeping, dynastic history, education, art, science, etc. |
| `rights_status` | project_owned / open_license / public_domain / third_party / unknown / private / restricted |
| `public_upload_decision` | public_raw / metadata_only / private_raw / link_only / rights_review_needed / exclude |
| `reading_status` | not_opened / metadata_only / opened_first_pages / skimmed_structurally / read_key_sections / full_text_read / OCR_or_visual_pass_needed / blocked_or_not_fulltext |
| `text_extraction_status` | not_started / extracted / OCR_needed / blocked / not_text |
| `quality_status` | unchecked / partial_check / verified / contaminated / duplicate |
| `corpus_action` | next exact action |

## Register

| source_id | file_name | actual_title | author_editor | year | language | source_type | region | topic_layer | rights_status | public_upload_decision | reading_status | text_extraction_status | quality_status | corpus_action |
|---|---|---|---|---:|---|---|---|---|---|---|---|---|---|---|
| WMCA-SRC-000001 | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | unknown | rights_review_needed | not_opened | not_started | unchecked | replace with real uploaded source row |
