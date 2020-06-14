# RuBERT-sense-disambiguation
Contextualized word embeddings (by fine-tuned RuBERT) for word sense disambiguation in Russian language.

This work is based on  competition RUSSE 2018 Word Sense Induction and Disambiguation Shared Task.

I introduce a method for word-sense disambiguating based on finetuning BERT's contextualized word embeddings on pairs of texts with same and different senses with a cosine triplet loss.

Requirements:
  - python==3.7.6
  - transformers==2.4.1
  - torch==1.3.1
