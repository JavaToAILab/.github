# Java to AI Lab

**AI for Java engineers, built the way production systems are built.**

This is the code companion to *Java to AI*, a Medium series written by an enterprise Java architect who is learning AI in public, one working build at a time.

Each article takes something Java engineers already know (a circuit breaker, a database index, an ESB route, an API contract), maps it to its AI equivalent, and builds it in Java. Every build article has its own repo here.

## Who this is for

- **Senior Java developers** who want hands-on AI skills without leaving the JVM
- **Architects** who need to design, integrate, secure and govern AI systems in production

No beginner tutorials or hype. Just working code, production gotchas, and an honest "what I got wrong" in every article.

## Stack

- Java 21, Maven; Spring Boot 3 where a framework earns its place
- Spring AI and LangChain4j
- PostgreSQL + pgvector
- Ollama for local models by default; hosted models through configuration

Every repo runs locally with no API keys required.

## Series index

| # | Article | Repo | Status |
|---|---------|------|--------|
| 1 | [An Enterprise Java Architect Starts Over With AI](https://medium.com/@abhinav.neo/an-enterprise-java-architect-starts-over-with-ai-9dff7bb36414) | — | Published |
| 2 | [The Java Developer's AI Skill Map: What to Learn, What to Skip](https://medium.com/@abhinav.neo/the-java-developers-ai-skill-map-what-to-learn-what-to-skip-7ed8aeb069d5) | — | Published |
| 3 | [Your First LLM Call From Java, Written Like Production Code](https://medium.com/@abhinav.neo/your-first-llm-call-from-java-written-like-production-code-bfc809df2a61) | [`first-llm-call`](https://github.com/JavaToAILab/first-llm-call) | Published |
| 4 | An LLM Is a Non-Deterministic Dependency | — | Coming soon |
| 5 | Tokens and Context Windows as Capacity Planning | `token-cost-estimator` | Coming soon |
| 7 | Structured Output With Java Records | `structured-output-records` | Coming soon |

This table is updated as each article goes live.

## Repo layout

- **One repo per build article**, named after what it builds (`first-llm-call`, `rag-spring-pgvector`, `mcp-server-java`, `eval-harness`, …)

Each repo's README links back to its article.

## Follow along

- Medium: [Java to AI series](https://medium.com/@abhinav.neo/list/java-to-ai-70943ef97ee9) · [@abhinav.neo](https://medium.com/@abhinav.neo)
- LinkedIn: [Abhinav Taduka](https://www.linkedin.com/in/abhinavtaduka/)

Questions, corrections and "you got this wrong" are welcome. Open an issue on the relevant repo.
