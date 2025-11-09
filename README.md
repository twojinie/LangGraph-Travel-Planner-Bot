## ✈️ LangGraph-Travel-Planner-Bot

### 📌 Overview
This project is based on the DACON course *“Designing Conversational AI Systems with LangGraph.”*  
It walks through the step-by-step process of designing an interactive **travel planning chatbot** powered by LLMs (Large Language Models) and LangGraph’s graph-based workflow.

By the end of the course, the chatbot can handle natural language travel requests like  
> “Recommend tourist attractions in Paris for a 3-day trip.”
> 
and autonomously call tools (e.g., flight search, itinerary planner) through LangGraph’s tool invocation mechanism.

--- 

### Methodology
#### 1️⃣ Understanding LangGraph
**Core Concepts:** `State`, `Node`, `Edge`, `Graph-based Workflow`, `LLM Orchestration`  
Understand why LangGraph emerged and how it extends LangChain for complex, multi-step reasoning.

#### 2️⃣ Handling Messages and States
**Core Concepts:** `HumanMessage`, `AIMessage`, `SystemMessage`, `Conversation Memory`, `State Object`  
Learn how to accumulate and manage dialogue history to maintain conversational context.

#### 3️⃣ Building State-Based Conversation Flows
**Core Concepts:** `StateGraph`, `MessagesState`, `Node Execution`, `Message Accumulation`  
Design modular conversational flows that automatically track and update dialogue states.

#### 4️⃣ Integrating Tool Calls
**Core Concepts:** `@tool Decorator`, `ToolNode`, `LLM + Tool Integration`, `External API Invocation`  
Enable LLMs to autonomously select and execute external tools within the graph.

#### 5️⃣ Conditional Flow + Automated Tools
**Core Concepts:** `Conditional Branching`, `tools_condition`, `LLM-based Decision`, `Dynamic Workflow`  
Build adaptive flows where LLMs decide whether to invoke tools based on user intent or conversation state.

#### 6️⃣ Building the Final Travel Planner
**Core Concepts:** `Multi-turn Dialogue`, `AssistantNode`, `Tool Coordination`, `Automated Travel Workflow`  
Combine conversation management, conditional logic, and tool execution to create a fully automated travel-planning chatbot.
