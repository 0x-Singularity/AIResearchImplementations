# AIResearchImplementations

A collection of implementations of AI and machine learning research papers. This repository is designed to help bridge the gap between theory and practice, with each project providing a paper link, relevant documentation, and code that re-creates the research from scratch.

## Directory Structure
The repository is organized into different areas of AI and machine learning research, including deep learning, convolutional neural networks (CNNs), and others.

---

## Papers and Implementations

1. **Learning Representations by Backpropagating Errors (Rumelhart et al., 1986)**  
   [Original Paper](https://www.nature.com/articles/323533a0) | [My Implementation](CNNs/LearningRepresentations/myimplementation)  
   **Tags:** Backpropagation, Neural Networks

2. **ImageNet Classification with Deep Convolutional Neural Networks (AlexNet)**  
   [Original Paper](https://papers.nips.cc/paper_files/nips2012/2012_Hinton.pdf) | [My Implementation](CNNs/AlexNet/myimplementation)  
   **Tags:** CNNs, Computer Vision

3. **Attention Is All You Need (Vaswani et al., 2017)**  
   [Original Paper](https://arxiv.org/abs/1706.03762) | [My Implementation](DeepLearning/AttentionIsAllYouNeed/myimplementation)  
   **Tags:** Transformers, Deep Learning, NLP

---

## How to Use

Each project uses its **own virtual environment** to ensure dependency isolation. Follow the steps below to set up and run an implementation.

### Step-by-Step Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AIResearchImplementations.git
    ```
   
2. Navigate to the desired project
   ```bash
   cd AIResearchImplementations/CNNs/LearningRepresentations
   ```
   
3. Create the virtual environment
   ```bash
   python3 -m venv venv
   ```
   
4. Activate the virtual environment
   Linux/Mac
   ```bash
   source venv/bin/activate
   ```
   Windows
   ```bash
   venv\Scripts\activate
   ```
5. Install Dependencies: Install required packages for the implementation:
   ```bash
   pip install -r requirements.txt
   ```
6. Run the code
   ```bash
   python myimplementation.py
   ```
7. Deactivate the virtual environment
   ```bash
   deactivate
   ```
