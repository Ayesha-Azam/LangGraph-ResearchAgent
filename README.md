![ChatGPT Image Apr 20, 2025, 11_03_33 PM](https://github.com/user-attachments/assets/b7c0e574-67b0-436a-bf20-58a2391fac9c)Lately retrieval-augmented generation (RAG) systems have been commonly used to answer questions by using context from important documents. These systems are great, but they usually fail in their ability to carry out multi-step, dynamic tasks or to adapt to new information on the fly. That’s where AI agents come into play.

Agents expand upon RAG systems. They hold state between interactions, reason over actions, and utilize tools to help accomplish tasks. Recently, I had the opportunity to look into LangGraph, a framework for constructing structured, tool-augment agents that builds off the LangChain framework. I built a minimal Research Agent as a quick weekend experiment that can do the following:

- Take natural language research questions
- Automatically query arXiv for relevant papers
- Summarize the findings using an LLM served via the Groq API

 ![Screenshot 2025-04-17 165309](https://github.com/user-attachments/assets/6ee7f51d-8989-4b75-af2c-5a75b99ea25b)


Read the complete Article here: https://medium.com/@ayeshaazam998/building-agentic-workflow-for-research-literature-using-langgraph-1115b513b5af
