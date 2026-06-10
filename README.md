# Awesome-Vector-Embeddings
## Types of Vector Embeddings in AI

Vector embeddings convert high-dimensional, unstructured data (like text, images, or audio) into low-dimensional, dense numerical vectors. This process captures semantic meaning, relationships, and context, enabling machines to perform fast similarity searches and machine learning tasks.

## 1. Text Embeddings

* **Word Embeddings:** Map individual words into a vector space where words with similar meanings are close together.
  * *Static:* Words have a fixed vector regardless of context (e.g., Word2Vec, GloVe, FastText).
  * *Contextual:* Vector representations change dynamically depending on surrounding words (e.g., BERT, RoBERTa).
* **Sentence & Paragraph Embeddings:** Encode entire phrases or short texts into a single dense vector to capture semantic intent (e.g., Sentence-BERT).
* **Document Embeddings:** Vectorize long-form documents or entire articles to enable document classification and cluster analysis (e.g., Doc2Vec).

## 2. Multi-Modal & Vision Embeddings

* **Image Embeddings:** Extract deep visual features from images using Convolutional Neural Networks (CNNs) or Vision Transformers (ViTs), capturing textures, shapes, and semantic objects.
* **Cross-Modal Embeddings:** Map multiple modalities (like text and images) into a single, shared vector space. This allows an image and its textual description to sit close together (e.g., OpenAI's CLIP).
* **Video Embeddings:** Capture both spatial imagery from frames and temporal movement across time, which powers automated video tagging and video search engines.

## 3. Structured Data & Graph Embeddings

* **Graph Embeddings:** Convert nodes, edges, or entire network substructures into vectors. This preserves the structural topology of the graph and powers modern recommendation engines (e.g., Node2Vec, GraphSAGE).
* **Categorical Embeddings:** Map discrete relational database columns (such as User IDs, Zip Codes, or Product SKUs) into continuous vector spaces to enhance deep tabular model predictions.

## 4. Specialized Sequence Embeddings

* **Audio & Speech Embeddings:** Translate raw acoustic waves or spectrogram patterns into numeric vectors, forming the backbone of voice recognition and sound classification (e.g., Wav2Vec).
* **Code Embeddings:** Vectorize human-written source code to enable developer tools like automated code generation, vulnerability detection, and semantic code search (e.g., CodeBERT).
* **Biological / Chemical Embeddings:** Map amino acid chains, DNA sequences, or molecular graphs (SMILES) into vectors to predict molecular properties and accelerate automated drug discovery.
