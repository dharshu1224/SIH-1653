# Smart India Hackathon Workshop
# Date:29\03\2025
## Register Number:212224230061
## Name:Dharshini.S
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
Software Objective: The goal is to develop an AI-powered, web-based simulation platform that replicates a real-life boardroom interview experience for candidates and interviewers. The platform should ensure unbiased evaluations by dynamically aligning questions with the applicant's domain expertise and providing real-time scoring for responses.

Key Features: Candidate Profile Analysis: Extract key expertise areas based on the applicant’s resume, qualifications, and experience. Use Natural Language Processing (NLP) to analyze submitted documents and auto-generate a profile summary.

Dynamic Question Generation: AI-based question bank with domain-specific, behavioral, and managerial questions. Adaptive questioning to ensure progressive complexity based on candidate responses. Ice-breaking questions followed by in-depth techno-managerial questions.

Real-time Response Evaluation: Use NLP and AI models to evaluate responses for relevance, correctness, and depth. Assign scores for each response and aggregate them to derive an overall score.

Expert Panel Simulation: Enable multi-panel interview simulation to allow multiple interviewers to participate. Provide real-time feedback to panel members on candidate performance.

Scoring and Recommendation Engine: Assign weighted scores to responses based on relevance and technical depth. Generate a final candidate score with a detailed performance summary. Provide suggestions on the candidate’s suitability for the applied post.

Dashboard and Analytics: Provide analytics and insights for decision-making. Generate interview reports with candidate ranking for post-interview reference.

Innovation/Uniqueness: AI-driven adaptive questioning to ensure unbiased and tailored interviews. Real-time response analysis with scoring using NLP and Machine Learning (ML). Seamless experience that replicates real-world boardroom interviews. Ensuring transparency and reducing subjectivity in candidate evaluation.


## Proposed Solution / Architecture Diagram
Proposed Solution We propose developing an AI-powered web-based simulation platform that replicates a real-life boardroom interview experience. The system will dynamically generate domain-specific questions, analyze candidate responses using NLP, and assign objective scores to evaluate suitability for the position.

Key Features: Candidate Profile Analysis: Extracts expertise using NLP from resumes. Adaptive Question Generation: AI-driven, progressive questioning. Real-time Response Evaluation: Analyzes and scores answers dynamically. Multi-Panel Simulation: Real-time interaction for interviewers. Scoring & Ranking Engine: Provides objective performance evaluation. Analytics Dashboard: Displays detailed candidate performance reports.

Architecture Overview Key Components: UI Layer: Web interface (React/Angular). API Gateway: Manages requests and ensures security. Candidate Profile Module: Processes resumes and extracts expertise. Question Generation Engine: AI-based adaptive question bank. Interview Simulation Module: Real-time multi-panel interaction. Response Evaluation Module: NLP-based answer analysis. Scoring Engine: Computes final scores and ranks candidates. Database: Stores profiles, responses, and evaluations. Dashboard: Generates performance insights and reports.

ARCHITECTURE DIAGRAM :

![WhatsApp Image 2025-03-29 at 10 40 01_1701d444](https://github.com/user-attachments/assets/486d3d64-fd86-42e0-bdd7-3e19f8b9e0fe)


## Use Cases
Candidate Registration & Profile Creation Actors: Candidate Description: Candidate uploads resume and provides details. System extracts expertise using NLP for personalized question generation.

Adaptive Question Generation Actors: System, Interviewer Description: AI dynamically generates domain-specific, behavioral, and managerial questions based on candidate expertise and interview progression.

Real-time Interview Simulation Actors: Candidate, Interviewer(s) Description: Multi-panel interview simulation replicating a real-life boardroom environment with real-time interaction and adaptive questioning.

Response Evaluation & Scoring Actors: System Description: NLP analyzes candidate responses for relevance and correctness, assigning real-time scores for objective evaluation.

Candidate Scoring & Ranking Actors: System, Interview Panel Description: System aggregates scores, ranks candidates, and generates detailed performance reports for decision-making.

Dashboard & Analytics Access Actors: Interview Panel, Admin Description: Provides interview insights, performance summaries, and comparative analysis for panel review


## Technology Stack
Frontend: React / Angular – For an interactive and responsive user interface.

Bootstrap / Tailwind CSS – For consistent and clean UI design.

⚙ Backend: Python (Django/Flask) or Node.js – For API development and business logic.

FastAPI – For secure and efficient API handling.

Database: PostgreSQL / MySQL – For structured data storage.

MongoDB – For flexible document-based storage (optional).

AI/ML Models: NLP Engine: SpaCy / BERT – For profile analysis and response evaluation.

TensorFlow / Scikit-Learn – For question generation and scoring algorithms.

API Gateway: Express / FastAPI – For managing API requests and ensuring security.

Cloud/Hosting: AWS / Azure / GCP – For scalable hosting and deployment.

Docker / Kubernetes – For containerization and microservices management.

Analytics & Reporting: Power BI / Tableau – For data visualization and report generation.


## Dependencies
Backend Dependencies: Django/Flask/Node.js: Framework for API and business logic.

FastAPI: For high-performance, secure API management.

PostgreSQL/MySQL: Database for storing candidate data and interview results.

MongoDB (Optional): For document-based data storage.

AI/ML Dependencies: SpaCy/BERT: For NLP-based profile analysis and response evaluation.

TensorFlow/Scikit-Learn: For question generation and scoring models.

Frontend Dependencies: React/Angular: For a responsive user interface.

Bootstrap/Tailwind CSS: For consistent and clean UI design.

API & Middleware: Express/FastAPI: For managing API requests and routing.

JWT/OAuth: For secure user authentication and authorization.

Cloud & Deployment: AWS/Azure/GCP: For scalable cloud hosting.

Docker/Kubernetes: For containerization and orchestration.

Analytics & Reporting: Power BI/Tableau: For generating performance insights and reports.

