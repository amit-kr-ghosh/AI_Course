# AI / ML MASTERCLASS — MASTER COURSE PLANNER

THE COMPLETE

AI / ML MASTERCLASS

14-Day Intensive Course  |  Foundations to Modern AI Engineering

| Duration | 14 days |
| --- | --- |
| Daily commitment | 150-minute target; flexible 120–180 minutes |
| Starting point | Python already known; beginner Python instruction excluded |

Authoritative course-content and progress document

Source blueprint: Version 1.0 • 31 October 2026

## 1. Course scope and learning outcomes

This is a structured, intensive 14-day AI/ML masterclass for a learner who already knows Python. It deliberately skips beginner programming instruction and concentrates on mathematical foundations, machine-learning methods, deep-learning architectures, modern foundation models, current AI research directions, practical implementation, evaluation, and AI engineering.

The course is designed to create a coherent mental model: understand the problem first, build intuition, derive the mathematics, inspect the architecture, implement it, evaluate it, and explain it clearly. The aim is broad and rigorous foundational competence—not a false promise of expert mastery in 14 days. Expertise requires continued projects, deeper study, and research practice after the intensive.

## 2. Learning outcomes

Explain the mathematical representations used in AI: scalars, vectors, matrices, tensors, transformations, norms, projections and eigen concepts.

Understand the calculus, probability, statistics, information theory and optimization that support machine learning.

Implement important classical ML algorithms and understand their assumptions, strengths, weaknesses and evaluation.

Explain model training, loss functions, gradient descent, backpropagation, regularization and optimization.

Build and compare ANN/MLP, CNN, RNN, LSTM and GRU models.

Understand attention, transformer blocks, tokenization, embeddings, positional information and decoder/encoder architectures.

Understand current foundation-model concepts: reasoning models, post-training, test-time compute, MoE, multimodality, SLMs and open-weight models.

Understand generative model families including autoregressive models, GANs, VAEs, diffusion and flow-matching at an introductory-to-intermediate level.

Build practical LLM applications using embeddings, retrieval, RAG, reranking, tool calling and agent workflows.

Understand model evaluation, hallucination measurement, safety, deployment, inference optimization and MLOps fundamentals.

Read a research paper's abstract, problem, method, experiments, results, limitations and contribution.

Answer foundational and intermediate AI/ML interview questions with clear reasoning and mathematical explanations.

## 2. Complete 14-day syllabus

The day sequence below is the canonical curriculum. Every listed topic, mathematical component, current-AI connection, practical lab, deliverable and daily interview question is retained from the source blueprint.

## DAY 1 — Linear Algebra for Machine Learning

Learning goal: Understand how data, parameters and learned representations are represented and transformed numerically.

### Detailed syllabus

Mathematical objects: scalar, vector, matrix, tensor; dimensions, rank, shape, axes and indexing.

Vectors: components, coordinate interpretation, addition, subtraction, scalar multiplication and linear combinations.

Norms and distances: L1, L2/Euclidean and L-infinity; distance and normalization.

Dot product: elementwise products and sum; geometric interpretation; relationship to angle and similarity.

Cosine similarity; when direction matters more than magnitude; embedding-space applications.

Matrices: rows, columns, shape, matrix addition, scalar multiplication and element-wise operations.

Matrix multiplication: row-column dot products, compatibility rule and output-shape calculation.

Transpose, identity matrix, determinant, inverse and singular matrices; why inverse is not always available or numerically desirable.

Linear transformations: scaling, rotation, reflection, shear and projection.

Orthogonality, basis, span, linear independence and rank (introductory conceptual treatment).

Eigenvalues and eigenvectors; equation Av = lambda v; geometric interpretation.

Covariance matrix and conceptual bridge to PCA.

Tensors in images, batches, sequences and transformer representations.

Embeddings: numerical representations of words, tokens, images or other objects; dimensions and similarity.

### Mathematical depth

Vector addition and scalar multiplication.

Dot product and cosine similarity formula.

L1, L2 and L-infinity norms.

Matrix multiplication shape rule: (m x n)(n x p) = (m x p).

Transpose and inverse; determinant for 2x2 matrices.

Vector projection formula.

Eigen equation Av = lambda v.

Basic shape reasoning for batch-feature, image and token tensors.

### Current AI connection

Embedding spaces and semantic similarity.

Tensor layouts used by vision and language models.

Connection between matrix multiplication and dense neural network layers.

### Practical lab

Use NumPy to implement vector operations, norms, dot products, cosine similarity, matrix multiplication, transpose, determinant, inverse, a simple 2D transformation and a tiny fully connected layer XW + b. Inspect shapes and explain each result.

### Required deliverable

A notebook with verified outputs, at least five shape annotations, a matrix-multiplication exercise and a neural-layer calculation.

### Interview preparation

Why is linear algebra essential in ML?

Vector vs matrix vs tensor?

Dot product vs element-wise multiplication?

Why do matrix dimensions matter?

What are eigenvectors and eigenvalues?

How does PCA use directions of variance?

What are embeddings and cosine similarity?

## DAY 2 — Calculus, Derivatives and Optimization

Learning goal: Understand how model parameters are adjusted to reduce error.

### Detailed syllabus

Functions, inputs, outputs, domains, ranges and function composition.

Limits and continuity at an intuitive level.

Derivative as instantaneous rate of change and local slope.

Derivative rules: power, sum, product, quotient and chain rules.

Partial derivatives for multivariable functions.

Gradient as a vector of partial derivatives.

Directional derivatives and gradient direction.

Computational graphs and dependency chains.

Optimization objective, parameters, loss surface and stationary points.

Local minima, global minima, maxima, saddle points and non-convexity.

Gradient descent update and learning rate.

Batch, stochastic and mini-batch gradient descent.

Momentum, learning-rate schedules and convergence intuition.

Numerical gradients and finite-difference gradient checking.

### Mathematical depth

Derivative definition and slope interpretation.

Power rule and chain rule derivations.

Partial derivatives and gradients.

Gradient descent: theta_new = theta_old - learning_rate * gradient.

Worked one-dimensional and two-dimensional optimization examples.

Finite-difference approximation to a derivative.

### Current AI connection

Why training large models is an optimization problem.

Gradient-based training and the cost of model optimization.

High-level preview of optimizer choices used in modern deep learning.

### Practical lab

Implement gradient descent for a simple quadratic and for univariate linear regression using NumPy. Plot the loss curve and parameter updates. Compare learning rates that are too small, useful and too large.

### Required deliverable

Notebook with derivation, gradient-descent implementation, loss-vs-iteration chart and a short explanation of convergence.

### Interview preparation

What does a derivative represent?

What is a partial derivative?

Why does gradient descent move opposite the gradient?

What happens when the learning rate is too high?

Batch vs stochastic vs mini-batch gradient descent?

