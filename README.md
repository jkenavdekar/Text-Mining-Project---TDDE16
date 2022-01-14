# Text-Mining-Project---TDDE16
MCQ Question Generation system using Transfer learning and information extraction.

<img src="https://github.com/jkenavdekar/Text-Mining-Project---TDDE16/blob/main/QG%20block.png" width="400" height="200">

Transfer learning applied using T5, BART, BERT based Linformer.

Evaluation on SQuAD test dataset.

|    Models     |  Exact match  |  BLEU  |  ROUGE  |  F1  |  SPS  |  SBERT  |
| ----- | ------ | ----- | ----- | -----| ----- | ----- |
| BERT based Linformer  | 0.0 | 13.4 | 18.6 | 15.1 | 0.0 | 0.0 |
| small T5 base  | 2.5 | 43.8 | 39.6 | 40.4 | 61.5 | 74.2 |
| large T5 base  | 3.4 | 46.5 | 43.7 | 44.0 | 58.0 | 76.7 |
| mT5  | 0.1 | 25.3 | 13.4 | 16.9 | 44.7 | 46.3 |
| BART  | 0.0 | 29.4 | 21.3 | 24.0 | 39.5 | 55.9 |

