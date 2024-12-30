# Fine-Tuning DistilBERT for Medical NER

This project explores the effectiveness of fine-tuning DistilBERT on medical domain data for two tasks:

1. **Masked Language Modeling (MLM)**: Fine-tune DistilBERT on medical domain data to create a domain-adapted language model.
2. **Named Entity Recognition (NER)**: Use the fine-tuned model from step 1 for NER on a custom medical dataset.

The results will be compared against the performance of a BERT model fine-tuned directly for the NER task, as outlined in this [article](https://medium.com/ai-advances/how-to-fine-tune-bert-model-for-ner-on-a-custom-dataset-946406e355d9).

## Steps

1. Pre-train DistilBERT on masked language modeling using a medical text corpus.
2. Fine-tune the pre-trained model for NER using a labeled medical dataset.
3. Evaluate the NER performance and compare it with BERT's NER results from the reference article.

## Goal

The objective is to assess whether domain-specific pre-training on medical data enhances NER performance and to quantify the efficiency and effectiveness of DistilBERT compared to BERT for NER tasks in the medical domain.

## Progress
- MLM:  Dataset preparation and tokenization: DONE
- Debug the MLM training: WIP


## References

- [How to Fine-Tune BERT Model for NER on a Custom Dataset](https://medium.com/ai-advances/how-to-fine-tune-bert-model-for-ner-on-a-custom-dataset-946406e355d9)