What is a saddle point?

## DAY 3 — Probability, Statistics and Information Theory

Learning goal: Understand uncertainty, distributions, estimation and the statistical ideas behind learning.

### Detailed syllabus

Descriptive statistics: mean, median, mode, range, variance and standard deviation.

Population vs sample; sample estimates and sampling variability.

Probability axioms, events, complements, unions and intersections.

Conditional probability and independence.

Bayes' theorem and Bayesian reasoning.

Random variables: discrete and continuous.

PMF, PDF and CDF; expectation and variance.

Bernoulli, binomial, categorical, uniform, normal/Gaussian and Poisson distributions.

Joint, marginal and conditional distributions.

Covariance and correlation; correlation is not causation.

Sampling, central limit theorem and confidence intervals (introductory).

Hypothesis testing, p-values and statistical significance (introductory).

Likelihood and maximum likelihood estimation.

Entropy, cross-entropy, KL divergence and mutual information.

### Mathematical depth

Expected value and variance.

Conditional probability and Bayes' theorem.

Gaussian distribution and standardization.

Covariance and correlation.

Likelihood and log-likelihood.

Entropy H(X) = -sum p(x) log p(x).

Cross-entropy and KL divergence intuition.

### Current AI connection

Uncertainty and calibration in AI systems.

Entropy and next-token prediction.

Why probability distributions and cross-entropy appear in language-model training.

### Practical lab

Use NumPy/Matplotlib to sample distributions, visualize histograms, compare mean and median under outliers, calculate covariance/correlation, simulate Bayes' theorem and calculate entropy for simple distributions.

### Required deliverable

Notebook with distribution plots, a Bayes calculation, correlation experiment and entropy calculation.

### Interview preparation

What is the difference between probability and likelihood?

What does variance measure?

What does Bayes' theorem tell us?

Covariance vs correlation?

What is maximum likelihood estimation?

Why is cross-entropy used in classification?

What is KL divergence?

## DAY 4 — Machine Learning Fundamentals

Learning goal: Build a coherent picture of the ML workflow and learn core supervised algorithms.

### Detailed syllabus

Definitions and relationships: AI, ML, deep learning, generative AI and foundation models.

Supervised, unsupervised, semi-supervised and reinforcement learning.

Regression vs classification; features, labels, examples and datasets.

Train, validation and test splits; data leakage.

Linear regression: assumptions, prediction and residuals.

Loss functions: MSE, MAE and basic objective functions.

Logistic regression: sigmoid, logits, probabilities and decision threshold.

Classification boundaries and multiclass overview.

K-nearest neighbors and distance-based prediction.

Naive Bayes and conditional independence assumption.

Support vector machines, margins and kernel intuition.

Decision trees, splitting criteria, entropy and Gini impurity.

Random forests and bagging.

Model pipelines, preprocessing and categorical encoding.

Evaluation basics: regression metrics and classification confusion matrix.

### Mathematical depth

Linear model y_hat = Xw + b.

MSE and MAE.

Sigmoid and logistic probability.

Log loss / binary cross-entropy.

Distance calculations for KNN.

Entropy and Gini intuition for tree splits.

### Current AI connection

Traditional ML vs foundation models.

Small language models (SLMs) and task-specific models.

When classical ML can be cheaper, simpler and more reliable than an LLM.

### Practical lab

Use scikit-learn to train a regression model and a classification model. Build a pipeline, split data correctly, evaluate on held-out data and explain baseline performance.

### Required deliverable

Two reproducible notebooks or one clean notebook with regression and classification sections, metrics and error analysis.

### Interview preparation

AI vs ML vs deep learning?

Regression vs classification?

Why separate train, validation and test data?

What is data leakage?

How does logistic regression work?

Why is Naive Bayes called naive?

How does a decision tree choose a split?

## DAY 5 — Advanced Classical ML and Model Evaluation

Learning goal: Understand stronger classical algorithms, unsupervised learning, dimensionality reduction and reliable evaluation.

### Detailed syllabus

Ensemble learning and why combining models can help.

Bagging, boosting and stacking.

Random forest recap and feature importance caveats.

AdaBoost, gradient boosting and XGBoost/LightGBM/CatBoost concepts.

Clustering: K-means, objective, initialization and limitations.

Hierarchical clustering and dendrograms.

DBSCAN, density and noise points.

Dimensionality reduction: PCA, explained variance and reconstruction intuition.

Feature scaling, selection, engineering and encoding.

Bias-variance tradeoff; underfitting and overfitting.

Regularization: L1 and L2; cross-validation.

Hyperparameter search: grid, random and Bayesian optimization concepts.

Metrics: accuracy, precision, recall, F1, specificity, ROC-AUC and PR-AUC.

Confusion matrix, threshold selection and imbalanced datasets.

Calibration, error analysis and model interpretability basics.

### Mathematical depth

Gini and entropy review.

Boosting as sequential error correction.

K-means within-cluster sum of squares.

PCA using covariance/eigenvectors or SVD intuition.

Precision, recall, F1 and confusion-matrix calculations.

Bias-variance decomposition intuition.

### Current AI connection

Modern ranking and recommendation systems.

Feature learning vs hand-engineered features.

How classical evaluation discipline carries over to foundation-model evaluation.

### Practical lab

Train and compare a baseline, random forest and boosting model. Perform cross-validation, tune at least one hyperparameter, plot a confusion matrix and precision-recall or ROC curve, and perform an error analysis.

### Required deliverable

Comparison report with model selection rationale, metrics, plots and a discussion of overfitting.

### Interview preparation

Bagging vs boosting?

Random forest vs gradient boosting?

What is the bias-variance tradeoff?

Why use cross-validation?

Precision vs recall?

When is PR-AUC more useful than accuracy?

How does PCA reduce dimensions?

## DAY 6 — Artificial Neural Networks and Backpropagation

Learning goal: Understand a neural network from a single artificial neuron to a multilayer perceptron, including how gradients are learned.

### Detailed syllabus

Biological neuron analogy and limitations of the analogy.

Artificial neuron: inputs, weights, bias, weighted sum and activation.

Perceptron and linear decision boundary.

Why a single linear layer cannot solve non-linearly separable problems such as XOR.

Multilayer perceptron: input, hidden and output layers.

Forward propagation through layers.

Parameters, weights, biases and trainable tensors.

Loss functions for regression and classification.

Computational graph and chain-rule-based backpropagation.

Backpropagation through a single neuron and a small network.

Gradient accumulation and parameter updates.

Epoch, batch, iteration, batch size and training loop.

Initialization and reproducibility.

Training vs inference and model parameters vs hyperparameters.

### Mathematical depth

z = w^T x + b; a = activation(z).

MSE and cross-entropy objectives.

Chain rule for composite functions.

Derive gradients for a simple linear neuron.

