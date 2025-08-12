# AI Agents

**Agentic AI**: To achieve certain bigger goals using the collection of AI Agents. (Agentic AI = AI Agents + advanced autonomy + planning + tool use + memory + reasoning)

**AI Agents**: To achieve certain goals. (perceives -> decide -> and then act) [Examples: Simple Chatbots, Q&A Bots etc]


**Layers of Agentic AI:**

Layer 1 – Data Ingestion: Purpose: Gather raw data from multiple sources, clean it, and prepare it for processing.

Tools: Airbyte, AWS Glue, Fivetran, Apache NiFi.

Layer 2 – Index & Vectorization: Purpose: Convert data into embeddings (mathematical vectors) so the system can search and understand by meaning, not just keywords.

Tools: Pinecone, Weaviate, Milvus, Qdrant.

Layer 3 – Retrieval: Purpose: **Fetch the most relevant data** from the knowledge base when a query is asked.

Tools: Vespa, Elasticsearch, FAISS, OpenSearch.

Layer 4 – Reasoning & Planning: Purpose: Decide how to solve the problem—whether to retrieve more data, use a tool, or plan a sequence of actions.

Tools: Crew AI, LangGraph, AutoGen, Baby AGI.

Layer 5 – Augmentation & Context Fusion: Purpose: Merge retrieved data with the model’s own reasoning to make the answer richer, more accurate, and contextually correct.

Tools: LlamaIndex Context Fusion, LangChain, RAGAS, Haystack Pipeline.

Layer 6 – Generation: Purpose: Produce the final answer (**text, code, summary, table**) using all gathered and processed info.

Tools: **GPT-4o**, Claude, Mistral Large, LLaMA 3.

Layer 7 – Action & Feedback: Purpose: Execute the answer (**send reports**, trigger automation, or request feedback to improve).

Tools: Zapier, Hugging Face Agents, AWS Lambda, **Weights & Biases**.


Top frameworks for AI agent development:

        		A. LangChain – LLM-based agents with tools, memory, and chains
        		B. AutoGen (Microsoft) – Multi-agent orchestration and conversation with tool use
        		C. OpenAI Gym / Gymnasium – Standard RL environments for training agents
        		D. Hugging Face Transformers + Agents – Pretrained LLMs with built-in tools and agent API
        		E. Unity ML-Agents Toolkit – 3D simulation and training for embodied/robotic agents
        		F. Haystack (deepset) – Retrieval-Augmented Generation (RAG) pipelines for knowledge agents
        		G. RLlib (Ray) – Scalable reinforcement learning, supports multi-agent training
        		H. CrewAI – LLM-based agent teamwork with role delegation and task collaboration


List of AI Agents Protocol's:

                1. Model Context Protocol (MCP), 
                2. Agent-to-Agent (A2A) communication, and
                3. Agent Network Communication (ANC)


---------------------------

**Cloud Project 1: Healthcare Application: Health & Wellness AI Agentic System** 

Use cases: Wellness, fitness apps, health nudging. Simple AI tool, Just curates and simplifies and provide assistance. 

It's a guidance/recommendation system on a fitness, provides personalized lifestyle guidance (e.g., diet, sleep, hydration, exercise) based on user input and wearable data. To provide simple assitance like a chatbots. 

Tech: LLM + rule-based logic + wearable APIs.

