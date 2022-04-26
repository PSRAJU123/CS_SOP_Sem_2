# CS_SOP_Sem_2

## Text Summarization For Code-Mixed Languages

Pretrained [BART](https://arxiv.org/abs/1910.13461) was used for fine-tuning on custom datasets.

The BART was fine tuned on [SamSum](https://huggingface.co/datasets/samsum) and [TweetSumm](https://github.com/guyfe/Tweetsumm) datasets for using the models with chat data.

Google Translate API was used for handling Code-Mixing In the Chats. After preprocessing of the Chats the Data is passed into trained models for final Text Summarization.

## Named Entity Recognition For Chats

For Named Entity Recognition Spacy and Flair pretrained models were used.
Flair Models are pretrained on [OntoNotes Dataset](https://paperswithcode.com/dataset/ontonotes-5-0).

Demo Videos for Each Colab File
1. 