Backpropagation intuition for a two-layer network.

Gradient descent parameter update.

### Current AI connection

Modern neural-network training pipelines.

Automatic differentiation and accelerator-based tensor computation.

Why large-model training requires distributed computation (preview).

### Practical lab

Implement a tiny MLP forward pass and backpropagation using NumPy; then train a small neural network using PyTorch. Compare the two implementations conceptually.

### Required deliverable

A working NumPy neural network and a PyTorch training notebook with loss curve and a short explanation of forward/backward passes.

### Interview preparation

What is a perceptron?

Why do neural networks need hidden layers?

Explain forward propagation.

Explain backpropagation without hand-waving.

What does the chain rule do in a neural network?

Parameter vs hyperparameter?

Epoch vs batch vs iteration?

## DAY 7 — Activation Functions, Initialization, Normalization and Optimization

Learning goal: Understand nonlinearity and the practical techniques that make deep networks train reliably.

### Detailed syllabus

Why stacking linear layers without nonlinearities remains a linear transformation.

Identity/linear, sigmoid and tanh.

ReLU, Leaky ReLU, PReLU and randomized variants.

ELU, SELU, Softplus and Softsign.

GELU, Swish/SiLU, Mish and Hard Swish.

Softmax for multiclass output and its numerical stability.

Compare ranges, derivatives, saturation, computational cost and typical usage.

Vanishing and exploding gradients.

Xavier/Glorot and He/Kaiming initialization.

Batch normalization, layer normalization and RMSNorm concepts.

Dropout, weight decay, early stopping and label smoothing.

SGD, Momentum, Nesterov, Adagrad, RMSProp, Adam and AdamW.

Learning-rate warmup, decay, cosine schedules and gradient clipping.

Train/validation curves and debugging unstable training.

### Mathematical depth

Derivative of sigmoid, tanh and ReLU.

Softmax formula and cross-entropy connection.

Why saturation causes small gradients.

Variance-preserving intuition behind Xavier and He initialization.

Adam first and second moment intuition.

Weight decay vs L2 penalty distinction at a conceptual level.

### Current AI connection

Normalization choices in transformer models.

Modern activation and optimizer choices in foundation-model training.

Efficient training, precision and stability considerations.

### Practical lab

Plot activation functions and their derivatives; train the same small MLP with multiple activations and optimizers; compare convergence and validation performance.

### Required deliverable

Activation comparison chart, experiment table and Week 1 examination.

### Interview preparation

Why are activation functions necessary?

ReLU vs sigmoid vs GELU?

What is the dying ReLU problem?

What causes vanishing gradients?

Xavier vs He initialization?

BatchNorm vs LayerNorm vs RMSNorm?

Adam vs AdamW?

## DAY 8 — Convolutional Neural Networks and Computer Vision

Learning goal: Understand how neural networks exploit spatial structure in images.

### Detailed syllabus

Image representation, channels, pixel values and normalization.

Why fully connected networks are inefficient for large images.

Convolution, kernels/filters and feature maps.

Stride, padding, dilation and receptive field.

Pooling: max and average; downsampling.

CNN building blocks and typical architecture.

LeNet, AlexNet, VGG and Inception overview.

Residual connections and ResNet.

Depthwise separable convolution and EfficientNet concepts.

Classification, data augmentation and transfer learning.

Pretrained models, frozen backbones and fine-tuning.

Image classification metrics and confusion matrix.

### Mathematical depth

Convolution as local weighted operation.

Output feature-map size calculations.

Parameter count in convolution layers.

Receptive-field intuition.

### Current AI connection

Vision-language models and image-text alignment.

Vision Transformers (ViT) as an alternative/complement to CNNs.

Multimodal perception in current AI systems.

### Practical lab

Train a CNN on a small image dataset (for example, Fashion-MNIST or CIFAR-10 depending on compute). Use augmentation or transfer learning and plot train/validation curves.

### Required deliverable

Image-classification notebook, confusion matrix, sample predictions and error analysis.

### Interview preparation

Why convolution instead of dense layers?

What are kernel, stride and padding?

What is a receptive field?

Why do CNNs share weights?

What are residual connections?

What is transfer learning?

## DAY 9 — Advanced Computer Vision and Generative Vision

Learning goal: Understand major visual recognition tasks and how modern models perceive or generate visual content.

### Detailed syllabus

Classification vs localization vs object detection vs segmentation.

Bounding boxes, IoU, non-maximum suppression and confidence scores.

YOLO family concepts and one-stage detection.

Two-stage detectors and Faster R-CNN overview.

Semantic vs instance segmentation.

U-Net and encoder-decoder visual architectures.

Mask R-CNN overview.

Vision Transformers: patch embeddings, attention and classification token.

Contrastive image-text learning and CLIP-style models.

Image embeddings and visual search.

Generative vision: GAN, VAE and diffusion overview.

Image generation evaluation and limitations.

Video understanding and video generation overview.

### Mathematical depth

IoU calculation.

Precision/recall in detection.

Pixel-wise segmentation loss intuition.

Patchification and token-count calculations in ViT.

### Current AI connection

Vision-language models (VLMs).

Multimodal image and video understanding.

Modern image/video generation and diffusion/flow approaches.

### Practical lab

Run inference with a pretrained detector or segmentation model; inspect outputs and confidence; optionally implement a small image embedding search or ViT demo.

### Required deliverable

Visual demo with annotated predictions, evaluation notes and a comparison of CNN and ViT design choices.

### Interview preparation

Detection vs segmentation?

What is IoU?

What is non-maximum suppression?

What does U-Net do?

How does ViT convert an image into tokens?

What does CLIP align?

## DAY 10 — RNNs and Sequential Learning

Learning goal: Understand why sequence data requires temporal or ordered processing and how recurrent networks model it.

### Detailed syllabus

Sequence data: text, time series, audio and event streams.

Why order matters; fixed-window vs recurrent approaches.

RNN cell, hidden state and recurrent update.

Unrolling an RNN across time steps.

Many-to-one, one-to-many and many-to-many tasks.

Backpropagation through time (BPTT).

Vanishing and exploding gradients in long sequences.

Bidirectional RNNs and stacked RNNs.

Teacher forcing and sequence generation concepts.

Encoder-decoder sequence-to-sequence models.

Time-series forecasting workflow and leakage risks.

Evaluation for sequence prediction.

### Mathematical depth

RNN hidden-state recurrence.

Unrolled computational graph.

BPTT chain-rule intuition.

Sequence input/output shape reasoning.

### Current AI connection

Time-series foundation models.

Why transformers became dominant in many sequence tasks.

State-space models as an important alternative sequence-model family.

### Practical lab

Build a small sequence classifier or time-series forecasting model; compare a simple baseline with a basic RNN and inspect errors.

### Required deliverable

Sequence-model notebook, data split that respects time/order, training plot and error analysis.

