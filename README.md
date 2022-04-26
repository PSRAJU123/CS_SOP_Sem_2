# CS_SOP_Sem_2

## Text Summarization For Code-Mixed Languages

Pretrained [BART](https://arxiv.org/abs/1910.13461) was used for fine-tuning on custom datasets.

The BART was fine tuned on [SamSum](https://huggingface.co/datasets/samsum) and [TweetSumm](https://github.com/guyfe/Tweetsumm) datasets for using the models with chat data.

Google Translate API was used for handling Code-Mixing In the Chats. After preprocessing of the Chats the Data is passed into trained models for final Text Summarization.

## Named Entity Recognition For Chats

For Named Entity Recognition Spacy and Flair pretrained models were used.
Flair Models are pretrained on [OntoNotes Dataset](https://paperswithcode.com/dataset/ontonotes-5-0).

Demo Videos for Each Colab File
1. Text Summarization With BART
https://user-images.githubusercontent.com/44365490/165237615-7f498181-6214-467d-be30-f0d480dc472d.mp4

2. Named Entity Recognition on Chats

https://user-images.githubusercontent.com/44365490/165237694-320dd50c-ccf8-47dc-86c3-434285f36963.mp4

3. Preprocessing Chats to handle Code-Mixing

https://user-images.githubusercontent.com/44365490/165237949-3a406872-c20c-4bff-9c62-c8298857cc8f.mp4

https://user-images.githubusercontent.com/44365490/165237988-3b3fb91e-27d7-4ef2-8fd3-06be61561e14.mp4

4. FineTuning BART on TweetSumm

https://user-images.githubusercontent.com/44365490/165238039-1f8790b2-4605-49d9-a5d6-ad05adca80be.mp4

5. Testing Fine-Tuned Models on Chat-Data

https://user-images.githubusercontent.com/44365490/165238496-599458c3-1476-407c-b713-7c0799c50351.mp4





