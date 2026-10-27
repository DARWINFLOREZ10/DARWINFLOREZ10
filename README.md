# Darwin Cardenas Florez

Backend Software Engineer in Medellín. I work on APIs, relational data, and the failures that show up once a write is no longer a single request: a duplicate delivery, two people saving the same row, and work that still has to finish after the response is gone.

Since 2022 I have delivered software for paying clients. I am looking for international backend roles, including remote positions and relocation. The repositories below are portfolio systems. They are not client production.

## Selected systems

[Alertfold](https://github.com/DARWINFLOREZ10/Alertfold) takes a signed alert, attaches a storm to one open incident, and commits the notification with the incident. Tokens are tenant-scoped. A stale update returns 409. Dead letters are requeued on purpose. SQLite is the written limit: one host.

[ReleasePilot](https://github.com/DARWINFLOREZ10/releasepilot) is a flag control plane. A subject’s cohort is a hash, so raising the rollout does not reshuffle people already included. `enabled=false` beats the percentage. The change and its audit row commit together.

[Handoff](https://github.com/DARWINFLOREZ10/Handoff) runs one workflow step off the request. Membership is a row, not a header. The run and the job commit together. A worker POSTs that step with an idempotency key and a retry budget.

The portfolio is [darwin-cardenas.vercel.app](https://darwin-cardenas.vercel.app). The source lives in [darwin-cardenas](https://github.com/DARWINFLOREZ10/darwin-cardenas).

Freelance backend work since 2022. It continued after the CESDE contract ended in February 2026. The three systems are the public work from that stretch. Contract at CESDE, May 2025 to February 2026. Systems Engineering degree, Instituto Tecnológico Metropolitano, 2022–2026.

**Stack:** Python, FastAPI, TypeScript, Node.js, PostgreSQL, Redis, Docker. Next.js for the portfolio.

## Contact

- [LinkedIn](https://www.linkedin.com/in/darwin-cardenas-florez-8a921a374/)
- [Email](mailto:darwinflorezcardenas@gmail.com)
