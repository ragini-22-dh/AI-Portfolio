##  Ragini Honnaiah — AI Portfolio  

**AI Engineer | AI Agent Developer**  
📍 Byron, MN | ✉️ raginidh22@gmail.com  

This repository showcases my work in building intelligent AI systems, LLM-based agents, Retrieval-Augmented Generation (RAG) applications, and full-stack AI solutions. My focus is on designing production-ready AI applications that integrate large language models with real-world data, tools, and automation.

---

##  Technical Skills  

**Programming:**  
- Python, TypeScript, JavaScript, Bash, YAML, JSON  

**Artificial Intelligence:**  
- LLMs, OpenAI API, Prompt Engineering  
- LangChain, RAG, Hugging Face  
- AI Agents, Function Calling  

**Databases:**  
- MySQL, PostgreSQL, SQL Server, Prisma ORM  

**Machine Learning Libraries:**  
- TensorFlow, PyTorch, Keras  
- NumPy, Pandas, Matplotlib  

**Cloud & DevOps:**  
- AWS (EC2, S3, RDS)  
- Docker, Jenkins, CI/CD, Kubernetes  
- GitHub, Render  

**Frontend:**  
- HTML, CSS, React + Vite, Vercel  

**Backend:**  
- NestJS (Controllers, Services, Modules, Dependency Injection)  

---

#  Featured Projects  

---

## 1 AI-Powered Multi-Agent Logistics Tracking System**  
**Live Demo:**(https://youtu.be/Dm0pFj8i_eA?si=wJCwhhXo8fvy8nMD)

###  Overview  
A full-stack AI logistics platform that allows users to track shipments and interact with an AI assistant in real time.

### 🛠 Tech Stack  
NestJS | PostgreSQL | Prisma | OpenAI API | React + Vite | Render | Vercel  

###  Key Features  
- Real-time shipment tracking  
- AI-powered chat & voice assistant  
- REST API backend with NestJS  
- Secure database with PostgreSQL + Prisma  
- Deployed on Render (backend) and Vercel (frontend)  

---

## 2 Personal AI Assistant using LangChain**  
**Live Demo:**(https://youtu.be/MTTbw3yttlY)

### Overview  
An intelligent AI assistant that integrates web search, browsing, and email automation while maintaining conversational memory.

### Tech Stack  
Python | LangChain | OpenAI API | Web APIs  

### Key Features  
- Tool-based agent architecture  
- Conversational memory for context retention  
- Web search and email automation  
- Dynamic tool selection based on user intent  

---

## 3 PDF-Based RAG Chatbot**  
### Overview  
An AI-powered chatbot that retrieves information from PDFs using RAG pipelines.

### Tech Stack  
Python | LangChain | ChromaDB | RAG | OpenAI Swarm  

### Key Features  
- Document ingestion from PDFs  
- Semantic search with ChromaDB  
- Context-aware AI responses using RAG  

---

## 4 Multi-Agent Research System**  

**Live Demo:**(https://youtu.be/gGJiguhEhC4)

### Overview  
multi-agent research system using CrewAI where specialized agents (researcher, analyst, writer, presenter) collaborate in a sequential pipeline to produce research notes, analytical insights, a structured summary, and a slide-ready presentation outline

### Tech Stack  
CrewAI | OpenAI API | AutoGen

### Key Features  
- Used specialized Multi Agents
- Connected each using Autogen 
- Produced Structured Output 
- Multi-agent experimentation with CrewAI & AutoGen
   
## 5 Automated Job Tracking Agent 

**Live Demo:**(https://youtu.be/U8lBdfg8v_Y)

### Overview  
This project is an end-to-end automation agent that runs daily in the background to:
Scrape job listings from the web using Playwright
Deduplicate previously seen roles
Store new results in Google Sheets
Send a daily email summary via SendGrid
Run on a schedule using cron or GitHub Actions
It demonstrates real-world ntegrations, background execution, and production-style secret management.

### Tech Stack  
- Python
- Playwright (browser automation)
- Google Sheets API
- SendGrid Email API
- python-dotenv
- GitHub Actions / cron
- JSON persistence for deduplication

### How It Works
Scraper collects job listings from target sites.
Each job gets a hashed ID for deduplication.
Previously processed jobs are tracked in seen_jobs.json.
New jobs are appended to Google Sheets.
A summary email is generated and sent.
The whole pipeline runs automatically every day.

### .env
- GOOGLE_SHEET_ID=...
- GOOGLE_SERVICE_ACCOUNT_FILE=service_account.json
- SENDGRID_API_KEY=...
- FROM_EMAIL=...
- EMAIL_TO=...


