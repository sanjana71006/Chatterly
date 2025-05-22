🧠 Chatterly – A Graph-Based Conversational AI System
Chatterly is an experimental, modular chatbot framework built using LangGraph, integrating the power of both Anthropic’s Claude 3.5 Sonnet and Google’s Gemini 2.0 Flash models via the LangChain ecosystem.
At its core, Chatterly models the conversation as a stateful computation graph where each message updates the shared conversation state. Using typed state annotations and LangGraph’s visual and logical structure, it allows you to easily trace, extend, and experiment with the flow of a chatbot’s behavior.

✨ Features
StateGraph Architecture: Modular graph flow using StateGraph from LangGraph to manage and route chatbot logic.
Multi-LLM Support: Easily switch between or combine models like Claude 3.5 and Gemini Flash for comparative research or ensemble behavior.
Stateless Functions with Stateful Behavior: Defines chatbot as pure functions working over typed State, enabling easy testing and debugging.
Message Aggregation: Uses add_messages utility to accumulate chat history across function calls.
Graph Visualization: Visualizes the conversation flow for better understanding and debugging.
API Key Usage: Built-in environment variable management for LLM API keys (Claude, Gemini).

🛠️ Tech Stack
LangGraph – for graph-based computation
LangChain – for LLM integrations
Claude 3.5 and Gemini 2.0 – backend models
Python, Jupyter Notebook
