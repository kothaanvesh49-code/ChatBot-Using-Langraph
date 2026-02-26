# ChatBot-Using-Langraph
This project is a simple conversational AI chatbot built using LangGraph and LangChain, designed to demonstrate how stateful LLM workflows can be implemented using graph-based architectures.  

In this project, I built a stateful conversational chatbot using LangGraph and LangChain to demonstrate how graph-based orchestration can manage LLM workflows efficiently.

First, I set up the development environment by installing required libraries and configuring API keys securely using environment variables.

Next, I defined a custom state schema to store and manage conversation history, ensuring messages persist across interactions.

I then created a StateGraph workflow, defining clear START and END nodes, and implemented a chatbot node that invokes an LLM (GPT-4o / LLaMA 3.1 via Groq) to generate responses dynamically.

After that, I connected the nodes to build the execution flow and compiled the graph into a runnable application.

Finally, I tested the chatbot with user inputs, verified state management across turns, and visualized the workflow using Mermaid diagrams to clearly represent the graph structure.

This project demonstrates my hands-on experience in LLM integration, conversational state handling, graph-based AI workflow orchestration, and building scalable AI assistants using LangGraph.
