# AI-Chat-Bot

AI chat bot using Retrieval-Augmented Generation (RAG)

Large Language Models (LLMs) are great at generating text but they lack information about the users projects as most AI databases are not open-sourced. 

RAGs = LLM + project specific knowledge database. RAGs allow for more specific and accurate responses from the AI chat bot.

Expo docs was used as project knowledge database. 

OpenAI was used for the LLM. 

Vector PostgresQL and Supabase were used for the databases for the LLM.

React Native and Typescript were the main languages used for the UI.

How this app works:
1. User submits a prompt
2. App generates an embedding model (aka generative AI) that has our knowledge base (Expo Docs) built into it
3. The vector embedding is stored
4. The app finds the most relevant docs based on similarity
5. These docs are then sent to a LLM
6. The app will then generate an answer (text + links)

Tutorial link here: https://www.youtube.com/watch?v=BgrSLXwydvc
