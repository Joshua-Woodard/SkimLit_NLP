# SkimLit_NLP
Jupyter Notebook for Milestone Project for Natural Language Processing to make reading medical abstracts easier to read.

## What it covers:
* Preprocessing Data
  * Make numeric labels, LabelEncode the labels
  * Create Text Vectorization and Embedding
  * Create datasets to load data faster
* Create series of models:
  * Baseline
  * Conv1D with token embeddings
  * Feature extraction with pretrained token embeddings
  * Conv1D with character embeddings
  * Combining pretrained token embeddings + character embeddings (Hybrid)
  * Combining previous model with positional embeddings (Tri-brid)
* Compare model results
* Save/Load best performing model
* Make predictions and evaluate on test set
* Find most wrong predictions
* Make example predictions
