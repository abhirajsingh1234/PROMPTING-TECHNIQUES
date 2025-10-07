# PROMPTING-TECHNIQUES
This notebook explores and compares prompting techniques—Chain of Thought, Tree of Thought, ReAct, and Self-Consistency—on identical tasks. It evaluates how each method influences LLM output, reasoning, and accuracy in a controlled experimental setup.

# 🧠 Prompting Techniques Comparison in LLMs

This project is a Jupyter Notebook-based experiment designed to compare the performance of different prompting strategies used with large language models (LLMs). By applying the same task input to each technique, we analyze how their reasoning paths and outputs differ.

## 📌 Project Purpose

The goal is to understand how various prompting approaches influence the model’s reasoning and output quality. This is useful for anyone exploring prompt engineering, LLM behavior, or designing better AI agents.

## 🚀 Techniques Compared

The following prompting techniques are explored:

- **Chain of Thought (CoT):** Encourages the model to think step-by-step.
- **Tree of Thought (ToT):** Explores multiple reasoning paths like a tree.
- **ReAct:** Combines reasoning and acting, simulating interaction with tools.
- **Self-Consistency:** Generates multiple outputs using CoT and selects the most consistent answer.

Each technique is tested on the same task to allow clear comparison.

## 📓 How It Works

- The notebook defines a single input task (e.g., extracting human messages with numbers).
- Each technique is applied in a separate section.
- Outputs are displayed and can be compared side by side.
- Observations about differences in logic, clarity, and completeness are noted.

## 📊 Evaluation Criteria

Outputs are assessed based on:

- Accuracy
- Completeness
- Reasoning transparency
- Output structure
- Consistency across runs

## 🧪 Example Task

> "Extract all human messages that contain numbers from the conversation log below."

All prompting strategies are given the same data and task prompt.

## 🛠 Requirements

The project uses standard tools like:

- Jupyter Notebook
- Python 3.x
- (Optional) OpenAI API or similar LLM access
- (Optional) LangChain, pandas for data handling

## 📁 Project Layout

- **main_notebook.ipynb** — Contains the entire experiment.
- **README.md** — Project overview.
- **DESCRIPTION.md** — Detailed explanation of methods (300 lines of documentation).

## 👨‍🔬 Who It's For

- Prompt engineers
- AI/ML students
- Researchers in NLP
- Developers building reasoning agents

## 📄 License

This project is released under the MIT License.

---

Made with curiosity and care ✨
