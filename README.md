# corpora

If you use these corpora for academic purposes and wish to specify the origin of the corpus, please cite Chinese Text Project as the source of the digitized texts and Mariana Zorkina https://uzh.academia.edu/MarianaZorkina as the creator of the tagged versions. If there are publications associated with the corpora, they will be listed below.

## Peiwenzhai yongwushi xuan 佩文齋詠物詩選:

Tagged according to TEI P5 standards.

The source of the digitised texts is:
Chinese Text Project, by Dr. Donald Sturgeon https://ctext.org
Please note, that the texts are licenced by Donald Sturgeon for personal and academic use only.

Related publication:

Mariana Zorkina; Describing Objects in Tang Dynasty Poetic Language: A Study Based on Word Embeddings. Journal of Chinese Literature and Culture 1 November 2018; 5 (2): 250–275. doi: https://doi.org/10.1215/23290048-7256989

## QTS 全唐詩
The original source of the digitized text is Chinese Text Project.
The file used as base is from this repository https://github.com/snowtraces/poetry-source/tree/master/%E5%85%A8%E5%94%90%E8%AF%97/CText_JSON_cht

Changes made:
- all files combined into one
- QTS_JSON_CTEXT_clean_punc_no_comm.json
  - Rare characters that were displayed in the original files with alphanumeric codes are replaced with characters
  - Punctuation is unified
  - All commentaries removed for analysis
  - There were many cases where "□" appears in a poem. When it was a result of a mistake, a character was inserted. However, there are still 280 cases where these indicate loss in text, often indicating whole blank lines. These were kept
  - There are ca. 1390 casese where author name is inserted after a line in a poem composed by a group of people. This might influence the analysis


