# BERT Sentiment Analysis

Fine-tuning BERT for movie review sentiment classification as part of studying Transformer-based Language Models.

## What I did
- Loaded SST-2 dataset (Stanford Sentiment Treebank) from HuggingFace
- Fine-tuned `bert-base-uncased` on 100 movie reviews
- Achieved 100% accuracy on 20 validation samples

## Stack
- Python
- PyTorch
- HuggingFace Transformers
- HuggingFace Datasets

## Key concepts practiced
- BERT pre-trained model & fine-tuning
- [CLS] token for sentence classification
- DataLoader for batch processing
- `BertForSequenceClassification`

## Run
```bash
pip install -r requirements.txt
```
Then run `bert_sentiment.ipynb`