![image](https://github.com/user-attachments/assets/c65a7476-f97a-4202-ab1a-7e54acb6b420)


**Backend / AI:**
A. Python (FastAPI or Flask) for APIs

B. LLM integration: GPT-4, Claude, or open-source (e.g., LLaMA) via prompt templates

C. NLP/NLU: spaCy, Rasa NLU (for intent detection)

Optional AI hosting: Hugging Face Inference API or OpenAI API


**Tech Stack Using NVIDIA Ecosystem:**

1. LLM Inference: Use NVIDIA NIM or TensorRT-LLM for fast, GPU-optimized large language models.

2. Model Serving: Deploy models via NVIDIA Triton Inference Server.

3. NLP/Intent Detection: Leverage NVIDIA NeMo for prebuilt NLP models and training pipelines.

4. Backend: FastAPI (Python) for handling user interactions and routing to AI components.

5. Wearable Integration: Collect and process user health data from APIs like Fitbit or Apple Health.

6. Scheduling & Reminders: Use Celery with Redis for nudges and task queues.

7. Cloud Deployment: Run on AWS/GCP using NVIDIA GPU instances (A100/V100).

8. Containerization: Docker + NGC containers for scalable, reproducible deployments.

9. Monitoring: Use NVIDIA tools or Prometheus/Grafana for performance and inference tracking.


                          
----------------------------------------


                           

**Cloud Project 2: Fintech Application: Automating Fintech - Agentic AI for Cloud** [Completed Version - Agent 2]

Vision: To explore and harness agentic AI in global financial markets using **cloud-native infrastructure** for real-time, intelligent fintech actions. Enabling precision and speed through scalable, autonomous decision-making.

**Cloud Requirement's:** Azure Cloud Virtual Machine 24x7, Batch, Python, Task Scheduler, Databrics, APIs, Financial Knowlegde, Virtual Currency and Risk Management.

Financial API's Requirements: IBKR Historical Data (s - subscription) , Yfinance (Open Source), Alpha Vantage (s) , Polygon.io (s) and Zerodha (s)

Application Requirement's: IBKR Workstation - Papertrading Application, Zerodha Kite

Programming Requirement's: 10 Algorithms to execute the Buy/Sell Transactions,  2 Risk Management (Stop Loss, GTT, Time Limit and PnL Portfolio), 1 for Logging,  1 for Alert and  1 Detailed Report Summary.

Exchanges: Major Exchanges (For Multi Variable - Time Series Analysis) 

Value Prop: This AI-driven recommendations empowers fintech users with real-time, automated decision-making by executing multiple transactions simultaneously, dynamically allocating assets, and providing instant backtesting for optimized performance. With adaptive strategies for both bullish and bearish markets, success probability scoring, and multi-cloud scalability, bot ensures precision, efficiency, and a competitive edge in algorithmic trading.

Architecture: (Linear Execution Top to Bottom)

<img width="403" height="640" alt="image" src="https://github.com/user-attachments/assets/58062991-7962-4e67-add9-eb13cbc24177" />

Architecture: (Autonomous Execution)

<img width="817" height="530" alt="image" src="https://github.com/user-attachments/assets/1988cad5-78fb-4fde-83ed-53b4d0af624c" />

Detailed:

<img width="793" height="531" alt="image" src="https://github.com/user-attachments/assets/90015ded-1576-4a3d-a7f4-97324ca75164" />



Sample Live Results:

<img width="1642" height="537" alt="image" src="https://github.com/user-attachments/assets/27e2d800-2057-4e39-a3dc-21421cc0159e" />

<img width="1150" height="601" alt="image" src="https://github.com/user-attachments/assets/a2458510-78dd-417d-b554-75afa02d8e16" />


Conditions Optimization (Grid Search):

<img width="532" height="351" alt="image" src="https://github.com/user-attachments/assets/8744ecb0-e70a-4656-9618-47f22ec4944f" />


----------------------------------------





**Cloud Project 3: Climate Science / Earth System Science Application: Design and Development of AI-Agent Systems for Climate Change Modeling and Policy Simulation** 

**Description:** This system provides AI-driven modeling of **climate change impacts**, capturing complex interactions across Earth systems. It enables simulation of mitigation and adaptation strategies under different climate scenarios. The goal is to support faster, more informed climate decisions through scalable, intelligent modeling.

A. GPU/TPU Compute: Use cloud platforms (AWS, GCP, Azure) with GPU/TPU instances for training and simulation.

B. Scalable Storage: Store large climate datasets using S3 or GCS with DVC for version control.

C. Distributed Processing: Use Dask or Spark for efficient data preprocessing and simulation scaling.

D. Experiment Tracking: Track models with MLflow or Weights & Biases for reproducibility.

E. Containerization: Use Docker and Kubernetes for agent deployment and orchestration.

F. Data Access APIs: Integrate remote datasets via OPeNDAP, RESTful APIs, or Earthdata.

G. Cloud-Native Architecture: Design with microservices and auto-scaling for flexibility.

H. CI/CD Pipelines: Automate testing and deployment using GitHub Actions or GitLab CI.

I. Security & IAM: Enforce access controls, encryption, and audit logging.

J. Visualization: Dashboards with Streamlit or Grafana for insights and monitoring.


-----------------------------

**Other Industrial Applications and Use Cases of Agentic AI (To be in Watchlist for 2025):**

**1. Predictive Maintenance Agent:** (A commercially viable solution)

Consumes sensor logs from turbines, transformers, or imaging CT/MRI healthcare machines. Predicts failure using temporal models (e.g., transformer oil analytics + vibration + image logs + Sensor + temperature). Alert customers and field on time without any human interventions involved. 

**2. Digital Twin Control Agent** (Concept of digital twins has already seen heavy investment and mainstream adoption in the past, this agent focuses on a fresh angle: **simulating what-if scenarios**)

Simulates physical assets (gas turbines, wind farms, healthcare equipments) to test **what-if scenarios** for performance tuning, lifetime extension, or policy compliance. Auto identify the root casue and fix the product issues. 

Data Readiness & QA Agent: Evaluates data pipelines, spots data drift, missingness, schema violations, and alerts teams before models fail downstream.

**3. Auto-Dashboarding Agent** (Under-estimated Idea, but has great potential in Business Intelligence World, if successful it will be helpful for atleast 1M+ BI developers and users in the below pyramid)

Connects to Snowflake/Databricks/DataLake, builds dynamic BI dashboards with natural language prompts, including forecasting and anomaly explanations. And, do a better predictions/forecasting for commercial team.

**4. Investment Research Agent: Autonomous Decision-Makers & Planners**

Analyzes real-time data, economic indicators, and sentiment for portfolio suggestions. Autonomous Decision-Makers & Planners. Simulates a person’s decision-making for training or automation (e.g., for CEOs, investors).

-------------------------


**Sample Cloud Cost Estimates:**

![image](https://github.com/user-attachments/assets/a806ea3a-5cc6-48a6-8140-630068053cd5)


Services: Azure Bastion is a fully managed PaaS (Platform as a Service) that provides secure remote access (RDP Remote Desktop Protocol/SSH) to virtual machines (VMs) in Azure.

Few Alternative's:

![image](https://github.com/user-attachments/assets/5e79060a-bb85-443a-a069-dddae37911bf)


-----------------------------------------------


**Global agentic AI market:** (CAGR Rough Estimates)

It is expected that over 5-10 years, the CAGR growth to be between 35 to 45% [extremely high expected growth rates], for LLM market is expected to be between ~30–37% range for the same duration. 

<img width="607" height="250" alt="image" src="https://github.com/user-attachments/assets/d5f34e78-9fd5-4a8c-98c2-0385572d81ce" />


**The Real Builders Behind Agentic AI’s Predicted Exponential Growth: 40%+ CAGR**

<img width="660" height="275" alt="image" src="https://github.com/user-attachments/assets/ad9159bf-5313-42d1-83dc-08a25b39f016" />

(Sample estimations)

---------------------------


**List of Major Cloud Services:**

![image](https://github.com/user-attachments/assets/f1f436e3-9a04-404d-9430-4789b62d8e8e)


**List of Cloud Certifications:**

![image](https://github.com/user-attachments/assets/e49f436d-6968-4a62-ae4a-5137e4397b5c)


------------------------


