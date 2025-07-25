# Cloud Architecture

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


                           

**Cloud Project 2: Fintech Application: Automating Fintech - Agentic AI for Cloud**

Vision: To explore and harness agentic AI in global financial markets using **cloud-native infrastructure** for real-time, intelligent fintech actions. Enabling precision and speed through scalable, autonomous decision-making.

**Cloud Requirement's:** Azure Cloud Virtual Machine 24x7, Batch, Python, Task Scheduler, Databrics, APIs, Financial Knowlegde, Virtual Currency and Risk Management.

Financial API's Requirements: IBKR Historical Data (s - subscription) , Yfinance (Open Source), Alpha Vantage (s) , Polygon.io (s) and Zerodha (s)

Application Requirement's: IBKR Workstation - Papertrading Application, Zerodha Kite

Programming Requirement's: 10 Algorithms to execute the Buy/Sell Transactions,  2 Risk Management (Stop Loss, GTT, Time Limit and PnL Portfolio), 1 for Logging,  1 for Alert and  1 Detailed Report Summary.

Exchanges: Major Exchanges (For Multi Variable - Time Series Analysis) 

Value Prop: This AI-driven recommendations empowers fintech users with real-time, automated decision-making by executing multiple transactions simultaneously, dynamically allocating assets, and providing instant backtesting for optimized performance. With adaptive strategies for both bullish and bearish markets, success probability scoring, and multi-cloud scalability, bot ensures precision, efficiency, and a competitive edge in algorithmic trading.

Architecture:

<img width="403" height="640" alt="image" src="https://github.com/user-attachments/assets/58062991-7962-4e67-add9-eb13cbc24177" />

Sample Results:

<img width="1642" height="537" alt="image" src="https://github.com/user-attachments/assets/27e2d800-2057-4e39-a3dc-21421cc0159e" />

<img width="985" height="398" alt="image" src="https://github.com/user-attachments/assets/60d79b18-b380-463a-ac31-1f6d0fe6f185" />

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


--------------------------------------------------------------------------------------------------------------------------------------------


**Cloud Cost Estimates:**

![image](https://github.com/user-attachments/assets/a806ea3a-5cc6-48a6-8140-630068053cd5)


Services: Azure Bastion is a fully managed PaaS (Platform as a Service) that provides secure remote access (RDP Remote Desktop Protocol/SSH) to virtual machines (VMs) in Azure.

Few Alternative's:

![image](https://github.com/user-attachments/assets/5e79060a-bb85-443a-a069-dddae37911bf)


-----------------------------------------------

**List of Major Cloud Services:**

![image](https://github.com/user-attachments/assets/f1f436e3-9a04-404d-9430-4789b62d8e8e)


**List of Cloud Certifications:**

![image](https://github.com/user-attachments/assets/e49f436d-6968-4a62-ae4a-5137e4397b5c)



Few Data Apps and MLops Experiements:

1.https://www.tensorflow.org/tensorboard
2. https://grafana.com/
3. https://streamlit.io/
4. https://wandb.ai/









