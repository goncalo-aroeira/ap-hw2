# Deep Learning Homework 2 - IST 2023/24

This repository contains the solutions for Homework 2 of the Deep Learning course at Instituto Superior Técnico (IST). The assignment covers three topics: self-attention approximations, convolutional neural networks (CNNs) for image classification, and automatic speech recognition (ASR) using encoder-decoder architectures.

## Topics Covered
### 1. Self-Attention Approximations  
- Analysis of the computational complexity of the self-attention mechanism in transformers.  
- Feature map approximation using the McLaurin series expansion.  
- Reformulating self-attention to achieve linear complexity.  

### 2. CNNs for Image Classification  
- Implementation of a convolutional neural network for **OCTMNIST** image classification using **PyTorch**.  
- Architecture includes multiple convolutional layers, max-pooling, dropout, and fully connected layers.  
- Performance evaluation using training loss and validation accuracy over epochs.  

### 3. Automatic Speech Recognition (ASR)  
- Comparison of **RNN-based** and **transformer-based** decoders for transcribing speech from the **LJ Speech dataset**.  
- Implementation of sequence-to-sequence models using encoder-decoder architectures.  
- Evaluation using similarity metrics such as **Jaccard similarity, Cosine similarity, and Damerau-Levenshtein distance**.  

## Installation & Setup
To set up the environment and run the models, follow these steps:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/deep-learning-hw2.git
   cd deep-learning-hw2
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the CNN Model for Image Classification**  
   ```bash
   python hw2-q2.py
   ```

4. **Run the Speech Recognition Model**  
   Open `hw2-q3.ipynb` in Jupyter Notebook and execute the cells.

## Results
- **CNN Performance:**  
  - Best validation accuracy achieved: **87.24%**  
  - Alternative architecture without max-pooling: **85.76%**  

- **Speech Recognition Performance:**  
  - Transformer-based decoder outperforms LSTM-based decoder.  
  - Best test similarity scores:  
    - Jaccard similarity: **0.765**  
    - Cosine similarity: **0.866**  
    - Damerau-Levenshtein similarity: **0.634**  

## License
This project is for educational purposes and follows an open-access policy.



