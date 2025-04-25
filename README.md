Lately retrieval-augmented generation (RAG) systems have been commonly used to answer questions by using context from important documents. These systems are great, but they usually fail in their ability to carry out multi-step, dynamic tasks or to adapt to new information on the fly. That’s where AI agents come into play.

Agents expand upon RAG systems. They hold state between interactions, reason over actions, and utilize tools to help accomplish tasks. Recently, I had the opportunity to look into LangGraph, a framework for constructing structured, tool-augment agents that builds off the LangChain framework. I built a minimal Research Agent as a quick weekend experiment that can do the following:

- Take natural language research questions
- Automatically query arXiv for relevant papers
- Summarize the findings using an LLM served via the Groq API

Read the complete Article here: https://medium.com/@ayeshaazam998/building-agentic-workflow-for-research-literature-using-langgraph-1115b513b5af
