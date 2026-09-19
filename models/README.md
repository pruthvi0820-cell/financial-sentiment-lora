# Models

This project uses the pretrained FinBERT model from Hugging Face:

`ProsusAI/finbert`

The model is used as the pretrained backbone for financial sentiment classification.

The FinBERT + LoRA model was fine-tuned using Parameter-Efficient Fine-Tuning (PEFT).

The trained model artifacts are not included directly in this repository to keep the repository lightweight. The model can be reproduced by running the notebook in `notebooks/financial_sentiment_lora.ipynb`.
