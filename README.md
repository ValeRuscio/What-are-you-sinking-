This repository contains the code implementation for our paper "What are you sinking? A geometric approach on attention sink" submitted to NeurIPS 2025. We analyze transformer attention mechanisms through multiple geometric and information-theoretic lenses to understand the formation and structure of reference frames.
 

## Overview

Transformer attention mechanisms develop reference frames that organize the geometric structure of representations. This research investigates these structures through complementary analyses spanning topology, spectral graph theory, and information geometry. We examine both decoder-only models (LLaMA-3.2/3.1, Phi-2, Qwen-2.5, Mistral, Gemma, Pythia) and encoder-only models (BERT, XLM-RoBERTa).


## Notebooks

Our analysis is implemented across eight Jupyter notebooks:

topology.ipynb: Implements persistent homology and Betti number analysis to quantify the topological structure of attention networks. Calculates connected components (Betti₀) and cycles (Betti₁) using the Ripser algorithm.

RMT.ipynb: Uses Random Matrix Theory to analyze how attention structures evolve during training, tracking spectral gap, participation ratio, and KL divergence from Marchenko-Pastur distribution across Pythia model checkpoints.

Laplacian.ipynb: Analyzes attention graphs' Laplacian matrices (L = D - A) to assess connectivity patterns, computing metrics across multiple thresholds (0.001-0.2).

Fiedler.ipynb: Focuses on algebraic connectivity (Fiedler value) to quantify graph connectedness and measure proximity to ideal star topologies.

KL.ipynb: Quantifies information-geometric properties of attention distributions, measuring KL divergence reduction when attention sinks are removed.

Fisher.ipynb: Computes the Fisher information matrix to provide a Riemannian metric on probability distributions, calculating layer-wise Fisher norms to quantify information content.

attention_value.ipynb: Examines relationships between attention and geometric transformations through attention entropy, transformation magnitude, and their correlation.

reference_point.ipynb: Measures the influence of reference tokens through relative magnitude, directional guidance, and structural importance via KL divergence.


## Data and Hardware

Our analysis uses a dataset of STEM-focused Wikipedia sentences (mathematics, chemistry, medicine, physics) ranging from 6 to 50 tokens, that is provided in "Data". We processed 500 samples for topology, spectral and Fisher information analysis, 50 samples for KL divergence analysis, and 100 samples for the temporal RMT analysis.
All experiments were conducted using Google Colab with T4 or A100 GPUs. Some notebooks may take several hours to run, especially for larger models.


## How to Use

Each notebook is self-contained and can be run independently in a Colab environment. The notebooks save results to Google Drive, so you may need to modify output paths to match your directory structure.


## Sample Results

Each notebook generates visualizations and statistical reports saved to the specified output directory. Sample outputs are provided in the results/ folder for reference.


## License

This project is licensed under the MIT License - see the LICENSE file for details.
