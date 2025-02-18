# Hugging Face AI Agents Course (Student Notebooks)

![](images/HF-Class.png)

Welcome to this public repository, where I document my journey through the [Hugging Face 🤗 AI Agents Course](https://huggingface.co/learn/agents-course/). As a student, I learn best by building, so I decided to create a series of Jupyter notebooks to explore and share key concepts around AI agents and LLMs for each unit. For example, models like [SmolLM2](https://huggingface.co/HuggingFaceTB/SmolLM2-1.7B-Instruct) are used throughout this course, and I wanted to break things down from the basics of efficiently loading these models, predicting next tokens, and working with tool-calling and ReAct agentic patterns to ultimately building AI agents. And this is just the beginning! there’s much more to come!

## Follow Along! 👀

I'm constantly iterating on these notebooks, refining ideas, and adding new insights. If you're also taking the AI Agents Course (or just curious about SmolLM2 and AI agents), feel free to watch this repo and reach out if you have any questions or ideas.

| Notebooks | Unit Name | Description |
| --- | --- | --- |
| [Unit 1](unit1/README.md) | Introduction to Agents | Explain Tools, Thoughts, Actions, Observations, and their formats. Explain LLMs, messages, special tokens and chat templates. Show a simple use case using python functions as tools. |

## Set Up Your Development Environment

Follow these steps to get started with the project:

1. **Clone Repo**:

```bash
git clone https://github.com/Cyb3rWard0g/HF-Agents-Course-Notes
cd HF-Agents-Course-Notes
```

2. Set Up a Virtual Environment (optional but recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install python packages

```bash
pip install -r requirements.txt
```