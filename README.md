# RFP-generator
RFP generator using GenAI

Data has been ingested using url's provided by customer
I have used langchain url loader and text splitter 
AWS Bedrock Titan embeddings have been used to create the embeddings and store vectors in Chroma DB
I have used Claude Sonnet LLM in AWS Bedrock
Prompt technique detail - 
Used Langchain retreival QA to retrieve data using similarity search
Used Stremlit to launch it as an app 
