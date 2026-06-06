<img width="546" height="463" alt="output1" src="https://github.com/user-attachments/assets/2b21b4f5-1c3b-4327-aacc-97bd4a53fcf3" />
# Traffic Scene Retrieval and Analysis using ViLT + RAG

## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline for traffic scene understanding using the BDD100K dataset and ViLT (Vision-and-Language Transformer).

## Dataset

- Dataset: BDD100K
- Images Processed: 500+
- Embedding Size: 768
- Retrieval Method: Cosine Similarity
- Model: ViLT (Vision-and-Language Transformer)

## Features
- ViLT-based image embeddings
- Similar scene retrieval using cosine similarity
- Traffic scene analysis
- Dynamic scene description generation
- BDD100K dataset integration

## Tech Stack
- Python
- ViLT
- PyTorch
- Transformers
- Scikit-Learn
- Matplotlib
- BDD100K

## Workflow
1. Load BDD100K images and labels
2. Extract ViLT embeddings
3. Build retrieval database
4. Retrieve similar scenes
5. Generate contextual scene descriptions

## Results
The system retrieves visually similar traffic scenes and generates descriptions based on detected objects and traffic conditions.

## Sample Output

<p align="center">
  <img src="sample_output.png" width="850">
</p>

<p align="center">
  <em>Traffic Scene Retrieval and Analysis using ViLT + RAG</em>
</p>