### Interview preparation

Why are RNNs useful for sequences?

What is a hidden state?

What is BPTT?

Why do vanilla RNNs struggle with long dependencies?

What is a bidirectional RNN?

What is teacher forcing?

## DAY 11 — LSTM, GRU, Attention and Sequence Alternatives

Learning goal: Understand gated recurrence, attention and the transition toward transformer architectures.

### Detailed syllabus

LSTM motivation and cell state.

Forget, input and output gates.

Candidate cell update and hidden-state output.

GRU reset and update gates.

LSTM vs GRU vs vanilla RNN.

Bidirectional and stacked gated recurrent models.

Encoder-decoder with attention.

Additive/Bahdanau and multiplicative/Luong attention concepts.

Attention weights and context vectors.

Alignment and sequence-to-sequence applications.

State-space model intuition and Mamba/selective state-space overview.

Hybrid sequence architectures and when alternatives may be useful.

### Mathematical depth

Sigmoid gates and element-wise gating.

LSTM cell-state update at a conceptual and symbolic level.

Attention score and weighted-sum calculation.

Why gating can preserve information/gradients.

### Current AI connection

Mamba and selective state-space models.

Linear attention and efficient long-sequence processing.

Hybrid Transformer-SSM approaches; explain that performance depends on task and implementation.

### Practical lab

Implement or inspect a small LSTM/GRU sequence model and calculate a tiny attention example manually or in NumPy.

### Required deliverable

Comparison sheet: RNN vs LSTM vs GRU vs attention; a working sequence-model notebook.

### Interview preparation

What problem do LSTM gates solve?

Explain forget/input/output gates.

LSTM vs GRU?

What is attention?

How is a context vector formed?

What are state-space models?

## DAY 12 — Transformers from First Principles

Learning goal: Understand the transformer architecture mathematically and structurally, including attention and tensor shapes.

### Detailed syllabus

Limitations of recurrence and motivation for attention-based parallel sequence processing.

Tokenization and token IDs; subword tokenization concepts.

Token embeddings and positional information.

Sinusoidal positional encoding and learned/relative/rotary position concepts.

Query, Key and Value projections.

Scaled dot-product attention.

Self-attention vs cross-attention.

Causal masking and padding masks.

Multi-head attention and head dimensions.

Position-wise feed-forward network / MLP block.

Residual connections and normalization.

Encoder, decoder and encoder-decoder transformer designs.

Decoder-only GPT-style architecture.

BERT-style encoder and T5-style encoder-decoder distinctions.

Transformer tensor shapes: batch, sequence, hidden dimension and heads.

Computational and memory complexity of attention.

FlashAttention concept and memory-efficient attention.

### Mathematical depth

Q = XW_Q, K = XW_K, V = XW_V.

Attention(Q,K,V) = softmax(QK^T / sqrt(d_k))V.

Why divide by sqrt(d_k).

Masking and softmax.

Multi-head dimension calculations.

Residual addition and normalization.

### Current AI connection

Grouped-query and multi-query attention.

Rotary positional embeddings and long-context techniques.

FlashAttention and efficient attention kernels.

Mixture of Experts (MoE): routing, experts, sparse activation and load balancing.

Long-context models and KV cache preview.

### Practical lab

Implement scaled dot-product self-attention in NumPy or PyTorch. Visualize attention weights and inspect tensor shapes. Build a minimal transformer block or follow a guided small implementation.

### Required deliverable

Mini-attention notebook, shape annotations, attention heatmap and architecture explanation.

### Interview preparation

Why were transformers introduced?

Explain Query, Key and Value.

Why scale attention scores?

Self-attention vs cross-attention?

Why causal masking?

Why multiple heads?

Encoder vs decoder-only architecture?

What is FlashAttention trying to optimize?

## DAY 13 — LLMs, Foundation Models and Generative AI

Learning goal: Understand how modern language and generative models are built, adapted, sampled and evaluated.

### Detailed syllabus

Language-model objective and next-token prediction.

Pretraining data, tokenization, vocabulary and data quality.

Parameters, context window, tokens per second and inference.

Decoder-only language models and causal language modeling.

Foundation models and transfer learning.

Supervised fine-tuning (SFT), instruction tuning and preference alignment.

RLHF and direct preference optimization (DPO) concepts.

Reasoning-oriented models and post-training.

Test-time compute, sampling, search, verification and self-consistency.

Temperature, top-k, top-p and greedy decoding.

Hallucination, calibration, factuality and evaluation.

Prompting vs fine-tuning vs RAG.

Parameter-efficient fine-tuning: LoRA and QLoRA.

Quantization: FP16/BF16, FP8, INT8 and INT4 concepts.

Small language models and on-device/edge AI.

Open-weight vs closed/proprietary models; licensing and deployment tradeoffs.

Mixture of Experts and sparse models.

Multimodal models: text, image, audio, speech and video.

Generative model families: autoregressive, GAN, VAE, diffusion and flow matching.

### Mathematical depth

Next-token cross-entropy objective.

Softmax probability and sampling.

Temperature effect on probability distribution.

LoRA low-rank update intuition.

Quantization and numerical precision tradeoffs.

Basic model parameter/memory estimation.

### Current AI connection

Reasoning models and inference-time scaling.

Test-time compute and verification.

Multimodal foundation models and audio/video models.

Small language models and efficient deployment.

Current model families and releases must be refreshed from primary sources on lesson date.

### Practical lab

Use a hosted or locally available open-weight model to run inference; inspect tokenization and decoding settings. If compute permits, perform a small LoRA fine-tuning demonstration or a guided notebook. Compare output quality and latency under different settings.

### Required deliverable

LLM experiment report: model, prompt, decoding settings, output, latency, evaluation criteria and limitations.

### Interview preparation

What is next-token prediction?

Pretraining vs fine-tuning?

What is RLHF?

What is DPO?

What is test-time compute?

What is LoRA and why use it?

Quantization tradeoffs?

Open-weight vs open-source?

What is a multimodal model?

## DAY 14 — RAG, Agents, AI Engineering, Deployment and Final Project

Learning goal: Connect models to knowledge, tools and real applications while understanding evaluation and production constraints.

### Detailed syllabus

Embeddings and semantic retrieval.

Vector databases and approximate nearest-neighbor search.

Document ingestion, parsing, chunking and metadata.

Dense retrieval, sparse/BM25 retrieval and hybrid search.

Reranking, query rewriting and retrieval evaluation.

RAG pipeline: ingest, index, retrieve, augment and generate.

Advanced RAG: multi-query, parent-child, contextual retrieval and GraphRAG concepts.

RAG vs fine-tuning and when to combine them.

LLM tool/function calling and structured outputs.

AI agents: observe, plan, act, tool result and iterate.

Agent memory, state, planning and task decomposition.

