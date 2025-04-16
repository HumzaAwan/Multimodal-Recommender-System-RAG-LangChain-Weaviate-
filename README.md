# Multimodal-Recommender-System-RAG-LangChain-Weaviate-


A fully multimodal Retrieval-Augmented Generation (RAG) system that uses image and text embeddings to recommend movies based on posters or natural language descriptions. Built using LangChain, Weaviate, OpenAI, and Google Gemini, this system enables seamless semantic search and generation across text and images.

🚀 Project Highlights
🧠 RAG Architecture: Combines retrieval (Weaviate) with generation (Gemini / GPT) for rich, context-aware recommendations.

🔍 Text & Vision Search: Supports searching by movie overview, title, and even movie posters.

🛠️ Multivector Indexing: Uses Weaviate’s multi2vec and text2vec for multimodal vector spaces.

🔗 LangChain Integration (optional): Chain your query inputs and retrieval steps into pipelines.

✨ LLM Descriptions: Generates rich descriptions from images using Gemini 1.5 Flash or GPT-4 Vision.

🧰 Tech Stack

Layer	Tool / Library
Vector DB	Weaviate (local embedded)
Text Embeddings	text2vec-openai (via OpenAI API)
Image Embeddings	multi2vec-palm (Google PaLM/Gemini)
LLM Generation	Gemini 1.5 Flash, GPT-4 Vision
RAG Framework	LangChain (optional pipeline chaining)
Backend Language	Python
🧪 Core Features
Multimodal Retrieval: Search using text or image inputs.

LLM-Enhanced RAG: Retrieve image/poster → Generate movie description using Gemini.

Batch Movie Imports: Load and embed large datasets.

Image-to-Text Pipeline: Converts poster to text using LMM → enables downstream recommendations.



# Full multimodal RAG: retrieve poster & describe it
mm_rag("Epic superhero adventure in the mountains")
🖼 Sample Output
vbnet
Copy
Edit
🎬 Title: Avengers: Infinity War
📝 Overview: The Avengers must stop Thanos...
🧠 LLM Description: This poster features a group of heroes surrounded by cosmic destruction...
