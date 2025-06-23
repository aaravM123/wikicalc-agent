
# 🧠 WikiCalc: GPT-Powered Research + Math Agent

This assistant uses LangChain and OpenAI to:
- Answer questions by searching Wikipedia
- Do basic math with reasoning (like 42 * 3 - countries in South America)

## Example Prompts
- “What is the average lifespan of a dolphin plus 50 divided by 2?”
- “What is 42 * 3 minus the number of countries in South America?”

## Features
- 📚 Wikipedia search using LangChain tools
- 🧮 Custom calculator with safe `eval()`
- 🧠 Agent-based multi-step reasoning (ZERO_SHOT_REACT_DESCRIPTION)

## Run Instructions
```bash
pip install langchain langchain-openai langchain-community wikipedia
