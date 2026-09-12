# Deep Learning

A structured, self-contained repository for learning **Deep Learning from fundamentals to modern architectures, research, engineering, deployment, and real-world projects**.

This repository is designed to:

- Fully cover the **Semester VII Neural Networks and Deep Learning syllabus**.
- Build a strong foundation as a **Deep Learning student**.
- Develop practical **Deep Learning engineering skills**.
- Prepare for **research, projects, internships, and technical interviews**.

The learning path is self-contained and does not depend on another repository.

---

## 🎯 Goals

The main goals of this repository are to:

- Understand the foundations of Deep Learning.
- Understand the mathematics behind neural networks.
- Build Neural Networks from first principles.
- Understand forward propagation and backpropagation.
- Understand loss functions and risk minimization.
- Learn optimization and gradient-based training.
- Understand regularization and generalization.
- Learn Deep Neural Networks.
- Master Convolutional Neural Networks (CNNs).
- Master Recurrent Neural Networks (RNNs).
- Understand LSTM and GRU architectures.
- Understand Hidden Markov Models and Conditional Random Fields.
- Learn Attention and Transformer architectures.
- Study representation learning.
- Study generative Deep Learning.
- Apply Deep Learning to Computer Vision and NLP.
- Understand Large Language Model fundamentals.
- Develop practical skills using PyTorch.
- Learn Deep Learning engineering and deployment.
- Read and implement Deep Learning research papers.
- Build progressively challenging Deep Learning projects.
- Prepare for Deep Learning technical interviews.

---

# 📚 Learning Philosophy

This repository is not intended to be a collection of definitions and library calls.

The goal is to understand:

- **What** a method does.
- **Why** it works.
- **How** it works mathematically.
- **How** it is implemented.
- **When** it should be used.
- **What** its limitations are.

For important concepts, the learning process follows:

```text
Concept
   ↓
Intuition
   ↓
Mathematics
   ↓
Derivation
   ↓
From-Scratch Implementation
   ↓
PyTorch Implementation
   ↓
Visualization
   ↓
Experiment
   ↓
Analysis
   ↓
Practical Application
   ↓
Exam Preparation
   ↓
Interview Preparation
```

Not every small topic requires every stage, but the core Deep Learning concepts should be studied deeply.

---

# 🗂️ Repository Structure

