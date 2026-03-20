# Rahul-18r — Projects Portfolio

> A complete overview of all repositories, their descriptions, and tech stacks.

---

## 👨‍💻 About Me

**Backend Developer** specialising in **Java | Spring Boot | Microservices**.

I build robust, scalable backend systems designed for real-world performance.

**Core Tech Stack:** Java · Spring Boot · Python · MySQL · MongoDB · Docker · Git

📧 rahulmogaveer18@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rahul-18r) · [GitHub](https://github.com/Rahul-18r)

---

## 📦 Projects

### 1. 🌦️ Weather Checker
**Repository:** [Rahul-18r/weather](https://github.com/Rahul-18r/weather)

A visually appealing weather-checking web app with dynamic 3D background effects. Enter any place name to get current weather information, enhanced with interactive snow, sunlight, or star particle effects depending on the weather and time of day.

**Features:**
- Search weather by city/place name using OpenWeatherMap Geocoding API
- Displays temperature, min/max, weather description, and country
- Dynamic background colour changes based on weather and day/night
- 3D particle effects (snow, sunlight, stars) powered by Three.js
- Responsive and clean UI with smooth transitions

**Tech Stack:**

| Layer | Technology |
|---|---|
| Markup & Styling | HTML5, CSS3, CSS Flexbox |
| Logic | JavaScript (ES6+) |
| 3D Graphics | [Three.js](https://threejs.org/) |
| APIs | OpenWeatherMap Geocoding API, Current Weather Data API |

---

### 2. 💰 Personal Expense Tracker API
**Repository:** [Rahul-18r/Personel-Expense-Tracker](https://github.com/Rahul-18r/Personel-Expense-Tracker)

A full-featured personal expense tracking REST API built with enterprise-grade architecture including race-condition handling (optimistic/pessimistic locking), paginated queries, and budget threshold monitoring.

**Features:**
- JWT-secured REST API with user registration and login
- CRUD for categories, expenses/income entries, and budgets
- Monthly summary with income/expense/balance breakdown
- Budget progress tracking with percentage used
- 3-layer race-condition protection (pessimistic lock → unique constraint → optimistic lock)
- Budget threshold alerts at 80% and 100% of limit

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Java 25 |
| Framework | Spring Boot 4.0.3 |
| Security | Spring Security 7.x + JWT (jjwt 0.12.6) |
| ORM | Spring Data JPA / Hibernate 7.x |
| Database | MySQL 8+ |
| Validation | Jakarta Bean Validation |
| Build Tool | Maven |
| Utilities | Lombok, Jackson 3.x |

---

### 3. 📖 VTU Internship Diary Automator
**Repository:** [Rahul-18r/VTU-Internship-Dairy](https://github.com/Rahul-18r/VTU-Internship-Dairy)

A Python automation tool that generates structured VTU internship diary entries from class topics and then auto-fills and submits them on the VTU internship portal using Selenium.

**Features:**
- Converts topic titles into ready-to-submit diary content
- Supports combined entries (core topic + programming topic per date)
- Automates portal login, date selection, form filling, and save
- Retries failed dates automatically
- Detailed logging for debugging

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Python 3.10+ |
| Browser Automation | Selenium ≥ 4.18.0 |
| Driver Management | webdriver-manager ≥ 4.0.1 |
| Runtime | Windows (primary) |

---

### 4. 🏥 Medicnosis — Disease Prediction from Symptoms
**Repository:** [Rahul-18r/Disease-Prediction-from-Symptoms](https://github.com/Rahul-18r/Disease-Prediction-from-Symptoms)

An AI-powered disease prediction system that analyses symptom descriptions using an ensemble of 5 machine learning models to predict potential diseases with 94–98% accuracy.

**Features:**
- 5-model ML ensemble (Text Pipeline, Decision Tree, Gradient Boosting, Random Forest, Naive Bayes)
- Gender-aware filtering for accurate predictions
- NLP-based gender inference from symptom text
- Voice input via Web Speech API
- Real-time confidence score visualisation
- 34 disease classes, 1 800 training samples

**Model Performance:**

| Model | Accuracy |
|---|---|
| Text Pipeline (Logistic Regression) | 98.33% |
| Multinomial Naive Bayes | 98.06% |
| Random Forest | 94.72% |
| Gradient Boosting | 93.06% |
| Decision Tree | 62.78% |

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language (Backend) | Python 3.8+ |
| ML Libraries | scikit-learn, joblib |
| NLP | spaCy (en_core_web_sm), TF-IDF |
| Web Framework | Flask / Gradio |
| Audio Processing | speech_recognition |
| Language (Frontend) | JavaScript (React 18.3) |
| Build Tool | Vite 5.3 |
| Styling | TailwindCSS 3.4 |
| HTTP Client | Axios |
| Voice | Web Speech API |

---

### 5. ✅ To-Do App (Full-Stack)
**Repository:** [Rahul-18r/To-Do](https://github.com/Rahul-18r/To-Do)

A full-stack To-Do application where users can add, edit, and delete tasks. Integrates a React frontend with a Spring Boot REST backend.

**Features:**
- Create, read, update, and delete tasks
- RESTful API with clean separation of concerns
- React frontend connected to Spring Boot backend via Axios/fetch

**Tech Stack:**

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Spring Boot (Java 11+) |
| Build Tool | Maven |
| Package Manager | npm |

---

### 6. 🦅 Web Scraper with AI
**Repository:** [Rahul-18r/Web-Scrapper-with-AI](https://github.com/Rahul-18r/Web-Scrapper-with-AI)

A Streamlit-based web scraping tool that combines Selenium, BeautifulSoup, and LLaMA 3.2 (via Ollama) to extract meaningful insights from website content, with a built-in chatbot for interactive Q&A.

**Features:**
- Scrape any website using Selenium + BeautifulSoup
- Automatic DOM cleaning and structuring
- LLM-powered insight extraction and content parsing
- Built-in chatbot interface for natural language queries
- Simple Streamlit UI

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Python |
| UI | Streamlit |
| Browser Automation | Selenium |
| HTML Parsing | BeautifulSoup |
| LLM Orchestration | LangChain |
| Local LLM | Ollama + LLaMA 3.2 |

---

### 7. 📄 Resume Analyzer
**Repository:** [Rahul-18r/resumeanalyzer](https://github.com/Rahul-18r/resumeanalyzer)

A React-based web application for analysing resumes. Provides a clean frontend interface where users can submit and review resume content.

**Features:**
- React single-page application scaffold for resume analysis
- Webpack-bundled production build with Babel transpilation
- Modular component structure ready for extension

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | JavaScript (ES6+) |
| UI Library | React 18.2 |
| Bundler | Webpack 5 |
| Transpiler | Babel 7 (preset-env, preset-react) |
| Build Tool | webpack-cli + webpack-dev-server |

---

### 8. 🔐 CyberSentinel
**Repository:** [Rahul-18r/CyberSentinel](https://github.com/Rahul-18r/CyberSentinel)

A comprehensive cybersecurity toolkit combining Safe Browsing, Zero-Knowledge Proof (ZKP) Authentication, and Email Spam Detection — wrapped in a cyberpunk-inspired interface.

**Features:**
- Real-time threat detection and blocking for unsafe websites
- Privacy-preserving ZKP authentication (no sensitive data revealed)
- Advanced spam and phishing email filtering
- Cyberpunk-themed, modular UI

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | JavaScript (Node.js) |
| Frontend Dev Server | Vite |
| Backend Runtime | Node.js |
| Package Manager | npm |

---

### 9. 🧠 AI-Powered Research Assistant (Chrome Extension)
**Repository:** [Rahul-18r/research-assistant-chrome](https://github.com/Rahul-18r/research-assistant-chrome)

A full-stack application that enhances productivity by summarising, explaining, rephrasing, and analysing content using Google Gemini's generative AI APIs, with an integrated Chrome Extension for quick in-browser access.

**Supported Operations:**
`summarize` · `explain` · `suggest` · `define` · `highlight` · `rephrase` · `extract` · `related` · `analyze` · `citation`

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Java 17 |
| Framework | Spring Boot 3 |
| HTTP Client | WebClient |
| AI / LLM | Google Gemini API |
| Build Tool | Maven |
| Chrome Extension | HTML / CSS / JavaScript |

---

### 10. 🔗 URL Shortener Service
**Repository:** [Rahul-18r/urlshortener](https://github.com/Rahul-18r/urlshortener)

A web application that shortens long URLs (similar to Bitly / TinyURL), generates unique short links, and tracks click statistics. Provides both a user-friendly Thymeleaf frontend and a REST API.

**Features:**
- Transform long URLs into compact shareable links
- HTTP 302 redirect with click analytics
- Custom aliases and optional time-based expiration
- REST API + Thymeleaf web UI
- H2 (dev) / MySQL / PostgreSQL (production) support

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Java 17+ |
| Framework | Spring Boot 3.x |
| ORM | Spring Data JPA |
| Database | H2 (dev), MySQL / PostgreSQL (prod) |
| Frontend | Thymeleaf Templates |
| Build Tool | Maven 3.9+ |
| Testing | JUnit 5, Spring Boot Test |

---

### 11. 🏨 Hoen Scanner
**Repository:** [Rahul-18r/hoen-scanner](https://github.com/Rahul-18r/hoen-scanner)

A Dropwizard application that handles car rental and hotel searches based on city.

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | Java 19 |
| Framework | Dropwizard |
| Build Tool | Maven |

---

### 12. 🎪 Sambhram 2025 — Event Management System
**Repository:** [Rahul-18r/Backend](https://github.com/Rahul-18r/Backend)

A full-stack event management platform built for **Sambhram 2025**, a college cultural fest. The system handles participant registration, ticket generation with QR codes, payment processing, and an admin portal for managing events and attendees.

**Features:**
- JWT-secured REST API with role-based access (admin / participant)
- Online payment integration via Razorpay and Cashfree
- QR-code-embedded PDF ticket generation using Puppeteer
- AWS S3 integration for file and image storage
- Admin portal (Vite + React) for participant oversight, analytics, and event management
- Rate limiting, request logging (Winston/Morgan), and health-check endpoint
- Production-ready CORS, 404 handler, and environment-aware logging
- MongoDB data models for registrations, tickets, and admin users

**Tech Stack:**

| Layer | Technology |
|---|---|
| Language | JavaScript (Node.js ≥ 18) |
| Framework | Express 4.x |
| Database | MongoDB (Mongoose 8.x) |
| Authentication | JWT (jsonwebtoken) + bcryptjs |
| Payment Gateways | Razorpay 2.x, Cashfree PG 5.x |
| Cloud Storage | AWS S3 (aws-sdk v3) |
| PDF / QR Tickets | Puppeteer 24.x, qrcode |
| Rate Limiting | express-rate-limit |
| Logging | Winston 3.x, Morgan |
| Validation | express-validator |
| Dev Tool | nodemon |
| Frontend (Admin) | Vite + React (separate Admin/ directory) |

---

## 📊 Tech Stack Summary

| Language / Technology | Projects |
|---|---|
| **Java / Spring Boot** | Personel-Expense-Tracker, To-Do, research-assistant-chrome, urlshortener, hoen-scanner |
| **Python** | VTU-Internship-Dairy, Disease-Prediction-from-Symptoms, Web-Scrapper-with-AI |
| **JavaScript / React** | weather, Disease-Prediction-from-Symptoms (frontend), To-Do (frontend), resumeanalyzer, CyberSentinel |
| **Node.js / Express** | Backend (Sambhram 2025) |
| **MongoDB** | Backend (Sambhram 2025) |
| **MySQL** | Personel-Expense-Tracker, urlshortener |
| **Machine Learning (scikit-learn)** | Disease-Prediction-from-Symptoms |
| **LLM / AI** | Web-Scrapper-with-AI (LLaMA 3.2), research-assistant-chrome (Google Gemini) |
| **Selenium / Browser Automation** | VTU-Internship-Dairy, Web-Scrapper-with-AI |
| **Payment Gateways (Razorpay / Cashfree)** | Backend (Sambhram 2025) |
| **AWS S3** | Backend (Sambhram 2025) |
| **Docker** | (planned/used across multiple projects) |

---

*Last updated: March 2026*