# 📘 Semantic Text Similarity Using SBERT  

## 📌 Project Overview  
This project explores semantic text similarity, clustering, and query-based retrieval using **Sentence-BERT (SBERT)**.  

The SNLI dataset was processed to generate sentence embeddings, compute similarity scores, perform clustering, and enable intelligent semantic search.

## 🎯 Objectives  
• Generate high-quality sentence embeddings using SBERT  
• Compute semantic similarity between sentence pairs  
• Perform clustering on sentence embeddings  
• Visualize high-dimensional embeddings  
• Implement query-based semantic retrieval  

## 📊 Dataset  
• SNLI (Stanford Natural Language Inference) dataset  
• Extracted premises, hypotheses, and labels  
• Removed missing values  
• Applied class balancing using resampling techniques  

## 🧠 Sentence Embedding Models  

• `all-MiniLM-L6-v2` – Efficient and lightweight sentence embeddings  
• `paraphrase-MiniLM-L6-v2` – Fine-tuned for paraphrase detection  
• `all-distilroberta-v1` – DistilRoBERTa-based embedding model  

## 📈 Semantic Similarity Analysis  
• Computed cosine similarity between premise-hypothesis pairs  
• Retrieved Top-N most similar sentences for a query  
• Compared embedding differences across models  

## 🔍 Clustering & Visualization  
• Applied K-Means clustering on sentence embeddings  
• Used PCA for dimensionality reduction  
• Visualized clusters to analyze semantic grouping  

## 🔎 Query-Based Retrieval  
• Implemented semantic search using query embeddings  
• Retrieved most relevant sentences from dataset  
• Ensured diversity by avoiding duplicate results  

## 🚀 Tech Stack  
• Python  
• Scikit-learn  
• Matplotlib, Seaborn  
• Hugging Face Datasets & Transformers  
• SentenceTransformers Library  
• XGBoost (for future classification extensions)  

## 📌 Conclusion  
This project demonstrates how SBERT embeddings can power semantic similarity analysis, clustering, and intelligent retrieval systems. It highlights the effectiveness of transformer-based embeddings for capturing contextual meaning in natural language tasks.
