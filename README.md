# Multimedia_documents_indexing_and_retrieval

## Overview
This repository contains two major projects focused on **Content-Based Image Retrieval (CBIR)** and the development of a **Document Retrieval System** with indexing and classification. These projects showcase techniques for multimedia document indexing and retrieval, allowing users to interactively search for images and textual data based on their content.

## Projects

### 1. **Content-Based Image Retrieval (CBIR)**
   This project demonstrates how to implement a Content-Based Image Retrieval system, which allows users to search for images based on visual content rather than metadata. By extracting and comparing image features, the system retrieves images similar to a query image.

   **Key Features:**
   - Feature extraction using color histograms, texture, and shape descriptors
   - Distance metrics (e.g., Euclidean distance, Cosine similarity) to compare images
   - Searching for similar images based on the visual features of the query image

   **Dataset Used:**
   - [COIL-100](https://www.cs.columbia.edu/CAVE/software/softlib/coil-100.php): A dataset containing images of 100 objects captured from different angles.

   **Techniques Used:**
   - Feature extraction (Color, Texture, Shape)
   - Similarity measurements (Euclidean, Cosine)
   - Retrieval based on visual similarity

### 2. **Document Retrieval System with Indexing and Classification**
   This project focuses on creating a document retrieval system that indexes textual documents and classifies them based on their content. The system supports searching through a collection of documents using indexing methods (e.g., TF-IDF) and classification techniques.

   **Key Features:**
   - Indexing of documents using Term Frequency-Inverse Document Frequency (TF-IDF)
   - Document classification using machine learning techniques (e.g., Naive Bayes, SVM)
   - Query-based document retrieval with ranking of relevant results

   **Datasets Used:**
   - [Europarl](http://www.statmt.org/europarl/): A parallel corpus containing the proceedings of the European Parliament, used for multilingual document retrieval.
   - [Tobacco Examples](https://tobaccodocuments.org/): A dataset containing tobacco industry documents, used for exploring text indexing and classification.

   **Techniques Used:**
   - Text indexing (TF-IDF)
   - Text classification (Naive Bayes, Support Vector Machines)
   - Search and retrieval with ranked results

## How to Use

### 1. **Setup**
Clone the repository:
```bash
git clone https://github.com/FrereAlidor/Multimedia_Indexing_Retrieval.git