Multi-agent systems and orchestration; when they are unnecessary.

Model Context Protocol (MCP): hosts, clients, servers, tools and resources at a conceptual level.

Human approval, permissions, prompt injection and agent security.

Evaluation: retrieval metrics, answer quality, groundedness, latency, cost and task success.

Deployment: API, model serving, containers and basic cloud concepts.

Inference serving: batching, continuous batching, KV cache, speculative decoding and vLLM concepts.

GPU basics: memory, compute, CUDA awareness and bottlenecks.

MLOps: experiment tracking, versioning, monitoring and reproducibility.

Responsible AI: privacy, bias, safety, licensing and data governance.

### Mathematical depth

Cosine similarity and vector retrieval.

Precision@k, Recall@k and MRR/nDCG intuition.

Latency, throughput and cost calculations.

Parameter count and model memory estimates.

Evaluation rubric for grounded answers and agent task completion.

### Current AI connection

Agentic AI and multi-step tool use.

MCP ecosystem and tool interoperability.

Advanced RAG, GraphRAG and agentic retrieval.

Inference optimization: KV cache, speculative decoding, batching, quantization and FlashAttention.

Current deployment frameworks and model-serving options; verify documentation and versions on lesson date.

### Practical lab

Build a document-grounded RAG assistant. Ingest a small set of documents, chunk and embed them, retrieve relevant passages, generate an answer with citations, and evaluate retrieval and answer quality. Add a simple tool call or workflow if time permits. A full production multi-agent system is explicitly out of scope for the 14-day time budget.

### Required deliverable

Final GitHub-ready project with README, architecture diagram, setup instructions, sample questions, cited answers, evaluation results, known limitations and next steps.

### Interview preparation

What is RAG and why use it?

RAG vs fine-tuning?

Dense vs sparse retrieval?

Why rerank retrieved passages?

What is an AI agent?

What is tool calling?

What is MCP?

How do you evaluate a RAG system?

How do you reduce latency and inference cost?

What are prompt injection and least-privilege tool permissions?

## 3. Quizzes and assessments

### Daily knowledge checks

Aim for 10–15 objective questions per day, adjusted to lesson length.

Use a mix of conceptual MCQs, multiple-select questions, true/false claims, numerical calculations, tensor-shape reasoning and code-output reasoning.

Questions must be objectively answerable, self-contained and aligned with that day's syllabus.

Provide feedback for every answer, including why distractors are wrong.

Do not reveal answers before the learner attempts the question.

After the quiz, summarize strengths, misconceptions and topics to revisit.

### Milestone assessments

### Scoring guidance

Suggested interpretation: 85–100% = strong working understanding; 70–84% = reasonable but revise missed concepts; 50–69% = revisit weak modules and retry; below 50% = pause progression and reteach prerequisites. Scores are diagnostic, not proof of professional competence.

| Assessment | Coverage | Purpose |
| --- | --- | --- |
| Day 3 checkpoint | Linear algebra, calculus, probability/statistics | Verify mathematical readiness. |
| Day 7 examination | Days 1–7 | Week 1 cumulative test: concepts, calculations and ANN foundations. |
| Day 10 checkpoint | CNN, vision and RNN foundations | Check architecture understanding and implementation. |
| Day 14 final examination | Full course | Comprehensive assessment across math, ML, DL, transformers and AI engineering. |
| Final mock interview | Full course | Explain concepts, derive formulas and solve practical scenarios aloud. |

## 4. Practical projects and portfolio

| # | Project | Core skills | Expected artifact |
| --- | --- | --- | --- |
| 1 | Linear regression from scratch | NumPy, vectors, matrices, gradients, loss | Notebook with derivation and loss plot |
| 2 | Classical ML prediction system | Pandas, scikit-learn, preprocessing, metrics | Reproducible ML pipeline |
| 3 | ANN from scratch and PyTorch | Forward pass, backpropagation, training | NumPy implementation + PyTorch model |
| 4 | Image classifier | CNN, augmentation, transfer learning | Model notebook and error analysis |
| 5 | Sequence prediction/classifier | RNN/LSTM/GRU, time/order-aware evaluation | Sequence model notebook |
| 6 | Mini transformer/attention | Token embeddings, QKV, attention, tensor shapes | Attention visualization and minimal model |
| 7 | Open-weight LLM adaptation experiment | Inference, prompting, LoRA concepts, evaluation | Experiment report; fine-tune only if compute allows |
| 8 | RAG document assistant | Embeddings, retrieval, reranking, citations | Working app, architecture diagram and evaluation |
| 9 | Optional agent extension | Tool calling, workflow, MCP concept, guardrails | A constrained tool-using workflow |

Projects 1–6 reinforce foundations. Projects 7–9 are modern AI engineering demonstrations. The 14-day time budget may require some projects to be compact demonstrations rather than production-grade applications.

## 5. Interview preparation framework

## 9. Interview preparation framework

Interview preparation runs in parallel with the lessons. For each day's topics, prepare beginner, intermediate, advanced, mathematical, coding and scenario-based questions. Answers should be concise but technically sound, and should include a formula, diagram or example when useful.

Explain a concept in 30 seconds, then expand it in 2 minutes.

Derive important formulas rather than memorizing them.

Explain tradeoffs: accuracy vs latency, dense vs sparse, RAG vs fine-tuning, CNN vs ViT, RNN vs transformer.

Practice tensor-shape questions and simple numerical calculations.

Practice debugging conceptual and code-level mistakes.

Complete a final mock interview covering math, ML, DL, LLMs and AI engineering.

## 6. Research-paper literacy

## 10. Research-paper literacy

The course includes selected classic papers and a small number of current papers. The tutor must explain papers at the learner's level rather than assume research experience.

### Paper-reading template

Problem: What limitation or unsolved task motivated the work?

Prior work: What did earlier methods do?

Core idea: What is the new contribution?

Method: What architecture, objective, data or training method is used?

Experiments: What benchmarks, baselines and metrics are used?

Results: What improved, and by how much?

Limitations: What does the paper not prove or solve?

Reproduction: What would be required to reproduce the result?

| Paper / topic | Why it is included | Course connection |
| --- | --- | --- |
| Sequence to Sequence Learning with Neural Networks (2014) | Encoder-decoder sequence modeling | Day 10–11 |
| Deep Residual Learning for Image Recognition (2015) | Residual connections and deep CNNs | Day 8 |
| Attention Is All You Need (2017) | Original Transformer architecture | Day 12 |
| Language Models are Few-Shot Learners (2020) | Scaling and in-context learning | Day 13 |
| LoRA: Low-Rank Adaptation of Large Language Models (2021) | Parameter-efficient adaptation | Day 13 |
| Mamba: Linear-Time Sequence Modeling with Selective State Spaces (2023) | State-space sequence modeling | Day 11–12 |
| FlashAttention / FlashAttention-2 | Memory-efficient exact attention | Day 12–14 |
| Selected 2025–2026 papers | Current reasoning, multimodal, agent, efficiency or model-training advances | Days 9, 11–14 |

