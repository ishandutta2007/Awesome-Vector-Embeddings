# Awesome-Vector-Embeddings
## Types of Vector Embeddings in AI

Vector embeddings convert high-dimensional, unstructured data (like text, images, or audio) into low-dimensional, dense numerical vectors. This process captures semantic meaning, relationships, and context, enabling machines to perform fast similarity searches and machine learning tasks.

## 1. Text Embeddings

* **[Word Embeddings](word_embeddings.md):** Map individual words into a vector space where words with similar meanings are close together.
  * *Static:* Words have a fixed vector regardless of context (e.g., Word2Vec, GloVe, FastText).
  * *Contextual:* Vector representations change dynamically depending on surrounding words (e.g., BERT, RoBERTa).
* **[Sentence & Paragraph Embeddings](sentence_paragraph_embeddings.md):** Encode entire phrases or short texts into a single dense vector to capture semantic intent (e.g., Sentence-BERT).
* **[Document Embeddings](document_embeddings.md):** Vectorize long-form documents or entire articles to enable document classification and cluster analysis (e.g., Doc2Vec).

## 2. Multi-Modal & Vision Embeddings

* **[Image Embeddings](image_embeddings.md):** Extract deep visual features from images using Convolutional Neural Networks (CNNs) or Vision Transformers (ViTs), capturing textures, shapes, and semantic objects.
* **[Cross-Modal Embeddings](cross_modal_embeddings.md):** Map multiple modalities (like text and images) into a single, shared vector space. This allows an image and its textual description to sit close together (e.g., OpenAI's CLIP).
* **[Video Embeddings](video_embeddings.md):** Capture both spatial imagery from frames and temporal movement across time, which powers automated video tagging and video search engines.

## 3. Structured Data & Graph Embeddings

* **[Graph Embeddings](graph_embeddings.md):** Convert nodes, edges, or entire network substructures into vectors. This preserves the structural topology of the graph and powers modern recommendation engines (e.g., Node2Vec, GraphSAGE).
* **[Categorical Embeddings](categorical_embeddings.md):** Map discrete relational database columns (such as User IDs, Zip Codes, or Product SKUs) into continuous vector spaces to enhance deep tabular model predictions.

## 4. Specialized Sequence Embeddings

* **[Audio & Speech Embeddings](audio_speech_embeddings.md):** Translate raw acoustic waves or spectrogram patterns into numeric vectors, forming the backbone of voice recognition and sound classification (e.g., Wav2Vec).
* **[Code Embeddings](code_embeddings.md):** Vectorize human-written source code to enable developer tools like automated code generation, vulnerability detection, and semantic code search (e.g., CodeBERT).
* **[Biological / Chemical Embeddings](biological_chemical_embeddings.md):** Map amino acid chains, DNA sequences, or molecular graphs (SMILES) into vectors to predict molecular properties and accelerate automated drug discovery.


## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Vector-Embeddings&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Embeddings&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Embeddings&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Embeddings&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>
