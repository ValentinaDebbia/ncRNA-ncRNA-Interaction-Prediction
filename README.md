# ncRNA–ncRNA Interaction Prediction with RNA‑FM Embeddings
This repository contains the full implementation of a deep learning framework for predicting interactions between non‑coding RNAs (ncRNAs), developed for the Bioinformatics exam (A.Y. 2025/2026, University of Milan).
# Overview
Understanding ncRNA–ncRNA interactions is essential for characterizing post‑transcriptional regulation and RNA‑based cellular networks. Experimental mapping remains limited, motivating computational approaches capable of generalizing beyond handcrafted thermodynamic models.
This project leverages RNA‑FM, a transformer‑based RNA foundation model trained on >23M sequences, to extract contextual embeddings directly from raw nucleotide sequences. These embeddings are aggregated and used as input to a deep feed‑forward neural network trained to classify interacting versus non‑interacting RNA pairs.
