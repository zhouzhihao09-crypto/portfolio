# Portfolio

A static developer portfolio showcasing six software projects:

- **Evidence-First Agent** — MCP server and Python library that make AI agent work auditable, sealing each run into a versioned AI Work Receipt with a SHA-256 hash
- **ProofPilot** — Evidence-grounded verification with deterministic guardrails, optional semantic verification, provenance tracking, evidence graphs, and audit reports
- **Tender AI** — AI-powered tender analysis and evidence organization
- **Doc AI Assistant** — Local PDF question answering with semantic search
- **Telecom Log Ingestion Service** — High-throughput telecom event ingestion
- **SafeHTML** — Security-focused HTML sanitization library for Java 21

## Preview locally

Open `index.html` directly in a browser, or run a simple static server:

```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
```

## Project structure

```
portfolio/
├── index.html
├── styles.css
├── script.js
├── favicon.svg
├── README.md
├── .nojekyll
├── .gitignore
├── assets/
│   ├── evidence-first-agent-architecture.svg
│   ├── evidence-first-agent-demo.gif
│   ├── proofpilot-architecture.svg
│   ├── proofpilot-demo.png
│   ├── tender-ai-dashboard.png
│   ├── tender-ai-tender-analysis.png
│   ├── tender-ai-evidence-results.png
│   ├── tender-ai-demo.gif
│   ├── doc-ai-assistant-main-interface.png
│   ├── doc-ai-assistant-document-question-workflow.png
│   ├── doc-ai-assistant-example-answer-result.png
│   ├── doc-ai-assistant-demo.gif
│   ├── telecom-log-ingestion-api-ingestion.png
│   ├── telecom-log-ingestion-batch-processing.png
│   ├── telecom-log-ingestion-database-results.png
│   ├── telecom-log-ingestion-demo.gif
│   ├── safe-html-sanitizer-demo.png
│   └── safe-html-sanitizer-demo.gif
└── .github/
    └── workflows/
        └── deploy.yml
```

## Deploy to GitHub Pages

This is a plain static site with no build step.

1. Create a new GitHub repository (or use an existing one).
2. Push `index.html`, `styles.css`, `script.js`, `README.md`, `favicon.svg`, the `assets/` folder, `.nojekyll`, and `.github/workflows/deploy.yml`.
3. In the repository settings, enable **Pages** under the *Pages* section.
4. Select the `main` branch and `/` root as the build source.
5. After a few minutes, the site will be live at `https://<username>.github.io/<repo>/`.

The `.nojekyll` file ensures the static files are served as-is without Jekyll processing. The `.github/workflows/deploy.yml` workflow deploys automatically on pushes to `main`.

No build step is required — this is a plain static site.