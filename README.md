# N-Gram-LM
This project implements statistical N-gram language models from scratch to model and generate natural language text using probabilistic methods. It demonstrates a foundational approach to language modeling prior to neural architectures, emphasizing mathematical rigor, algorithmic clarity, and efficient implementation.

### Overview

The notebook builds and evaluates:

Unigram, Bigram, and Trigram models

Maximum Likelihood Estimation (MLE) for probability computation

Text generation using conditional probability distributions

Perplexity evaluation for model performance comparison

Handling of unseen tokens and vocabulary management

The goal of this project is to deeply understand how probabilistic language models work under the hood without relying on high-level NLP libraries.

### Technical Highlights

Manual tokenization and vocabulary construction

Frequency table construction using efficient data structures

Conditional probability computation:

𝑃
(
𝑤
𝑛
∣
𝑤
𝑛
−
1
,
.
.
.
,
𝑤
𝑛
−
(
𝑘
−
1
)
)
P(w
n
	
∣w
n−1
	​,...,w
n−(k−1)
	​

)

Log-probability calculations for numerical stability

Perplexity as an intrinsic evaluation metric

Comparative analysis across different N values

This implementation prioritizes transparency over abstraction to reinforce core NLP and probabilistic modeling concepts.

### Why This Project Matters

Before transformers and large language models, N-gram models were the backbone of:

Speech recognition systems

Machine translation

Autocomplete engines

Early search ranking systems

Understanding these models builds intuition for:

Probability theory in NLP

Markov assumptions

Model bias vs variance tradeoffs

Data sparsity challenges

Smoothing strategies (extendable)

Skills Demonstrated

Applied Probability & Statistics

Natural Language Processing Fundamentals

Algorithm Design

Computational Efficiency

Model Evaluation Metrics

Clean, reproducible notebook workflows

### Future Improvements

Add Laplace / Good-Turing smoothing

Implement backoff and interpolation methods

Compare performance against neural language models

Scale to larger corpora

Benchmark computational complexity
