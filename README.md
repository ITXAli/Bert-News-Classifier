# 📰 BERT AG News Classifier

This model is a fine-tuned version of `bert-base-uncased` on the AG News dataset using Hugging Face Transformers. It classifies English news articles into four categories:

- **World**
- **Sports**
- **Business**
- **Sci/Tech**

## 🧠 Training Details

- **Base model**: BERT (bert-base-uncased)
- **Dataset**: AG News (120,000 training samples, 7,600 test samples)
- **Accuracy**: ~94%
- **Training time**: ~45 minutes on T4 x2 GPU
- **Max sequence length**: 128
- **Batch size**: 32
- **Epochs**: 2
- **Framework**: PyTorch with Hugging Face `Trainer`

## 🔧 Intended Use

This model is intended for text classification of short news snippets or headlines. It can be used in educational, prototyping, or research settings.

## 🧾 Limitations

- English-only
- May misclassify ambiguous or sarcastic headlines
- Not suitable for real-time production without further evaluation

## 📎 Citation

If you use this model in your work, please cite the original AG News dataset and BERT paper.

---
