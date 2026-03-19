# Projects

> All flagship AI/ML and software development projects.
> 🔗 [Back to main profile](../README.md)

---

## 🤖 AI & Machine Learning

### Recommender Chatbot for Netflix (Neo4j + LangChain + Streamlit)
**[GitHub Repo](https://github.com/grzegorz-gomza/Recommender_System_with_Neo4j)** &nbsp;|&nbsp; **[🌐 Live App](https://gg-netflix-recommender.streamlit.app/)** &nbsp;|&nbsp; **[▶ YouTube](https://youtu.be/HAIaNS-dj-E)**

Conversational movie recommender powered by a LangChain agent with four specialised tools: relationship-based, preference-based, and description-similarity recommendations via Neo4j graph queries, plus a general movie chatbot. The LLM generates Cypher queries from natural language and returns context-aware suggestions.

**Stack:** Python · LangChain · Neo4j · OpenAI · Streamlit

---

### Custom AI Agentic Chatbot with RAG & Websearch (LangGraph + Streamlit)
**[GitHub Repo](https://github.com/grzegorz-gomza/Langgraph_Agent)** &nbsp;|&nbsp; **[🌐 Live App](https://gg-langgraphagent.streamlit.app/)** &nbsp;|&nbsp; **[▶ YouTube](https://youtu.be/DuAuMw9S9J0)**

Combines a LangGraph agent with live web search and a multimodal RAG pipeline capable of reading PDFs — including tables and embedded graphics. Answers questions using the LLM itself, internet research, or deep document understanding.

**Stack:** Python · LangGraph · LangChain · OpenAI · Streamlit

---

### Chest Cancer Classifier (VGG16 + MLOps Pipeline + AWS)
**[GitHub Repo](https://github.com/grzegorz-gomza/Chest_Cancer_Classification_MLOps)** &nbsp;|&nbsp; **[▶ YouTube](https://youtu.be/TW8r8h0-0PY)**

MLOps-style image classification system for chest CT scans using a fine-tuned VGG16 CNN with a custom classification head. Full pipeline: config-driven training, DVC data versioning, MLflow experiment tracking, Docker containerisation, and AWS deployment via GitHub Actions CI/CD. Classifies three types of lung cancer: **Adenocarcinoma, Large Cell Carcinoma, and Squamous Cell Carcinoma**.

**Stack:** Python · PyTorch · VGG16 · DVC · MLflow · Flask · Docker · AWS EC2 · GitHub Actions

---

### Waste Classifier — 30 Classes (ResNet50 / MobileNetV2 / EfficientNet-B0 + XGBoost)
**[GitHub Repo](https://github.com/grzegorz-gomza/Waste_Classifier)**

Transfer learning system classifying **30 types of waste** from 15,000 images. Compares three CNN architectures × three classification head complexities (9 CNN configurations), plus two XGBoost baseline models — **11 models total**. Best result: **92.70% accuracy** (ResNet50 + semi-complex head).

Interactive frontend with two views:
- **Prediction page** — run inference on sample or custom uploaded images, showing predictions across all 5 selected models
- **Metrics dashboard** — training/validation accuracy, loss curves, and confusion matrix per model

**Stack:** Python · PyTorch · ResNet50 · MobileNetV2 · EfficientNet-B0 · XGBoost · config-driven pipeline · Strategy / Factory / Pipeline / Observer design patterns

---

### RAG Chatbot over PDFs (OpenAI + Streamlit)
**[GitHub Repo](https://github.com/grzegorz-gomza/Chat_with_PDF)**

Streamlit app that lets users chat with multiple uploaded PDF documents. Text is extracted, chunked, and indexed; OpenAI provides conversational responses grounded in the document content.

**Stack:** Python · OpenAI · LangChain · Streamlit

---

### E-Mail Spam Detector (NLP + FastAPI + Airflow + Docker)
**[GitHub Repo](https://github.com/grzegorz-gomza/E-mail_Spam_Detection)**

End-to-end NLP pipeline detecting spam emails. scikit-learn model, FastAPI backend, Streamlit frontend, Airflow DAGs for orchestration, fully containerised with Docker.

**Stack:** Python · scikit-learn · FastAPI · Streamlit · Airflow · Docker

---

### Punching Shear Resistance Prediction (Structural ML)
**[GitHub Repo](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Concrete%20Punching)**

ML model predicting punching shear resistance (Pu) for concrete slab-column connections from geometric and material properties. Domain knowledge from 10+ years of civil engineering applied to supervised ML — bridges the gap between engineering and AI.

**Stack:** Python · scikit-learn · Pandas · Matplotlib

---

### Lego Brick Classifier (CNN)
**[GitHub Repo](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Lego%20recognition)**

CNN model classifying individual LEGO bricks from images. Built during a Data Science Bootcamp.

---

## 🌐 Web Development

### mAIniac — AI & IT Social Media Website
**[Live URL](https://mayar.abertay.ac.uk/~2511872/)**

> *Note: Hosted on a university server — may be offline outside term time.*

Full-stack social media platform for AI and tech news. Built for the **HEP504 Web Development** module at Abertay University (M.Sc. Computer Science with AI).

**Key features:**
- Two-tier user authentication (Level 1: Admin, Level 2: User)
- Article CRUD with rich-text editor, image uploads, and category tagging
- Nested comment system with real-time like functionality (JavaScript/AJAX)
- User search and profile management
- Fully responsive with Bootstrap 5 (mobile-first, hamburger nav)
- WCAG 2.1 AA accessibility compliance (semantic HTML, ARIA labels, keyboard navigation, colour contrast ≥ 4.5:1)
- MVC-style PHP architecture with prepared statements (SQL injection prevention), bcrypt password hashing, session management

**Stack:** PHP · MySQL · Bootstrap 5 · JavaScript · HTML5 · CSS3

---

## 🎮 Other

### Tic Tac Toe in C++ (3×3 to 10×10)
**[GitHub Repo](https://github.com/grzegorz-gomza/Tic_Tac_Toe_C--)**

C++ implementation with customisable board sizes (3×3 to 10×10), automatic winner detection, draw detection, and input validation.

---

## 📊 Learning & Practice (Codecademy)

<details>
<summary>Click to expand 14 Codecademy portfolio projects</summary>

| Project | Description |
|---|---|
| [A/B Testing for ShoeFly.com](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_A_B%20Testing%20for%20ShoeFly) | A/B testing analysis on website variables |
| [Airline Analysis](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Airline%20Analysis) | Trend analysis on airline industry data |
| [Biodiversity](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Biodiversity) | Species variety and environmental factors |
| [Cleaning US Census Data](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Cleaning%20US%20Census%20Data) | Data cleaning on census datasets |
| [Exploring Mushrooms](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Exploring%20Mushrooms) | EDA on mushroom characteristics |
| [Hurricane Analysis](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Hurricane_Analysis) | Hurricane data patterns and impacts |
| [Life Expectancy & GDP](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Life-Expectancy-and-GDP-Starter) | Cross-country GDP vs life expectancy |
| [Medical Insurance](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Medical%20Insurance) | Insurance cost exploration |
| [NBA Trends](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_NBA_Trends_Project) | Player and game statistics |
| [Product Defects](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Product%20Defects) | Defect data for quality control |
| [PySpark Training](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_PySpark_Training) | Large-scale data processing |
| [Reggie's Linear Regression](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Codecademy_Reggie's%20Linear%20Regression) | Linear regression fundamentals |
| [Customer Behaviour on Website](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Customer%20Behaviour%20on%20Website) | Website behaviour analysis |
| [Daily Training Sessions](https://github.com/grzegorz-gomza/Portfolio_Projects/tree/main/Z_Code%20from%20daily%20Training%20sessions) | PySpark and daily coding exercises |

</details>

---

*🔗 [Back to main profile](../README.md) · [Experience](EXPERIENCE.md) · [Blogs](BLOGS.md) · [Certificates](CERTIFICATES.md)*
