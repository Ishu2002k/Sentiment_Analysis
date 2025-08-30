# 📝 Gender Stereotype Detection in Text  

A deep learning project focused on identifying **gender stereotypes in textual data** using a combination of **classical ML models, transformers, and fine-tuned LLMs**.  

---

## 📌 Project Overview  

Gender stereotypes are often embedded in text and can reinforce societal biases. This project explores multiple **machine learning** and **deep learning** approaches to detect such stereotypes in text data, with a focus on **generalization, interpretability, and high accuracy**.  

---

## 🚀 Features  
- Curated and synthesized a dataset of **8,000 IMDb reviews** + targeted stereotype samples.  
- Applied **Random Forest, XGBoost, SVM** as baseline classifiers.  
- Integrated **FLAN-T5 and LLAMA** for advanced NLP classification.  
- Performed **zero-shot and 2-shot prompting** to analyze results.  
- Fine-tuned **LLAMA model with QLoRA adapters**.  
- Achieved **91% accuracy** with **5-fold cross-validation**.  

---

## 🏗️ Architecture  

1. **Data Preparation**  
   - IMDb + stereotype text samples  
   - Preprocessing: tokenization, cleaning, embeddings  

2. **Modeling Approaches**  
   - Baseline ML Models: Random Forest, XGBoost, SVM  
   - Transformer Models: FLAN-T5, LLAMA (zero-shot & few-shot)  
   - Fine-tuning: LLAMA with **QLoRA adapters**  

3. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Cross-validation (5-fold)  

---

## 📊 Results  

| Model            | Accuracy |
|------------------|----------|
| Random Forest    | 0.81     |
| XGBoost          | 0.84     |
| FLAN-T5          | 0.86     |
| LLAMA (few-shot) | 0.86     |
| LLAMA + QLoRA    | **0.91** |

---

## 🛠️ Tech Stack  

- **Languages:** Python  
- **Libraries:** PyTorch, Transformers (Hugging Face), Scikit-learn  
- **Models:** Random Forest, XGBoost, FLAN-T5, LLAMA  
- **Tools:** Jupyter, Colab, QLoRA adapters  

---
