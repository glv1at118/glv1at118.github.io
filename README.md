# Guannan Lyu

## SUMMARY

Software engineer with 5+ years of enterprise full-stack development: Java/Spring Boot microservices, ASP.NET Core REST APIs, Angular/Ionic clients and cloud migrations to GCP and Firebase. Also builds multi-agent orchestration systems in Python.

## SKILLS

<table>
  <tr><td><b>Languages</b></td><td>Java, C#, TypeScript, Python, SQL</td></tr>
  <tr><td><b>Backend</b></td><td>Spring Boot, ASP.NET Core (.NET 10), Entity Framework Core, Hibernate, MyBatis, Node.js</td></tr>
  <tr><td><b>Front end &amp; mobile</b></td><td>Angular, React, Ionic, NativeScript</td></tr>
  <tr><td><b>Data &amp; messaging</b></td><td>PostgreSQL, SQL Server, Apache Kafka, RabbitMQ</td></tr>
  <tr><td><b>Cloud</b></td><td>GCP (Anthos, Cloud Storage), Firebase, Azure Blob Storage</td></tr>
  <tr><td><b>DevOps &amp; tools</b></td><td>Azure DevOps (TFVC, Pipelines, Boards), GitHub, Docker, Jira</td></tr>
  <tr><td><b>Testing</b></td><td>unit testing (Mockito, Jasmine), load testing (Apache JMeter)</td></tr>
  <tr><td><b>Agentic AI</b></td><td>multi-agent orchestration, RAG, smolagents, OpenAI API</td></tr>
  <tr><td><b>AI-assisted dev</b></td><td>GitHub Copilot, Claude Code, Accenture AI SDLC</td></tr>
</table>

## EXPERIENCE

### Accenture

**Senior Full Stack Engineer**, Airbus (national defense program) &nbsp;|&nbsp; *Feb 2026 – Present*

- Migrated 5+ legacy applications (Angular front ends, ASP.NET Core REST APIs) to a new program environment, moving source control from TFVC on Azure DevOps to Git on GitHub to enable Copilot agent workflows.
- Upgraded Angular 18 to 22 and .NET 8 to .NET 10, along with their dependencies; replaced commercial and outdated libraries with open-source alternatives, refactored code and fixed defects uncovered during the migration.
- Deliver features through AI-native development (Accenture AI SDLC, GitHub Copilot, Claude Code) as the human reviewer, auditing all AI-generated code for spec drift, hallucinated logic and quality before merge.

**Senior Full Stack Developer / Tech Lead**, CN Rail &nbsp;|&nbsp; *Jul 2022 – Jan 2026*

- Led feature delivery on MRS, an Ionic enterprise Android app for train scheduling and logistics, with 90% unit test coverage and JMeter load testing; built offline-first sync with connection-quality monitoring.
- Built MRS’s two most mission-critical features:
  - Train consist PDF report, shareable by email, Bluetooth or cloud upload, and never lost when offline.
  - Train consist chart, a color-coded view that gives conductors the whole train at a glance.
- Led MRS’s migration from the retired Kinvey platform to Firebase/GCP: ran multiple POCs to test feasibility and catch issues early, refactored data structures, migrated collections, and designed and built the Firebase Authentication workflow.
- Owned the train journal Spring Boot microservice on Anthos: moved its storage from a network file share to Google Cloud Storage and redesigned its architecture, file parsing and REST endpoints; replaced one catch-all regex search with small, targeted patterns, making search faster and easier to maintain.
- Delivered 5 major stories on an undocumented legacy Google Web Toolkit app that the client team could neither run locally nor maintain; became the go-to expert (20+ support requests), recognized by the client manager for outstanding work.
- Mentored developers and QA, reviewed pull requests and worked with the platform team to diagnose pre-production issues; promoted in July 2025.

**Full Stack Developer (Contract)**, Airbus &nbsp;|&nbsp; *Jun 2021 – Jul 2022*

- Cut a key internal application’s load time by over 70% through optimized DOM rendering and front-end/back-end data flow.
- Delivered enhancements across Angular UI components, API logic and data access.

## PROJECT

**Private Knowledge-Base Assistant (multi-agent RAG)** &nbsp;|&nbsp; *Oct 2026*

- Built a RAG Q&A application grounded in an organization’s private documents rather than public sources: content is chunked and embedded, the most relevant chunks are retrieved, and an OpenAI model synthesizes the answer.
- Designed the orchestration, with an orchestrator agent routing tasks to specialized sub-agents, and tuned similarity thresholds and retrieval criteria, noticeably improving answer quality. Built for the Accenture FDE certification.

## CERTIFICATIONS & EDUCATION

**Certified Full Stack Forward Deployed Engineer (FDE)**, Accenture &nbsp;|&nbsp; *Oct 2026*\
**Building Agents; Multi-Agent Systems**, Udacity &nbsp;|&nbsp; *May 2026*\
**Microsoft Certified: Azure Fundamentals (AZ-900)**, Microsoft &nbsp;|&nbsp; *Feb 2024*\
**Oracle Certified Associate, Java SE 8 Programmer**, Oracle &nbsp;|&nbsp; *Dec 2022*

**Master of Engineering (MEng)**, University of Toronto &nbsp;|&nbsp; *2018*
