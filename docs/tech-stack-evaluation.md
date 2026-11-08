# Tech Stack Evaluation

## Project
An Image-Based HR Information Extraction System Using Multimodal Large Language Models.

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- [FR1]: [The system shall allow users to upload or capture images of HR documents.]
- [FR2]: [The system shall automatically extract employee information from uploaded documents using multimodal AI.]
- [FR3]: [The system shall allow HR administrators to review, correct, and save extracted information.]
- [NFR1]: [The system should process documents within 11 seconds.]
- [NFR2]: [The system should achieve approximately 95% extraction accuracy and restrict access to authorized HR administrators.]

## Options
- Option A: [Angular frontend, Spring Boot backend, MySQL database, and Multimodal AI API]
- Option B: [React frontend, Python FastAPI backend, PostgreSQL database, and Multimodal AI API.]
- Option C: [Streamlit frontend, Python backend, SQLite database, and Multimodal AI API.]

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |   5    |    5    |    5    |    3    |
| Skills I already have              |   4    |    5    |    3    |    3    |
| Time to build before my deadline   |   4    |    3    |    3    |    5    |
| Free hosting and tools             |   4    |    3    |    3    |    5    |
| Performance and security needs     |   5    |    4    |    4    |    2    |
| Room to grow later                 |   3    |    5    |    5    |    2    |
| **Total (weighted)**               |        |   104   |    96   |    83   |

## Decision record
- **Context:** [Requires developing a web-based HR document information extraction system using multimodal large language models. The project must support document uploads, automatic information extraction, data verification, and secure storage. Development time and budget are limited.]
- **Decision:** [I choose Option A: Angular, Spring Boot, MySQL, and a Multimodal AI API.]
- **Reasons:** [
1. I already have experience developing applications using Angular, Spring Boot, and MySQL, reducing the learning curve.
2. This stack supports API integration, user authentication, document processing, and structured data storage.
3. Option A achieved the highest weighted score of 104, making it the most suitable option for my current skills and project requirements.]
- **Consequences:** [Using familiar technologies will make development and maintenance easier. However, integrating multimodal AI services with Spring Boot may require additional development and testing. Hosting the frontend, backend, and database may also require separate services.]
- **Risks and next review:** [Potential risks include AI API costs, inaccurate information extraction, security issues when handling employee documents, and processing delays. I will review this decision after completing an initial prototype and testing its extraction accuracy and response time.]
