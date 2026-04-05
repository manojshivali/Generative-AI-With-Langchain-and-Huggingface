 # Generative-AI-With-Langchain-and-Huggingface

## Course Materials
**-Python :** https://github.com/krishnaik06/Complete-Python-Bootcamp  
**-Anaconda/Jupyter download link:** https://www.youtube.com/watch?v=UTqOXwAi1pE  
**-Set Env variable for conda:** https://www.youtube.com/watch?v=zFKD2Q9m_nQ    **=> Not needed in MAC M4**  
**-Install VSCode for MAC M4**
## Generative AI Application with Langchain:  
## Topics covering:  
1) Python Programming => Basic to Advance    
2) NLP in Deep Learning => RNN, LSTM RNN, GRU RNN, Bidirectional RNN, Encoder Decoder, Attention Mechanism, Transformer, BERT ==> These all are Basic Building block for "LLM Models" => Generative AI    
3) Langchain Ecosystem => Generative AI Web framework => Paid LLM, Multi Model, Open Source LLM, Agents, Chat with SQL, Vector Database, Retrivers, Chain, Text summarization, Chatbots with chat message history  
4) 3 Imp Libraries a) Langchain Core  b) Langchain Community  c) Langchain Tools    
5) Deployment Techniques => We will use free sources  
6) We will use Streamlit framework(Library) to develop all apps  
7) Fine Tuning Techniques => free source(Fine tune with open source LLM Models) like Google Colab => Quentization, LORA, QLORA    
8) One of the paid LLM Model is OpenAI  
9) GenAI in AWS => AWS BEDROCK: Service in AWS which has many open source models in hosted mode. => Will use Lambda function and we will learn how to deploy in AWS Sagemaker  
10) Nvidia NIM => Help to deploy Genrative AI models in cloud.    
11) CREW AI => Multi AI Agents -> Gen AI Apps      

  We will use LLM and MultiModels (both paid and free)  
  Open source models:  
  a) Open AI -> GPT 4.0, GPT 4 Turbo, Open AI Embedding    
  b) Google Model -> Gemma, Gemma 2  
  c) Meta -> LLama 3, CodeLama  
  d) Anthropic -> Mistral
  e) Huggingface-> both open source and paid      
  
  GROQ AI Infrastructure -> LPU Engine(Better than GPU)

Steps  
Install Anaconda and VSCode for MAC M4.    
Creating env:  
Open VSCode Terminal by pressing ctrl+`    
(base) manoj@MANOJs-MacBook-Air VSCode % pwd  
/Users/manoj/MJ_Soft/Generative_AI/VSCode  
(base) manoj@MANOJs-MacBook-Air VSCode % conda create -p venv python==3.12    
Activating env:  
(base) manoj@MANOJs-MacBook-Air VSCode % conda activate venv/    
(/Users/manoj/MJ_Soft/Generative_AI/VSCode/venv) manoj@MANOJs-MacBook-Air VSCode %  
Running app.py file:  
(/Users/manoj/MJ_Soft/Generative_AI/VSCode/venv) manoj@MANOJs-MacBook-Air VSCode % pwd  
/Users/manoj/MJ_Soft/Generative_AI/VSCode  
(/Users/manoj/MJ_Soft/Generative_AI/VSCode/venv) manoj@MANOJs-MacBook-Air VSCode % python app.py  
2  
Create test.ipynb file under folder 1_Python_Basics  
Select Kernel -> venv(Python 3.12.0)  
We have two things in .ipynb file : Code cell and Markdown cell(Press Shift+Enter to run Markdown)  
If we put "1+1" in Code cell and try to run then it will show: requires the ipykernel package.  
So we put below command in VSCode terminal:  
(/Users/manoj/MJ_Soft/Generative_AI/VSCode/venv) manoj@MANOJs-MacBook-Air VSCode % pip install ipykernel  
Now Code cell with "1+1" will work  
ipykernel package provides kernel to this specific Jupyter notebook which will be responsible in executing the python code  
In Anaconda, default jupyter notebook has ipykernel already integrated to it.  
.py file has already that envirionment setup so we don't need to setup again.  
(base) manoj@MANOJs-MacBook-Air VSCode % python --version  
Python 3.13.9  

https://github.com/krishnaik06/Complete-Python-Bootcamp/tree/main/1-Python%20Basics  

##Single line commnet   

'''  
Multiline comments  
'''  

Always do conda acitvate before use/install:  
conda activate venv/  
pip install -r Streamlit/requirements.txt  

streamlit run app.py  

## Natural Language Processing In Machine Learning  
ML : a) Supervised b) Unsupervised  
Supervised: a) Classification  b) Regression  
Roadmap of NLP:  
a) Cleaning the input: Text preprocessing : Tokenization, Lemmatization, Stemming, Stopwords  ==> ML (Libraries: NLTK, Spacy)  
b) Text preprocessing: Input Text -> Vectors : BOW (Bag Of Words), TF-IDF, Unigrams, Bigrams  ==> ML (Libraries: NLTK, Spacy)  
c) Text preproceesing: Input Text -> Vectors : Word2Vec, AvgWord2Vec  ==> ML (Libraries: NLTK, Spacy)  
d) Text preproceesing: Deep Learning: Neural Networks: RNN, LSTM RNN, GRU RNN    ==> Deep Learning (TensorFlow, PyTorch)  
e) Text preproceesing: Input Text -> Vectors : Word Embeddings  ==> Deep Learning (TensorFlow, PyTorch)  
f) TRANSFORMERS  ==> Deep Learning (TensorFlow, PyTorch)  
g) BERT(Most accurate) ==> Deep Learning (TensorFlow, PyTorch)  

Tokenization in NLP:  
a) Corpus: Paragraph    
b) Documents: Sentences  
c) Vocabulary: Unique Words  
d) Words   

Tokenization: Corpus(Paragraph) ---> Tokens(Sentences/Documents)  
            : Sentences/Documents ---> Words  





Need to resume: From Video Lecture 38  



















# Rough:









