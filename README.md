# Classification-of-Figurative-and-Literal-Usage-in-Hebrew
Automatic Classification of Figurative and Literal Usage in Hebrew Idioms

Figurative vs. Literal Idiom Classification in Hebrew
This project explores the ability of pre-trained Transformer models to distinguish between literal and figurative usages of idiomatic expressions in Hebrew—a morphologically rich, low-resource language. Idioms pose a significant challenge for NLP systems due to their context-dependent meaning, especially in tasks like sentiment analysis, machine translation, and dialogue understanding.

We construct a balanced Hebrew dataset of idioms annotated for literal vs. figurative usage, and evaluate both multilingual and Hebrew-specific models. The study compares fine-tuning and frozen feature extraction approaches, with performance assessed through quantitative metrics (accuracy, F1), confusion matrices, attention visualizations, and interpretability tools.

Key Features
Balanced dataset of Hebrew idioms with figurative/literal labels

Evaluation of multiple Transformer architectures (e.g., XLM-R, AlephBERT)

Comparison of fine-tuning vs. frozen embeddings

Visualization of attention and model interpretability insights
