# Agentic AI Workflows

Four agentic AI workflows built as graduate coursework for the M.S. in
Artificial Intelligence in Business at Arizona State University. Each
project applies a core agentic design pattern to a practical task.

Built with AI assistance (ChatGPT and Claude); I served as the human in
the loop, directing each build and verifying that generated code and
output were correct.

## Projects

**1. Tool Use & Reflection** (`01_tool_use_and_reflection.ipynb`)
An agentic workflow with a drafter–evaluator–reviser loop: the model
drafts an answer with live web search, critiques its own draft, then
revises it. Uses custom tools and OpenAI's built-in web search.

**2. Multi-LLM Planning Workflow** (`02_multi_llm_planning_workflow.ipynb`)
A 5-stage blogging workflow — Planner, Researcher, Writer, Editor,
Reviser — that adds planning as a design pattern. Mixes Groq and OpenAI
models across stages to cut inference cost where a stronger model isn't
needed.

**3. Gradio Blogging App** (`03_gradio_blogging_app.ipynb`)
The blogging workflow converted into a Gradio web application so a
non-technical user can run it from a browser.

**4. Multi-Agent Customer Service System** (`04_multi_agent_customer_service.ipynb`)
A multi-agent workflow for e-commerce returns and refunds: a guardrail
agent that blocks unauthorized data requests, a policy agent, a database
agent that queries a SQLite customer database, and a return-decision
agent. Tested against a synthetic customer database.

## Tech

Python, OpenAI API, Groq API (Llama), Gradio, SQLite, Jupyter

## Note

These are graduate coursework projects. Assignments 3 and 5 began from a
course-provided framework; the agent logic, prompts, and workflow design
within them are my work.
