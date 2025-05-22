# Agentic AI Intro using LangGraph

This is a **very basic introduction to Agentic AI**, aimed at helping you understand the foundational concepts and practical tools used to build agents that can reason and act on our behalf.

We are currently experimenting with a agent workflow tools: **LangChain** (specifically its graph-based framework, [**LangGraph**](https://langchain-ai.github.io/langgraph/)). However, the concepts here are **not limited to LangChain** — there are other  frameworks out there, such as:

- [CrewAI](https://docs.crewai.com/)
- [AutoGen](https://microsoft.github.io/autogen/)
- [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent)
- [OpenAI Agents SDK](https://platform.openai.com/docs/guides/agents)

This is not intended to be a complete or exhaustive guide. There is a lot happening in the Agentic AI space, with many powerful tools and evolving best practices. What we present here is just a starting point. There’s much more to explore beyond this intro — including topics like memory management, human-in-the-loop, and Model Context Protocol (MCPs)

## Learning Flow

### 1. Agentic AI Basics

We begin with the **core concepts of Agentic AI**, using a foundational source from **Anthropic** that explains the structure and goals of agents — how they plan, reason, take actions, and interact with tools.

[Article source](https://www.anthropic.com/engineering/building-effective-agents)

### 2. LangGraph Essentials

Next, we cover the **LangGraph**, a framework for building composable, reactive agents using LangChain. 

Through basic, hands-on examples, we explore how to:

- [Build a state graph](./intro-langgraph-1.ipynb)
- [Handle message flow](./intro-langgraph-2.ipynb)
- [Incorporate tools](./intro-langgraph-3.ipynb)

To be able to run the examples, you should:
- clone this repository
- add the required keys in the `.env` file.
- create a virtual environment (e.g `python -m venv env`)
- activate the virtual environment using the `activate` script
- install the packages present in the requirements file (e.g. `pip install -r requirements.txt`)
- opening the notebooks using your preferred IDE (e.g. vscode, pycharm, vi)

### 3. Exercise – Trello Task Manager Agent

In the exercise, we create a [**task management agent**](./intro-langgraph-4.ipynb) that can:

- View tasks from a Trello board
- Add new tasks
- Mark tasks as done

We give the agent a set of tools and let it decide what actions to take based on the user's intent. 

Happy experimenting!

### 4. Additional resources:

https://www.cohorte.co/blog/unleashing-the-power-of-langgraph-an-introduction-to-the-future-of-ai-workflows
https://www.ionio.ai/blog/a-comprehensive-guide-about-langgraph-code-included
https://anderfernandez.com/en/blog/agent-systems-with-langgraph/