```text
Deep_Learning/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── 01_Deep_Learning_Foundations/
│   ├── 01_Introduction_to_Deep_Learning.ipynb
│   ├── 02_Deep_Learning_Paradigms.ipynb
│   ├── 03_Perspectives_and_Issues.ipynb
│   ├── 04_Deep_Learning_Workflow.ipynb
│   └── 05_Mathematical_Foundations.ipynb
│
├── 02_Neural_Network_Fundamentals/
│   ├── 01_Biological_and_Artificial_Neurons.ipynb
│   ├── 02_Perceptron.ipynb
│   ├── 03_Artificial_Neural_Networks.ipynb
│   ├── 04_Activation_Functions.ipynb
│   ├── 05_Multi_Layer_Perceptron.ipynb
│   ├── 06_Fuzzy_Relations.ipynb
│   └── 07_Fuzzy_Relations_Cardinality_Operations_Properties.ipynb
│
├── 03_Neural_Network_Training/
│   ├── 01_Risk_Minimization.ipynb
│   ├── 02_Loss_Functions.ipynb
│   ├── 03_Computational_Graphs.ipynb
│   ├── 04_Forward_Propagation.ipynb
│   ├── 05_Backpropagation.ipynb
│   ├── 06_Gradient_Descent.ipynb
│   ├── 07_Optimization_Algorithms.ipynb
│   ├── 08_Weight_Initialization.ipynb
│   ├── 09_Regularization.ipynb
│   ├── 10_Batch_Normalization.ipynb
│   ├── 11_Normalization_and_Stabilization.ipynb
│   └── 12_Model_Selection_and_Hyperparameter_Tuning.ipynb
│
├── 04_Deep_Neural_Networks/
│   ├── 01_Deep_Feedforward_Networks.ipynb
│   ├── 02_Training_Deep_Models.ipynb
│   ├── 03_Deep_Model_Regularization.ipynb
│   ├── 04_Dropout.ipynb
│   ├── 05_Vanishing_and_Exploding_Gradients.ipynb
│   ├── 06_Residual_Learning.ipynb
│   └── 07_Deep_Belief_Networks.ipynb
│
├── 05_Convolutional_Neural_Networks/
│   ├── 01_Image_Data_and_Representation.ipynb
│   ├── 02_Convolution_Operation.ipynb
│   ├── 03_Kernels_Filters_and_Feature_Maps.ipynb
│   ├── 04_Stride_Padding_and_Receptive_Field.ipynb
│   ├── 05_Pooling.ipynb
│   ├── 06_CNN_Architecture.ipynb
│   ├── 07_CNN_Training.ipynb
│   ├── 08_Data_Augmentation.ipynb
│   ├── 09_Transfer_Learning.ipynb
│   └── 10_Modern_CNN_Architectures.ipynb
│
├── 06_Recurrent_Neural_Networks/
│   ├── 01_Sequence_Data.ipynb
│   ├── 02_Recurrent_Neural_Networks.ipynb
│   ├── 03_RNN_Forward_and_Backward_Pass.ipynb
│   ├── 04_Vanishing_and_Exploding_Gradients_in_RNNs.ipynb
│   ├── 05_LSTM.ipynb
│   ├── 06_GRU.ipynb
│   ├── 07_Bidirectional_RNNs.ipynb
│   └── 08_Sequence_to_Sequence_Models.ipynb
│
├── 07_Probabilistic_Sequence_Models/
│   ├── 01_Probability_and_Entropy_Review.ipynb
│   ├── 02_Hidden_Markov_Models.ipynb
│   ├── 03_Markov_Networks.ipynb
│   ├── 04_Conditional_Random_Fields.ipynb
│   ├── 05_Linear_Chain_CRF.ipynb
│   ├── 06_Partition_Function.ipynb
│   ├── 07_Belief_Propagation.ipynb
│   └── 08_Training_CRFs.ipynb
│
├── 08_Attention_and_Transformers/
│   ├── 01_Motivation_for_Attention.ipynb
│   ├── 02_Attention_Mechanism.ipynb
│   ├── 03_Self_Attention.ipynb
│   ├── 04_Multi_Head_Attention.ipynb
│   ├── 05_Positional_Encoding.ipynb
│   ├── 06_Transformer_Architecture.ipynb
│   ├── 07_Encoder_Decoder_Transformers.ipynb
│   └── 08_Transformers_for_Vision_and_NLP.ipynb
│
├── 09_Representation_Learning/
│   ├── 01_Representation_Learning.ipynb
│   ├── 02_Autoencoders.ipynb
│   ├── 03_Denoising_Autoencoders.ipynb
│   ├── 04_Sparse_Coding.ipynb
│   ├── 05_Variational_Autoencoders.ipynb
│   └── 06_Self_Supervised_Learning.ipynb
│
├── 10_Generative_Deep_Learning/
│   ├── 01_Generative_Modeling.ipynb
│   ├── 02_Generative_Adversarial_Networks.ipynb
│   ├── 03_GAN_Training.ipynb
│   ├── 04_Variational_Generative_Models.ipynb
│   └── 05_Diffusion_Models.ipynb
│
├── 11_Computer_Vision/
│   ├── 01_Object_Recognition.ipynb
│   ├── 02_Image_Classification.ipynb
│   ├── 03_Object_Detection.ipynb
│   ├── 04_Image_Segmentation.ipynb
│   ├── 05_Vision_Transformers.ipynb
│   └── 06_Advanced_Computer_Vision.ipynb
│
├── 12_Natural_Language_Processing/
│   ├── 01_Text_Representation.ipynb
│   ├── 02_Word_Embeddings.ipynb
│   ├── 03_Neural_Language_Models.ipynb
│   ├── 04_Sequence_NLP.ipynb
│   ├── 05_Transformer_NLP.ipynb
│   └── 06_Language_Modeling.ipynb
│
├── 13_Large_Language_Models/
│   ├── 01_LLM_Foundations.ipynb
│   ├── 02_Tokenization.ipynb
│   ├── 03_Pretraining.ipynb
│   ├── 04_Fine_Tuning.ipynb
│   ├── 05_Instruction_Tuning.ipynb
│   ├── 06_RLHF_and_Alignment.ipynb
│   └── 07_RAG_and_LLM_Applications.ipynb
│
├── 14_Deep_Learning_Frameworks/
│   ├── 01_PyTorch_Fundamentals.ipynb
│   ├── 02_Tensors_and_Operations.ipynb
│   ├── 03_Autograd.ipynb
│   ├── 04_Neural_Network_Modules.ipynb
│   ├── 05_Datasets_and_DataLoaders.ipynb
│   ├── 06_Training_Loops.ipynb
│   ├── 07_GPU_Computing.ipynb
│   └── 08_Model_Saving_and_Loading.ipynb
│
├── 15_Deep_Learning_Engineering/
│   ├── 01_Data_Pipelines.ipynb
│   ├── 02_Experiment_Tracking.ipynb
│   ├── 03_Hyperparameter_Optimization.ipynb
│   ├── 04_Model_Evaluation.ipynb
│   ├── 05_Debugging_Deep_Networks.ipynb
│   ├── 06_Model_Optimization.ipynb
│   └── 07_Reproducibility.ipynb
│
├── 16_Deep_Learning_Research/
│   ├── 01_How_to_Read_DL_Papers.ipynb
│   ├── 02_Research_Methodology.ipynb
│   ├── 03_Paper_Implementation_1.ipynb
│   ├── 04_Paper_Implementation_2.ipynb
│   ├── 05_Computer_Vision_Research.ipynb
│   ├── 06_NLP_Research.ipynb
│   └── Research_Notes/
│
├── 17_Deep_Learning_Projects/
│   ├── 01_Beginner/
│   ├── 02_Intermediate/
│   ├── 03_Advanced/
│   ├── 04_Computer_Vision/
│   ├── 05_NLP/
│   ├── 06_Generative_AI/
│   ├── 07_LLM/
│   └── 08_End_to_End/
│
├── 18_Deep_Learning_Deployment/
│   ├── 01_Model_Serving/
│   ├── 02_FastAPI/
│   ├── 03_Docker/
│   ├── 04_Model_Optimization/
│   └── 05_Deployment_Project/
│
└── 19_Deep_Learning_Interview_Preparation/
    ├── 01_Theory/
    ├── 02_Mathematics/
    ├── 03_Neural_Networks/
    ├── 04_CNN/
    ├── 05_RNN_and_Transformers/
    ├── 06_PyTorch/
    ├── 07_Coding/
    └── 08_System_Design/
```

