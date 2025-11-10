# Clinical Trials Agent

An AI-driven intelligent agent designed to analyze and interact with clinical trial data in real time using Large Language Models (LLMs), CrewAI, and SQLite.  
This project demonstrates how Generative AI can automate data understanding, query answering, and insights generation for healthcare research.

---

## Features

- AI Agent Integration: Built with CrewAI and a custom LLaMA model for natural language query handling  
- Clinical Trial Analysis: Processes and analyzes structured and unstructured trial data  
- Database Connectivity: Real-time interaction with SQLite for dynamic query responses  
- LLM-driven Reasoning: Uses natural language to interpret, summarize, and generate insights from medical datasets  
- Interactive Notebook: Includes a ready-to-run Jupyter notebook for demonstration and experimentation  

---

## Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| AI / NLP | CrewAI, spaCy, LangChain, Transformers, LLaMA |
| Database | SQLite |
| Machine Learning | scikit-learn, pandas, numpy |
| Visualization | matplotlib, seaborn |
| Environment | Jupyter Notebook |

---

## Dataset

This project uses the 1.6 GB Clinical Trials Dataset from Kaggle.

**Download link:**  
[Clinical Trials Dataset on Kaggle]([https://www.kaggle.com/your-dataset-link](https://www.kaggle.com/datasets/hariniravichandran06/clinical-trials-data)) 

After downloading:
1. Create a folder named `data` inside your project directory.
2. Place the downloaded dataset (e.g., `clinical_trials.db`) inside the `data/` folder.




---

## Installation and Setup

### Step 1: Clone the Repository

git clone https://github.com/Harini172003/clinical-trials-agent.git
cd clinical-trials-agent


python -m venv env
env\Scripts\activate    # on Windows
# or
source env/bin/activate # on Mac/Linux

---

## pip install -r requirements.txt

### steps to be followed: 
Open the clinical_trials.ipynb in juypter notebook and the serve llama in kaggle or google colab
Run the serve llama first and get the api call and copy it and paste it in the clinical trials groq receiver code to connect to the llama model
(Here ngrok api is used for calling and the groq model is used for fast generation of the response.)
After pasting the API calls in clinical trials code run it so that the gradio UI opens up for the user response to be given as input.
Any user query can be asked regarding medical terms, symptoms and disease, medications, etc.




