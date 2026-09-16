# 🏎️ AI DevOps Racer — Day 3

A small browser car game used as the application workload for **Day 3 of the AI DevOps Tools series**.

## Workflow
**Build → Test → Containerize → CI → Deploy**

## Run
Open `index.html`, or run:

```bash
docker compose up --build
```

Then visit `http://localhost:8080`.

Run tests with:

```bash
npm test
```

## Demo idea
Ask your AI DevOps tool to inspect the repo, explain it, run/fix tests, review the Dockerfile, and then push the project to GitHub so the GitHub Actions pipeline runs automatically.
