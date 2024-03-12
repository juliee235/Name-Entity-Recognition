# Name-Entity-Recognition for Thai word
This project aimed to recognize Name Entity of thai word Using train set and Validation set in [lst20_Compus](https://aiforthai.in.th/corpus.php)\
Code : NER_Thai_word.ipynb

## Dataset
Lst20 Compus : The LST20 Corpus is a language dataset for Thai language processing developed by the National Electronics and Computer Technology Center (NECTEC). This dataset is annotated with language information at 5 levels, including word boundaries, part of speech, named entities, clause boundaries, and sentence boundaries. The dataset comprises 3,164,002 words, 288,020 named entities, 248,181 sub-sentences, and 74,180 sentences. The total number of word types is only 16 tags.
![ภาพ](https://github.com/juliee235/Name-Entity-Recognition/assets/138569824/9cbeff52-b037-4ce7-a8ae-e9a9bbe069b2)

 ## Model Training
XLM-RoBERTa is a multilingual version of RoBERTa. It is pre-trained on 2.5TB of filtered CommonCrawl data containing 100 languages.\

RoBERTa is a transformers model pretrained on a large corpus in a self-supervised fashion. This means it was pretrained on the raw texts only, with no humans labelling them in any way (which is why it can use lots of publicly available data) with an automatic process to generate inputs and labels from those texts.
![ภาพ](https://github.com/juliee235/Name-Entity-Recognition/assets/138569824/1db2ba18-84f4-4776-927a-b1e95d70e19f)
### Parameter setting
1. Learning rate = 1e-4
2. batch size = 128
3. epoch = 4

## results
Summission via Kaggle : F1 marco on test set = 0.38 (Highest 0.45)


