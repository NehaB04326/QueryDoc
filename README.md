# QueryDoc 
Advanced Document Intelligence Platform to answer your queries

**Built an AI-powered Document Intelligence Tool — QueryDoc**

Working with large PDFs can be time-consuming, especially when trying to extract meaningful insights. To solve this, I developed *QueryDoc*, a tool that makes document analysis faster and more interactive.

**Key features:**

•**Conversation with documents**
Ask questions directly from PDFs using semantic search and LLMs

• **Multi-document support**
Upload and work with multiple PDFs at once, with separate context-aware chats

• **Structured extraction**
Get executive summaries, core arguments, key evidence, and insights instantly

• **Writing style analysis**
Analyze readability, formality, vocabulary, and writing patterns with visualizations

• **Knowledge graph**
Generate relationships between entities to better understand the document context

• **Smart rewrite engine**
Convert content into plain language, structured notes, editorial articles, or LinkedIn-ready posts

**Tech stack:**
Streamlit, LLM APIs, OCR, vector search, Plotly, PyVis

One of the biggest challenges I faced was maintaining chat memory and accurate retrieval. I experimented with multiple database approaches, but faced issues with consistency and performance.

Eventually, I implemented ChromaDB for vector storage, which significantly improved retrieval quality and made contextual conversations more reliable.

This project helped me understand concepts like Retrieval-Augmented Generation (RAG), embeddings, and handling real-world document data, including scanned PDFs using OCR.

**Live Link:**
https://querydoc.streamlit.app/

**Workflow Diagram**
<img width="4193" height="4976" alt="deepseek_mermaid_20260418_61ab6e" src="https://github.com/user-attachments/assets/fd353712-b2b4-46b6-b4e8-ff308adc64d8" />

**Component Architecture Diagram**
<img width="5098" height="3243" alt="deepseek_mermaid_20260418_0f4b4a" src="https://github.com/user-attachments/assets/e698de52-eb82-4173-92e1-82d50f310de5" />






















