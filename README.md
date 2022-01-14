# Text-Mining-Project---TDDE16
MCQ Question Generation system using Transfer learning and information extraction.

<img src="https://github.com/jkenavdekar/Text-Mining-Project---TDDE16/blob/main/QG%20block.png" width="400" height="200">

Transfer learning applied using T5, BART, BERT based Linformer.

Evaluation on SQuAD test dataset.

|    Models     |  Exact match  |  BLEU  |  ROUGE  |  F1  |  SPS  |  SBERT  |
| ------------- | ------------- |  ----- | -------|| -----| ----- |  -----  |
| BERT based Linformer  | - | 13 | 19 | 15 | - | - |
| small T5 base  | 2.5 | 44 | 40 | 40 | 62 | 74 |
| large T5 base  | 3.4 | 46 | 44 | 44 | 58 | 77 |
| mT5  | 0.1 | 25 | 13 | 17 | 45 | 46 |
| BART  | 0.0 | 29 | 21 | 24 | 39 | 55 |
