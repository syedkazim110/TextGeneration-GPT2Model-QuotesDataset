# Text Generation with GPT-2 Fine-Tuning

This project demonstrates **fine-tuning GPT-2** on a custom dataset using the Hugging Face Transformers library.  
The goal was to adapt GPT-2 to a specific domain for improved text generation quality and contextual relevance.

---

##  Project Overview

- **Model**: GPT-2 (medium)
- **Framework**: TensorFlow / Hugging Face Transformers
- **Task**: Language Modeling (Next Token Prediction)
- **Dataset**: Custom domain-specific corpus
- **Training Objective**: Minimize cross-entropy loss for better generative performance

---

## 📊 Results

After fine-tuning, the model achieved:

| Metric        | Value     |
|---------------|-----------|
| **Loss**      | 3.1714    |
| **Perplexity**| 23.8414   |

 A **perplexity of ~23.84** means the model is significantly better at predicting the next token compared to the pre-trained baseline for this dataset.

---

## Text Generation Example 
**Prompt** : The purpose of life is
**Answer from FineTuned Model ** : The purpose of life is not to make things easy or beautiful, but rather how to find them. Life does this by giving up something that you already have; it's what makes people happy and interesting. People want more than anything else in the world -- happiness means knowing their fate can be better spent making good choices for themselves when they're wronged. Happiness doesn't mean loving a bad person because he wasnâ€™t right enough at the time (you know those horrible times where your heart was broken? That was one of my favorite moments ever! But I never loved anyone as much again until we'd kissed each other after all) It just meant being there with him every day...and then falling apart--to feel sorry about yourself completely without really wanting someone to do everything within reason if necessary on behalf myself.”