---



# 🧠 Core Competencies

After completing the repository properly, the target is to be able to:

## Understand

- Neural-network architectures
- Activation functions
- Loss functions
- Risk minimization
- Backpropagation
- Gradient-based optimization
- Regularization
- Deep neural networks
- CNNs
- RNNs
- LSTMs
- GRUs
- Attention
- Transformers
- Representation learning
- Generative models
- Computer Vision
- NLP
- LLM fundamentals

## Implement

- Neural networks from scratch
- Forward propagation
- Backpropagation
- Optimization algorithms
- CNNs
- RNNs
- LSTMs
- GRUs
- Transformers
- Autoencoders
- Generative models
- PyTorch training pipelines

## Analyze

- Training behavior
- Overfitting
- Underfitting
- Gradient problems
- Model performance
- Hyperparameters
- Architecture choices
- Experimental results
- Model limitations

## Build

- Deep Learning applications
- Computer Vision systems
- NLP systems
- Generative AI systems
- LLM applications
- End-to-end Deep Learning projects

## Research

- Read research papers
- Understand new architectures
- Reproduce published methods
- Implement research ideas
- Analyze limitations
- Design experiments
- Propose improvements

---

# 🛠️ Technologies

The primary tools and frameworks used in this repository are:

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn where appropriate
- PyTorch
- TorchVision
- Transformers
- Jupyter Notebook

