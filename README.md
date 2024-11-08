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
The Matcha repository is organized to facilitate access to textual data and annotations within domains of Blockchain Technology and Material Science.

- At the top level, the repository includes essential files such as **`README.md`** and **`sources.txt`**, which provide documentation and references for the project.

- Within the **`en`** directory, there is a subdirectory named **`block`** that contains annotated resources:
  - The **`annotated`** folder is subdivided into two main sections:
    - The **`annotations`** folder includes a subfolder named **`unique_annotation_lists`**, which contains **`block_en_terms.txt`**. This file lists the unique terms that have been manually extracted from the textual data, serving as a vital resource for understanding key concepts within the domain.
    - The **`texts`** folder contains multiple text files (e.g., **`block_en_01.txt`**, **`block_en_02.txt`**, and so on), each representing blocks of annotated text. These documents provide a rich source of information relevant to the project.

- Additionally, there is a **`material_sci`** folder, which serves as an equivalent section to the **`block`** directory, indicating that similar resources are available for the field of material science.

- Finally, the **`kaz`** directory mirrors the **`en`** structure, providing resources in Kazakh, ensuring that the project is accessible to a broader audience.

This organization allows users to efficiently navigate the repository and access both textual content and annotation resources, enhancing the overall usability and research capabilities of the Matcha project.

Finally, the kaz directory mirrors the en structure, providing resources in Kazakh, ensuring that the project is accessible to a broader audience
```
Matcha
├── README.md  
├── sources.txt  
│  
├── en  
│   └── block  
│      ├── annotated  
│      │   ├── annotations  
│      │   │   └── unique_annotation_lists  
│      │   │      └── block_en_terms.txt  
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


