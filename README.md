<h1 align="center">Hi 👋, I'm Siddharth Hiraou</h1>
<h3 align="center">AI/ML Engineer | Building production LLM systems | MS Data Science, University at Buffalo</h3>

<img align="right" alt="Coding" width="400" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTZlYjZkYzA4YzhmMzk2MTc4ZDBkYTYzNGEyZTliMmE4MTE5MzFhYiZjdD1n/qgQUggAC3Pfv687qPC/giphy.gif">

- ⚙️ Recent work: multi-agent systems with CrewAI, OCR/document extraction pipelines with AWS Textract, and Claude-powered agent architectures
- 🎓 **MS in Data Science**, University at Buffalo (Dec 2025)
- 🏆 AWS Certified AI Practitioner | Google Cloud Certified
- 🌱 Currently exploring **Kafka** and agentic AI system design
- 💬 Ask me about **LLM agents, AWS, Python, data engineering, or signal processing (CNNs on sensor data)**
- 📫 Reach me at **sidhiraou@gmail.com**
- 🌐 Portfolio: **siddharth-portfolio-smoky.vercel.app**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/siddharth-hiraou/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left">
<a href="https://aws.amazon.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/></a>
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://cloud.google.com" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/></a>
<a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/></a>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/></a>
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/></a>
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/></a>
<a href="https://opencv.org/" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/></a>
<a href="https://www.linux.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/></a>
<a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>
</p>

<h2 align="left">Featured Work:</h2>


**Smart Chicken Disease Detection and Farm Management Solution**

Venky's Kitchen and Farm
Real-time poultry health platform flagging sick, dead, and abnormally behaving birds from shed camera feeds within seconds. Two-stage CV pipeline (YOLOv8 detection → fine-tuned disease classifier for coccidiosis, Newcastle disease, and salmonella indicators) served via Dockerized FastAPI on edge hardware. Automated climate control through an MQTT rules engine with full command audit trail, plus a Next.js/Supabase ops dashboard with realtime alerting, health scoring, RBAC, and client-side face check-in.
`Python` `YOLOv8` `PyTorch` `OpenCV` `FastAPI` `MQTT` `Docker` `Next.js` `Supabase/PostgreSQL` `Edge AI` `IoT`

🔗 [Demo](https://smart-poultry-platform.vercel.app/)


**AutoETL** 

Natural language to executable ETL pipelines
Converts plain-English prompts into ETL pipelines using an "LLM plans, engine executes" design — the model emits a schema-validated JSON DAG, never code. Custom Python DAG executor (Polars, DuckDB) with topological ordering, per-node retries, and live status streaming over Redis pub/sub and SSE. Hardened end to end with dual validation (Zod + Pydantic), a sandboxed AST expression compiler, AES-256-GCM encrypted credentials, and Postgres RLS. Cost-aware LLM routing sends simple prompts to a small model and complex joins to a stronger one. Backed by 52 tests.
`TypeScript` `Next.js 15` `React Flow` `Python` `FastAPI` `Polars` `DuckDB` `Redis` `Supabase` `Zod/Pydantic` `LLM APIs` `Docker`

🔗 [Demo](https://autoetl-mu.vercel.app/)
