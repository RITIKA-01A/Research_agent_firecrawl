# 🧠 Developer Tool Research Agent

An intelligent multi-step AI agent that finds, analyzes, and recommends the best developer tools for any technical query using **LLMs**, **Firecrawl**, and **LangGraph**.

---

## 🚀 Overview

This project uses a structured AI workflow to:
- 🔍 Search the web for relevant developer tools
- 📄 Scrape and summarize web content using Firecrawl
- 🧠 Extract tool names and technical details via LLMs
- 💡 Recommend the best options with reasoning

Built using:
- 🧩 LangGraph (multi-step workflow orchestration)
- 🔗 LangChain + OpenAI/Groq models
- 🔥 Firecrawl (search & scraping)
- 🧾 Structured output via Pydantic
- 🧠 Custom LLM prompts for tool extraction and analysis

---

## 📦 Features

- ✅ Automatic search & scraping of top articles
- ✅ Extracts tool names from content using LLM
- ✅ Analyzes each tool's pricing, tech stack, integrations, etc.
- ✅ Generates recommendations based on developer needs
- ✅ Fully modular and extendable

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| AI Models | `Groq LLaMA3`, or any LangChain-compatible LLM |
| Workflow | [LangGraph](https://github.com/langchain-ai/langgraph) |
| Scraping | [Firecrawl API](https://firecrawl.dev) |
| Prompts | Custom prompt engineering for tool extraction/analysis |
| Output Structuring | [Pydantic](https://docs.pydantic.dev) models |
| CLI Entry | Python function: `Workflow.run(query: str)`

---



