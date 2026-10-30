# Java to AI Lab

**AI for Java engineers, built the way production systems are built.**

This is the code companion to *Java to AI*, a Medium series written by an enterprise Java architect who is learning AI in public, one working build at a time.

Each article takes something Java engineers already know (a circuit breaker, a database index, an ESB route, an API contract), maps it to its AI equivalent, and builds it in Java.

## The running example: IncidentPilot

The whole series builds one real-time application: **[IncidentPilot](https://github.com/JavaToAILab/incident-pilot), an AI incident copilot for a microservices platform**.

Alerts and log events stream in through Kafka. IncidentPilot summarizes each incident as a structured record, finds similar past incidents and the matching runbook, queries metrics, logs and deploy history through tools, and streams a triage recommendation to a live dashboard. A human approves every action.

Every build article adds one piece and ends with a git tag (`article-03`, `article-05`, …), so you can check out exactly the code each article describes.

## Who this is for

- **Senior Java developers** who want hands-on AI skills without leaving the JVM
- **Architects** who need to design, integrate, secure and govern AI systems in production

No beginner tutorials or hype. Just working code, production gotchas, and an honest "what I got wrong" in every article.

## Stack

- Java 21, Maven; Spring Boot 3 from the real-time article onward
- Spring AI and LangChain4j
- Kafka, PostgreSQL + pgvector
- Ollama for local models by default; hosted models through configuration

Everything runs locally with no API keys required.

## Series index

| # | Article | Code | Status |
|---|---------|------|--------|
| 1 | [An Enterprise Java Architect Starts Over With AI](https://medium.com/@abhinav.neo/an-enterprise-java-architect-starts-over-with-ai-9dff7bb36414) | — | Published |
| 2 | [The Java Developer's AI Skill Map: What to Learn, What to Skip](https://medium.com/@abhinav.neo/the-java-developers-ai-skill-map-what-to-learn-what-to-skip-7ed8aeb069d5) | — | Published |
| 3 | [Your First LLM Call From Java, Written Like Production Code](https://medium.com/@abhinav.neo/your-first-llm-call-from-java-written-like-production-code-bfc809df2a61) | [`incident-pilot@article-03`](https://github.com/JavaToAILab/incident-pilot/tree/article-03) | Published |
| 4 | [Meet IncidentPilot: An LLM Is a Non-Deterministic Dependency](https://medium.com/@abhinav.neo/meet-incidentpilot-an-llm-is-a-non-deterministic-dependency-97de8825c3c6) | [`incident-pilot`](https://github.com/JavaToAILab/incident-pilot) | Published |
| 5 | Tokens and Context Windows as Capacity Planning | `article-05` | Coming soon |
| 7 | Structured Output With Java Records | `article-07` | Coming soon |

This table is updated as each article goes live.

## Repos

- **[incident-pilot](https://github.com/JavaToAILab/incident-pilot)**: the application, one module per build article, tagged per article
- **[first-llm-call](https://github.com/JavaToAILab/first-llm-call)**: Article 3's standalone code, kept as published

## Follow along

- Medium: [Java to AI series](https://medium.com/@abhinav.neo/list/java-to-ai-70943ef97ee9) · [@abhinav.neo](https://medium.com/@abhinav.neo)
- LinkedIn: [Abhinav Taduka](https://www.linkedin.com/in/abhinavtaduka/)

Questions, corrections and "you got this wrong" are welcome. Open an issue on the relevant repo.
