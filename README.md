# Book Recommendation System

A scalable book recommendation system built using **collaborative filtering** and **content-based filtering**, capable of handling large datasets and providing personalized book suggestions.

## Features

- **Scalable Recommendation System**: Handles **6 million ratings** and **10,000 books** efficiently.  
- **NLP & Embeddings**: Generates book embeddings using **Sentence-BERT (SBERT)** for content-based recommendations.  
- **Collaborative Filtering**: Implements **Surprise SVD** for rating predictions.  
- **Ranking & Similarity Search**: Uses **FAISS** for fast nearest-neighbor search in content-based filtering.  
- **Optimized Performance**: Leverages **NumPy** and vectorized operations for high-performance computations.  
- **Data Analysis & Insights**: Explores trends and patterns in user ratings to enhance recommendation quality.  

![Recsys workflow](rec_image/rec_img.png)

## Performance

### Content-Based Filtering (Ranking Task)
- Framed as a **ranking problem** using FAISS  
- **Recall@K**: 0.90  

### Collaborative Filtering (Rating Prediction)
- Framed as a **rating prediction problem** using cosine similarity and Surprise SVD  
- **RMSE**: 0.79  
- **MAE**: 0.61  

### Collaborative Filtering (Ranking with Sparse Matrices)
- **Recall@K**: 0.02  
- **Precision@K**: 0.01  
- **Baseline Metrics**:  
  - Baseline Recall@K: 0.001  
  - Baseline Precision@K: 0.0005  

## Technologies Used

- **Python**  
- **FAISS** – Efficient similarity search and clustering  
- **NumPy** – Optimized numerical operations  
- **Sentence Transformers (SBERT)** – NLP embeddings  
- **Surprise** – Collaborative filtering and rating prediction  

## Project Highlights

- Optimized code for large-scale datasets with vectorized operations  
- Successfully combined **content-based** and **collaborative filtering** approaches  
- Achieved performance metrics exceeding baseline models  

## Author

**Misty Roy**  
Email: your.email@example.com  
GitHub: [https://github.com/your-github-profile](https://github.com/your-github-profile)
