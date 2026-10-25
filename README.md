# Hi, I'm Ömercan

Data scientist with a focus on applied AI and generative AI solutions (M.Sc. Data Science at TU Dortmund, graduating December 2026) and an industrial engineering background. Hands-on experience building multimodal LLM pipelines (ChatGPT, Claude, Gemini), modeling knowledge graphs and automating previously manual business processes in Python in an industrial setting. Solid foundation in statistics, machine learning, Bayesian inference, simulation, optimization and software engineering, combined with a disciplined, solution-oriented and analytical way of working. Track record of leading teams and delivering results under pressure.

## Education

- **M.Sc. Data Science**, TU Dortmund University (Oct 2024 to present), GPA 1.7. Master's thesis with Wilhelm Böllhoff: *AI-Based Patent Infringement Detection Using Knowledge Graphs and Multimodal Language Models*. Coursework includes advanced statistics, simulation-based inference, neural networks, high-dimensional time series and forecasting, network theory, game theory, generalized linear models, big-data analysis, Bayesian analysis and multilevel models.
- **B.Sc. Industrial Engineering**, Boğaziçi University, Istanbul (2018 to 2024), GPA 1.7 (German scale). Coursework includes statistics, optimization, time series and forecasting, data mining and machine learning, simulation (Siman, ARENA, Python), SQL, and production and supply chain.

## Experience

- **Wilhelm Böllhoff, AI & Automation** (Mar 2026 to Dec 2026): Intern and master's thesis student in the R&D and patent department. Built AI-powered pipelines with multimodal models (ChatGPT, Claude, Gemini) and cut analysis time by at least 20 times by parallelizing the workflow and removing key bottlenecks. Connected an external API to parallel LLM queries with spreadsheet output, which reduced hours of manual search to a few minutes of input. Designed a modular Python codebase from scratch, replacing unstructured notebooks with a clean, reusable project structure in the team repository (Git), and implemented RAG and GraphRAG retrieval over knowledge graphs to structure, query and analyze patent-relevant information.
- **Hitit Computer Services, Airline IT Solutions** (Mar 2024 to Sep 2024): Business analyst. Translated airlines' operational requirements into specifications for software modules, ran system tests and contributed to RFPs and proofs of concept by defining KPIs for performance, scalability and robustness.
- **4GLOBAL PLC** (Aug 2022 to Mar 2024): Data analytics intern (remote). Ran industry analyses for 50+ European fitness operators and supported the NEOM project strategy with location intelligence from satellite and map data.
- **Geleceğin Yıldızları (Future Stars)** (May 2019 to Jul 2023): Volunteer program lead and coach. Led multinational youth summer camps with 2000+ participants and 400 staff from 10 countries.

## Projects

**Featured**

- [energiewende-agent](https://github.com/Omercan4/energiewende-agent): An LLM agent (LangGraph) that answers German energy questions with live data APIs (SMARD, Open-Meteo), a price forecast tool and RAG over 99 Bundestag documents (LlamaIndex, Chroma, filters by party and paper type). Evaluated with 35 test questions and an LLM judge, tracked in MLflow (numbers 100% correct, 94% of answers fully correct). FastAPI, Docker, GitHub Actions CI and a deployment on Azure Container Apps.
- [energy-price-forecast](https://github.com/Omercan4/energy-price-forecast): Day-ahead electricity price forecast for Germany with LightGBM quantile models and a conformal 80% prediction interval. In a 12-month rolling backtest (every month forecast by a model trained on earlier data only) the error (MAE 19.6 EUR/MWh) is 22.3% lower than the best classical baseline, Holt-Winters exponential smoothing (25.2), and 47.6% lower than the seasonal naive forecast with m=168 (37.4); the interval covers 79% of real prices. Includes anomaly detection, SHAP, MLflow, a FastAPI service and a daily GitHub Action that forecasts, scores finished days, checks input drift and updates a [live page](https://omercan4.github.io/energy-price-forecast/).

**More projects from my studies, all in [My-Projects](https://github.com/Omercan4/My-Projects)**

- [Bayesian Analysis of the World Happiness Report](https://github.com/Omercan4/My-Projects/tree/main/Master%20Projects/Bayesian%20Analysis%20of%20World%20Happiness%20Report): Bayesian multilevel models (Stan, R) for the drivers of life satisfaction, with quantified uncertainty and interpreted effect sizes.
- [Spotify Recommendation Algorithm Analysis](https://github.com/Omercan4/My-Projects/tree/main/Master%20Projects/Spotify%20Recommendation%20Algorithm%20Analysis): Sensitivity of Spotify's recommender via a full-factorial design with 90 user profiles, using cosine similarity, ANOVA and t-tests.
- [Graduation Project: Conversational Schedule Explainer](https://github.com/Omercan4/My-Projects/tree/main/Bachelor%20Projects/Graduation%20Project%20-%20Conversational%20Schedule%20Explainer%20using%20ChatGPT%20API): A Streamlit chat assistant (OpenAI function calling, GPT-3.5) that routes natural-language requests to Python tools for schedule queries, shift swaps, feasibility checks and rescheduling, built on Gurobi optimization models. Agent-style tool use in 2023/24, shortly after OpenAI introduced function calling.
- [Forecasting Gasoline Prices](https://github.com/Omercan4/My-Projects/tree/main/Bachelor%20Projects/Forecasting%20Gasoline%20Prices%20using%20Time%20Series%20and%20Regression): Time series and regression models for price forecasting.
- [Customer Segmentation Analysis](https://github.com/Omercan4/My-Projects/tree/main/Bachelor%20Projects/Customer%20Segmentation%20Analysis%20for%20East-West%20Airlines): Segmenting airline customers with machine learning methods.
- [All Bachelor projects](https://github.com/Omercan4/My-Projects/tree/main/Bachelor%20Projects) and [all Master projects](https://github.com/Omercan4/My-Projects/tree/main/Master%20Projects)

My master's thesis tool is an internal project, so the code is not public.

## Skills

- **Generative AI and LLMs:** multimodal models (ChatGPT, Claude, Gemini), RAG, GraphRAG, prompt engineering, API integration, knowledge graphs, agents (LangGraph)
- **Programming:** Python (NumPy, pandas, scikit-learn), R, SQL, C/C++; modular codebases and Git
- **Machine learning and statistics:** regression, classification, neural networks, Bayesian inference (Stan), time series and forecasting, gradient boosting (LightGBM), prediction intervals, anomaly detection, simulation-based inference, process automation
- **Tools and deployment:** FastAPI, MLflow, Docker, GitHub Actions, Azure, Databricks (introductory), simulation (SimPy, ARENA), LaTeX, Microsoft Office

## Languages

German (C1), English (C1), Turkish (native)

## Find me

[LinkedIn](https://www.linkedin.com/in/omercanmisirlioglu4) · [GitHub](https://github.com/Omercan4)
