# Traffic Scene Retrieval and Analysis using ViLT + RAG

## Overview
This project implements a Retrieval-Augmented Generation (RAG) pipeline for traffic scene understanding using the BDD100K dataset and ViLT (Vision-and-Language Transformer).

## Dataset
This project uses the BDD100K dataset.

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

## Sample Outputs

### Output 1

![Output 1](output1.png)

### Output 2

![Output 2](output2.png)<img width="562" height="462" alt="output2" src="https://github.com/user-attachments/assets/ec7f14bc-5978-41c7-a8b6-5cb20abf955d" />
<img width="546" height="463" alt="output1" src="https://github.com/user-attachments/assets/c0b3c1f9-48e1-46a5-93c5-b49a0c4154fc" />