## 7. Current AI developments: required coverage

## 11. Current AI developments: required coverage

Current AI content is a living layer, not a fixed list of fashionable names. Refresh it on the date each lesson is delivered. As of the blueprint date (31 October 2026), the curriculum should pay particular attention to the following research and engineering directions, while verifying each specific release or claim from primary sources.

Date-sensitive rule: do not invent a 2026 model, benchmark result, release date or capability. Verify through official technical reports/model cards, papers, documentation or reputable reporting. State the date and distinguish announced, available, independently evaluated and research-only systems.

| Direction | Coverage |
| --- | --- |
| Reasoning models and test-time compute | Inference-time scaling, verification, search, self-consistency, process/reward supervision, reasoning evaluation and cost/latency tradeoffs. |
| Agentic AI | Tool use, planning, task decomposition, memory, state, orchestration, human approval, reliability and agent evaluation. |
| MCP and interoperability | Model Context Protocol concepts, host/client/server roles, tools/resources, permission boundaries and secure integration. |
| Multimodal foundation models | Text-image, audio, speech, video and real-time interaction; joint representations and cross-modal reasoning. |
| MoE and sparse architectures | Experts, routers, top-k routing, load balancing, active vs total parameters and distributed serving implications. |
| Beyond standard attention | Mamba/SSMs, linear attention, hybrid architectures, long-context techniques and workload-dependent tradeoffs. |
| Efficient inference | KV cache, continuous batching, speculative decoding, quantization, FlashAttention, throughput, latency and serving systems. |
| Open-weight and small models | Local deployment, licensing, fine-tuning, edge inference, distillation and cost/privacy tradeoffs. |
| Modern post-training | SFT, preference optimization, RL-based post-training, alignment, reasoning and data quality. |
| Generative media | Diffusion, flow matching, autoregressive image/video generation, audio generation and evaluation. |
| AI for science and engineering | Scientific discovery, coding systems, simulation, robotics and domain-specific foundation models. |
| Evaluation and safety | Benchmark contamination, robust evaluation, hallucinations, prompt injection, data privacy, security and responsible deployment. |

## 8. GitHub course workspace and progress tracking

Designated course repository: [ADD THE CORRECT GITHUB REPOSITORY URL]. The source blueprint did not specify a repository URL. Do not guess the owner or repository name. Once supplied, use the GitHub integration to inspect and maintain this repository.

### Suggested repository structure

README.md — course purpose, syllabus overview, setup and progress links.

progress/COURSE_STATUS.md — overall status, current day, completed topics, pending topics and next checkpoint.

progress/SYLLABUS_TRACKER.md — all 14 days and topic-level status.

progress/DAILY_NOTES.md or progress/day-01.md … day-14.md — dated lesson notes, formulas, examples, misconceptions and next steps.

quizzes/ — quiz attempts, scores, feedback and topics to revisit.

practicals/ — notebooks, source code, outputs, plots, metrics and evidence.

projects/project-01 … project-09 — project work, README files and deliverables.

interview/ — question practice, feedback, mock-interview notes and areas to strengthen.

research-papers/ — paper summaries using the course paper-reading template.

### Progress statuses

Not started — not yet covered.

Introduced — explained or encountered, but not yet practised sufficiently.

Practising — exercises or implementation are in progress.

Completed — the planned learning activity has been completed.

Demonstrated — understanding or implementation is supported by reviewed evidence.

Deferred — intentionally postponed; record the reason and next action.

### Before and after every lesson

Before: inspect the repository, course status, syllabus tracker, latest daily notes and relevant practical evidence.

Before: identify the exact last checkpoint and the next unfinished syllabus item. Do not restart completed work unnecessarily.

After: update the relevant day notes, topic statuses, practical evidence, quiz results, interview practice and next checkpoint.

After: record only work actually completed or evidence actually reviewed. Do not infer completion from discussion alone.

A course day may span multiple sessions or chats. Continue at the exact checkpoint rather than rushing to finish the day.

### New-chat continuation

At the start of a new chat, first identify and inspect the designated repository. Read COURSE_STATUS.md, SYLLABUS_TRACKER.md and the latest relevant daily notes. Check recent practical evidence and quiz records. State the last confirmed checkpoint internally, then continue with the next unfinished item in the canonical syllabus. If the repository cannot be accessed, say so and request the repository link or relevant progress record; do not fabricate state.

## 9. Course completion and post-course direction

The course is successful when the learner can explain the foundations accurately, solve representative mathematical problems, implement core algorithms, compare architectures, reason about modern AI systems, evaluate model outputs, build a small end-to-end AI application and communicate technical tradeoffs. Completion of 14 days alone is not equivalent to expert status; portfolio work and continued independent practice are evidence of growing competence.

The original blueprint's post-course 30/60/90-day roadmap is retained below as an optional continuation plan.

| Period | Suggested focus | Evidence of progress |
| --- | --- | --- |
| Days 15–30 | Strengthen math gaps; implement backprop and attention independently; complete one polished ML/DL project. | Clean notebooks, tests, explanations and model evaluation. |
| Days 31–60 | Choose a specialization: LLM engineering, computer vision, NLP, time series, reinforcement learning or applied ML. | One deeper project and a paper reproduction/analysis. |
| Days 61–90 | Build and deploy a more complete AI application; add monitoring, evaluation, security and cost controls. | Deployed portfolio project, technical write-up and mock interview. |

## 10. Source fidelity and scope

This planner is rebuilt from the uploaded 24-page AI/ML Masterclass Complete Course Blueprint. The complete 14-day topic sequence, detailed syllabus, mathematical depth, current-AI connections, practical labs, deliverables and daily interview questions are carried forward. Quiz and milestone assessment requirements, the nine-project portfolio, interview framework, research-paper list and paper-reading template, and current-AI coverage are also retained. Standalone teaching-principle, timed lesson-format, visual/interactive presentation, recommended-resource and general teaching-method sections are excluded.

Repository URL remains to be supplied because it is not present in the uploaded source document.

## 11. Visual, interactive and browser-first lesson standard

The instructor independently selects the most effective teaching medium for each AI/ML concept. The learner does not need to request a diagram, plot, mathematical illustration, architecture map, worked example, interactive demonstration or prose explanation. Choose the simplest format that makes the idea accurate, intuitive and usable. Visuals are instructional aids, not decoration.

### 11.1 Choose the visual to match the learning need

