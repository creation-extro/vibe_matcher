
# 🎵 Vibe Matcher – AI-Powered Fashion Recommendation System

**By:** Tejaswi Mane  
**Repository:** creation-extro/vibe_matcher  

## 🧠 Overview
This project builds a mini recommendation system that matches a user’s **vibe query** (e.g., "urban chic", "relaxed beach look") to the most relevant fashion products using **semantic embeddings and cosine similarity**.

Developed as part of the **AI @ Nexora internship challenge**, the system demonstrates how vector embeddings can power personalized style discovery.

## 🧩 Features
- Generates embeddings using **Hugging Face Sentence Transformers**
- Computes similarity between vibe queries and fashion product descriptions
- Returns top-3 matching products with similarity scores
- Includes latency and visualization analysis
- Handles edge cases (e.g., irrelevant queries)

## 📊 Results
Average Latency: **41.55 ms**  
Example Query Results:
- **Relaxed beach look → Casual Beach Shorts (0.64)**  
- **Sophisticated formal elegance → Elegant Evening Gown (0.64)**  

Edge case "medieval knight armor" → No matches (✅ threshold control).

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy, Matplotlib  
- Scikit-learn (cosine similarity)  
- SentenceTransformers (for embeddings)

## 🚀 Future Enhancements
- Integration with **Pinecone / FAISS** for scalable vector search  
- Streamlit UI for interactive vibe querying  
- Fine-tuned embeddings on fashion datasets  
- Personalized recommendations from user data  

## 📚 Author
**Tejaswi Mane**  
B.Sc. Data Science & AI | Mumbai  
GitHub: [creation-extro](https://github.com/creation-extro)  
LinkedIn: [Your LinkedIn link here]
