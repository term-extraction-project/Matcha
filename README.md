# Matcha

## 1. General

Matcha is a manually annotated dataset for term extraction, covering 2 languages (English and Kazakh), and 2 domains (Blockchain and Material Science).

## 2. Abbreviations
**Languages and domains:**
* "en" = English
* "kaz" = Kazakh
* "block" = Blockchain
* "material_sci" = Material Science

## 3. Structure
The repository of each domain has folders “texts” and “unique_annotation_lists”. The “texts” folder contains documents containing textual information about the blockchain. The “unique_annotation_lists” folder contains a list of manually extracted unique terms.

Matcha
├── en
│   ├── block
│   │   ├── annotated
│   │   │   ├── texts
│   │   │   │   ├── text_en_block01.txt
│   │   │   ├── annotations
│   │   │   │   ├── block_en_terms.txt
│   ├── material_sci
│   │   ├── annotated
│   │   │   ├── texts
│   │   │   │   ├── text_en_material01.txt
│   │   │   ├── annotations
│   │   │   │   ├── material_en_terms.txt
├── kaz
│   ├── block
│   │   ├── annotated
│   │   │   ├── texts
│   │   │   │   ├── text_kaz_block01.txt
│   │   │   ├── annotations
│   │   │   │   ├── block_kaz_terms.txt
│   ├── material_sci
│   │   ├── annotated
│   │   │   ├── texts
│   │   │   │   ├── text_kaz_material01.txt
│   │   │   ├── annotations
│   │   │   │   ├── material_kaz_terms.txt



## 4. Number of documents and term
In the blockchain domain, there are 6 documents with 668 total extracted terms for English and 6 documents with 511 total extracted terms for Kazakh. In the materials science domain there are 7 documents with 375 terms extracted for the English language.
| Language | Domain            | Documents | Terms | Words | Characters |
|----------|--------------------|-----------|-------|-------|------------|
| english  | Blockchain        | 6         | 668   | 18478 | 115774     |
| english  | Material Science  | 7         | 375   | 11569 | 81447      |
| kazakh   | Blockchain        | 6         | 511   | 14368 | 119515     |
| kazakh   | Material Science  | 7         |       | 9005  | 81758      |


