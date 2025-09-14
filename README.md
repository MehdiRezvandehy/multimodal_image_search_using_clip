# multimodal_image_search_using_siglip

This notebook walks through building an **image search system** using **Google’s SigLIP model**, part of the **CLIP** (Contrastive Language–Image Pre-training) family. The process includes:

1. **Data Retrieval** – Collecting a set of candidate images.
2. **Model Setup** – Loading a pre-trained CLIP (no fine-tuning required).
3. **Embedding Generation** – Encoding both images and text queries into a shared representation space.
4. **Similarity Search** – Applying cosine similarity to match text queries against image embeddings.
5. **Result Exploration** – Retrieving and visualizing the most relevant images for each query.

<img width="784" height="378" alt="image" src="https://github.com/user-attachments/assets/4990848f-59b9-4e7d-8655-17d0bec31b2c" />