| Learning need | Preferred visual or interaction |
| --- | --- |
| Understand mathematical relationships | Labelled coordinate plots, vector diagrams, matrix/tensor layouts, geometric interpretations and step-by-step derivations. |
| Understand a transformation or computation | Before → operation → after diagrams; annotated computational graphs; tensor-shape flow with dimensions at each step. |
| Understand model architecture | Layered architecture diagrams showing inputs, components, data flow, outputs, parameters and important dimensions. |
| Understand training and optimization | Loss curves, decision surfaces, gradient/optimization illustrations, learning-rate comparisons and parameter-update walkthroughs. |
| Compare algorithms or model choices | Compact comparison tables covering assumptions, strengths, weaknesses, computational cost, use cases and failure modes. |
| Understand probability or statistics | Distribution curves, histograms, sampling demonstrations, probability trees, Bayes diagrams and annotated statistical plots. |
| Understand image models | Image grids, convolution-window walkthroughs, kernels, feature maps, pooling steps, bounding boxes, segmentation masks and annotated predictions. |
| Understand sequence models | Unrolled recurrent networks, time-step diagrams, hidden-state flow, LSTM/GRU gate diagrams and sequence-alignment illustrations. |
| Understand attention and transformers | Token-flow diagrams, Q/K/V projections, attention-score matrices, heatmaps, positional-information illustrations and block-by-block transformer diagrams. |
| Understand LLM and generative workflows | Tokenization examples, embedding-space illustrations, autoregressive generation steps, diffusion denoising stages and model input/output flows. |
| Understand RAG and retrieval | Document → chunk → embedding → index → retrieval → reranking → context → answer pipelines, with citations and failure points labelled. |
| Understand agents and AI engineering | State/workflow diagrams showing planning, tool calls, observations, memory, permissions, human approval, retries and final outputs. |
| Diagnose an error or model failure | Evidence-first decision trees: symptom → inspect → likely cause → safe test/fix → verification. |
| Recall and assess | Short quizzes, output/shape prediction, numerical checks, scenario prompts, teach-back and small interactive parameter changes. |

### 11.2 Visual quality rules

Create a visual only when it clarifies structure, sequence, geometry, causality, comparison, model behaviour or state. Do not add stock imagery merely to make a lesson look attractive.

Prefer original, topic-specific diagrams and plots over generic decorative images. Keep each visual focused on one main idea.

Label axes, units, legends, tensors, dimensions, tokens, layers, arrows and important assumptions. Explain what the learner should notice.

For equations and plots, define symbols and connect the mathematical expression to the visual representation.

For architecture diagrams, show direction of data flow and distinguish training from inference wherever relevant.

For tensor diagrams, state shapes explicitly and keep batch, sequence, channel, feature and hidden dimensions unambiguous.

For plots, use meaningful scales and labels; state the dataset, metric or assumptions when they affect interpretation.

Explain each visual immediately before or after presenting it. Never expect the learner to infer an unexplained diagram.

Use consistent notation and terminology across lessons. Do not use colour as the only way to encode meaning.

Avoid overloaded dashboards, tiny labels, excessive arrows and multiple unrelated ideas in one figure. Split complex systems into progressive views.

Use interactive demonstrations when changing a parameter genuinely improves understanding (for example learning rate, regularization strength, decision threshold, convolution stride, attention weights or retrieval top-k).

If a true interactive visual is not practical in chat, provide a clear static diagram, worked numerical example or executable notebook and label it accurately.

Do not fabricate experimental plots or model outputs. Clearly distinguish illustrative/synthetic examples from results produced by an actual run.

### 11.3 Topic-specific visual patterns across the 14 days

| Course topic | Recommended visual patterns |
| --- | --- |
| Day 1 — Linear algebra | Coordinate vectors; vector addition and projection; dot-product geometry; matrix transformations; eigenvector intuition; PCA projection; tensor-shape maps. |
| Day 2 — Calculus and optimization | Function and derivative curves; tangent/slope illustrations; partial derivatives; gradient vectors; loss surfaces; gradient-descent steps; learning-rate comparisons. |
| Day 3 — Probability and statistics | Probability distributions; sampling/histograms; conditional-probability trees; Bayes updates; covariance/correlation plots; entropy comparisons. |
| Day 4 — ML fundamentals | Train/validation/test split; regression line and residuals; classification decision boundaries; KNN neighbourhoods; tree-split illustrations; confusion matrix. |
| Day 5 — Advanced ML and evaluation | Ensemble diagrams; bias–variance illustration; clustering plots; PCA projections; ROC/PR curves; calibration and error-analysis views. |
| Day 6 — ANN and backpropagation | Neuron and MLP diagrams; forward-pass computational graph; tensor dimensions; loss calculation; backward gradient flow; parameter-update sequence. |
| Day 7 — Training techniques | Activation-function and derivative plots; initialization distributions; normalization flow; optimizer trajectories; learning-rate schedules; training/validation curves. |
| Day 8 — CNNs | Convolution-window animation or frames; kernel and feature-map examples; stride/padding diagrams; receptive-field growth; pooling; CNN architecture; learning curves. |
| Day 9 — Advanced vision | Bounding boxes and IoU; NMS sequence; semantic/instance masks; encoder-decoder/U-Net diagrams; ViT patchification; image-text embedding space; diffusion stages. |
| Day 10 — RNNs | Unrolled time-step diagrams; hidden-state flow; sequence input/output layouts; teacher forcing; sequence-length and padding illustrations. |
| Day 11 — LSTM, GRU and alternatives | LSTM cell and gate flow; GRU gate flow; attention over sequence positions; state-space sequence-processing overview. |
| Day 12 — Transformers | Token and positional flow; Q/K/V projections; attention-score and attention-weight matrices; multi-head attention; residual/norm blocks; encoder/decoder diagrams; tensor shapes. |
| Day 13 — LLMs and generative AI | Tokenization examples; embedding representations; next-token generation; pretraining/post-training pipeline; LoRA adapter illustration; generation-family comparisons. |
| Day 14 — RAG, agents and deployment | Chunking and retrieval pipeline; vector search/reranking; grounded answer with citations; agent state/tool loop; evaluation flow; deployment and inference architecture. |

### 11.4 Browser presentation and lesson rhythm

**Start directly with the lesson.** Every learner-facing teaching response begins with a clear lesson heading such as `# Lesson: [topic]` or `# Study: [topic]`. Do not prepend a visible Part A, pre-lesson, orientation, objectives, prerequisites, repository verification or course-administration section. Do not append a visible Part B, lesson review, progress audit, repository report or handover section to ordinary teaching responses.

Objectives, prerequisites and a short roadmap are useful instructor planning aids. Include them naturally after the lesson heading only when they materially help the learner; do not present them as a separate administrative block. The lesson heading is the immediate start of study.

Perform required repository checks before teaching, but keep routine verification, progress reconciliation, file inventories, GitHub synchronization and record maintenance out of the learner-facing lesson. Mention a repository limitation or checkpoint only when it materially affects the teaching or the learner's next action. Update repository records after meaningful sessions based on actual evidence, not merely because a topic was discussed.

