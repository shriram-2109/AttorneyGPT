# AttorneyGPT - Multilingual Generative AI Law Chatbot

AttorneyGPT is a RAG based multilingual generative AI chatbot that is trained using Indian Penal Code data. This project was developed using Streamlit LangChain and TogetherAI API for the LLM. Ask any questions to the chatbot and it will give you the right justice as per the IPC.

![main](https://github.com/shriram-2109/AttorneyGPT/blob/main/images/AttorneyGPTcover.png)

## Installation

#### 1. Clone the repository:
   - ```bash
     git clone https://github.com/shriram-2109/AttorneyGPT.git
     ```
#### 2. Install necessary packages:
   - ```bash
     pip install -r requirements.txt
     ```
#### 3. Run the `ingest.py` file, on kaggle or google colab for faster embeddings processing and then download the `ipc_vector_db` and save it locally.
#### 4. Mistral-7B is accessed using Together AI as it offers free credits worth $25. Integrate Together AI into your Python environment by setting the API Key as an environment variable using secret .env file.
   - ```.env
      TOGETHER_API_KEY = "YOUR_TOGETHER_API_KEY"`
     ```
#### 5. Usage:
  - ```bash
    streamlit run app.py
    ```
#### 6. Output: 
- Main Window
![out1](https://github.com/shriram-2109/AttorneyGPT/blob/main/images/Main_Image.png)
- English
![out2](https://github.com/shriram-2109/AttorneyGPT/blob/main/images/English.png)
- Tamil
![out3](https://github.com/shriram-2109/AttorneyGPT/blob/main/images/Tamil.png)

#### 7. Walkthrough:
I've added the working of chatbot by asking query in Tamil and the chatbot responds to me in Tamil.

https://github.com/user-attachments/assets/32eb4895-8bc9-4f29-9bb9-779df68588cc
