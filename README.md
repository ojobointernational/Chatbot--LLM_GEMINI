
# Chatbot_LLM RAG System
This system uses a csv file that has all the information from which the llm should only provide answers 
to users based on users query.
## Requirement.txt
All libraries needed for the project are contained in this file 
## Model 
gemini-1.5-flash 
## Summary
Streamlit library to configure the front-end to respond to end users query
Text converted into vector and stored in the vector database (Chroma). Vector retrieval library used to retrieved data 
from the vector database based on similarity to users query and then the model respond accurately. Prompt for the model is 
configure to respond only based on the content of the texfile. 
Note: Environment file with api key is hidden from the public 