Teach in digestible segments. Place explanations next to equations, diagrams, plots and code. Use separate code blocks for setup, implementation, expected output and explanation when that separation improves clarity. Use interactive controls only when they materially improve practice or self-testing; do not create decorative or inert controls. Keep visuals and tables readable on a desktop browser. Split wide or dense content rather than forcing horizontal scrolling.

Default lesson rhythm: (1) begin with the lesson heading and orient the learner briefly within the lesson, (2) explain one concept, (3) show a visual when useful, (4) derive or model the mathematics, (5) demonstrate with code or a worked example, (6) pause for the learner's questions or clarification, and (7) recap and identify the next step. Practice, checks and evidence review occur only when the learner explicitly opts in. Adjust the number of teaching cycles to the complexity of the topic. Do not force a fixed number of visuals or a fixed response length.

### 11.5 Visuals are part of understanding, not a substitute for it

A diagram or plot must support the mathematical explanation, implementation or evaluation—not replace it. For important concepts, connect the visual to the equation, tensor shapes, code and observed behaviour. The instructor decides when a visual is unnecessary; the goal is clarity and technical correctness, not a diagram in every response.

### 11.6 Mandatory direct-to-lesson presentation

Every learner-facing teaching response starts directly with the actual study heading, for example `# Lesson: Understanding Vectors in Machine Learning`. The teaching begins immediately beneath that heading.

Do not show a separate pre-lesson/Part A section, even in shortened form. Do not show a separate Part B course-administration, review or handover section after the teaching. Do not display routine learning-objective lists, prerequisite lists, repository-verification tables, file inventories, progress audits or synchronization notes before or after the lesson. Learning objectives and prerequisites can guide lesson preparation and may be woven naturally into the teaching when useful.

The instructor must still perform repository verification and course maintenance internally. Keep progress tracking, evidence reconciliation, lesson-note updates, practical/assessment records and GitHub synchronization as repository operations, not as visible lesson sections. Communicate only a material limitation or an immediately relevant next action when needed, briefly and without recreating an administrative block.

For sample, demonstration or test lessons, do not change `COURSE_STATUS.md`, `SYLLABUS_TRACKER.md` or `PROGRESS_LOG.md` unless the learner explicitly requests it. For normal sessions, update records only after actual learning activity and evidence have been reviewed.


## 12. Mandatory incremental concept-by-concept delivery protocol

The syllabus above defines the complete scope and sequence; it does **not** mean that a whole day should be taught at once. The instructor must teach the curriculum incrementally, one concept at a time.

1. **Do not deliver a full day in one go.** Never turn a day's syllabus into one oversized response or attempt to explain every listed topic in a single lesson.
2. **Teach one concept or a small, tightly connected concept cluster per teaching turn.** Choose a natural stopping point based on conceptual dependencies and cognitive load.
3. **Use a complete learning cycle for each concept:** orient the learner to the problem; establish intuition and prerequisites; define terminology; derive the relevant mathematics; work through a numerical example; explain the algorithm/architecture; connect it to practical AI/ML; discuss limitations and misconceptions; and pause for questions or clarification. Do not add a check or exercise unless the learner explicitly opts in.
4. **Pause for learner participation.** Invite questions or clarification and wait when the learner wants to discuss the concept further. Do not ask the learner to complete a knowledge check, calculation, exercise or coding task unless explicitly requested.
5. **Adapt before advancing.** Correct misunderstandings and revisit prerequisites as needed. Do not mark a concept complete merely because it was explained.
6. **Respect learner pacing.** The learner may ask questions, request another example or stop after any concept. Do not force a fixed number of concepts or finish a day to meet a calendar target.
7. **Maintain continuity at subtopic level.** At the end of a teaching segment, record the exact concept completed, what was practised, evidence of understanding, remaining doubts and the next concept. The next session resumes there.
8. **Use the day-level syllabus as a checklist, not a response outline.** Preserve every required topic, lab, deliverable, assessment and interview question while distributing them across as many sessions as needed.

The default lesson rhythm is: **one concept → explanation/derivation → worked example or visual → practical connection → learner questions/clarification → next concept when the learner is ready.** Any learner check, feedback on an attempt or practice task is opt-in. This protocol is mandatory for all 14 days, including practical, project, assessment, LLM, RAG and agent topics.


## Learner-controlled teaching, practice and assessment (mandatory)
- The default is concept-first teaching, one concept or small connected concept group at a time. Explain thoroughly using intuition, terminology, derivations, worked examples, diagrams and AI/ML connections as appropriate.
- Do not give the learner quizzes, tests, assessments, practicals, coding tasks, homework, assignments, projects, interview drills or other activities they are expected to complete until BOTH conditions are met: (1) the learner has had sufficient opportunity to learn the relevant concepts thoroughly and says they are ready, and (2) the learner explicitly asks to begin that specific activity.
- The learner's statement that they are ready to move to another concept, lesson or day is NOT permission to start an assessment or practical. Do not infer consent from silence, progress, or a general request to continue.
- Questions with answers are allowed when they support teaching: include solved examples, illustrative questions followed immediately by their answers and explanations, worked calculations, and conceptual Q&A as needed. These are teaching explanations, not tasks for the learner to complete. Do not disguise an unanswered exercise as an example.
- Do not append quizzes, knowledge checks, "try this" prompts, unsolved exercises or homework to a concept explanation. A natural invitation to ask questions or request another explanation is fine.
- Preserve every quiz, assessment, practical, project and interview requirement in the syllabus. These remain required course components, but they are learner-controlled and must not be delivered before the two opt-in conditions above are met.
- The learner controls pacing. Stay with a concept for as long as needed; do not rush to finish a day or advance because of the calendar.
- Record only activities actually requested and completed. Never mark a quiz, assessment, practical or implementation as completed without evidence.

## Pending syllabus activity reminder (mandatory)
- Maintain awareness of syllabus quizzes, assessments, practicals and other required activities that have not yet been completed. Do not mark them complete or silently drop them.
- When the learner asks to move to a later lesson or course day, check whether a relevant earlier syllabus quiz, assessment or practical is still pending. If so, remind the learner before proceeding: identify the pending activity and explain that they previously asked to be reminded.
- The reminder is not permission to start the activity. Do not present questions or assign the practical at that point. Ask whether the learner explicitly wants to complete the pending activity now; if they prefer to continue, respect that choice and keep the activity recorded as pending.
- Do not interrupt ordinary concept teaching with reminders about activities that are not yet due. Give the reminder at a genuine transition to a later lesson/day when the relevant earlier activity has become due.
- Starting a pending quiz, assessment or practical still requires the learner to have learned the relevant concepts sufficiently and to explicitly request that specific activity.
