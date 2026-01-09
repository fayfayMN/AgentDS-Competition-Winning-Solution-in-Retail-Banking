---
license: cc-by-nc-sa-4.0
task_categories:
- tabular-classification
- feature-extraction
- text-classification
language:
- en
tags:
- agentic-ai
- synthetic-data
- data-science
- benchmark
- human-AI-collaboration
pretty_name: AgentDS-RetailBanking
---

# 🏦 AgentDS-RetailBanking
link: https://huggingface.co/datasets/lainmn/AgentDS-RetailBanking
This dataset is part of the **AgentDS Benchmark** — a multi-domain benchmark for evaluating human-AI collaboration in real-world, domain-specific data science.

**AgentDS-RetailBanking** includes structured transactional data for 2 challenges:

- Credit default prediction  
- Transaction-level fraud detection  

👉 Files are organized in the `RetailBanking/` folder and reused across challenges.  
Refer to the included `description.md` for:
- File usage and challenge mappings  
- Task descriptions and data schema notes  
- Submission format expectations  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧩 Project Context: AgentDS Benchmark
This project is inspired by the AgentDS benchmark competition, which explores how humans and AI agents can collaborate to solve real-world data science problems using messy, imperfect datasets across multiple domains.
The goal of this notebook is not to optimize a single metric, but to demonstrate:
Practical problem framing
Human–AI decision-making workflows
Responsible use of AI agents
Clear communication of insights and limitations


🎯 Problem Framing
The dataset reflects a real-world scenario where the problem is not fully specified upfront.
As a human analyst, the initial objectives were:
Understand the data structure and quality
Identify meaningful questions that the data can reasonably answer
Decide where AI assistance would add value and where human judgment is required


📊 Dataset & Domain Context
This dataset comes from the AgentDS benchmark, which includes challenges across domains such as:
Commerce
Retail banking
Insurance
Healthcare
Manufacturing
Food production
The data reflects real operational constraints, including missing values, noisy records, and heterogeneous feature formats.


🤝 Human–AI Collaboration Strategy
In this project, AI agents were used as assistive tools rather than decision-makers.
AI-assisted tasks:
Generating initial hypotheses
Suggesting feature transformations
Providing alternative modeling ideas
Human-led decisions:
Defining the analytical objective
Evaluating data quality issues
Selecting appropriate preprocessing strategies
Interpreting results and identifying limitations
This division ensured that AI enhanced productivity while humans retained accountability and judgment


🧹 Data Cleaning & Preparation
Data cleaning required trade-offs rather than fixed rules.
Key considerations included:
Whether to impute or retain missing values depending on context
Avoiding aggressive filtering that could remove informative edge cases
Preserving interpretability for downstream analysis
All preprocessing choices were evaluated for their impact on both data integrity and analytical goals.


🔍 Exploratory Data Analysis
EDA was used as a sense-making process to:
Identify dominant patterns
Detect anomalies or unexpected behavior
Validate or reject initial hypotheses
Findings from EDA informed subsequent modeling and feature selection decisions.


🤖 Modeling Approach
Given the real-world nature of the data, modeling prioritized:
Robustness over complexity
Interpretability over marginal performance gains
Baseline models were used to establish expectations, with incremental improvements evaluated carefully to avoid overfitting or false confidence.


📈 Results & Insights
Key insights from the analysis include:
Certain features consistently influenced outcomes across models
Data quality constraints significantly affected performance
Some intuitive assumptions were not supported by the data
These results emphasize the importance of critical interpretation in applied data science.

⚠️ Limitations
This analysis is subject to several limitations:
Limited sample size and scope
Potential biases in real-world data collection
Simplifying assumptions during modeling
Recognizing these limitations is essential for responsible deployment and decision-making.


🧠 Reflection: Human–AI Collaboration
This project demonstrates that effective human–AI collaboration is not about automation, but about augmentation.
AI agents accelerated exploration and ideation, while human judgment guided:
Problem framing
Ethical considerations
Interpretation of uncertainty
This balance is critical for real-world data science applications.


🚀 Next Steps
Future improvements could include:
Domain-informed feature engineering
Integration of additional data sources
More rigorous validation strategies
Deeper experimentation with agent orchestration      
