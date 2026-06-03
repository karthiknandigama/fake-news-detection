# 📰 Fake News Detection Pipeline & Interactive Chatbot

## 🚀 Overview
This project is a complete Natural Language Processing (NLP) pipeline designed to classify news articles as 'Fake' or 'Factual'. It demonstrates a full workflow from basic data ingestion and text preprocessing up through the implementation of a fine-tuned Large Language Model (LLM). 

To bridge the gap between static machine learning models and user interaction, this project features a custom-built, continuous-loop chatbot interface directly inside the notebook.

## ✨ Key Features
* **LLM Integration:** Utilizes the Hugging Face `transformers` library to deploy a pre-trained BERT model (`mrm8488/bert-tiny-finetuned-fake-news-detection`) for text classification.
* **Interactive Chatbot UI:** Features a custom back-end `while` loop interface that allows users to continuously paste text snippets and receive real-time model predictions without restarting the kernel.
* **Robust Error Handling:** Implements `try/except` blocks to gracefully handle model inference failures and maintain a seamless user experience.
* **Data Processing:** Handles raw CSV data ingestion and preprocessing using Pandas.

## 🛠️ Tech Stack
* **Language:** Python
* **AI/ML:** Hugging Face `transformers`
* **Data Manipulation:** Pandas
* **Environment:** Jupyter Notebook

## 💻 How to Run Locally
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed: `pip install pandas transformers`
3. Open `Fake_News_Detection_Pipeline.ipynb` in your Jupyter environment.
4. Run all cells from top to bottom to load the data and initialize the Hugging Face model.
5. At the very bottom of the notebook, interact with the **Fake News Detector Bot** by pasting article snippets into the input box! Type `quit` to exit the loop.
