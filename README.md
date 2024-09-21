# Multilingual Toxicity Detection Model in Hinglish

## Description
This project implements a multilingual toxicity detection model capable of identifying toxic comments in Hinglish, a hybrid language commonly used in India. The model leverages various machine learning techniques and tokenization methods to effectively classify comments as toxic or non-toxic.

## Applications
- **Indian Social Media**: Enhancing the moderation of comments on platforms by detecting toxic content.
- **Multiplayer Games**: Monitoring in-game chats to promote a healthy gaming environment.

## Dataset Sources
The dataset for this project was collected from various online sources, including:
- **Hinglish Profanity Dataset**: The dataset used in this research is detailed in the following paper:
 @InProceedings{W18-5118, author = "Mathur, Puneet and Sawhney, Ramit and Ayyar, Meghna and Shah, Rajiv", title = "Did you offend me? Classification of Offensive Tweets in Hinglish Language", booktitle = "Proceedings of the 2nd Workshop on Abusive Language Online (ALW2)", year = "2018", publisher = "Association for Computational Linguistics", pages = "138--148", location = "Brussels, Belgium", url = "http://aclweb.org/anthology/W18-5118" }
- ChatGpt


## Methodology
1. **Data Preprocessing**: Extensive preprocessing was performed to clean and prepare the data for model training.
2. **Tokenization Techniques**:
   - **TF-IDF**: Used for feature extraction.
   - **Word2Vec**: Implemented using CBOW and Skip-gram techniques.
   - **FastText**: Also applied using both CBOW and Skip-gram methods.
3. **Models Trained**:
   - **Traditional Models**: SVM, Gaussian Naive Bayes, Random Forest, XGB Classifier.
   - **Deep Learning Models**: RNN with LSTM and GRU architectures.
   - **BERT**: A BERT base-uncased model fine-tuned on the dataset.

## Results
The evaluation metrics demonstrated that the TF-IDF approach achieved the best performance across various models, including accuracy, precision, recall, and F1 score. Detailed comparative graphs for each model and tokenization method can be found in the `images` directory.

## Installation Instructions
To set up the environment and run the code, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/repository_name.git
   cd repository_name
   
2. Install the required packages:
   pip install -r requirements.txt

## Usage

This project consists of two Jupyter notebooks for analysis:

1. **Tokenization Comparison**: 
   To compare various tokenization methods, run the following notebook:
   ```bash
   jupyter notebook notebooks/tokenization_comparison.ipynb

2. **Model Comparison with TF-IDF**
   To compare different models using TF-IDF, run this notebook:
   ```bash
   jupyter notebook notebooks/model_comparison.ipynb
   
## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the repository**: Click on the "Fork" button at the top right corner of the repository page.
2. **Create a new branch**: 
   ```bash
   git checkout -b feature/YourFeature
3. **Make your changes and commit them**
    ```bash
    git commit -m 'Add your feature'
4. **Push to the branch**:
    ```bash
    git push origin feature/YourFeature
5.***Open a Pull Request***
    Go to the original repository and click on "New Pull Request" to submit your changes.
Thank you for your contributions!

