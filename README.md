# Self-Improving AI Agent (LangChain + Memory)

This project implements a simple **self-improving AI agent** using LangChain.
The agent learns from previous interactions by:
1. Storing conversation history.
2. Reflecting on past messages to generate improvement insights.
3. Updating its behavior based on those insights.
4. Producing improved responses over time.

### Key Features
- Conversational memory using `ChatMessageHistory`
- Reflection and learning loops (Reflect → Learn → Improve)
- Runnable chains with message history (`RunnableWithMessageHistory`)
- Modular design: respond(), reflect(), learn()

### Tech Stack
- **LangChain**
- **OpenAI Chat Models**
- **Prompt Chaining**
- **Runnable History Pipeline**

### How It Works
The agent runs in cycles:
1. User interacts with the agent.
2. Agent reflects on the full chat log.
3. Agent generates insights to improve.
4. Agent updates its internal behavior before the next reply.

### Note
Running this project requires OpenAI API keys.  
The code is fully implemented but cannot be executed without valid API credits.