Additional libraries may be introduced when required by a particular topic or project.

---

# 📈 Learning Progression

The intended progression is:

```text
Deep Learning Foundations
          ↓
Neural Network Fundamentals
          ↓
Neural Network Training
          ↓
Deep Neural Networks
          ↓
Convolutional Neural Networks
          ↓
Recurrent Neural Networks
          ↓
Probabilistic Sequence Models
          ↓
Attention
          ↓
Transformers
          ↓
Representation Learning
          ↓
Generative Deep Learning
          ↓
Computer Vision
          ↓
Natural Language Processing
          ↓
Large Language Models
          ↓
PyTorch
          ↓
Deep Learning Engineering
          ↓
Research
          ↓
Projects
          ↓
Deployment
          ↓
Interview Preparation
```

---

# 🔬 From Theory to Practice

The repository follows a gradual transition:

```text
Mathematical Understanding
          ↓
Conceptual Understanding
          ↓
From-Scratch Implementation
          ↓
PyTorch Implementation
          ↓
Controlled Experiments
          ↓
Real Datasets
          ↓
Advanced Architectures
          ↓
Research
          ↓
Projects
          ↓
Deployment
```

---

# 📖 Recommended References

The Semester VII syllabus recommends:

1. Ian Goodfellow, Yoshua Bengio, Aaron Courville — *Deep Learning*, MIT Press, 2016.
2. Christopher M. Bishop — *Pattern Recognition and Machine Learning*, Springer, 2006.
3. B. Yegnanarayana — *Artificial Neural Networks*, PHI Learning.
4. G. H. Golub and C. F. Van Loan — *Matrix Computations*, JHU Press.
5. Satish Kumar — *Neural Networks: A Classroom Approach*, Tata McGraw-Hill.
6. Dr. Rajiv Chopra — *Deep Learning*, Khanna Publishing House.

---

# 🚀 Project Philosophy

The purpose of this repository is not to simply complete notebooks.

The goal is to develop the ability to:

> **Understand → Derive → Implement → Experiment → Analyze → Build → Deploy → Research**

A completed topic should represent actual understanding rather than simply the presence of code.

---

# 📌 Progress

```text
01  Deep Learning Foundations          ⬜
02  Neural Network Fundamentals       ⬜
03  Neural Network Training           ⬜
04  Deep Neural Networks              ⬜
05  Convolutional Neural Networks     ⬜
06  Recurrent Neural Networks         ⬜
07  Probabilistic Sequence Models     ⬜
08  Attention and Transformers        ⬜
09  Representation Learning           ⬜
10  Generative Deep Learning          ⬜
11  Computer Vision                   ⬜
12  Natural Language Processing       ⬜
13  Large Language Models             ⬜
14  Deep Learning Frameworks          ⬜
15  Deep Learning Engineering         ⬜
16  Deep Learning Research            ⬜
17  Deep Learning Projects            ⬜
18  Deep Learning Deployment          ⬜
19  Interview Preparation             ⬜
```

---

# 🎓 Final Objective

By completing this repository, the objective is to develop from a learner of neural networks into someone capable of:

- Understanding Deep Learning theory.
- Deriving important algorithms mathematically.
- Implementing neural networks from scratch.
- Building models using PyTorch.
- Training and debugging Deep Learning systems.
- Working with CNNs, RNNs, Transformers, and generative models.
- Applying Deep Learning to Computer Vision and NLP.
- Understanding modern LLM architectures and workflows.
- Reading and implementing research papers.
- Building real-world Deep Learning projects.
- Deploying trained models.
- Discussing Deep Learning confidently in technical interviews.

---

## Status

🚧 **In Progress**

This repository is being developed systematically from **Deep Learning fundamentals to advanced applications, research, and deployment**.
