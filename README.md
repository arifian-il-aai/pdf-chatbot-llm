# Build a Chatbot to Analyze PDF Documents Using LLM
## Author : @sinanazeri 

Mentee assignment from IBM Advance AI @ Infinite Learning
Course completion of Build a Chatbot to Analyze PDF Documents Using LLM from CognitiveClass.ai
---

## Mentee Info
### Name : Arifian Saputra
### Program : IBM Advance AI

## Tech Stack: 
- Python
- HTML
- CSS
- JavaScript
- Flask

## Documentation
Install virtual environnment
```
pip install virtualenv
```

Go to parent folder and make virtual environment
```
cd ..
virtualenv my_env
source my_env/bin/activate
```

Then go back to main folder
```
cd pdf-chatbot-llm
```

Install the library needed
```
pip install Flask Flask_Cors langchain==0.0.299 openai==0.28 pdf2image chromadb==0.4.15 pypdf tiktoken
```

Run the server
```
python server.py
```
