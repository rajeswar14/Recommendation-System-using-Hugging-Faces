# 🎥 Anime Recommendation System using Hugging Face Transformers 🎌  

## 📌 Overview  
This project is a **content-based anime recommendation system** that uses **Hugging Face Transformers** to generate sentence embeddings. It leverages **cosine similarity** to find relevant anime recommendations based on user queries.  

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Hugging Face Transformers** 🤗  
- **Sentence-Transformers**  
- **Scikit-learn**  
- **Pandas & NumPy**  
- **PyTorch**  

## 📂 Dataset  
- **name** – Anime title  
- **genre** – Anime genres  
- **type** – Movie, TV Series, etc.  
- **rating** – User rating  
- **episodes** – Number of episodes  

## 🚀 How It Works  
1. **Preprocessing**: Combines anime details into a single description.  
2. **Embedding Generation**: Uses `sentence-transformers/all-MiniLM-L6-v2` to generate embeddings.  
3. **Similarity Computation**: Finds similar anime using **cosine similarity**.  
  
## 📊 Results
- The system successfully recommends anime based on user preferences.
- Cosine similarity ensures accurate and relevant recommendations.
- The model captures semantic meanings of anime descriptions rather than just keyword matches.
 
