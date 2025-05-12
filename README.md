# Financial-Sentiment-Analysis

📌 Overview: BERT Model for Financial Sentiment Analysis 

This script uses a powerful AI model called BERT (Bidirectional Encoder Representations from Transformers)  to analyze the sentiment  of financial text. The goal is to classify sentences into one of three categories: 

    ✅ Positive 
    ⚖️ Neutral 
    ❌ Negative 
     

This kind of analysis is very useful in finance, where understanding market sentiment from news, reports, or social media can help make better investment decisions. 
🔧 What Does the Code Do? 

    Installs Required Tools: 
    It installs libraries like transformers, datasets, and torch—which are essential for working with AI models and data. 

    Loads Financial Data: 
    It pulls a dataset called Financial PhraseBank  from Hugging Face, which contains real-world financial sentences labeled by human experts as positive, neutral, or negative. 

    Prepares the AI Model:    
        Uses a pre-trained BERT model (bert-base-uncased) as a starting point.
        Adapts it for classification by setting up 3 output labels (positive, neutral, negative).
        Prepares the text data by converting it into a format that BERT understands (tokenization).
         

    Trains the Model: 
    The model is trained for 3 rounds (epochs) using a portion of the data for training and another for validation to ensure it learns well and generalizes to new data. 

    Evaluates Performance: 
    After training, the model is tested on unseen data to measure how accurate it is. 

    Predicts Sentiment on New Text: 
    Example sentences are used to show how the model can predict sentiment on brand-new input—demonstrating its real-world use. 

    Saves the Model: 
    The fine-tuned model is saved locally so it can be reused later for predictions without retraining. 
     

💡 Why This Matters 

By fine-tuning BERT on financial language, we create a customized tool  that can automatically understand and categorize financial opinions and news—helping analysts and investors stay ahead of trends and manage risk more effectively. 
