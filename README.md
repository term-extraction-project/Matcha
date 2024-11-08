# Matcha
## 1. General
Matcha is a manually annotated dataset for term extraction, covering 2 languages (English and Kazakh), and 2 domains (Blockchain and Material Science).


## 2. Abbreviations
**Languages:**
* "en" = English
* "kaz" = Kazakh
  
**Domains:**
* "block" = Blockchain
* "material_sci" = Material Science

## 3. Data Structure
The repository of each domain has folders “texts” and “annotations”. The “texts” folder contains documents containing textual information about the blockchain. The “annotations” folder contains a list of manually extracted unique terms.


```
Matcha
├── README.md  
├── sources.txt  
│  
├── en  
│   ├── block  
│      ├── annotated  
│      │   ├── annotations  
│      │   │   ├── unique_annotation_lists  
│      │   │   │   └── block_en_terms.txt  
│      │   │  
│      │   └── texts  
│      │       ├── block_en_01.txt  
│      │       ├── block_en_02.txt  
│      │       ├── ...  
│      │       └── block_en_06.txt  
│      │  
│      └── material_sci (equivalent to "block")  
│    
│   
│  
└── kaz (equivalent to "en")  
```


## 4. Annotations 
In the blockchain domain, there are 6 documents with 668 total extracted terms for English and 6 documents with 511 total extracted terms for Kazakh. In the materials science domain there are 7 documents with 375 terms extracted for the English language.
| Language | Domain            | Documents | Terms | Words | Characters |
|----------|--------------------|-----------|-------|-------|------------|
| english  | Blockchain        | 6         | 668   | 18478 | 115774     |
| english  | Material Science  | 7         | 375   | 11569 | 81447      |
| kazakh   | Blockchain        | 6         | 511   | 14368 | 119515     |
| kazakh   | Material Science  | 7         |       | 9005  | 81758      |


