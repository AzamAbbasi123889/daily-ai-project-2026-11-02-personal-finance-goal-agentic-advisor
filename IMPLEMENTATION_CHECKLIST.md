# Implementation Checklist

Build the application yourself using `PROJECT_BRIEF.md`.

## Initial setup

- [ ] Read the project specification.
- [ ] Review the architecture and data model.
- [ ] Create a Python virtual environment.
- [ ] Install and pin the required dependencies.
- [ ] Configure credentials through environment variables.
- [ ] Review the data privacy and security requirements.

## Project acceptance criteria

- [ ] User can upload a file and see 95%+ of transactions stored
- [ ] Categories auto‑assigned with confidence >0.8
- [ ] No raw data leaves the local Docker container
- [ ] Planner returns a month‑by‑month budget plan
- [ ] Projected savings meet goal within ±5% tolerance
- [ ] Plan updates when new transactions are ingested
- [ ] Summary delivered via API endpoint within 2 seconds
- [ ] Contains at least three concrete suggestions
- [ ] Uses only data stored locally
- [ ] Set up FastAPI skeleton
- [ ] Configure Postgres + pgvector
- [ ] Create Neo4j schema
- [ ] Implement CSV upload & basic parsing
- [ ] Build LangGraph node for categorization
- [ ] Prompt design for LLM‑based category assignment
- [ ] Persist results to Neo4j
- [ ] Design financial simulation model
- [ ] Implement planner LangGraph node
- [ ] Expose goal creation endpoint
- [ ] Schedule nightly reviewer via Redis
- [ ] Generate natural‑language summary
- [ ] Create minimal React dashboard (optional)
- [ ] Unit tests for each FastAPI route (pytest)
- [ ] Integration tests for LangGraph workflow using mock LLM responses
- [ ] Load test ingestion of 10k transactions (Locust)
- [ ] Security test: ensure no outbound network calls for raw data
- [ ] Dockerfile for API & worker services
- [ ] docker‑compose.yml with Postgres, Neo4j, Redis, and worker containers
- [ ] GitHub Actions workflow: lint → test → build image → push to Docker Hub → deploy to Render (free tier)

## Before completion

- [ ] Implement the planned MVP features.
- [ ] Add unit and integration tests.
- [ ] Run the test suite.
- [ ] Measure the evaluation metrics in the brief.
- [ ] Record actual results and known limitations.
- [ ] Document setup and deployment.
- [ ] Update the README to reflect the implemented features.
- [ ] Add only verified outcomes to your resume.
